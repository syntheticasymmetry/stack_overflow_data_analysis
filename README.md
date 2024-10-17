# stack_overflow_data_analysis
This project analyzes the 2024 StackOverflow Survey data to explore three key business questions:
- differences in attitudes towards AI between junior developers and experienced professionals
- popular technologies among those who is learning to code
- how company size affects remote work preferences across different regions

Libriaries used:
- pandas
- numpy
- matplotlib

Files in the repository:
- README.md: Overview of the project and repository contents
- data/
  - survey_results_schema.csv: A schema file describing the dataset structure
  - survey_questions.pdf: A file with survey questions and methology
  - Dataset: The main dataset is too large to include here, but it can be downloaded directly from the [Stack Overflow Developer Survey 2024](https://survey.stackoverflow.co/)
- notebooks/: Contains Jupyter notebooks with data wrangling, analysis and visualizations
  - StackOverflow-Analysis.ipynb: Main notebook with the analysis based on the 2024 Stack Overflow Developer Survey
  - StackOverflow-Analysis_V2.ipynb: Updated notebook (added docstrings and visualizations for popular technologies based on the 2024 Stack Overflow Developer Survey)

Results Summary:
- Attitudes toward AI: Junior developers and experienced professionals show differences in how they perceive the benefits, accuracy and complexity of AI tools
- Popular technologies: Among those learning to code, there are particular favorable programming languages, platforms and web frameworks
- Remote work preferences: Larger companies tend to prefer remote work more than smaller ones, with notable differences across regions like the US, Germany, India and the UK.

Acknowledgements
- Dataset Credit: Stack Overflow, 2024 Developer Survey. Available at [Stack Overflow Developer Survey](https://survey.stackoverflow.co/).
- Thanks to StackOverflow for providing the data used in this analysis.
