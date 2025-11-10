### Software and libraries
  1. Visual Studio Code 1.100.3
  2. Python 3.10.9
  3. pandas 1.5.3
  4. numpy 1.26.4
  5. matplotlib 3.10.0
  6. seaborn 0.13.2
  7. scipy 1.15.3
  8. scikit-learn 1.5.2


### Operating systems
  Mac Studio(2022), Apple M1 Max, 32GB, Sequoia 15.4.1


### Instruction

## Quick Start
  1. Ensure all required libraries are installed
  2. Place the 'Dataset.csv' file in the same directory as the notebook
  3. Open the notebook in Visual Studio Code or Jupyter
  4. Run all cells sequentially

## Customization Options
  The comprehensive score is calculated as a weighted mean of three metrics.
The weights can be modified in the 'SCORE_WEIGHTS' dictionary.


## Ensembled Comprehensive Score
  1. Each of the 6 ML models generates a comprehensive score for every combination
  2. Scores are averaged across all 6 models for each combination
  3. The combination with the highest average score is selected as optimal

## Execution Time
  Approximate runtime: 2-3 minutes, depending on system specifications
