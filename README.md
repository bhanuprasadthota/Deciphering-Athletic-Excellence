# Deciphering Athletic Excellence

Principal Component Analysis (PCA) of the Olympic Heptathlon dataset. This project reduces the dimensionality of seven athletic event scores to uncover the underlying components that define elite athletic performance.

## Overview

The Heptathlon consists of seven events: hurdles, high jump, shot put, 200m, long jump, javelin, and 800m. PCA reveals how these events correlate and which principal components best capture overall athletic excellence.

## Techniques Used

- Exploratory data analysis with scatter plots and correlation panels
- Categorical binning of performance scores (Low / Medium / High)
- Train/test split
- Principal Component Analysis (PCA) via `prcomp`
- Orthogonality verification of principal components
- Biplot visualization

## Dataset

- **Source:** `heptathlon` dataset from the `HSAUR` R package
- **Events:** hurdles, highjump, shot, run200m, longjump, javelin, run800m
- **Athletes:** Olympic-level competitors

## Tech Stack

| Tool | Purpose |
|------|---------|
| R | Core language |
| HSAUR | Heptathlon dataset |
| psych | Correlation panels (pairs.panels) |
| base R | PCA via prcomp, biplot |

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/bhanuprasadthota/Deciphering-Athletic-Excellence.git
   cd Deciphering-Athletic-Excellence
   ```

2. Open R or RStudio and install required packages:
   ```r
   install.packages(c(HSAUR, psych))
   ```

3. Open and knit `HeptathlonDataAnalysis.Rmd` in RStudio.

## Key Findings

- PCA reduced 7 event dimensions to a small set of principal components explaining the majority of variance
- First principal component strongly captures overall athletic ability across events
- Scatter plots and correlation panels revealed strong inter-event correlations among speed and power disciplines

## License

MIT License — see [LICENSE](LICENSE) for details.
