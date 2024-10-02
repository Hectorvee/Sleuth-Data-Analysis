# Statistical Sleuth Projects

## Overview
This repository contains a collection of case studies and exercises derived from *The Statistical Sleuth: A Course in Methods of Data Analysis* (Third Edition) by Fred L. Ramsey and Daniel W. Schafer. Each case study illustrates various statistical analysis techniques, utilizing R and RMarkdown to promote reproducible research.

## Purpose
The aim of this project is to apply statistical concepts learned in the course to real-world data, allowing for practical understanding and application of methods such as hypothesis testing, regression analysis, and data visualization. 

## Repository Structure
The repository is organized as follows:

```
📦 Statistical-Sleuth-Projects/
├── 📜 README.md
├── 📁 CaseStudy1_HypothesisTesting/
│   ├── 📁 data/
│   ├── 📄 analysis.Rmd
│   ├── 📄 analysis.html
│   └── 📄 analysis.pdf
├── 📁 CaseStudy2_RegressionAnalysis/
│   ├── 📁 data/
│   ├── 📄 analysis.Rmd
│   ├── 📄 analysis.html
│   └── 📄 analysis.pdf
└── etc...
```

### Description of Folders
- **Case Study Folders**: Each folder corresponds to a specific case study, containing:
  - `data/`: Datasets used for analysis.
  - `analysis.Rmd`: The RMarkdown file that contains the analysis narrative and code.
  - `analysis.html` / `analysis.pdf`: Generated reports from the RMarkdown analysis.

## Getting Started
To reproduce the analyses or run the RMarkdown files, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Hectorvee/Statistical-Sleuth-Projects.git
   ```
   
2. **Set Up Your R Environment**:
   Ensure you have R and RStudio installed on your machine. You may also need to install required R packages:
   ```r
   install.packages(c("tidyverse", "knitr", "rmarkdown"))
   ```

3. **Open an RMarkdown File**:
   Open any `analysis.Rmd` file in RStudio. 

4. **Render the Report**:
   Click the **Knit** button in RStudio or use the following command in R:
   ```r
   rmarkdown::render("path/to/analysis.Rmd", "html_document")
   ```

## Case Studies
### 1. Hypothesis Testing on Environmental Data
- **Description**: This case study explores hypothesis testing techniques applied to environmental datasets.
- **Key Techniques**: T-tests, ANOVA, p-values, confidence intervals.

### 2. Regression Analysis on Sales Data
- **Description**: This case study analyzes the relationship between different sales factors using regression models.
- **Key Techniques**: Linear regression, residual analysis, model diagnostics.

## Contributing
Contributions are welcome! If you have suggestions for improvements or additional case studies, feel free to create an issue or submit a pull request.

## License
This repository is licensed under the [MIT License](LICENSE).

## Contact
For any inquiries or feedback, please contact me at vukosi1632@gmail.com.

## Acknowledgements
Special thanks to Fred L. Ramsey and Daniel W. Schafer for their contributions to statistical education through *The Statistical Sleuth*.
