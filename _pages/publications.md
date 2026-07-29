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
