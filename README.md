
# Data Visualisation — Example Notebooks

This repository is a compact collection of Jupyter notebooks that demonstrate common data visualization techniques in Python. It is designed for learners and practitioners who want runnable examples across both static (matplotlib / seaborn) and interactive (Plotly / Cufflinks) ecosystems.

## What's included
- [CategoricalPlots.ipynb](CategoricalPlots.ipynb) — Categorical plotting with seaborn and matplotlib.
- [DistributionPlot.ipynb](DistributionPlot.ipynb) — Histograms, KDEs, and distribution analysis.
- [Matplotlib.ipynb](Matplotlib.ipynb) — Core matplotlib usage, styling, and figure composition.
- [MatrixPlot.ipynb](MatrixPlot.ipynb) — Heatmaps and matrix-style visualizations.
- [PlotlyCufflinks.ipynb](PlotlyCufflinks.ipynb) — Interactive charts with Plotly and Cufflinks.
- [RegressionPlot.ipynb](RegressionPlot.ipynb) — Regression lines, scatterplots, and model-visualization hints.

## Recommended order (what to open first)
1. **[Matplotlib.ipynb](Matplotlib.ipynb)** — Start here to learn the fundamental plotting concepts (figures, axes, labels, and styles). This notebook provides a foundation that helps when you move to higher-level APIs.
2. **[CategoricalPlots.ipynb](CategoricalPlots.ipynb)** — Builds on matplotlib concepts using seaborn for categorical data.
3. **[DistributionPlot.ipynb](DistributionPlot.ipynb)** — Focuses on distributions and density estimation.
4. **[RegressionPlot.ipynb](RegressionPlot.ipynb)** — Learn how to visualize relationships and simple model fits.
5. **[MatrixPlot.ipynb](MatrixPlot.ipynb)** — Covers heatmaps and matrix visualizations for correlation and tabular data.
6. **[PlotlyCufflinks.ipynb](PlotlyCufflinks.ipynb)** — Finish with interactive plots and dashboard-ready examples.

## Quick start
1. Create a Python virtual environment (recommended):

```bash
python -m venv .venv
.
```

2. Activate the environment and install dependencies:

```bash
# Windows (PowerShell)
.\.venv\Scripts\Activate.ps1
pip install -U pip
pip install notebook pandas numpy seaborn matplotlib plotly cufflinks
```

3. Launch Jupyter Notebook / Lab and open the notebooks:

```bash
jupyter notebook
```


## Interactive examples
Detailed Plotly and Cufflinks explanations and runnable examples live in the notebook: [PlotlyCufflinks.ipynb](PlotlyCufflinks.ipynb). Open that notebook to see setup instructions, runnable snippets, and tips for notebook renderers and offline mode.

## Further resources
- Official Plotly docs: https://plotly.com/python/
- Cufflinks docs & examples: https://github.com/santosjorge/cufflinks
- Plotly Dash (for dashboards): https://dash.plotly.com/

## Contributing
Feel free to open issues or PRs. Add example datasets, improve explanations, or include small exercises.

## License
This repository is provided as-is for learning purposes. Add your preferred license if you plan to redistribute.

