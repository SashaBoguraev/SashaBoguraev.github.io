---
layout: clean
title: "cv"
permalink: /cv/
redirect_from:
  - /resume
---

[Download my CV (PDF).]({{ '/files/SashaBoguraevCV.pdf' | relative_url }})

<div id="cv-pages" class="cv-pages">
  <noscript>Your browser has JavaScript turned off, so the CV can't be shown inline. Use the link above.</noscript>
</div>

<script src="https://cdnjs.cloudflare.com/ajax/libs/pdf.js/3.11.174/pdf.min.js"></script>
<script>
  (function () {
    var container = document.getElementById("cv-pages");
    var url = "{{ '/files/SashaBoguraevCV.pdf' | relative_url }}";
    if (!window.pdfjsLib) return;
    pdfjsLib.GlobalWorkerOptions.workerSrc =
      "https://cdnjs.cloudflare.com/ajax/libs/pdf.js/3.11.174/pdf.worker.min.js";

    pdfjsLib.getDocument(url).promise.then(function (pdf) {
      var chain = Promise.resolve();
      for (var n = 1; n <= pdf.numPages; n++) {
        (function (n) {
          chain = chain.then(function () {
            return pdf.getPage(n).then(function (page) {
              var width = container.clientWidth;
              var base = page.getViewport({ scale: 1 });
              var dpr = window.devicePixelRatio || 1;
              var viewport = page.getViewport({ scale: (width / base.width) * dpr });
              var canvas = document.createElement("canvas");
              canvas.width = viewport.width;
              canvas.height = viewport.height;
              canvas.setAttribute("aria-label", "CV page " + n);
              container.appendChild(canvas);
              return page.render({ canvasContext: canvas.getContext("2d"), viewport: viewport }).promise;
            });
          });
        })(n);
      }
      return chain;
    }).catch(function () {
      container.textContent = "Couldn't render the CV here. Use the download link above.";
    });
  })();
</script>
