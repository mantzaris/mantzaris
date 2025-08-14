# Hi, I'm Alexander V. Mantzaris! 😃

I'm an academic (researcher) and developer focusing on Julia Lang packages, Electron.js apps :electron:, social physics simulations 🏙️, and useful tools. Below, I've organized my key repositories by category. Check them out—many include detailed docs, examples, and ways to contribute.

## Julia Language Packages
These tested tools have been peer-reviewed by the Journal of Open Source Software (JOSS). Great for data processing, NLP benchmarks, and more.

- **[WunDeeDB.jl](https://github.com/mantzaris/WunDeeDB.jl)**: A zero-config embedded vector database with WAL support. Useful for lightweight AI/ML embeddings. Ideal for vector search that scaled with transactions (which come with a cost for the confidence in data integrity) (JOSS-reviewed; in General registry)  
  ![Stars](https://img.shields.io/github/stars/mantzaris/WunDeeDB.jl) ![Forks](https://img.shields.io/github/forks/mantzaris/WunDeeDB.jl)  
  *tip*: `using Pkg; Pkg.add("WunDeeDB")`—try the examples for instant vector search.

- **[LMDiskANN.jl](https://github.com/mantzaris/LMDiskANN.jl)**: Julia implementation of Low Memory Disk ANN for efficient nearest-neighbor searches. (JOSS-reviewed; in General registry)  
  ![Stars](https://img.shields.io/github/stars/mantzaris/LMDiskANN.jl) ![Forks](https://img.shields.io/github/forks/mantzaris/LMDiskANN.jl)  
  * tip*: `using Pkg; Pkg.add("LMDiskANN")` Ideal for large datasets and speed where transactions are not needed. 

- **[BenchmarkDataNLP.jl](https://github.com/mantzaris/BenchmarkDataNLP.jl)**: Generates synthetic text (e.g., via Context-Free Grammars) with tunable complexity to test NLP methods like LLMs.
  ![Stars](https://img.shields.io/github/stars/mantzaris/BenchmarkDataNLP.jl) ![Forks](https://img.shields.io/github/forks/mantzaris/BenchmarkDataNLP.jl)
  *Newcomer tip*: Parameterize complexity to stress-test your models on less complex data before going into more complex natural corpora.



## Tagasaurus Electron.js Apps :electron:
Two finished desktop apps for media tagging and organization. Built with Electron.js for cross-platform use—download releases for Linux/Windows.

- **[Tagasaurus](https://github.com/mantzaris/Tagasaurus)**: Tag your planet with semantic search and machine learning. Search and annotate your media files with ease keeping all the data locally.
  ![Stars](https://img.shields.io/github/stars/mantzaris/Tagasaurus) ![Forks](https://img.shields.io/github/forks/mantzaris/Tagasaurus)  
  
- **[TagasaurusLegacy](https://github.com/mantzaris/TagasaurusLegacy)**: The original "Tag your Planet" app—gateway to your semantic multiverse. Here memes and emotions take a first place position in search with specific features to allow for users to search for the impact of memes on certain keywords by utilizing a bi-partite graph.
  ![Stars](https://img.shields.io/github/stars/mantzaris/TagasaurusLegacy) ![Forks](https://img.shields.io/github/forks/mantzaris/TagasaurusLegacy)



## Social Simulation Code from Papers 🏙️
Repos with code implementations from my research papers on social dynamics, entropy, and models like Schelling. Useful for simulations in physics/social sciences—many include Jupyter notebooks for reproducibility.

- **[Eurovision](https://github.com/mantzaris/eurovision)**: Investigating the collusion between countries for the complete historical data trajectory of the Eurovision Song Contest 
  ![Stars](https://img.shields.io/github/stars/mantzaris/eurovision) ![Forks](https://img.shields.io/github/forks/mantzaris/eurovision)  
  *featured in the economist magazine online and in print: https://www.economist.com/blogs/graphicdetail/2018/05/daily-chart-7 , https://www.economist.com/news/europe/21742117-continents-annual-singing-tournament-becoming-increasingly-partisan-neighbourly-voting . tip*: Run the notebooks to visualize the one-way and 2-way (collusion) biases.

- **[EurovisionBias](https://github.com/mantzaris/eurovisionBias)**: Investigating the collusion between countries with both the positive and negative biases. So that the tendencies for countries to allocate significantly more or significantly less can be seen.
  ![Stars](https://img.shields.io/github/stars/mantzaris/eurovisionBias) ![Forks](https://img.shields.io/github/forks/mantzaris/eurovisionBias)  
  *tip*: Run the notebooks to visualize the full range of biases.

- **[Schelling Consistent](https://github.com/mantzaris/schellingEntropyImproved)**: Addresses the issue of a decreasing entropy trajectory in the canonical Schelling simulation by introducing a dual dynamic with monetary exchanges so the arrow of time is respected.
  ![Stars](https://img.shields.io/github/stars/mantzaris/schellingEntropyImproved) ![Forks](https://img.shields.io/github/forks/mantzaris/schellingEntropyImproved)  

- **[Rat Utopia Modeling](https://github.com/mantzaris/RatUtopia)**: Explores how the population collapse in the Rat Utopia experiment (Universe 25) can be simulated through a degeneration of the entropy of the hierarchy given the full visibility the rats had in the enclosure.
  ![Stars](https://img.shields.io/github/stars/mantzaris/RatUtopia) ![Forks](https://img.shields.io/github/forks/mantzaris/RatUtopia)  



## Miscellaneous Useful Code
Handy packages and templates for everyday productivity, like LaTeX setups.

- **[Nighttime LaTeX Template](https://github.com/mantzaris/latexSonarTheme)**: A sonar themed dark-mode friendly LaTeX template for documents—reduces eye strain at night.
  *Newcomer tip*: Copy the .tex file and compile with pdflatex; perfect for late-night writing.

- **[UCF Style LaTeX Slides Template](https://github.com/mantzaris/PegasusBeamer)**: Beamer template in University of Central Florida style for presentations.  
  *Newcomer tip*: Customize the department logo.



## Get Involved
- Star ⭐ or fork repos you're interested in!
- Open issues/PRs if you spot improvements.

Thanks for visiting! 👏
