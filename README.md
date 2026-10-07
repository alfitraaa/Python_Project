# Python_Project

**Legacy educational Python exploratory analysis of relationships between movie attributes and the `gross` field.**

### Purpose
- pandas data preparation;
- exploratory data analysis;
- visualization;
- Pearson correlation among numeric variables.

### Repository contents
- one Jupyter notebook.

### Data availability
`movies.csv` is required to run the notebook, but it is not included in the repository. Source attribution is not preserved. Therefore, the notebook is not independently reproducible from a clean clone.

### Methodology
- numeric-only Pearson correlation;
- complete observations for correlation variables;
- nominal categorical fields are not converted to arbitrary integers for Pearson analysis;
- correlation is descriptive and non-causal.

### Historical notebook note
This repository originated as a 2022 educational notebook. This cleanup corrects methodology and documentation while preserving its portfolio scope.

### Running
1. place the original compatible dataset as `movies.csv` beside the notebook;
2. install/use Python with pandas, numpy, matplotlib, and seaborn;
3. run the notebook top-to-bottom.

### Validation status
- notebook structure and source were reviewed;
- revised runtime results were not independently reproduced because the input dataset is not tracked.
