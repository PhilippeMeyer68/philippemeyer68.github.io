---
layout: default
title: "Codes"
permalink: /codes/
---

<section class="section">
  <div class="section-header">
    <h3 class="section-title">Codes</h3>
  </div>
  <p>
    Here are the codes I have developed or co-developed. They range from Python packages to repositories supporting my papers, mainly in cheminformatics and synthetic biology. Each name links to its GitHub repository, and the associated paper, when there is one, is linked after the description.
  </p>
<ul>

<li>
  2026 – <strong><a href="https://github.com/brsynth/morganbiopilot" target="_blank" rel="noopener">Agentic Retrobiosynthesis</a>: </strong>
  MorganBioPilot, a retrobiosynthesis framework in which a <strong>large language model</strong> agent (Qwen2.5-7B-Instruct, prompted or <strong>LoRA</strong> fine-tuned) chooses which molecule to expand next, compared with breadth-first, depth-first, greedy best-first and <strong>Monte Carlo tree search</strong> (UCT) on a deterministic engine in ECFP fingerprint space.
  <a href="https://arxiv.org/abs/2608.30702" target="_blank" rel="noopener">Paper</a>
</li>

<li>
  2026 – <strong><a href="https://github.com/brsynth/morganrxn" target="_blank" rel="noopener">Vectorized Chemical Reactions</a>: </strong>
  morganrxn, a Python package representing chemical and enzymatic reactions as vectors in ECFP fingerprint space, both for fast applicability filtering of reaction rules and as features for <strong>machine learning</strong> classifiers (<strong>logistic regression</strong>, <strong>random forest</strong>, <strong>gradient boosting</strong>, <strong>extra-trees</strong>, <strong>MLP</strong>) predicting reaction classes and EC numbers.
  <a href="https://doi.org/10.26434/chemrxiv.15006884/v1" target="_blank" rel="noopener">Paper</a>
</li>

<li>
  2026 – <strong><a href="https://github.com/brsynth/mutant-covid" target="_blank" rel="noopener">Metabolic Biosensors</a>: </strong>
  COVID-19 prognosis and diagnosis from the full growth curves of engineered <em>E. coli</em> biosensor strains, with <strong>machine learning</strong> (<strong>SVM</strong>, <strong>logistic regression</strong>, <strong>XGBoost</strong>), <strong>deep learning</strong> time-series models (<strong>1D CNN</strong>, <strong>temporal convolutional networks</strong>) with <strong>FiLM</strong> conditioning and multi-strain fusion, and <strong>generalized additive mixed models</strong> (GAMMs).
  <a href="https://doi.org/10.64898/2026.08.04.740108" target="_blank" rel="noopener">Paper</a>
</li>

<li>
  2026 – <strong><a href="https://github.com/brsynth/bacterial_rc" target="_blank" rel="noopener">Bacterial Reservoir Computing</a>: </strong>
  Living <em>E. coli</em> used as a <strong>reservoir computer</strong>: a <strong>neural network</strong> encodes input features as growth media, <strong>ridge regression</strong> reads out the bacterial growth, and an <strong>artificial metabolic network</strong> (AMN), a <strong>hybrid neural–mechanistic model</strong>, predicts growth in silico, with <strong>SVM</strong>, <strong>MLP</strong> and <strong>XGBoost</strong> as baselines and for COVID-19 patient classification.
  <a href="https://www.cell.com/cell-systems/fulltext/S2405-4712(26)00136-5" target="_blank" rel="noopener">Paper</a>
</li>

<li>
  2025 – <strong><a href="https://github.com/brsynth/molecule-signature" target="_blank" rel="noopener">Deterministic Molecular Reverse Engineering</a>: </strong>
  molecule-signature, a Python package available on <a href="https://anaconda.org/conda-forge/molecule-signature" target="_blank" rel="noopener">conda-forge</a> that recovers molecular structures from their ECFP (Morgan) fingerprints by learning-free <strong>deterministic enumeration</strong> based on <strong>molecular signatures</strong> and <strong>linear Diophantine systems</strong>.
  <a href="https://doi.org/10.1186/s13321-025-01074-5" target="_blank" rel="noopener">Paper</a>, <a href="https://philippemeyer68.pythonanywhere.com" target="_blank" rel="noopener">Application</a>
