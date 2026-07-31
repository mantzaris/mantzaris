# Hi, I'm Alexander V. Mantzaris

I am an academic researcher and software developer working in machine learning, natural language processing, computational social science, social physics, and scientific software.

My open source work includes Julia packages, language-model research, local-first desktop applications, and reproducible code accompanying academic publications.

## Featured Project

### [KeemenaLM.jl](https://github.com/mantzaris/KeemenaLM.jl)

A proof-of-concept language model implemented in pure Julia. KeemenaLM.jl provides tools for preparing corpora, training tokenizers, training GPT-style decoder models, saving checkpoints, exporting model bundles, evaluating behavior, and generating text.

The project demonstrates that a substantial language-model pipeline can be implemented directly within the Julia ecosystem. It is a research platform and working proof of concept rather than a production chatbot.

**Status:** Research proof of concept | Install from GitHub

![Stars](https://img.shields.io/github/stars/mantzaris/KeemenaLM.jl.svg) ![Forks](https://img.shields.io/github/forks/mantzaris/KeemenaLM.jl.svg)

```julia
using Pkg
Pkg.add(url = "https://github.com/mantzaris/KeemenaLM.jl")
```

## Julia Language Packages

The status labels distinguish publication in the peer-reviewed Journal of Open Source Software from registration in the Julia General package registry.

### [WunDeeDB.jl](https://github.com/mantzaris/WunDeeDB.jl)

A zero-configuration embedded vector database with SQLite, write-ahead logging, transactional storage, and vector-search support.

**Status:** [Published in JOSS](https://joss.theoj.org/papers/10.21105/joss.08033) | [Julia General](https://github.com/JuliaRegistries/General/tree/master/W/WunDeeDB)

![Stars](https://img.shields.io/github/stars/mantzaris/WunDeeDB.jl.svg) ![Forks](https://img.shields.io/github/forks/mantzaris/WunDeeDB.jl.svg)

```julia
using Pkg
Pkg.add("WunDeeDB")
```

### [LMDiskANN.jl](https://github.com/mantzaris/LMDiskANN.jl)

A memory-efficient Julia implementation of Low Memory Disk Approximate Nearest Neighbor search using memory-mapped vector and graph storage.

**Status:** [Published in JOSS](https://joss.theoj.org/papers/10.21105/joss.08199) | [Julia General](https://github.com/JuliaRegistries/General/tree/master/L/LMDiskANN)

![Stars](https://img.shields.io/github/stars/mantzaris/LMDiskANN.jl.svg) ![Forks](https://img.shields.io/github/forks/mantzaris/LMDiskANN.jl.svg)

```julia
using Pkg
Pkg.add("LMDiskANN")
```

### [KeemenaPreprocessing.jl](https://github.com/mantzaris/KeemenaPreprocessing.jl)

Unicode-aware text cleaning, normalization, tokenization, vectorization, offset tracking, and controlled-memory corpus preprocessing for Julia NLP workflows.

**Status:** [Published in JOSS](https://joss.theoj.org/papers/10.21105/joss.09348) | [Julia General](https://github.com/JuliaRegistries/General/tree/master/K/KeemenaPreprocessing)

![Stars](https://img.shields.io/github/stars/mantzaris/KeemenaPreprocessing.jl.svg) ![Forks](https://img.shields.io/github/forks/mantzaris/KeemenaPreprocessing.jl.svg)

```julia
using Pkg
Pkg.add("KeemenaPreprocessing")
```

### [KeemenaSubwords.jl](https://github.com/mantzaris/KeemenaSubwords.jl)

A Julia-native subword tokenization library supporting BPE, byte-level BPE, WordPiece, Unigram, SentencePiece, tiktoken, and Hugging Face tokenizer formats.

**Status:** [Julia General](https://github.com/JuliaRegistries/General/tree/master/K/KeemenaSubwords)

![Stars](https://img.shields.io/github/stars/mantzaris/KeemenaSubwords.jl.svg) ![Forks](https://img.shields.io/github/forks/mantzaris/KeemenaSubwords.jl.svg)

```julia
using Pkg
Pkg.add("KeemenaSubwords")
```

### [BenchmarkDataNLP.jl](https://github.com/mantzaris/BenchmarkDataNLP.jl)

Generates controlled synthetic text datasets using grammars, state machines, structured triples, and parameterized templates for NLP benchmarking.

**Status:** [Published in JOSS](https://joss.theoj.org/papers/10.21105/joss.07844) | Install from GitHub

![Stars](https://img.shields.io/github/stars/mantzaris/BenchmarkDataNLP.jl.svg) ![Forks](https://img.shields.io/github/forks/mantzaris/BenchmarkDataNLP.jl.svg)

```julia
using Pkg
Pkg.add(url = "https://github.com/mantzaris/BenchmarkDataNLP.jl")
```

## Tagasaurus Desktop Applications

Local-first Electron applications for organizing, tagging, and searching personal media collections.

### [Tagasaurus](https://github.com/mantzaris/Tagasaurus)

An offline-first desktop application for semantic search and machine-learning-assisted organization of photos, videos, audio, GIFs, and PDFs.

![Stars](https://img.shields.io/github/stars/mantzaris/Tagasaurus.svg) ![Forks](https://img.shields.io/github/forks/mantzaris/Tagasaurus.svg)

### [TagasaurusMemetic](https://github.com/mantzaris/TagasaurusMemetic)

The original Tag Your Planet application, with tools for exploring relationships among media, keywords, memes, and emotions using semantic search and bipartite graphs.

![Stars](https://img.shields.io/github/stars/mantzaris/TagasaurusMemetic.svg) ![Forks](https://img.shields.io/github/forks/mantzaris/TagasaurusMemetic.svg)

## Computational Social Science and Social Physics

Research code and reproducibility materials related to voting behavior, segregation, entropy, social hierarchy, and population collapse.

### [Eurovision](https://github.com/mantzaris/eurovision)

Analysis of historical Eurovision Song Contest voting data, including voting biases and reciprocal voting relationships between countries.

Associated publication: [Examining Collusion and Voting Biases Between Countries During the Eurovision Song Contest Since 1957](https://www.jasss.org/21/1/1.html)

Featured by *The Economist*:

- [Which countries have the most biased Eurovision voters?](https://www.economist.com/blogs/graphicdetail/2018/05/daily-chart-7)
- [The continent's annual singing tournament is becoming increasingly partisan](https://www.economist.com/news/europe/21742117-continents-annual-singing-tournament-becoming-increasingly-partisan-neighbourly-voting)

![Stars](https://img.shields.io/github/stars/mantzaris/eurovision.svg) ![Forks](https://img.shields.io/github/forks/mantzaris/eurovision.svg)

### [EurovisionBias](https://github.com/mantzaris/eurovisionBias)

Analysis of both positive and negative Eurovision voting biases, including preference, neglect, reciprocity, and their relationships with competition outcomes.

Associated publication: [Preference and neglect amongst countries in the Eurovision Song Contest](https://link.springer.com/article/10.1007/s42001-018-0020-2)

![Stars](https://img.shields.io/github/stars/mantzaris/eurovisionBias.svg) ![Forks](https://img.shields.io/github/forks/mantzaris/eurovisionBias.svg)

### [Schelling Entropy Improved](https://github.com/mantzaris/schellingEntropyImproved)

A modification of the Schelling segregation model that introduces monetary exchanges and an associated entropy-producing process.

Associated publication: [Incorporating a monetary variable into the Schelling model addresses the issue of a decreasing entropy trace](https://www.nature.com/articles/s41598-020-74125-6)

![Stars](https://img.shields.io/github/stars/mantzaris/schellingEntropyImproved.svg) ![Forks](https://img.shields.io/github/forks/mantzaris/schellingEntropyImproved.svg)

### [Rat Utopia](https://github.com/mantzaris/RatUtopia)

A computational exploration of population collapse in the Universe 25 Rat Utopia experiment through social hierarchy, crowding, visibility, and organizational entropy.

![Stars](https://img.shields.io/github/stars/mantzaris/RatUtopia.svg) ![Forks](https://img.shields.io/github/forks/mantzaris/RatUtopia.svg)

## LaTeX and Presentation Tools

### [Nighttime LaTeX Template](https://github.com/mantzaris/latexSonarTheme)

A sonar-themed, dark-mode-friendly LaTeX template for nighttime writing and editing.

### [UCF Style LaTeX Slides](https://github.com/mantzaris/PegasusBeamer)

A University of Central Florida styled Beamer theme for lectures, conference presentations, and research talks.

## Journal of Open Source Software Publications

1. [KeemenaPreprocessing.jl: Unicode-Robust Cleaning, Multi-Level Tokenisation and Streaming Offset Bundling for Julia NLP](https://joss.theoj.org/papers/10.21105/joss.09348)
2. [WunDeeDB.jl: An Easy to Use, Zero Config, WAL, SQLite Backend Vector Database](https://joss.theoj.org/papers/10.21105/joss.08033)
3. [LMDiskANN.jl: An Implementation of the Low Memory Disk Approximate Nearest Neighbors Search Algorithm](https://joss.theoj.org/papers/10.21105/joss.08199)
4. [BenchmarkDataNLP.jl: Synthetic Data Generation for NLP Benchmarking](https://joss.theoj.org/papers/10.21105/joss.07844)

View my complete [JOSS author page](https://joss.theoj.org/papers/by/Alexander%20V.%20Mantzaris).

## Contributing

Contributions, issue reports, documentation improvements, and reproducibility checks are welcome.

- Open issues for bugs or concrete feature proposals.
- Submit focused pull requests with tests and documentation.
- Cite the associated software paper when using a JOSS-published package.
