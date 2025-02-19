# climate change's local impact: Statistical Inference and Confidence Intervals Analysis

## Overview
This project explores confidence intervals in statistical inference, focusing on analyzing public opinion about climate change's local impact. Using simulated Pew Research data, the analysis demonstrates how to construct and interpret confidence intervals, exploring their properties under different confidence levels and sample sizes.

## Key Features
- Bootstrap confidence interval construction
- Analysis of confidence level effects
- Sample size impact investigation
- Visualization of multiple confidence intervals
- Interactive simulation using Shiny app
- Exploration of bootstrap sample size effects

## Technologies Used
- R Programming Language
- Libraries:
  - tidyverse (for data manipulation and visualization)
  - openintro (for datasets)
  - infer (for bootstrap resampling and confidence intervals)
  - dplyr (for data manipulation)
  - tinytex (for PDF document generation)
  - shiny (for interactive visualization)

## Project Structure
The project is organized as an R Markdown document containing:
- Initial data setup and population creation
- Bootstrap confidence interval calculations
- Multiple confidence level comparisons
- Sample size effect analysis
- Interactive visualization components

## Key Concepts Explored

### Confidence Intervals
- Construction using bootstrapping
- Interpretation of confidence levels
- Relationship between interval width and confidence level
- Impact of sample size on interval width

### Bootstrapping Process
1. Sample with replacement from original data
2. Calculate statistic of interest
3. Repeat many times
4. Use percentiles to construct confidence intervals

### Key Findings
1. Confidence Level Effects:
   - Higher confidence levels produce wider intervals
   - Lower confidence levels produce narrower but less reliable intervals
   - Trade-off between precision and confidence

2. Sample Size Impact:
   - Larger samples lead to narrower confidence intervals
   - More precise estimation with increased sample size
   - Demonstration of the relationship between sample size and estimation precision

3. Bootstrap Sample Size Effects:
   - Number of bootstrap samples affects stability but not interval width
   - Primary determinant of interval width is original sample size
   - Importance of adequate bootstrap replications

## Getting Started

### Prerequisites
- R (version 4.0 or higher recommended)
- RStudio (for R Markdown compilation)
- Required R packages listed above

### Installation
```R
# Install required packages
install.packages(c("tidyverse", "openintro", "infer", "dplyr", "tinytex", "shiny"))
```

### Usage
1. Clone the repository
2. Open the R Markdown file in RStudio
3. Install required packages if not already installed
4. Run the entire document or individual chunks as needed

## Reproducibility
The analysis uses set.seed(341124) for reproducibility. All random sampling can be replicated exactly by using this seed value.

## Data Description
The project uses simulated data based on a 2019 Pew Research report about climate change perceptions. The population consists of 100,000 simulated responses, with:
- 62,000 responses indicating "Yes" (climate change affects local community)
- 38,000 responses indicating "No"

## Visualizations
The project includes multiple visualization types:
- Population distribution bar plots
- Sample distribution visualizations
- Confidence interval plots
- Interactive Shiny app for exploring different parameters

## Results and Conclusions
1. Confidence level directly affects interval width
2. Sample size significantly impacts precision of estimates
3. Bootstrap sample size mainly affects stability, not width
4. Trade-off exists between confidence level and precision

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
- Based on Pew Research data from 2019
- Inspired by statistical inference educational materials
- Built using R and the tidyverse ecosystem

## Contact
For questions or feedback about this project, please open an issue in the repository.


Depoloyed app at https://openintro.shinyapps.io/sampling_distributions/.
![1](https://github.com/user-attachments/assets/e299588f-0a75-49a4-8605-fb889ff79a88)![Screenshot from 2025-02-18 22-01-11](https://github.com/user-attachments/assets/4b4f2446-0948-43f6-8429-9b6009abb999)
![Screenshot from 2025-02-18 22-01-39](https://github.com/user-attachments/assets/4bc2a2c8-5ed8-4dbd-bd6c-2dbbd155423b)
![Screenshot from 2025-02-18 22-01-59](https://github.com/user-attachments/assets/67e96dd0-bc3e-47f2-812c-884c81e023c6)
![Screenshot from 2025-02-18 22-02-15](https://github.com/user-attachments/assets/2d4351b0-a717-4eaf-a890-3098dc6b27a9)
![Screenshot from 2025-02-18 22-02-43](https://github.com/user-attachments/assets/b87de7a7-00fe-4671-86f4-7213bdc5c413)
![preview](https://github.com/user-attachments/assets/033ecb38-6784-46bc-a6f3-ecb37b40aa40)
![Screenshot from 2025-02-18 22-41-05](https://github.com/user-attachments/assets/76a1da5f-03ee-47f4-84f1-28![8f31ebf6-b74d-4410-8a01-6cf00583c726](https://github.com/user-attachments/assets/13fbf820-e853-4943-a991-153768dcba8e)
8065ea887c)

![2](https://github.com/user-attachments/assets/a494e433-b7bf-4b1f-9c47-b4b441488780)

![Screenshot from 2025-02-18 21-34-59](https://github.com/user-attachments/assets/b6a4676b-8645-4486-8e0d-33a3101ae7fd)

