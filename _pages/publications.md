---
layout: clean
title: "papers"
permalink: /publications/
---

You can also find my articles on [my Google Scholar profile](https://scholar.google.com/citations?authuser=1&user=iUKlzyQAAAAJ).

<div class="author-note">
  <sup>*</sup> Indicates equal contribution
</div>

## 2026

<div class="paper">
<div class="paper-title"><a href="https://openreview.net/forum?id=pXYWXZE3QV">Parasite Features: Causal Abstraction Through Spurious Pathways</a></div>
<div class="paper-authors">
  Denis Sutter, Qing Yao, <strong>Sasha Boguraev</strong>, Julian Minder, Antonio Di Maio, Thomas Hofmann, Kyle Mahowald, Tiago Pimentel
</div>
<div class="paper-venue">NeurIPS 2026</div>
<div class="paper-links">
<details class="paper-toggle">
<summary>Abstract</summary>
<p>Causal Abstraction can be used to define a notion of equivalence between a neural network and an algorithm, thus serving as a powerful framework for mechanistic interpretability. In this paper, however, we show the existence of a class of spurious features which straightforwardly pass such equivalence tests. Suppose there are two directions in a model's representation space where: (i) one discriminates the input based on some specific feature, and (ii) the other steers the model towards a certain output. Causal Abstraction techniques can create a pathway leveraging these unrelated directions to simulate their combined behavior in the model, which thus spuriously appears to implement a certain feature. In such cases, we say the method discovered a parasite feature. Experimentally, we show that Distributed Alignment Search&mdash;a Causal Abstraction-based method&mdash;finds parasite features using linear alignment maps in two tasks: syntactic agreement and two-digit addition. Our paper highlights an important consideration for Causal Abstraction and contributes to the ongoing debate about best practices for mechanistic interpretability.</p>
</details>
<details class="paper-toggle">
<summary>BibTeX</summary>
<pre>@inproceedings{sutter2026parasite,
  title     = {Parasite Features: Causal Abstraction Through Spurious Pathways},
  author    = {Sutter, Denis and Yao, Qing and Boguraev, Sasha and Minder, Julian and Di Maio, Antonio and Hofmann, Thomas and Mahowald, Kyle and Pimentel, Tiago},
  booktitle = {Advances in Neural Information Processing Systems},
  year      = {2026}
}</pre>
</details>
</div>
</div>

<div class="paper">
<div class="paper-title"><a href="https://aclanthology.org/2026.emnlp-main.732/">The Emergence and Sparsification of a Syntactic Circuit</a></div>
<div class="paper-authors">
  Qing Yao, <strong>Sasha Boguraev</strong>, Tiago Pimentel, Kyle Mahowald
</div>
<div class="paper-venue">EMNLP 2026</div>
<div class="paper-links">
<details class="paper-toggle">
<summary>Abstract</summary>
<p>To understand the emergence of grammatical behavior in language models, we track circuits for subject&ndash;verb number agreement in pythia-1b and ten seeds of pythia-410m across training. We find that subject&ndash;verb agreement is learned early, and is initially handled by a diffuse collection of neurons. However, after agreement behavior has stabilized, the mechanisms responsible for it continue to reorganize. The attention heads which mediate agreement often shift during training: in the case of pythia-1b, behavior is controlled by two heads early in training but by a third (different) head later. Furthermore, the circuit shrinks over training, with pythia-1b's final circuit being strikingly sparse. We take these results to be informative about how linguistic knowledge emerges and is represented in a language model.</p>
</details>
<details class="paper-toggle">
<summary>BibTeX</summary>
<pre>@inproceedings{yao2026emergence,
  title     = {The Emergence and Sparsification of a Syntactic Circuit},
  author    = {Yao, Qing and Boguraev, Sasha and Pimentel, Tiago and Mahowald, Kyle},
  booktitle = {Proceedings of the 2026 Conference on Empirical Methods in Natural Language Processing},
  year      = {2026},
  url       = {https://aclanthology.org/2026.emnlp-main.732/}
}</pre>
</details>
</div>
</div>

<div class="paper">
<div class="paper-title"><a href="https://ling.auf.net/lingbuzz/010525">Language Models and Experimental Syntax</a></div>
<div class="paper-authors">
  <strong>Sasha Boguraev</strong>, Qing Yao, Kanishka Misra, Kyle Mahowald
</div>
<div class="paper-venue">Invited chapter, submitted to G. Goodall (ed.), <em>The Cambridge Handbook of Experimental Syntax</em>, 2nd edition, Cambridge University Press</div>
<div class="paper-links">
<details class="paper-toggle">
<summary>Abstract</summary>
<p>In the 20th and early 21st centuries, linguists developed techniques for studying syntactic competence and syntactic processing in humans. A key underlying assumption of this work was that all humans who have acquired a language in the typical way are syntactically competent. For much of this period, it was also obvious that machine systems were not syntactically competent. With the rise of Language Models that could seemingly produce and comprehend utterances in human language, this latter assumption was challenged. As a result, there was an explosion of work using the experimental syntax toolkit not to study syntactic processing in competent humans, but rather to ask whether Language Models had emergently developed syntactic competence. This research program proved fruitful, with the study of Language Model syntax now even offering testable hypotheses about human syntax. Here, we tell that story and argue that, while experimental work uncovered major lacunas in syntactic processing in earlier Language Models, modern Language Models have meaningfully acquired syntax.</p>
</details>
<details class="paper-toggle">
<summary>BibTeX</summary>
<pre>@incollection{boguraev2026experimental,
  title     = {Language Models and Experimental Syntax},
  author    = {Boguraev, Sasha and Yao, Qing and Misra, Kanishka and Mahowald, Kyle},
  booktitle = {The Cambridge Handbook of Experimental Syntax},
  editor    = {Goodall, Grant},
  edition   = {2},
  publisher = {Cambridge University Press},
  note      = {Under review. lingbuzz/010525},
  year      = {2026}
}</pre>
</details>
</div>
</div>

<div class="paper">
<div class="paper-title"><a href="https://arxiv.org/abs/2609.01491">GlossoGen: Emergent Language in Complex Multi-Agent LLM Interactions</a></div>
<div class="paper-authors">
  Elias Stengel-Eskin, Newton Sander, Carlos Bonetti, <strong>Sasha Boguraev</strong>, James Bowler, Hale Sirin, Simon Kirby
</div>
<div class="paper-venue">arXiv preprint</div>
<div class="paper-links">
<details class="paper-toggle">
<summary>Abstract</summary>
<p>The growing rate at which LLM agents interact with one another raises key questions about language evolution in multi-LLM-agent settings, with implications for safety and monitorability as well as for linguistic accounts of LLMs. To address these questions, we introduce GlossoGen, a novel platform for studying multi-agent language evolution in complex scenarios. Within GlossoGen, we build the SaveVeyru scenario, which requires agents with partial information to communicate under pressure. We find that language evolution does occur between LLM agents, that the resulting languages are compositional and morphologically productive, and that they deviate from the LLMs' English prior in ways that render them incomprehensible to humans. Moreover, we identify several qualities essential to this evolution: pressure towards efficiency; the strength of the models backing the agents; and access to a "postmortem" stage in which agents can agree on linguistic conventions. Importantly, we observe that different conditions govern the transmission of language to new agents. Specifically, we find that agents learn new languages from usage alone, take an active role in this learning, and that while stronger models are required for novel language emergence, weaker models can learn an existing language once it has emerged. Taken together, our results indicate that current LLMs have the potential for cumulative cultural evolution &mdash; previously attested only in humans &mdash; with mixed populations of agents developing capacities that go beyond their lowest common denominator.</p>
</details>
<details class="paper-toggle">
<summary>BibTeX</summary>
<pre>@article{stengeleskin2026glossogen,
  title   = {GlossoGen: Emergent Language in Complex Multi-Agent LLM Interactions},
  author  = {Stengel-Eskin, Elias and Sander, Newton and Bonetti, Carlos and Boguraev, Sasha and Bowler, James and Sirin, Hale and Kirby, Simon},
  journal = {arXiv preprint arXiv:2609.01491},
  year    = {2026}
}</pre>
</details>
</div>
</div>

<div class="paper">
<div class="paper-title"><a href="https://arxiv.org/abs/2608.28924">Causal Interventions Reveal Typologically Organized Syntactic Mechanisms in Multilingual Language Models</a></div>
<div class="paper-authors">
  <strong>Sasha Boguraev</strong>, Toshiki Nakai, Kyle Mahowald, Julius Steuer
</div>
<div class="paper-venue">arXiv preprint</div>
<div class="paper-links">
<details class="paper-toggle">
<summary>Abstract</summary>
<p>Linguistic theory has long recognized cross-linguistic syntactic regularities, leading to claims that these similar structures are processed by similar mechanisms. However, this hypothesis has been difficult to test empirically due to our lack of fine-grained, manipulable access of human processing mechanisms. In this work, we take advantage of techniques from mechanistic interpretability to study such a question in multilingual LMs. We first isolate language-internal mechanisms before attempting to transfer them cross-lingually. Across four models and three well-studied constructions (subject&ndash;verb number agreement, anaphoric pronoun gender agreement, and filler&ndash;gap object extraction) we find consistent cross-lingual mechanism transfer. We further find transfer to be graded, with more transfer between more typologically similar languages. We believe our work provides novel hypotheses about cross-linguistic syntactic structures and multilingual processing, and more broadly shows how the study of language models can help inform linguistic theory.</p>
</details>
<details class="paper-toggle">
<summary>BibTeX</summary>
<pre>@article{boguraev2026typologically,
  title   = {Causal Interventions Reveal Typologically Organized Syntactic Mechanisms in Multilingual Language Models},
  author  = {Boguraev, Sasha and Nakai, Toshiki and Mahowald, Kyle and Steuer, Julius},
  journal = {arXiv preprint arXiv:2608.28924},
  year    = {2026}
}</pre>
</details>
</div>
</div>

<div class="paper">
<div class="paper-title"><a href="https://arxiv.org/abs/2604.13950">Causal Drawbridges: Characterizing Gradient Blocking of Syntactic Islands in Transformer LMs</a></div>
<div class="paper-authors">
  <strong>Sasha Boguraev</strong>, Kyle Mahowald
</div>
<div class="paper-venue">COLM 2026</div>
<div class="paper-links">
<details class="paper-toggle">
<summary>Abstract</summary>
<p>We show how causal interventions in Transformer models provide insights into English syntax by focusing on a long-standing challenge for syntactic theory: syntactic islands. Extraction from coordinated verb phrases is often degraded, yet acceptability varies gradiently with lexical content (e.g., "I know what he hates art and loves" vs. "I know what he looked down and saw"). We show that modern Transformer language models replicate human judgments across this gradient. Using causal interventions that isolate functionally relevant subspaces in Transformer blocks, attention modules, and MLPs, we demonstrate that extraction from coordination islands engages the same filler-gap mechanisms as canonical wh-dependencies, but that these mechanisms are selectively blocked to varying degrees. By projecting a large corpus of unrelated text onto these causally identified subspaces, we derive a novel linguistic hypothesis: the conjunction "and" is represented differently in extractable versus non-extractable constructions, corresponding to expressions encoding relational dependencies versus purely conjunctive uses. These results illustrate how mechanistic interpretability can inform syntax, generating new hypotheses about linguistic representation and processing.</p>
</details>
<details class="paper-toggle">
<summary>BibTeX</summary>
<pre>@article{boguraev2026causal,
  title   = {Causal Drawbridges: Characterizing Gradient Blocking of Syntactic Islands in Transformer LMs},
  author  = {Boguraev, Sasha and Mahowald, Kyle},
  journal = {arXiv preprint arXiv:2604.13950},
  year    = {2026}
}</pre>
</details>
<a href="https://github.com/SashaBoguraev/causal-drawbridges" class="paper-github" target="_blank" rel="noopener" aria-label="GitHub repository">{% include github-icon.html %}</a>
</div>
</div>

<div class="paper">
<div class="paper-title"><a href="https://arxiv.org/abs/2602.23547">France or Spain or Germany or France: A Neural Account of Non-Redundant Redundant Disjunctions</a></div>
<div class="paper-authors">
  <strong>Sasha Boguraev<sup>*</sup></strong>, Qing Yao<sup>*</sup>, Kyle Mahowald
</div>
<div class="paper-venue">Proceedings of the Annual Meeting of the Cognitive Science Society, 48</div>
<div class="paper-links">
<details class="paper-toggle">
<summary>Abstract</summary>
<p>Sentences like "She will go to France or Spain, or perhaps to Germany or France." appear formally redundant, yet become acceptable in contexts such as "Mary will go to a philosophy program in France or Spain, or a mathematics program in Germany or France." While this phenomenon has typically been analyzed using symbolic formal representations, we aim to provide an account grounded in artificial neural mechanisms. We first present new behavioral evidence from humans and large language models demonstrating the robustness of this apparent non-redundancy across contexts. We then show that, in language models, redundancy avoidance arises from two interacting mechanisms: models learn to bind contextually relevant information to repeated lexical items, and Transformer induction heads selectively attend to these context-licensed representations. We argue that this neural explanation sheds light on the mechanisms underlying context-sensitive semantic interpretation, and that it complements existing symbolic analyses.</p>
</details>
<details class="paper-toggle">
<summary>BibTeX</summary>
<pre>@inproceedings{boguraev2026france,
  title     = {France or Spain or Germany or France: A Neural Account of Non-Redundant Redundant Disjunctions},
  author    = {Boguraev, Sasha and Yao, Qing and Mahowald, Kyle},
  booktitle = {Proceedings of the Annual Meeting of the Cognitive Science Society},
  volume    = {48},
  year      = {2026}
}</pre>
</details>
</div>
</div>

## 2025

<div class="paper award">
<div class="paper-title">🏆 <a href="https://aclanthology.org/2025.emnlp-main.1271/">Causal Interventions Reveal Shared Structure Across English Filler–Gap Constructions</a></div>
<div class="paper-authors"><strong>Sasha Boguraev</strong>, Christopher Potts, Kyle Mahowald</div>
<div class="paper-venue">EMNLP 2025 Outstanding Paper Award, Oral Spotlight</div>
<div class="paper-links">
<details class="paper-toggle">
<summary>Abstract</summary>
<p>Language Models (LMs) have emerged as powerful sources of evidence for linguists seeking to develop theories of syntax. In this paper, we argue that causal interpretability methods, applied to LMs, can greatly enhance the value of such evidence by helping us characterize the abstract mechanisms that LMs learn to use. Our empirical focus is a set of English filler–gap dependency constructions (e.g., questions, relative clauses). Linguistic theories largely agree that these constructions share many properties. Using experiments based in Distributed Interchange Interventions, we show that LMs converge on similar abstract analyses of these constructions. These analyses also reveal previously overlooked factors – relating to frequency, filler type, and surrounding context – that could motivate changes to standard linguistic theory. Overall, these results suggest that mechanistic, internal analyses of LMs can push linguistic theory forward.</p>
</details>
<details class="paper-toggle">
<summary>BibTeX</summary>
<pre>@inproceedings{boguraev-etal-2025-causal,
    title     = "Causal Interventions Reveal Shared Structure Across {E}nglish Filler{--}Gap Constructions",
    author    = "Boguraev, Sasha and Potts, Christopher and Mahowald, Kyle",
    booktitle = "Proceedings of the 2025 Conference on Empirical Methods in Natural Language Processing",
    month     = nov,
    year      = "2025",
    address   = "Suzhou, China",
    publisher = "Association for Computational Linguistics",
    url       = "https://aclanthology.org/2025.emnlp-main.1271/",
    doi       = "10.18653/v1/2025.emnlp-main.1271",
    pages     = "25021--25042"
}</pre>
</details>
<a href="https://github.com/SashaBoguraev/causal-filler-gap" class="paper-github" target="_blank" rel="noopener" aria-label="GitHub repository">{% include github-icon.html %}</a>
</div>
</div>

<div class="paper">
<div class="paper-title"><a href="https://escholarship.org/uc/item/5c03t5fp">Reinforcement learning produces efficient case-marking systems</a></div>
<div class="paper-authors"><strong>Sasha Boguraev</strong>, Katrin Erk, Kyle Mahowald, James Shearer, Steve Wechsler</div>
<div class="paper-venue">Proceedings of the Annual Meeting of the Cognitive Science Society, 47</div>
<div class="paper-links">
<details class="paper-toggle">
<summary>Abstract</summary>
<p>Many languages mark either accusative case (for objects of transitives) or ergative case (for subjects of transitives), but some "split ergative" languages mix the two systems depending on the type of nominal. It has been noted that these languages tend towards marking the less frequent case for each nominal type. This raises the question of what mechanism could underlie the emergence of such an efficient system. We propose a model that can provide an explanation, based on a simple reinforcement learning framework and simple assumptions about asymmetries between the kinds of nominals (e.g., pronouns vs. full noun phrases) that appear in subject vs. object position.</p>
</details>
<details class="paper-toggle">
<summary>BibTeX</summary>
<pre>@inproceedings{boguraev2025reinforcement,
  title     = {Reinforcement learning produces efficient case-marking systems},
  author    = {Boguraev, Sasha and Erk, Katrin and Mahowald, Kyle and Shearer, James and Wechsler, Steve},
  booktitle = {Proceedings of the Annual Meeting of the Cognitive Science Society},
  volume    = {47},
  year      = {2025}
}</pre>
</details>
</div>
</div>

## 2024

<div class="paper">
<div class="paper-title"><a href="https://arxiv.org/abs/2409.17005">Models Can and Should Embrace the Communicative Nature of Human-Generated Math</a></div>
<div class="paper-authors"><strong>Sasha Boguraev</strong>, Ben Lipkin, Leonie Weissweiler, Kyle Mahowald</div>
<div class="paper-venue">4th MATH-AI Workshop at NeurIPS'24</div>
<div class="paper-links">
<details class="paper-toggle">
<summary>Abstract</summary>
<p>Math is constructed by people for people: just as natural language corpora reflect not just propositions but the communicative goals of language users, the math data that models are trained on reflects not just idealized mathematical entities but rich communicative intentions. We contend that treating mathematics as situated linguistic communication offers benefits, particularly for language models: we present two main findings that language models interpret the equals sign in humanlike ways, generating different word problems for identical equations presented differently, and that they prefer logically equivalent proofs when ordered naturally.</p>
</details>
<details class="paper-toggle">
<summary>BibTeX</summary>
<pre>@inproceedings{boguraev2024models,
  title     = {Models Can and Should Embrace the Communicative Nature of Human-Generated Math},
  author    = {Boguraev, Sasha and Lipkin, Ben and Weissweiler, Leonie and Mahowald, Kyle},
  booktitle = {4th Workshop on Mathematical Reasoning and AI at NeurIPS'24},
  year      = {2024}
}</pre>
</details>
</div>
</div>

<div class="paper">
<div class="paper-title"><a href="https://SashaBoguraev.github.io/files/BoguraevHonorsThesis.pdf">What Do You Mean by That? - Idiolects, Casual Miscommunication, and the Evolutionary Fitness of Languages</a></div>
<div class="paper-authors"><strong>Sasha Boguraev</strong></div>
<div class="paper-venue">Undergraduate Honors Thesis</div>
<div class="paper-links">
<details class="paper-toggle">
<summary>BibTeX</summary>
<pre>@mastersthesis{boguraev2024what,
  title  = {What Do You Mean by That? - Idiolects, Casual Miscommunication, and the Evolutionary Fitness of Languages},
  author = {Boguraev, Sasha},
  school = {Cornell University},
  type   = {Undergraduate Honors Thesis},
  year   = {2024}
}</pre>
</details>
</div>
</div>