</li>

<li>
  2025 – <strong><a href="https://github.com/brsynth/molecule-signature-paper" target="_blank" rel="noopener">Generative Molecular Reverse Engineering</a>: </strong>
  A <strong>generative encoder–decoder transformer</strong> that produces molecular structures (SMILES) from ECFP fingerprints, <strong>pre-trained</strong> on eMolecules and <strong>fine-tuned</strong> on MetaNetX metabolites, decoded with <strong>beam search</strong> and benchmarked against deterministic enumeration.
  <a href="https://doi.org/10.1186/s13321-025-01074-5" target="_blank" rel="noopener">Paper</a>
</li>

<li>
  2025 – <strong><a href="https://github.com/PhilippeMeyer68/linear-diophantine" target="_blank" rel="noopener">Linear Diophantine Systems</a>: </strong>
  lineardiophantine, a Python package that solves <strong>linear Diophantine systems</strong> over the natural numbers with the <strong>Contejean–Devie algorithm</strong>, and over the integers with the <strong>Smith normal form</strong>.
</li>

<li>
  2024 – <strong><a href="https://github.com/PhilippeMeyer68/glyph-SNN" target="_blank" rel="noopener">Glyph Similarities</a>: </strong>
  A <strong>siamese convolutional neural network</strong>, trained on Omniglot with <strong>data augmentation</strong>, that measures similarities between glyphs and writing systems, followed by <strong>multidimensional scaling</strong> and <strong>Ward hierarchical clustering</strong> of 51 historical European, Mediterranean and Middle Eastern scripts.
  <a href="https://aclanthology.org/2024.lt4hala-1.12/" target="_blank" rel="noopener">Paper</a>, <a href="{{ '/glyph.html' | relative_url }}" target="_blank" rel="noopener">3D view</a>
</li>

<li>
  2023 – <strong><a href="https://github.com/PhilippeMeyer68/TDA_Morphotypes" target="_blank" rel="noopener">Human Body Shapes</a>: </strong>
  <strong>Topological data analysis</strong> of 3D human body scans, with <strong>persistence diagrams</strong> compared through <strong>bottleneck</strong> and <strong>Wasserstein</strong> distances and vectorized as <strong>persistence silhouettes</strong>, for anomaly detection and body shape classification.
  <a href="https://doi.org/10.3390/a16030161" target="_blank" rel="noopener">Paper</a>
</li>

<li>
  2022 – <strong>Anthropometric Data Explorer: </strong>
  ExploRed, an <strong>R Shiny</strong> application for exploring the French national sizing survey (Campagne Nationale de Mensuration, 2004–2006) and its ~11 600 3D body scans, served from <strong>sodium-encrypted</strong> data unlocked by a password acting as the private key. It provides <strong>descriptive statistics</strong>, <strong>correlation</strong> and <strong>hypothesis testing</strong>, interactive trivariate scatter plots, body scans rendered as <strong>point clouds</strong> or <strong>meshes</strong>, and <strong>survey calibration</strong> of measurement means on INSEE census margins over 2001–2021, all stratified by sex, age class, region and socio-professional category, and is <strong>deployed with Docker</strong> on an internal server for IFTH and UTT users.
  <details class="code-demo">
    <summary>Watch a demo of the application</summary>
    <video controls preload="none" playsinline width="560"
           poster="{{ '/assets/video/explored_poster.jpg' | relative_url }}">
      <source src="{{ '/assets/video/explored_1_1.mp4' | relative_url }}" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </details>
</li>
</ul>

</section>
