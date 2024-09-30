# A/B Testing and Causal Inference in Webpage Design Optimization

## Overview
This project explores the application of causal inference techniques to A/B testing for webpage design optimization. The goal is to assess whether splitting a download button into platform-specific options increases user engagement. Using real-world web traffic data, the analysis includes hypothesis testing, simulation, and statistical modeling to derive insights.

## Motivation
User engagement and conversion rate optimization are critical metrics in web design. Through this project, I aim to leverage causal analysis techniques to understand user behavior better and make data-driven decisions for optimizing user interfaces.

## Technologies Used
- **R** for statistical analysis
- **R Markdown** for documentation and report generation
- **gtools** for randomization and permutation generation
- **Data visualization** using built-in R libraries

## Project Structure
- **src/**: Source code for the data analysis and hypothesis testing
- **data/**: Contains the experimental web traffic data (`expdta-click.csv`)
- **results/**: Generated plots, simulation results, and tables
- **README.md**: This documentation

## Methodology
The project follows a structured approach:
- **Formulating hypotheses**: Test whether splitting the download button increases clicks by 2000.
- **Randomized experiment**: Simulate potential outcomes under both versions of the webpage.
- **Statistical analysis**: Apply Fisher's exact test, Neyman variance estimators, and confidence intervals to determine the effectiveness of the webpage redesign.

## Results
The analysis found a significant difference between the two webpage designs, supporting the hypothesis that splitting the download button increases user engagement by more than 2000 clicks. Confidence intervals and Neyman variance estimators reinforce the robustness of these results.

## How to Use
To run the analysis:
1. Install R and RStudio.
2. Clone this repository.
3. Open `analysis.Rmd` in RStudio.
4. Run the code chunks and generate the final report by clicking "Knit" to PDF or HTML.

## Conclusion
This project demonstrates the importance of applying rigorous statistical methods to optimize user experience. By using A/B testing and causal inference, I was able to confirm that the proposed design changes led to a measurable improvement in user engagement.
