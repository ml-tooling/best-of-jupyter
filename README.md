<!-- markdownlint-disable -->
<h1 align="center">
    Best-of Jupyter
    <br>
</h1>

<p align="center">
    <strong>🏆&nbsp; A ranked list of awesome Jupyter projects. Updated weekly.</strong>
</p>

<p align="center">
    <a href="https://best-of.org" title="Best-of-badge"><img src="http://bit.ly/3o3EHNN"></a>
    <a href="#Contents" title="Project Count"><img src="https://img.shields.io/badge/projects-300-blue.svg?color=5ac4bf"></a>
    <a href="#Contribution" title="Contributions are welcome"><img src="https://img.shields.io/badge/contributions-welcome-green.svg"></a>
    <a href="https://github.com/ml-tooling/best-of-jupyter/releases" title="Best-of Updates"><img src="https://img.shields.io/github/release-date/ml-tooling/best-of-jupyter?color=green&label=updated"></a>
    <a href="https://mltooling.substack.com/subscribe" title="Subscribe to newsletter"><img src="http://bit.ly/2Md9rxM"></a>
    <a href="https://twitter.com/mltooling" title="Follow on Twitter"><img src="https://img.shields.io/twitter/follow/mltooling.svg?style=social&label=Follow"></a>
</p>

This curated list contains 300 awesome open-source projects with a total of 420K stars grouped into 13 categories. All projects are ranked by a project-quality score, which is calculated based on various metrics automatically collected from GitHub and different package managers. If you like to add or update projects, feel free to open an [issue](https://github.com/ml-tooling/best-of-jupyter/issues/new/choose), submit a [pull request](https://github.com/ml-tooling/best-of-jupyter/pulls), or directly edit the [projects.yaml](https://github.com/ml-tooling/best-of-jupyter/edit/main/projects.yaml). Contributions are very welcome!

---

<p align="center">
     🧙‍♂️&nbsp; Discover other <a href="https://best-of.org">best-of lists</a> or create <a href="https://github.com/best-of-lists/best-of/blob/main/create-best-of-list.md">your own</a>.<br>
    📫&nbsp; Subscribe to our <a href="https://mltooling.substack.com/subscribe">newsletter</a> for updates and trending projects.
</p>

---


## Contents

- [Notebook Environments](#notebook-environments) _16 projects_
- [Interactive Widgets & Visualization](#interactive-widgets--visualization) _56 projects_
- [Jupyter Extensions](#jupyter-extensions) _24 projects_
- [Jupyter Magic](#jupyter-magic) _12 projects_
- [Jupyter Kernels](#jupyter-kernels) _44 projects_
- [Notebook Sharing & Conversion](#notebook-sharing--conversion) _24 projects_
- [Notebook Tools](#notebook-tools) _26 projects_
- [JupyterLab Renderer](#jupyterlab-renderer) _8 projects_
- [JupyterLab Themes](#jupyterlab-themes) _9 projects_
- [JupyterLab Extensions](#jupyterlab-extensions) _52 projects_
- [JupyterHub Authenticators](#jupyterhub-authenticators) _15 projects_
- [JupyterHub Spawners](#jupyterhub-spawners) _8 projects_
- [Jupyter Components](#jupyter-components) _3 projects_
- [Others](#others) _4 projects_

## Explanation
- 🥇🥈🥉&nbsp; Combined project-quality score
- ⭐️&nbsp; Star count from GitHub
- 🐣&nbsp; New project _(less than 6 months old)_
- 💤&nbsp; Inactive project _(6 months no activity)_
- 💀&nbsp; Dead project _(12 months no activity)_
- 📈📉&nbsp; Project is trending up or down
- ➕&nbsp; Project was recently added
- ❗️&nbsp; Warning _(e.g. missing/risky license)_
- 👨‍💻&nbsp; Contributors count from GitHub
- 🔀&nbsp; Fork count from GitHub
- 📋&nbsp; Issue count from GitHub
- ⏱️&nbsp; Last update timestamp on package manager
- 📥&nbsp; Download count from package manager
- 📦&nbsp; Number of dependent projects

<br>

## Notebook Environments

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Development environments with support for Jupyter Notebooks._

<details><summary><b><a href="https://github.com/jupyter/notebook">Jupyter</a></b> (🥇46 ·  ⭐ 13K) - Jupyter Interactive Notebook. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/notebook) (👨‍💻 660 · 🔀 5.2K · 📥 25K · 📦 360K · 📋 5K - 39% open · ⏱️ 28.05.2025):

	```
	git clone https://github.com/jupyter/notebook
	```
- [PyPi](https://pypi.org/project/notebook) (📥 41M / month · 📦 2.5K · ⏱️ 26.05.2025):
	```
	pip install notebook
	```
- [Conda](https://anaconda.org/conda-forge/jupyter) (📥 5.3M · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge jupyter
	```
- [Docker Hub](https://hub.docker.com/r/jupyter/datascience-notebook) (📥 35M · ⭐ 1.1K · ⏱️ 20.10.2023):
	```
	docker pull jupyter/datascience-notebook
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/jupyterhub">JupyterHub</a></b> (🥇39 ·  ⭐ 8.4K) - Multi-user server for Jupyter notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/jupyterhub) (👨‍💻 380 · 🔀 2.1K · 📦 3.4K · 📋 2.5K - 7% open · ⏱️ 04.06.2025):

	```
	git clone https://github.com/jupyterhub/jupyterhub
	```
- [PyPi](https://pypi.org/project/jupyterhub) (📥 250K / month · 📦 230 · ⏱️ 15.04.2025):
	```
	pip install jupyterhub
	```
- [Conda](https://anaconda.org/conda-forge/jupyterhub) (📥 1.4M · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge jupyterhub
	```
- [Docker Hub](https://hub.docker.com/r/jupyterhub/jupyterhub) (📥 5.6M · ⭐ 350 · ⏱️ 25.05.2025):
	```
	docker pull jupyterhub/jupyterhub
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/docker-stacks">Docker Stacks</a></b> (🥈33 ·  ⭐ 8.7K) - Ready-to-run Docker images containing Jupyter applications. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/docker-stacks) (👨‍💻 260 · 🔀 3K · 📦 21 · 📋 920 - 0% open · ⏱️ 03.06.2025):

	```
	git clone https://github.com/jupyter/docker-stacks
	```
- [Docker Hub](https://hub.docker.com/r/jupyter/scipy-notebook) (📥 92M · ⭐ 460 · ⏱️ 20.10.2023):
	```
	docker pull jupyter/scipy-notebook
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab">JupyterLab</a></b> (🥈32 ·  ⭐ 15K) - JupyterLab computational environment. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab) (👨‍💻 520 · 🔀 3.6K):

	```
	git clone https://github.com/jupyterlab/jupyterlab
	```
- [PyPi](https://pypi.org/project/jupyterlab) (📥 44M / month · 📦 3.3K · ⏱️ 26.05.2025):
	```
	pip install jupyterlab
	```
- [Conda](https://anaconda.org/conda-forge/jupyterlab) (📥 14M · ⏱️ 03.06.2025):
	```
	conda install -c conda-forge jupyterlab
	```
- [npm](https://www.npmjs.com/package/@jupyterlab/ui-components) (📥 250K / month · 📦 450 · ⏱️ 26.05.2025):
	```
	npm install @jupyterlab/ui-components
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/vscode-jupyter">VSCode Jupyter</a></b> (🥈32 ·  ⭐ 1.4K) - VS Code Jupyter extension. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/vscode-jupyter) (👨‍💻 280 · 🔀 320 · 📥 2K · 📦 3 · 📋 10K - 2% open · ⏱️ 04.06.2025):

	```
	git clone https://github.com/microsoft/vscode-jupyter
	```
- [Conda](https://anaconda.org/conda-forge/vscode-jupyter) (📥 140K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge vscode-jupyter
	```
</details>
<details><summary><b><a href="https://github.com/vatlab/sos">sos</a></b> (🥈28 ·  ⭐ 280 · 💤) - SoS workflow system for daily data analysis. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/vatlab/sos) (👨‍💻 36 · 🔀 46 · 📦 7.7K · 📋 1.5K - 4% open · ⏱️ 17.10.2024):

	```
	git clone https://github.com/vatlab/SOS
	```
- [PyPi](https://pypi.org/project/sos-notebook) (📥 890 / month · 📦 22 · ⏱️ 25.09.2023):
	```
	pip install sos-notebook
	```
- [Conda](https://anaconda.org/conda-forge/sos) (📥 220K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge sos
	```
</details>
<details><summary><b><a href="https://github.com/Kaggle/docker-python">docker-python</a></b> (🥉25 ·  ⭐ 2.8K) - Kaggle Python docker image. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Kaggle/docker-python) (👨‍💻 170 · 🔀 950 · 📋 370 - 4% open · ⏱️ 08.05.2025):

	```
	git clone https://github.com/kaggle/docker-python
	```
- [Docker Hub](https://hub.docker.com/r/kaggle/python) (📥 200K · ⭐ 190 · ⏱️ 08.05.2025):
	```
	docker pull kaggle/python
	```
</details>
<details><summary><b><a href="https://github.com/iot-salzburg/gpu-jupyter">gpu-jupyter</a></b> (🥉15 ·  ⭐ 740) - GPU-Jupyter: Your GPU-accelerated JupyterLab with a rich data.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/iot-salzburg/gpu-jupyter) (👨‍💻 15 · 🔀 230 · 📋 98 - 3% open · ⏱️ 28.02.2025):

	```
	git clone https://github.com/iot-salzburg/gpu-jupyter
	```
</details>
<details><summary><b><a href="https://github.com/jtpio/jupyterlite">jupyterlite</a></b> (🥉13 ·  ⭐ 110) - Wasm powered Jupyter running in the browser. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jtpio/jupyterlite) (👨‍💻 72 · 🔀 7 · ⏱️ 05.06.2025):

	```
	git clone https://github.com/jtpio/jupyterlite
	```
</details>
<details><summary>Show 7 hidden projects...</summary>

- <b><a href="https://github.com/nteract/nteract">nteract</a></b> (🥈30 ·  ⭐ 6.3K · 💀) - The interactive computing suite for you!. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/nteract/hydrogen">Hydrogen</a></b> (🥉22 ·  ⭐ 4K · 💀) - Run code interactively, inspect data, and plot. All the power of.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/googledatalab/datalab">DataLab</a></b> (🥉22 ·  ⭐ 970 · 💀) - Interactive tools and developer experiences for Big Data on.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/jupyter-server/jupyverse">jupyverse</a></b> (🥉21 ·  ⭐ 270) - A Jupyter server based on FastAPI. <code><a href="https://tldrlegal.com/search?q=BSD-1-Clause">❗️BSD-1-Clause</a></code>
- <b><a href="https://github.com/ml-tooling/ml-workspace">ML Workspace</a></b> (🥉20 ·  ⭐ 3.5K · 💀) - All-in-one web-based IDE specialized for machine learning.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/jupyterlab/retrolab">retrolab</a></b> (🥉20 ·  ⭐ 280 · 💀) - JupyterLab distribution with a retro look and feel. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/ml-tooling/ml-hub">ML Hub</a></b> (🥉15 ·  ⭐ 320 · 💀) - Multi-user development platform for machine learning teams. Simple.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
</details>
<br>

## Interactive Widgets & Visualization

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Extensions that provide interactive UI-widgets and visualization tools._

🔗&nbsp;<b><a href="https://github.com/ml-tooling/best-of-ml-python#data-visualization">best-of-ml-python - Data Visualization</a></b>  - Python-based data visualization libraries.

<details><summary><b><a href="https://github.com/bokeh/bokeh">bokeh</a></b> (🥇44 ·  ⭐ 20K) - Interactive Data Visualization in the browser, from Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/bokeh/bokeh) (👨‍💻 710 · 🔀 4.2K · 📦 100K · 📋 8K - 10% open · ⏱️ 03.06.2025):

	```
	git clone https://github.com/bokeh/bokeh
	```
- [PyPi](https://pypi.org/project/bokeh) (📥 3.7M / month · 📦 2K · ⏱️ 12.05.2025):
	```
	pip install bokeh
	```
- [Conda](https://anaconda.org/conda-forge/bokeh) (📥 17M · ⏱️ 12.05.2025):
	```
	conda install -c conda-forge bokeh
	```
- [npm](https://www.npmjs.com/package/@bokeh/bokehjs) (📥 29K / month · 📦 21 · ⏱️ 12.05.2025):
	```
	npm install @bokeh/bokehjs
	```
</details>
<details><summary><b><a href="https://github.com/holoviz/panel">panel</a></b> (🥇39 ·  ⭐ 5.2K) - Panel: The powerful data exploration & web app framework for Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/holoviz/panel) (👨‍💻 190 · 🔀 540 · 📦 18K · 📋 3.9K - 29% open · ⏱️ 05.06.2025):

	```
	git clone https://github.com/holoviz/panel
	```
- [PyPi](https://pypi.org/project/panel) (📥 980K / month · 📦 490 · ⏱️ 28.05.2025):
	```
	pip install panel
	```
- [Conda](https://anaconda.org/conda-forge/panel) (📥 2.1M · ⏱️ 28.05.2025):
	```
	conda install -c conda-forge panel
	```
- [npm](https://www.npmjs.com/package/@holoviz/panel) (📥 1.6K / month · 📦 5 · ⏱️ 28.05.2025):
	```
	npm install @holoviz/panel
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-widgets/ipywidgets">ipywidgets</a></b> (🥇39 ·  ⭐ 3.2K) - Interactive Widgets for the Jupyter Notebook. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-widgets/ipywidgets) (👨‍💻 230 · 🔀 950 · 📦 3 · 📋 2.1K - 36% open · ⏱️ 05.05.2025):

	```
	git clone https://github.com/jupyter-widgets/ipywidgets
	```
- [PyPi](https://pypi.org/project/ipywidgets) (📥 25M / month · 📦 5.2K · ⏱️ 05.05.2025):
	```
	pip install ipywidgets
	```
- [Conda](https://anaconda.org/conda-forge/ipywidgets) (📥 19M · ⏱️ 05.05.2025):
	```
	conda install -c conda-forge ipywidgets
	```
- [npm](https://www.npmjs.com/package/@jupyter-widgets/jupyterlab-manager) (📥 43K / month · 📦 130 · ⏱️ 05.05.2025):
	```
	npm install @jupyter-widgets/jupyterlab-manager
	```
</details>
<details><summary><b><a href="https://github.com/ydataai/ydata-profiling">pandas-profiling</a></b> (🥇37 ·  ⭐ 13K) - 1 Line of code data quality profiling & exploratory data.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ydataai/ydata-profiling) (👨‍💻 140 · 🔀 1.7K · 📥 370 · 📦 6.7K · 📋 840 - 30% open · ⏱️ 26.03.2025):

	```
	git clone https://github.com/pandas-profiling/pandas-profiling
	```
- [PyPi](https://pypi.org/project/pandas-profiling) (📥 350K / month · 📦 180 · ⏱️ 03.02.2023):
	```
	pip install pandas-profiling
	```
- [Conda](https://anaconda.org/conda-forge/pandas-profiling) (📥 520K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge pandas-profiling
	```
</details>
<details><summary><b><a href="https://github.com/evidentlyai/evidently">evidently</a></b> (🥇36 ·  ⭐ 6.2K) - Evidently is an open-source ML and LLM observability framework... <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/evidentlyai/evidently) (👨‍💻 85 · 🔀 680 · 📥 440 · 📦 6.5K · 📋 460 - 47% open · ⏱️ 05.06.2025):

	```
	git clone https://github.com/evidentlyai/evidently
	```
- [PyPi](https://pypi.org/project/evidently) (📥 680K / month · 📦 21 · ⏱️ 04.06.2025):
	```
	pip install evidently
	```
- [Conda](https://anaconda.org/conda-forge/evidently) (📥 87K · ⏱️ 28.05.2025):
	```
	conda install -c conda-forge evidently
	```
</details>
<details><summary><b><a href="https://github.com/nteract/papermill">papermill</a></b> (🥇33 ·  ⭐ 6.2K · 💤) - Parameterize, execute, and analyze notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/nteract/papermill) (👨‍💻 120 · 🔀 430 · 📦 7.4K · 📋 410 - 36% open · ⏱️ 05.10.2024):

	```
	git clone https://github.com/nteract/papermill
	```
- [PyPi](https://pypi.org/project/papermill) (📥 7.1M / month · 📦 340 · ⏱️ 26.04.2024):
	```
	pip install papermill
	```
- [Conda](https://anaconda.org/conda-forge/papermill) (📥 820K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge papermill
	```
</details>
<details><summary><b><a href="https://github.com/matplotlib/ipympl">jupyter-matplotlib</a></b> (🥇33 ·  ⭐ 1.6K) - Matplotlib Jupyter Integration. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/matplotlib/ipympl) (👨‍💻 36 · 🔀 230 · 📦 15K · 📋 330 - 48% open · ⏱️ 05.03.2025):

	```
	git clone https://github.com/matplotlib/ipympl
	```
- [PyPi](https://pypi.org/project/ipympl) (📥 590K / month · 📦 470 · ⏱️ 05.03.2025):
	```
	pip install ipympl
	```
- [Conda](https://anaconda.org/conda-forge/ipympl) (📥 1.9M · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge ipympl
	```
- [npm](https://www.npmjs.com/package/jupyter-matplotlib) (📥 3.9K / month · 📦 7 · ⏱️ 05.03.2025):
	```
	npm install jupyter-matplotlib
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-widgets/ipyleaflet">ipyleaflet</a></b> (🥇33 ·  ⭐ 1.5K) - A Jupyter - Leaflet.js bridge. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jupyter-widgets/ipyleaflet) (👨‍💻 94 · 🔀 360 · 📦 18K · 📋 670 - 45% open · ⏱️ 04.06.2025):

	```
	git clone https://github.com/jupyter-widgets/ipyleaflet
	```
- [PyPi](https://pypi.org/project/ipyleaflet) (📥 210K / month · 📦 280 · ⏱️ 22.07.2024):
	```
	pip install ipyleaflet
	```
- [Conda](https://anaconda.org/conda-forge/ipyleaflet) (📥 1.5M · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge ipyleaflet
	```
- [npm](https://www.npmjs.com/package/jupyter-leaflet) (📥 590 / month · 📦 9 · ⏱️ 22.07.2024):
	```
	npm install jupyter-leaflet
	```
</details>
<details><summary><b><a href="https://github.com/bqplot/bqplot">bqplot</a></b> (🥈30 ·  ⭐ 3.7K · 💤) - Plotting library for IPython/Jupyter notebooks. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/bqplot/bqplot) (👨‍💻 65 · 🔀 470 · 📦 61 · 📋 640 - 42% open · ⏱️ 22.10.2024):

	```
	git clone https://github.com/bqplot/bqplot
	```
- [PyPi](https://pypi.org/project/bqplot) (📥 210K / month · 📦 110 · ⏱️ 21.05.2025):
	```
	pip install bqplot
	```
- [Conda](https://anaconda.org/conda-forge/bqplot) (📥 1.6M · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge bqplot
	```
- [npm](https://www.npmjs.com/package/bqplot) (📥 1.1K / month · 📦 21 · ⏱️ 24.12.2024):
	```
	npm install bqplot
	```
</details>
<details><summary><b><a href="https://github.com/mwouts/itables">itables</a></b> (🥈29 ·  ⭐ 870) - Pandas DataFrames as Interactive DataTables. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mwouts/itables) (👨‍💻 10 · 🔀 60 · 📦 1.2K · 📋 200 - 18% open · ⏱️ 31.05.2025):

	```
	git clone https://github.com/mwouts/itables
	```
- [PyPi](https://pypi.org/project/itables) (📥 1.1M / month · 📦 76 · ⏱️ 17.05.2025):
	```
	pip install itables
	```
- [Conda](https://anaconda.org/conda-forge/itables) (📥 140K · ⏱️ 18.05.2025):
	```
	conda install -c conda-forge itables
	```
</details>
<details><summary><b><a href="https://github.com/spacetelescope/jdaviz">jdaviz</a></b> (🥈27 ·  ⭐ 160) - Interactive data visualization and analysis tools for astronomical.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/spacetelescope/jdaviz) (👨‍💻 38 · 🔀 84 · 📦 59 · 📋 1.1K - 30% open · ⏱️ 05.06.2025):

	```
	git clone https://github.com/spacetelescope/jdaviz
	```
- [PyPi](https://pypi.org/project/jdaviz) (📥 2.9K / month · 📦 6 · ⏱️ 12.05.2025):
	```
	pip install jdaviz
	```
</details>
<details><summary><b><a href="https://github.com/widgetti/ipyvuetify">ipyvuetify</a></b> (🥈26 ·  ⭐ 360) - Jupyter widgets based on vuetify UI components. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/widgetti/ipyvuetify) (👨‍💻 14 · 🔀 60 · 📦 1.8K · 📋 220 - 36% open · ⏱️ 03.06.2025):

	```
	git clone https://github.com/mariobuikhuizen/ipyvuetify
	```
- [PyPi](https://pypi.org/project/ipyvuetify) (📥 210K / month · 📦 99 · ⏱️ 03.06.2025):
	```
	pip install ipyvuetify
	```
- [Conda](https://anaconda.org/conda-forge/ipyvuetify) (📥 270K · ⏱️ 05.06.2025):
	```
	conda install -c conda-forge ipyvuetify
	```
- [npm](https://www.npmjs.com/package/jupyter-vuetify) (📥 2.9K / month · 📦 6 · ⏱️ 03.06.2025):
	```
	npm install jupyter-vuetify
	```
</details>
<details><summary><b><a href="https://github.com/timkpaine/ipydagred3">ipydagred3</a></b> (🥈25 ·  ⭐ 3.2K · 💤) - ipywidgets library for drawing directed acyclic graphs in.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/ipydagred3) (👨‍💻 4 · 🔀 950 · 📦 3 · 📋 24 - 20% open · ⏱️ 18.11.2024):

	```
	git clone https://github.com/timkpaine/ipydagred3
	```
- [PyPi](https://pypi.org/project/ipydagred3) (📥 280K / month · 📦 6 · ⏱️ 31.10.2023):
	```
	pip install ipydagred3
	```
- [Conda](https://anaconda.org/conda-forge/ipydagred3) (📥 50K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge ipydagred3
	```
- [npm](https://www.npmjs.com/package/@jupyter-widgets/jupyterlab-manager) (📥 43K / month · 📦 130 · ⏱️ 05.05.2025):
	```
	npm install @jupyter-widgets/jupyterlab-manager
	```
</details>
<details><summary><b><a href="https://github.com/InsightSoftwareConsortium/itkwidgets">itkwidgets</a></b> (🥈25 ·  ⭐ 600) - An elegant Python interface for visualization on the web platform.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/InsightSoftwareConsortium/itkwidgets) (👨‍💻 27 · 🔀 84 · 📥 130 · 📦 380 · 📋 290 - 42% open · ⏱️ 13.03.2025):

	```
	git clone https://github.com/InsightSoftwareConsortium/itkwidgets
	```
- [PyPi](https://pypi.org/project/itkwidgets) (📥 8.7K / month · 📦 32 · ⏱️ 07.02.2025):
	```
	pip install itkwidgets
	```
- [Conda](https://anaconda.org/conda-forge/itkwidgets) (📥 500K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge itkwidgets
	```
- [npm](https://www.npmjs.com/package/itkwidgets) (📥 86 / month · 📦 5 · ⏱️ 02.03.2023):
	```
	npm install itkwidgets
	```
</details>
<details><summary><b><a href="https://github.com/finos/ipyregulartable">ipyregulartable</a></b> (🥈24 ·  ⭐ 3.2K · 💤) - High performance, editable, stylable datagrids in.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/finos/ipyregulartable) (👨‍💻 5 · 🔀 950 · 📦 15 · 📋 27 - 37% open · ⏱️ 18.11.2024):

	```
	git clone https://github.com/jpmorganchase/ipyregulartable
	```
- [PyPi](https://pypi.org/project/ipyregulartable) (📥 100 / month · 📦 2 · ⏱️ 08.01.2021):
	```
	pip install ipyregulartable
	```
- [Conda](https://anaconda.org/conda-forge/ipyregulartable) (📥 8.7K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge ipyregulartable
	```
- [npm](https://www.npmjs.com/package/@jupyter-widgets/jupyterlab-manager) (📥 43K / month · 📦 130 · ⏱️ 05.05.2025):
	```
	npm install @jupyter-widgets/jupyterlab-manager
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/responsible-ai-toolbox">responsible-ai-widgets</a></b> (🥈24 ·  ⭐ 1.6K) - Responsible AI Toolbox is a suite of tools providing.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/responsible-ai-toolbox) (👨‍💻 43 · 🔀 400 · 📋 320 - 26% open · ⏱️ 07.02.2025):

	```
	git clone https://github.com/microsoft/responsible-ai-toolbox
	```
- [PyPi](https://pypi.org/project/raiwidgets) (📥 7.7K / month · 📦 6 · ⏱️ 08.07.2024):
	```
	pip install raiwidgets
	```
</details>
<details><summary><b><a href="https://github.com/nglviewer/nglview">nglview</a></b> (🥈24 ·  ⭐ 870) - Jupyter widget to interactively view molecular structures and trajectories. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nglviewer/nglview) (👨‍💻 39 · 🔀 130 · 📥 310 · 📋 510 - 7% open · ⏱️ 28.05.2025):

	```
	git clone https://github.com/nglviewer/nglview
	```
- [PyPi](https://pypi.org/project/nglview) (📥 20K / month · 📦 91 · ⏱️ 25.11.2024):
	```
	pip install nglview
	```
- [Conda](https://anaconda.org/conda-forge/nglview) (📥 910K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge nglview
	```
- [npm](https://www.npmjs.com/package/nglview-js-widgets) (📥 300 / month · 📦 7 · ⏱️ 28.11.2024):
	```
	npm install nglview-js-widgets
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-widgets/ipydatagrid">ipydatagrid</a></b> (🥈24 ·  ⭐ 610) - Fast Datagrid widget for the Jupyter Notebook and JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-widgets/ipydatagrid) (👨‍💻 26 · 🔀 53 · 📦 230 · 📋 170 - 45% open · ⏱️ 16.12.2024):

	```
	git clone https://github.com/bloomberg/ipydatagrid
	```
- [PyPi](https://pypi.org/project/ipydatagrid) (📥 36K / month · 📦 31 · ⏱️ 17.12.2024):
	```
	pip install ipydatagrid
	```
- [Conda](https://anaconda.org/conda-forge/ipydatagrid) (📥 210K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge ipydatagrid
	```
- [npm](https://www.npmjs.com/package/ipydatagrid) (📥 120 / month · 📦 5 · ⏱️ 17.12.2024):
	```
	npm install ipydatagrid
	```
</details>
<details><summary><b><a href="https://github.com/vizzuhq/ipyvizzu">ipyvizzu</a></b> (🥉23 ·  ⭐ 960) - Build animated charts in Jupyter Notebook and similar environments.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/vizzuhq/ipyvizzu) (👨‍💻 21 · 🔀 86 · 📥 370 · 📦 180 · 📋 90 - 14% open · ⏱️ 26.02.2025):

	```
	git clone https://github.com/vizzuhq/ipyvizzu
	```
- [PyPi](https://pypi.org/project/ipyvizzu) (📥 1.8K / month · 📦 6 · ⏱️ 26.02.2025):
	```
	pip install ipyvizzu
	```
</details>
<details><summary><b><a href="https://github.com/mapbox/mapboxgl-jupyter">Mapbox GL</a></b> (🥉22 ·  ⭐ 680 · 📉) - Use Mapbox GL JS to visualize data in a Python Jupyter notebook. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mapbox/mapboxgl-jupyter) (👨‍💻 23 · 🔀 140 · 📋 110 - 38% open · ⏱️ 06.02.2025):

	```
	git clone https://github.com/mapbox/mapboxgl-jupyter
	```
- [PyPi](https://pypi.org/project/mapboxgl) (📥 8.3K / month · 📦 12 · ⏱️ 02.06.2019):
	```
	pip install mapboxgl
	```
</details>
<details><summary><b><a href="https://github.com/vega/ipyvega">vega</a></b> (🥉22 ·  ⭐ 380) - IPython/Jupyter notebook module for Vega and Vega-Lite. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/vega/ipyvega) (👨‍💻 15 · 🔀 65 · 📦 4 · 📋 110 - 14% open · ⏱️ 01.01.2025):

	```
	git clone https://github.com/vega/ipyvega
	```
- [PyPi](https://pypi.org/project/vega) (📥 17K / month · 📦 17 · ⏱️ 25.09.2024):
	```
	pip install vega
	```
- [Conda](https://anaconda.org/conda-forge/vega) (📥 740K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge vega
	```
</details>
<details><summary><b><a href="https://github.com/medialab/ipysigma">ipysigma</a></b> (🥉22 ·  ⭐ 260) - A Jupyter widget using sigma.js to render interactive networks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/medialab/ipysigma) (👨‍💻 6 · 🔀 20 · 📦 88 · 📋 230 - 30% open · ⏱️ 02.02.2025):

	```
	git clone https://github.com/Yomguithereal/ipysigma
	```
- [PyPi](https://pypi.org/project/ipysigma) (📥 43K / month · 📦 2 · ⏱️ 02.02.2025):
	```
	pip install ipysigma
	```
- [npm](https://www.npmjs.com/package/ipysigma) (📥 130 / month · 📦 5 · ⏱️ 02.02.2025):
	```
	npm install ipysigma
	```
</details>
<details><summary><b><a href="https://github.com/widgetti/ipyvue">ipyvue</a></b> (🥉21 ·  ⭐ 71 · 💤) - Jupyter widgets base for Vue libraries. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/widgetti/ipyvue) (👨‍💻 6 · 🔀 18 · 📦 1.4K · 📋 17 - 47% open · ⏱️ 14.11.2024):

	```
	git clone https://github.com/mariobuikhuizen/ipyvue
	```
- [PyPi](https://pypi.org/project/ipyvue) (📥 210K / month · 📦 36 · ⏱️ 14.11.2024):
	```
	pip install ipyvue
	```
- [Conda](https://anaconda.org/conda-forge/ipyvue) (📥 220K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge ipyvue
	```
- [npm](https://www.npmjs.com/package/jupyter-vue) (📥 2.3K / month · 📦 16 · ⏱️ 14.11.2024):
	```
	npm install jupyter-vue
	```
</details>
<details><summary><b><a href="https://github.com/1kbgz/tributary">tributary</a></b> (🥉20 ·  ⭐ 450) - Streaming reactive and dataflow graphs in Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/1kbgz/tributary) (👨‍💻 7 · 🔀 37 · 📦 70 · 📋 83 - 12% open · ⏱️ 18.04.2025):

	```
	git clone https://github.com/timkpaine/tributary
	```
- [PyPi](https://pypi.org/project/tributary) (📥 100 / month · ⏱️ 10.05.2023):
	```
	pip install tributary
	```
- [Conda](https://anaconda.org/conda-forge/tributary) (📥 70K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge tributary
	```
</details>
<details><summary>Show 31 hidden projects...</summary>

- <b><a href="https://github.com/man-group/dtale">D-Tale</a></b> (🥈30 ·  ⭐ 4.9K) - Visualizer for Pandas Data Structures. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1">❗️LGPL-2.1</a></code>
- <b><a href="https://github.com/jupyter-widgets/pythreejs">pythreejs</a></b> (🥈28 ·  ⭐ 970 · 💀) - A Jupyter - Three.js bridge. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/plotly/jupyter-dash">jupyter-dash</a></b> (🥈28 ·  ⭐ 960 · 💀) - OBSOLETE - Dash v2.11+ has Jupyter support built in!. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/PAIR-code/facets">facets-overview</a></b> (🥈27 ·  ⭐ 7.4K · 💀) - Visualizations for machine learning datasets. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/quantopian/qgrid">qgrid</a></b> (🥈26 ·  ⭐ 3.1K · 💀) - An interactive grid for sorting, filtering, and editing DataFrames.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/widgetti/ipyvolume">ipyvolume</a></b> (🥈26 ·  ⭐ 2K · 💀) - 3d plotting for Python in the Jupyter notebook based on IPython.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/cytoscape/ipycytoscape">ipycytoscape</a></b> (🥈25 ·  ⭐ 280 · 💀) - A Cytoscape Jupyter widget. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/lux-org/lux">lux</a></b> (🥈24 ·  ⭐ 5.3K · 💀) - Automatically visualize your pandas dataframe via a single print!. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/maartenbreddels/ipywebrtc">ipywebrtc</a></b> (🥈24 ·  ⭐ 250 · 💀) - WebRTC for Jupyter notebook/lab. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/PAIR-code/what-if-tool">What-If Tool</a></b> (🥉23 ·  ⭐ 950 · 💀) - Source code/webpage/demos for the What-If Tool. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/pbugnion/gmaps">gmaps</a></b> (🥉23 ·  ⭐ 760 · 💀) - Google maps for Jupyter notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/nicolaskruchten/jupyter_pivottablejs">pivottablejs</a></b> (🥉22 ·  ⭐ 700 · 💀) - Dragndrop Pivot Tables and Charts for Jupyter/IPython Notebook,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/martinRenou/ipycanvas">ipycanvas</a></b> (🥉22 ·  ⭐ 690 · 💀) - Interactive Canvas in Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jupyter-widgets-contrib/ipysheet">ipysheet</a></b> (🥉22 ·  ⭐ 550 · 💀) - Jupyter handsontable integration. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/vidartf/ipydatawidgets">ipydatawidgets</a></b> (🥉22 ·  ⭐ 44 · 💀) - A set of widgets to help facilitate reuse of large datasets.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/lgpage/nbtutor">nbtutor</a></b> (🥉21 ·  ⭐ 460 · 💀) - Visualize Python code execution (line-by-line) in Jupyter Notebook.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jupyter-widgets-contrib/ipytree">ipytree</a></b> (🥉20 ·  ⭐ 130 · 💀) - A Tree Widget using Jupyter-widgets protocol and jsTree. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/altair-viz/altair_viewer">Altair Viewer</a></b> (🥉18 ·  ⭐ 81 · 💀) - Viewer for Altair and Vega-Lite visualizations. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/OpenGeoscience/geonotebook">geonotebook</a></b> (🥉16 ·  ⭐ 1.1K · 💀) - A Jupyter notebook extension for geospatial visualization.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/g2nb/igv-jupyter">igv.js widget</a></b> (🥉16 ·  ⭐ 150 · 💀) - Extension for Jupyter which integrates igv.js. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/vidartf/ipyscales">ipyscales</a></b> (🥉16 ·  ⭐ 14 · 💀) - A widget library for scales. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/CermakM/jupyter-datatables">Jupyter DataTables</a></b> (🥉15 ·  ⭐ 240 · 💀) - Jupyter Notebook extension leveraging pandas DataFrames.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/nipy/niwidgets">niwidgets</a></b> (🥉15 ·  ⭐ 86 · 💀) - Neuroimaging widgets for jupyter notebooks. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/DGothrek/ipyaggrid">ipyaggrid</a></b> (🥉15 ·  ⭐ 57 · 💀) - Jupyter widget - ag-grid in the notebook. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/maartenbreddels/ipymaterialui">ipymaterialui</a></b> (🥉13 ·  ⭐ 86 · 💀) - Jupyter Widgets based on React Material UI components. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/agermanidis/pigeon">pigeon</a></b> (🥉12 ·  ⭐ 790 · 💀) - Quickly annotate data from the comfort of your Jupyter notebook. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/leifwalsh/perfume">perfume</a></b> (🥉11 ·  ⭐ 33 · 💀) - Interactive performance benchmarking in Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/ipyannotate/ipyannotate">ipyannotate</a></b> (🥉10 ·  ⭐ 140 · 💀) - Jupyter Widget for data annotation. <code>❗Unlicensed</code>
- <b><a href="https://github.com/jtpio/ipyp5">ipyp5</a></b> (🥉10 ·  ⭐ 42 · 💀) - p5.js Jupyter Widget. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/GianniBalistreri/easyexplore">easyexplore</a></b> (🥉10 ·  ⭐ 5 · 💀) - Toolbox for easy and effective data exploration in Python. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/asvcode/Vision_UI">Vision UI</a></b> (🥉7 ·  ⭐ 250 · 💀) - UI visual interface for fastai - now compatible with Google.. <code>❗Unlicensed</code>
</details>
<br>

## Jupyter Extensions

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Application plugins that extend the functionality of Jupyter itself._

<details><summary><b><a href="https://github.com/jupyter/nbgrader">nbgrader</a></b> (🥇28 ·  ⭐ 1.3K) - A system for assigning and grading notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/nbgrader) (👨‍💻 110 · 🔀 330 · 📥 680 · 📦 3 · 📋 960 - 29% open · ⏱️ 09.05.2025):

	```
	git clone https://github.com/jupyter/nbgrader
	```
- [PyPi](https://pypi.org/project/nbgrader) (📥 11K / month · 📦 21 · ⏱️ 17.01.2025):
	```
	pip install nbgrader
	```
- [Conda](https://anaconda.org/conda-forge/nbgrader) (📥 220K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge nbgrader
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-server/jupyter-resource-usage">Resource Usage</a></b> (🥈27 ·  ⭐ 520) - Jupyter Notebook Extension for monitoring your own Resource.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/jupyter-server/jupyter-resource-usage) (👨‍💻 36 · 🔀 100 · 📥 510 · 📦 950 · 📋 99 - 49% open · ⏱️ 04.02.2025):

	```
	git clone https://github.com/jupyter-server/jupyter-resource-usage
	```
- [PyPi](https://pypi.org/project/jupyter-resource-usage) (📥 90K / month · 📦 17 · ⏱️ 04.02.2025):
	```
	pip install jupyter-resource-usage
	```
- [Conda](https://anaconda.org/conda-forge/nbresuse) (📥 570K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge nbresuse
	```
- [npm](https://www.npmjs.com/package/@jupyter-server/resource-usage) (📥 1.5K / month · 📦 6 · ⏱️ 31.07.2024):
	```
	npm install @jupyter-server/resource-usage
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/jupyter-server-proxy">jupyter-server-proxy</a></b> (🥈27 ·  ⭐ 370) - Jupyter notebook server extension to proxy web services. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/jupyter-server-proxy) (👨‍💻 79 · 🔀 150 · 📦 5 · 📋 230 - 37% open · ⏱️ 21.05.2025):

	```
	git clone https://github.com/jupyterhub/jupyter-server-proxy
	```
- [PyPi](https://pypi.org/project/jupyter-server-proxy) (📥 220K / month · 📦 200 · ⏱️ 29.08.2024):
	```
	pip install jupyter-server-proxy
	```
- [Conda](https://anaconda.org/conda-forge/jupyter-server-proxy) (📥 1.7M · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge jupyter-server-proxy
	```
- [npm](https://www.npmjs.com/package/@jupyterlab/server-proxy) (📥 1.8K / month · 📦 9 · ⏱️ 11.06.2024):
	```
	npm install @jupyterlab/server-proxy
	```
</details>
<details><summary><b><a href="https://github.com/Jupyter-contrib/jupyter_nbextensions_configurator">NBextensions Configurator</a></b> (🥈26 ·  ⭐ 990 · 💤) - A jupyter notebook serverextension providing config.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Jupyter-contrib/jupyter_nbextensions_configurator) (👨‍💻 24 · 🔀 120 · 📦 1.2K · 📋 110 - 66% open · ⏱️ 05.06.2024):

	```
	git clone https://github.com/jupyter-contrib/jupyter_nbextensions_configurator
	```
- [PyPi](https://pypi.org/project/jupyter_nbextensions_configurator) (📥 390K / month · 📦 35 · ⏱️ 05.06.2024):
	```
	pip install jupyter_nbextensions_configurator
	```
- [Conda](https://anaconda.org/conda-forge/jupyter_nbextensions_configurator) (📥 1.9M · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge jupyter_nbextensions_configurator
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/nbgitpuller">nbgitpuller</a></b> (🥈26 ·  ⭐ 220) - Jupyter server extension to sync a git repository one-way to a.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/nbgitpuller) (👨‍💻 35 · 🔀 87 · 📦 960 · 📋 180 - 47% open · ⏱️ 27.01.2025):

	```
	git clone https://github.com/jupyterhub/nbgitpuller
	```
- [PyPi](https://pypi.org/project/nbgitpuller) (📥 23K / month · 📦 10 · ⏱️ 27.01.2025):
	```
	pip install nbgitpuller
	```
- [Conda](https://anaconda.org/conda-forge/nbgitpuller) (📥 120K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge nbgitpuller
	```
</details>
<details><summary><b><a href="https://github.com/8080labs/pyforest">pyforest</a></b> (🥈22 ·  ⭐ 1.1K · 💤) - pyforest - feel the bliss of automated imports. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/8080labs/pyforest) (👨‍💻 15 · 🔀 200 · 📋 34 - 32% open · ⏱️ 14.06.2024):

	```
	git clone https://github.com/8080labs/pyforest
	```
- [PyPi](https://pypi.org/project/pyforest) (📥 1.9K / month · 📦 15 · ⏱️ 14.06.2024):
	```
	pip install pyforest
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab-contrib/jupyter-archive">jupyter-archive</a></b> (🥈22 ·  ⭐ 83 · 📈) - A Jupyter/Jupyterlab extension to make, download and.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab-contrib/jupyter-archive) (👨‍💻 11 · 🔀 15 · 📥 3.3K · 📦 360 · 📋 44 - 18% open · ⏱️ 05.03.2025):

	```
	git clone https://github.com/jupyterlab-contrib/jupyter-archive
	```
- [PyPi](https://pypi.org/project/jupyter-archive) (📥 74K / month · 📦 7 · ⏱️ 15.08.2023):
	```
	pip install jupyter-archive
	```
- [Conda](https://anaconda.org/conda-forge/jupyter-archive) (📥 93K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge jupyter-archive
	```
- [npm](https://www.npmjs.com/package/@hadim/jupyter-archive) (📥 24 / month · 📦 5 · ⏱️ 15.08.2023):
	```
	npm install @hadim/jupyter-archive
	```
</details>
<details><summary><b><a href="https://github.com/mamba-org/gator">gator</a></b> (🥉21 ·  ⭐ 270) - Conda environment and package management extension from within Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mamba-org/gator) (👨‍💻 28 · 🔀 32 · 📥 8 · 📦 5 · 📋 67 - 31% open · ⏱️ 04.06.2025):

	```
	git clone https://github.com/mamba-org/gator
	```
- [PyPi](https://pypi.org/project/mamba-gator) (📥 45 / month · ⏱️ 03.09.2021):
	```
	pip install mamba-gator
	```
- [Conda](https://anaconda.org/conda-forge/mamba_gator) (📥 54K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge mamba_gator
	```
- [npm](https://www.npmjs.com/package/@mamba-org/gator-lab) (📥 10 / month · 📦 5 · ⏱️ 03.09.2021):
	```
	npm install @mamba-org/gator-lab
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/jupyter-rsession-proxy">Rsession Proxy</a></b> (🥉21 ·  ⭐ 120) - Jupyter extensions for running an RStudio rsession proxy. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/jupyter-rsession-proxy) (👨‍💻 29 · 🔀 87 · 📦 63 · 📋 91 - 45% open · ⏱️ 17.03.2025):

	```
	git clone https://github.com/jupyterhub/jupyter-rsession-proxy
	```
- [PyPi](https://pypi.org/project/jupyter-rsession-proxy) (📥 4.6K / month · 📦 2 · ⏱️ 14.01.2025):
	```
	pip install jupyter-rsession-proxy
	```
- [Conda](https://anaconda.org/conda-forge/jupyter-rsession-proxy) (📥 36K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge jupyter-rsession-proxy
	```
</details>
<details><summary><b><a href="https://github.com/drillan/jupyter-black">Jupyter Black</a></b> (🥉8 ·  ⭐ 440 · 💀) - Black formatter for Jupyter Notebook. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/drillan/jupyter-black) (👨‍💻 2 · 🔀 24 · 📋 26 - 46% open · ⏱️ 01.02.2020):

	```
	git clone https://github.com/drillan/jupyter-black
	```
</details>
<details><summary>Show 14 hidden projects...</summary>

- <b><a href="https://github.com/ipython-contrib/jupyter_contrib_nbextensions">Contrib NBextensions</a></b> (🥇30 ·  ⭐ 5.3K · 💀) - A collection of various notebook extensions for.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/dunovank/jupyter-themes">Jupyter Themes</a></b> (🥇28 ·  ⭐ 9.8K · 💀) - Custom Jupyter Notebook Themes. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/oschuett/appmode">Appmode</a></b> (🥈22 ·  ⭐ 460 · 💀) - A Jupyter extensions that turns notebooks into web applications. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/googlecolab/jupyter_http_over_ws">HTTP-over-WebSocket</a></b> (🥉20 ·  ⭐ 270 · 💀) - Jupyter support for HTTP-over-ws. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/krishnan-r/sparkmonitor">Spark Monitor</a></b> (🥉18 ·  ⭐ 170 · 💀) - Monitor Apache Spark from Jupyter Notebook. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/mozilla/jupyter-spark">Jupyter Spark</a></b> (🥉17 ·  ⭐ 190 · 💀) - Jupyter Notebook extension for Apache Spark integration. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code>
- <b><a href="https://github.com/anaconda/nb_conda">nb_conda</a></b> (🥉17 ·  ⭐ 140 · 💀) - Conda environment and package access extension from within Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/codota/jupyter-tabnine">jupyter-tabnine</a></b> (🥉16 ·  ⭐ 790 · 💀) - Autocompletion with Deep Learning on Jupyter Notebook. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/lspvic/jupyter_tensorboard">jupyter-tensorboard</a></b> (🥉16 ·  ⭐ 460 · 💀) - Start Tensorboard in Jupyter Notebook. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/jupyter-incubator/contentmanagement">Content Management</a></b> (🥉16 ·  ⭐ 78 · 💀) - Jupyter Content Management Extensions. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/berkeley-dsep-infra/nbzip">nbzip</a></b> (🥉15 ·  ⭐ 90 · 💀) - Zips and downloads all the contents of a jupyter notebook. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/paypal/PPExtensions">PPExtensions</a></b> (🥉14 ·  ⭐ 50 · 💀) - Set of iPython and Jupyter extensions to improve user.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/thoth-station/jupyter-nbrequirements">jupyter-nbrequirements</a></b> (🥉14 ·  ⭐ 21 · 💀) - Dependency management and optimization in Jupyter.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/willkessler/jupyterterminals">jupyterterminals</a></b> (🥉8 ·  ⭐ 12 · 💀) - Jupyter plugin to support inline terminal shells along with.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Jupyter Magic

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Extensions that provide magic commands to access convenient functionality within a notebook._

<details><summary><b><a href="https://github.com/jupyter-incubator/sparkmagic">sparkmagic</a></b> (🥇30 ·  ⭐ 1.4K) - Jupyter magics and kernels for working with remote Spark clusters. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-incubator/sparkmagic) (👨‍💻 70 · 🔀 450 · 📦 390 · 📋 460 - 34% open · ⏱️ 28.05.2025):

	```
	git clone https://github.com/jupyter-incubator/sparkmagic
	```
- [PyPi](https://pypi.org/project/sparkmagic) (📥 26K / month · 📦 7 · ⏱️ 13.11.2024):
	```
	pip install sparkmagic
	```
- [Conda](https://anaconda.org/conda-forge/sparkmagic) (📥 170K · ⏱️ 28.05.2025):
	```
	conda install -c conda-forge sparkmagic
	```
</details>
<details><summary><b><a href="https://github.com/rasbt/watermark">watermark</a></b> (🥈24 ·  ⭐ 920 · 💤) - An IPython magic extension for printing date and time stamps,.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/rasbt/watermark) (👨‍💻 21 · 🔀 92 · 📦 2.7K · 📋 48 - 29% open · ⏱️ 22.09.2024):

	```
	git clone https://github.com/rasbt/watermark
	```
- [PyPi](https://pypi.org/project/watermark) (📥 51K / month · 📦 82 · ⏱️ 21.09.2024):
	```
	pip install watermark
	```
- [Conda](https://anaconda.org/conda-forge/watermark) (📥 350K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge watermark
	```
</details>
<details><summary><b><a href="https://github.com/dnanhkhoa/nb_black">nb_black</a></b> (🥈18 ·  ⭐ 360) - A simple extension for Jupyter Notebook and Jupyter Lab to beautify.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/dnanhkhoa/nb_black) (🔀 38):

	```
	git clone https://github.com/dnanhkhoa/nb_black
	```
- [PyPi](https://pypi.org/project/nb_black) (📥 16K / month · 📦 19 · ⏱️ 30.11.2019):
	```
	pip install nb_black
	```
- [Conda](https://anaconda.org/conda-forge/nb_black) (📥 430K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge nb_black
	```
</details>
<details><summary><b><a href="https://github.com/rossant/ipycache">ipycache</a></b> (🥉17 ·  ⭐ 140 · 💤) - Defines a %%cache cell magic in the IPython notebook to cache.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/rossant/ipycache) (👨‍💻 11 · 🔀 25 · 📦 37 · 📋 39 - 43% open · ⏱️ 21.11.2024):

	```
	git clone https://github.com/rossant/ipycache
	```
- [PyPi](https://pypi.org/project/ipycache) (📥 44 / month · 📦 2 · ⏱️ 13.10.2013):
	```
	pip install ipycache
	```
- [Conda](https://anaconda.org/conda-forge/ipycache) (📥 100K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge ipycache
	```
</details>
<details><summary>Show 8 hidden projects...</summary>

- <b><a href="https://github.com/catherinedevlin/ipython-sql">ipython-sql</a></b> (🥇30 ·  ⭐ 1.8K · 💀) - %%sql magic for IPython, hopefully evolving into full SQL client. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/nteract/pick">pick</a></b> (🥈21 ·  ⭐ 720 · 💀) - Customize your kernels on Launch!. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/csurfer/blackcellmagic">blackcellmagic</a></b> (🥈18 ·  ⭐ 310 · 💀) - IPython magic command to format python code in cell using.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/csurfer/pyheatmagic">heat</a></b> (🥉17 ·  ⭐ 1K · 💀) - IPython magic command to profile and view your python code as a heat map. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/ResidentMario/py_d3">py_d3</a></b> (🥉16 ·  ⭐ 450 · 💀) - D3 block magic for Jupyter notebook. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/tmthyjames/SQLCell">SQLCell</a></b> (🥉15 ·  ⭐ 150 · 💀) - SQLCell is a magic function for the Jupyter Notebook that executes.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/krassowski/jupyter-manim">jupyter-manim</a></b> (🥉12 ·  ⭐ 200 · 💀) - manim cell magic for IPython/Jupyter to show the output video. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/ShopRunner/jupyter-notify">jupyter-notify</a></b> (🥉12 ·  ⭐ 200 · 💀) - A Jupyter Notebook magic for browser notifications of cell.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
</details>
<br>

## Jupyter Kernels

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Jupyter kernels that run and introspect the user's code in a given language._

<details><summary><b><a href="https://github.com/ipython/ipykernel">IPython Kernel</a></b> (🥇38 ·  ⭐ 680) - IPython Kernel for Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/ipython/ipykernel) (👨‍💻 190 · 🔀 380 · 📥 3.4K · 📦 530K · 📋 560 - 52% open · ⏱️ 24.04.2025):

	```
	git clone https://github.com/ipython/ipykernel
	```
- [PyPi](https://pypi.org/project/ipykernel) (📥 41M / month · 📦 4.8K · ⏱️ 07.03.2025):
	```
	pip install ipykernel
	```
- [Conda](https://anaconda.org/anaconda/ipykernel) (📥 1M · 📦 77 · ⏱️ 22.04.2025):
	```
	conda install -c anaconda ipykernel
	```
</details>
<details><summary><b><a href="https://github.com/lfortran/lfortran">LFortran</a></b> (🥇29 ·  ⭐ 1.1K) - Official main repository for LFortran. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/lfortran/lfortran) (👨‍💻 120 · 🔀 200 · 📥 2.9K · 📋 3.6K - 49% open · ⏱️ 05.06.2025):

	```
	git clone https://github.com/lfortran/lfortran
	```
- [PyPi](https://pypi.org/project/lfortran) (📥 180 / month · ⏱️ 31.07.2020):
	```
	pip install lfortran
	```
- [Conda](https://anaconda.org/conda-forge/lfortran) (📥 240K · ⏱️ 06.05.2025):
	```
	conda install -c conda-forge lfortran
	```
</details>
<details><summary><b><a href="https://github.com/evcxr/evcxr">Evcxr</a></b> (🥇27 ·  ⭐ 6.1K) - An evaluation context for Rust, including a Jupyter Kernel. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/evcxr/evcxr) (👨‍💻 51 · 🔀 230 · 📥 7.6K · 📦 170 · 📋 270 - 43% open · ⏱️ 21.05.2025):

	```
	git clone https://github.com/evcxr/evcxr
	```
</details>
<details><summary><b><a href="https://github.com/Calysto/metakernel">Metakernel</a></b> (🥇27 ·  ⭐ 360) - Jupyter/IPython Kernel Tools. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Calysto/metakernel) (👨‍💻 34 · 🔀 87 · 📥 390 · 📦 1K · 📋 160 - 25% open · ⏱️ 07.04.2025):

	```
	git clone https://github.com/Calysto/metakernel
	```
- [PyPi](https://pypi.org/project/metakernel) (📥 28K / month · 📦 58 · ⏱️ 02.04.2025):
	```
	pip install metakernel
	```
- [Conda](https://anaconda.org/conda-forge/metakernel) (📥 960K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge metakernel
	```
</details>
<details><summary><b><a href="https://github.com/takluyver/bash_kernel">Bash Kernel</a></b> (🥈26 ·  ⭐ 720) - A bash kernel for IPython. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/takluyver/bash_kernel) (👨‍💻 21 · 🔀 140 · 📦 400 · 📋 110 - 11% open · ⏱️ 05.01.2025):

	```
	git clone https://github.com/takluyver/bash_kernel
	```
- [PyPi](https://pypi.org/project/bash_kernel) (📥 95K / month · 📦 23 · ⏱️ 05.01.2025):
	```
	pip install bash_kernel
	```
- [Conda](https://anaconda.org/conda-forge/bash_kernel) (📥 250K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge bash_kernel
	```
</details>
<details><summary><b><a href="https://github.com/dotnet/interactive">.NET Interactive</a></b> (🥈24 ·  ⭐ 3.1K) - .NET Interactive combines the power of .NET with many other.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/dotnet/interactive) (👨‍💻 130 · 🔀 400 · 📥 520 · 📋 1.7K - 33% open · ⏱️ 03.06.2025):

	```
	git clone https://github.com/dotnet/interactive
	```
</details>
<details><summary><b><a href="https://github.com/SciRuby/iruby">IRuby</a></b> (🥈24 ·  ⭐ 920) - Official gem repository: Ruby kernel for Jupyter/IPython Notebook. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/SciRuby/iruby) (👨‍💻 54 · 🔀 34 · 📥 22 · 📦 260 · 📋 210 - 24% open · ⏱️ 10.04.2025):

	```
	git clone https://github.com/SciRuby/iruby
	```
- [Docker Hub](https://hub.docker.com/r/rubydata/datascience-notebook) (📥 2.7K · ⭐ 5 · ⏱️ 03.02.2023):
	```
	docker pull rubydata/datascience-notebook
	```
</details>
<details><summary><b><a href="https://github.com/IHaskell/IHaskell">IHaskell</a></b> (🥈23 ·  ⭐ 2.6K) - A Haskell kernel for the Jupyter project. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/IHaskell/IHaskell) (👨‍💻 120 · 🔀 260 · 📋 790 - 5% open · ⏱️ 05.06.2025):

	```
	git clone https://github.com/gibiansky/IHaskell
	```
- [npm](https://www.npmjs.com/package/ihaskell_jupyterlab) (📥 13 / month · 📦 5 · ⏱️ 01.08.2018):
	```
	npm install ihaskell_jupyterlab
	```
</details>
<details><summary><b><a href="https://github.com/almond-sh/almond">almond</a></b> (🥈23 ·  ⭐ 1.6K · 📈) - A Scala kernel for Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/almond-sh/almond) (👨‍💻 42 · 🔀 250 · 📥 3K · 📋 340 - 38% open · ⏱️ 03.03.2025):

	```
	git clone https://github.com/almond-sh/almond
	```
- [Docker Hub](https://hub.docker.com/r/almondsh/almond) (📥 21K · ⭐ 6 · ⏱️ 25.02.2025):
	```
	docker pull almondsh/almond
	```
</details>
<details><summary><b><a href="https://github.com/Calysto/octave_kernel">Octave Kernel</a></b> (🥈23 ·  ⭐ 460) - An Octave kernel for IPython. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Calysto/octave_kernel) (👨‍💻 20 · 🔀 66 · 📥 320 · 📦 120 · 📋 180 - 18% open · ⏱️ 11.05.2025):

	```
	git clone https://github.com/calysto/octave_kernel
	```
- [PyPi](https://pypi.org/project/octave_kernel) (📥 8.1K / month · 📦 7 · ⏱️ 15.04.2024):
	```
	pip install octave_kernel
	```
- [Conda](https://anaconda.org/conda-forge/octave_kernel) (📥 640K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge octave_kernel
	```
</details>
<details><summary><b><a href="https://github.com/JuliaLang/IJulia.jl">IJulia.jl</a></b> (🥈22 ·  ⭐ 2.8K) - Julia kernel for Jupyter. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/JuliaLang/IJulia.jl) (👨‍💻 120 · 🔀 420 · 📋 880 - 11% open · ⏱️ 02.06.2025):

	```
	git clone https://github.com/JuliaLang/IJulia.jl
	```
</details>
<details><summary><b><a href="https://github.com/apache/incubator-toree">Apache Toree</a></b> (🥈21 ·  ⭐ 740) - Jupyter kernel for Apache Spark. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/apache/incubator-toree) (👨‍💻 110 · 🔀 220 · ⏱️ 06.05.2025):

	```
	git clone https://github.com/apache/incubator-toree
	```
- [PyPi](https://pypi.org/project/toree) (📥 5.3K / month · ⏱️ 21.04.2022):
	```
	pip install toree
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-xeus/xeus-python">xeus-python</a></b> (🥈21 ·  ⭐ 450) - Jupyter kernel for the Python programming language. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-xeus/xeus-python) (👨‍💻 25 · 🔀 77 · 📋 200 - 33% open · ⏱️ 06.05.2025):

	```
	git clone https://github.com/jupyter-xeus/xeus-python
	```
- [PyPi](https://pypi.org/project/xeus-python) (📥 7.3K / month · 📦 7 · ⏱️ 22.12.2023):
	```
	pip install xeus-python
	```
- [Conda](https://anaconda.org/conda-forge/xeus-python) (📥 2M · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge xeus-python
	```
</details>
<details><summary><b><a href="https://github.com/anaconda/nb_conda_kernels">nb_conda_kernels</a></b> (🥉19 ·  ⭐ 630) - Package for managing conda environment-based kernels inside.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/anaconda/nb_conda_kernels) (👨‍💻 20 · 🔀 70 · 📋 160 - 7% open · ⏱️ 12.02.2025):

	```
	git clone https://github.com/Anaconda-Platform/nb_conda_kernels
	```
- [Conda](https://anaconda.org/conda-forge/nb_conda_kernels) (📥 1.6M · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge nb_conda_kernels
	```
</details>
<details><summary><b><a href="https://github.com/sassoftware/sas_kernel">SAS Kernel</a></b> (🥉19 ·  ⭐ 200 · 💤) - A Jupyter kernel for SAS. This opens up all the data.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/sassoftware/sas_kernel) (👨‍💻 11 · 🔀 83 · 📋 60 - 1% open · ⏱️ 17.07.2024):

	```
	git clone https://github.com/sassoftware/sas_kernel
	```
- [PyPi](https://pypi.org/project/sas_kernel) (📥 4.6K / month · 📦 2 · ⏱️ 01.12.2022):
	```
	pip install sas_kernel
	```
- [Conda](https://anaconda.org/anaconda/sas_kernel) (📥 3.1K · ⏱️ 22.04.2025):
	```
	conda install -c anaconda sas_kernel
	```
</details>
<details><summary><b><a href="https://github.com/clojupyter/clojupyter">clojupyter</a></b> (🥉18 ·  ⭐ 850 · 📉) - a Jupyter kernel for Clojure. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/clojupyter/clojupyter) (👨‍💻 31 · 🔀 90 · 📥 140 · 📋 130 - 8% open · ⏱️ 18.03.2025):

	```
	git clone https://github.com/clojupyter/clojupyter
	```
- [Conda](https://anaconda.org/simplect/clojupyter) (📥 3.9K · ⏱️ 25.03.2025):
	```
	conda install -c simplect clojupyter
	```
- [Docker Hub](https://hub.docker.com/r/simplect/clojupyter) (📥 430 · ⏱️ 25.04.2019):
	```
	docker pull simplect/clojupyter
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-xeus/xeus-sqlite">xeus-sqlite</a></b> (🥉17 ·  ⭐ 170) - Jupyter kernel for SQLite. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-xeus/xeus-sqlite) (👨‍💻 14 · 🔀 25 · 📋 49 - 36% open · ⏱️ 16.12.2024):

	```
	git clone https://github.com/jupyter-xeus/xeus-sqlite
	```
- [Conda](https://anaconda.org/conda-forge/xeus-sqlite) (📥 66K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge xeus-sqlite
	```
</details>
<details><summary><b><a href="https://github.com/hugetim/nbstata">nbstata</a></b> (🥉11 ·  ⭐ 32) - A Jupyter kernel for Stata built on pystata. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code></summary>

- [GitHub](https://github.com/hugetim/nbstata) (👨‍💻 1 · 🔀 4 · 📋 41 - 24% open · ⏱️ 19.04.2025):

	```
	git clone https://github.com/hugetim/nbstata
	```
- [PyPi](https://pypi.org/project/nbstata) (📥 130 / month · ⏱️ 29.10.2024):
	```
	pip install nbstata
	```
</details>
<details><summary>Show 26 hidden projects...</summary>

- <b><a href="https://github.com/xonsh/xonsh">xonsh</a></b> (🥇36 ·  ⭐ 8.8K) - Python-powered shell. Full-featured and cross-platform. <code><a href="https://github.com/xonsh/xonsh/blob/main/license">❗️Custom</a></code>
- <b><a href="https://github.com/jupyter-server/kernel_gateway">Kernel Gateway</a></b> (🥈25 ·  ⭐ 530 · 💀) - Jupyter Kernel Gateway. <code>❗Unlicensed</code>
- <b><a href="https://github.com/n-riesco/ijavascript">IJavascript</a></b> (🥈24 ·  ⭐ 2.2K · 💀) - IJavascript is a javascript kernel for the Jupyter notebook. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/IRkernel/IRkernel">IRkernel</a></b> (🥈24 ·  ⭐ 1.7K · 💀) - R kernel for Jupyter. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/gopherdata/gophernotes">gophernotes</a></b> (🥈22 ·  ⭐ 3.9K · 💀) - The Go kernel for Jupyter notebooks and nteract. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/jupyter-server/enterprise_gateway">Enterprise Gateway</a></b> (🥈22 ·  ⭐ 640 · 💤) - A lightweight, multi-tenant, scalable and secure.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/jupyter-xeus/xeus-cling">xeus-cling</a></b> (🥈21 ·  ⭐ 3.2K · 💀) - Jupyter kernel for the C++ programming language. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/adtech-labs/spylon-kernel">Spylon Kernel</a></b> (🥈21 ·  ⭐ 190 · 💀) - Jupyter kernel for scala and spark. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/SpencerPark/IJava">IJava</a></b> (🥉19 ·  ⭐ 1.1K · 💀) - A Jupyter kernel for executing Java code. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/ansible/ansible-jupyter-kernel">Ansible Kernel</a></b> (🥉19 ·  ⭐ 540 · 💀) - Jupyter Notebook Kernel for running Ansible Tasks and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/Calysto/matlab_kernel">Matlab Kernel</a></b> (🥉19 ·  ⭐ 470 · 💀) - Jupyter Kernel for Matlab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/akabe/ocaml-jupyter">OCaml Kernel</a></b> (🥉18 ·  ⭐ 300 · 💀) - An OCaml kernel for Jupyter (IPython) notebook. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/scijava/scijava-jupyter-kernel">SciJava Kernel</a></b> (🥉18 ·  ⭐ 180 · 💀) - [RETIRED] Try IJava or BeakerX. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/fsprojects/IfSharp">F# Kernel</a></b> (🥉17 ·  ⭐ 440 · 💀) - F# for Jupyter Notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/Cadair/jupyter_environment_kernels">Kernel Detection</a></b> (🥉17 ·  ⭐ 150 · 💀) - An Jupyter plugin to enable the automatic detection of.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code>
- <b><a href="https://github.com/WolframResearch/WolframLanguageForJupyter">Wolfram Kernel</a></b> (🥉16 ·  ⭐ 1.1K · 💀) - Wolfram Language kernel for Jupyter notebooks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/jorgehpo/notebookJS">notebookJS</a></b> (🥉16 ·  ⭐ 270 · 💀) - notebookJS: seamless JavaScript integration in Python Notebooks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/minrk/allthekernels">allthekernels</a></b> (🥉15 ·  ⭐ 80 · 💀) - A multiplexer kernel for Jupyter. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/yunabe/lgo">lgo</a></b> (🥉14 ·  ⭐ 2.5K · 💀) - Interactive Go programming with Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/pprzetacznik/IElixir">IElixir</a></b> (🥉14 ·  ⭐ 360 · 💀) - Jupyters kernel for Elixir programming language. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/NII-cloud-operation/sshkernel">SSH Kernel</a></b> (🥉13 ·  ⭐ 75 · 💀) - SSH Kernel for Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/deathbeds/pidgy">pidgy</a></b> (🥉13 ·  ⭐ 44 · 💀) - Interactive computing in Markdown. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/tdaff/remote_ikernel">remote_ikernel</a></b> (🥉13 ·  ⭐ 19 · 💀) - All your Jupyter kernels, on all your machines, in one place. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code>
- <b><a href="https://github.com/bernhard-42/ssh_ipykernel">ssh_ipykernel</a></b> (🥉11 ·  ⭐ 17 · 💀) - A remote jupyter kernel via ssh. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/zabirauf/icsharp">ICSharp</a></b> (🥉10 ·  ⭐ 280 · 💀) - C# kernel for Jupyter. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/nteract/kernel-relay">kernel-relay</a></b> (🥉4 ·  ⭐ 12 · 💀) - kernel-relay is a GraphQL service for interfacing with.. <code>❗Unlicensed</code>
</details>
<br>

## Notebook Sharing & Conversion

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Tools to share, convert and simplify collaboration (e.g., via git) with notebook files._

<details><summary><b><a href="https://github.com/jupyter/nbconvert">nbconvert</a></b> (🥇40 ·  ⭐ 1.8K) - Jupyter Notebook Conversion. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/nbconvert) (👨‍💻 280 · 🔀 580 · 📥 1.8K · 📦 370K · 📋 1.2K - 46% open · ⏱️ 28.01.2025):

	```
	git clone https://github.com/jupyter/nbconvert
	```
- [PyPi](https://pypi.org/project/nbconvert) (📥 38M / month · 📦 2.4K · ⏱️ 28.01.2025):
	```
	pip install nbconvert
	```
- [Conda](https://anaconda.org/conda-forge/nbconvert) (📥 21M · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge nbconvert
	```
</details>
<details><summary><b><a href="https://github.com/mwouts/jupytext">Jupytext</a></b> (🥇35 ·  ⭐ 6.9K) - Jupyter Notebooks as Markdown Documents, Julia, Python or R scripts. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mwouts/jupytext) (👨‍💻 97 · 🔀 400 · 📦 10K · 📋 730 - 17% open · ⏱️ 01.06.2025):

	```
	git clone https://github.com/mwouts/jupytext
	```
- [PyPi](https://pypi.org/project/jupytext) (📥 1.3M / month · 📦 700 · ⏱️ 01.06.2025):
	```
	pip install jupytext
	```
- [Conda](https://anaconda.org/conda-forge/jupytext) (📥 1.1M · ⏱️ 02.06.2025):
	```
	conda install -c conda-forge jupytext
	```
- [npm](https://www.npmjs.com/package/jupyterlab-jupytext) (📥 2.4K / month · 📦 5 · ⏱️ 05.05.2024):
	```
	npm install jupyterlab-jupytext
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-book/jupyter-book">Jupyter Book</a></b> (🥇33 ·  ⭐ 4.1K) - Create beautiful, publication-quality books and documents from.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-book/jupyter-book) (👨‍💻 140 · 🔀 680 · 📥 89 · 📦 18K · 📋 1.5K - 45% open · ⏱️ 20.05.2025):

	```
	git clone https://github.com/executablebooks/jupyter-book
	```
- [PyPi](https://pypi.org/project/jupyter-book) (📥 210K / month · 📦 400 · ⏱️ 25.03.2025):
	```
	pip install jupyter-book
	```
- [Conda](https://anaconda.org/conda-forge/jupyter-book) (📥 220K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge jupyter-book
	```
</details>
<details><summary><b><a href="https://github.com/getnikola/nikola">nikola</a></b> (🥇33 ·  ⭐ 2.7K) - A static website and blog generator. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/getnikola/nikola) (👨‍💻 240 · 🔀 440 · 📥 190 · 📦 540 · 📋 2.2K - 2% open · ⏱️ 29.05.2025):

	```
	git clone https://github.com/getnikola/nikola
	```
- [PyPi](https://pypi.org/project/nikola) (📥 2.1K / month · 📦 2 · ⏱️ 17.05.2025):
	```
	pip install nikola
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/nbdime">nbdime</a></b> (🥈32 ·  ⭐ 2.7K · 💤) - Tools for diffing and merging of Jupyter notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/nbdime) (👨‍💻 51 · 🔀 170 · 📥 280 · 📦 13K · 📋 370 - 27% open · ⏱️ 05.09.2024):

	```
	git clone https://github.com/jupyter/nbdime
	```
- [PyPi](https://pypi.org/project/nbdime) (📥 260K / month · 📦 99 · ⏱️ 05.09.2024):
	```
	pip install nbdime
	```
- [Conda](https://anaconda.org/conda-forge/nbdime) (📥 1.2M · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge nbdime
	```
- [npm](https://www.npmjs.com/package/nbdime-jupyterlab) (📥 12K / month · 📦 12 · ⏱️ 05.09.2024):
	```
	npm install nbdime-jupyterlab
	```
</details>
<details><summary><b><a href="https://github.com/voila-dashboards/voila">Voila</a></b> (🥈31 ·  ⭐ 5.7K) - Voil turns Jupyter notebooks into standalone web applications. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/voila-dashboards/voila) (👨‍💻 73 · 🔀 510 · 📥 1.9K · 📦 12K · 📋 770 - 41% open · ⏱️ 06.05.2025):

	```
	git clone https://github.com/voila-dashboards/voila
	```
- [PyPi](https://pypi.org/project/voila) (📥 110K / month · 📦 150 · ⏱️ 18.10.2024):
	```
	pip install voila
	```
- [Conda](https://anaconda.org/conda-forge/voila) (📥 480K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge voila
	```
- [npm](https://www.npmjs.com/package/@jupyter-voila/jupyterlab-preview) (📥 63 / month · 📦 5 · ⏱️ 19.05.2020):
	```
	npm install @jupyter-voila/jupyterlab-preview
	```
</details>
<details><summary><b><a href="https://github.com/stencila/stencila">Stencila</a></b> (🥈28 ·  ⭐ 830) - Documents with Scientific Intelligence. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/stencila/stencila) (👨‍💻 48 · 🔀 51 · 📥 5.6K · 📦 20 · 📋 890 - 13% open · ⏱️ 30.05.2025):

	```
	git clone https://github.com/stencila/stencila
	```
- [npm](https://www.npmjs.com/package/stencila) (📥 140 / month · 📦 9 · ⏱️ 06.11.2020):
	```
	npm install stencila
	```
- [Docker Hub](https://hub.docker.com/r/stencila/cloud) (📥 17K · ⏱️ 08.04.2019):
	```
	docker pull stencila/cloud
	```
</details>
<details><summary><b><a href="https://github.com/danielfrg/mkdocs-jupyter">mkdocs-jupyter</a></b> (🥈27 ·  ⭐ 440) - Use Jupyter Notebook in mkdocs. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/danielfrg/mkdocs-jupyter) (👨‍💻 33 · 🔀 56 · 📦 3.9K · 📋 150 - 28% open · ⏱️ 21.02.2025):

	```
	git clone https://github.com/danielfrg/mkdocs-jupyter
	```
- [PyPi](https://pypi.org/project/mkdocs-jupyter) (📥 260K / month · 📦 450 · ⏱️ 15.10.2024):
	```
	pip install mkdocs-jupyter
	```
- [Conda](https://anaconda.org/conda-forge/mkdocs-jupyter) (📥 110K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge mkdocs-jupyter
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/nbviewer">nbviewer</a></b> (🥈25 ·  ⭐ 2.3K) - nbconvert as a web service: Render Jupyter Notebooks as static web.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/nbviewer) (👨‍💻 97 · 🔀 550 · 📦 28 · 📋 590 - 30% open · ⏱️ 23.01.2025):

	```
	git clone https://github.com/jupyter/nbviewer
	```
- [Docker Hub](https://hub.docker.com/r/jupyter/nbviewer) (📥 2.8M · ⭐ 34 · ⏱️ 23.01.2025):
	```
	docker pull jupyter/nbviewer
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/binderhub">BinderHub</a></b> (🥉23 ·  ⭐ 2.6K) - Run your code in the cloud, with technology so advanced, it feels.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/binderhub) (👨‍💻 100 · 🔀 390 · 📦 12 · 📋 740 - 31% open · ⏱️ 03.06.2025):

	```
	git clone https://github.com/jupyterhub/binderhub
	```
- [PyPi](https://pypi.org/project/binderhub) (📥 20 / month · ⏱️ 07.11.2018):
	```
	pip install binderhub
	```
</details>
<details><summary><b><a href="https://github.com/nbgallery/nbgallery">nbgallery</a></b> (🥉21 ·  ⭐ 150) - Enterprise Jupyter notebook sharing and collaboration app. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nbgallery/nbgallery) (👨‍💻 28 · 🔀 36 · 📋 510 - 9% open · ⏱️ 19.05.2025):

	```
	git clone https://github.com/nbgallery/nbgallery
	```
- [Docker Hub](https://hub.docker.com/r/nbgallery/nbgallery) (📥 170K · ⭐ 5 · ⏱️ 19.05.2025):
	```
	docker pull nbgallery/nbgallery
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-book/thebe">ThebeLab</a></b> (🥉20 ·  ⭐ 420) - Turn static HTML pages into live documents with Jupyter kernels. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-book/thebe) (👨‍💻 32 · 🔀 66 · 📦 15 · 📋 250 - 44% open · ⏱️ 14.05.2025):

	```
	git clone https://github.com/executablebooks/thebe
	```
- [npm](https://www.npmjs.com/package/thebe) (📥 390 / month · 📦 3 · ⏱️ 28.01.2025):
	```
	npm install thebe
	```
</details>
<details><summary><b><a href="https://github.com/ideonate/cdsdashboards">cdsdashboards</a></b> (🥉18 ·  ⭐ 200 · 💤) - JupyterHub extension for ContainDS Dashboards. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/ideonate/cdsdashboards) (👨‍💻 14 · 🔀 37 · 📋 95 - 37% open · ⏱️ 15.08.2024):

	```
	git clone https://github.com/ideonate/cdsdashboards
	```
- [PyPi](https://pypi.org/project/cdsdashboards) (📥 320 / month · ⏱️ 19.09.2022):
	```
	pip install cdsdashboards
	```
- [Conda](https://anaconda.org/conda-forge/cdsdashboards) (📥 80K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge cdsdashboards
	```
</details>
<details><summary>Show 11 hidden projects...</summary>

- <b><a href="https://github.com/damianavila/RISE">RISE</a></b> (🥈29 ·  ⭐ 3.7K · 💀) - RISE: Live Reveal.js Jupyter/IPython Slideshow Extension. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/airbnb/knowledge-repo">Knowledge Repo</a></b> (🥈25 ·  ⭐ 5.5K · 💀) - A next-generation curated knowledge sharing platform.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/aaren/notedown">notedown</a></b> (🥉23 ·  ⭐ 860 · 💀) - Markdown = IPython Notebook. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code>
- <b><a href="https://github.com/nteract/scrapbook">scrapbook</a></b> (🥉22 ·  ⭐ 290 · 💀) - A library for recording and reading data in notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/nteract/commuter">commuter</a></b> (🥉21 ·  ⭐ 6.2K · 💀) - Notebook sharing hub. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/danielfrg/jupyter-flex">jupyter-flex</a></b> (🥉21 ·  ⭐ 320 · 💀) - Build dashboards using Jupyter Notebooks. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/greenape/mknotebooks">mknotebooks</a></b> (🥉21 ·  ⭐ 140 · 💀) - A plugin for mkdocs to help you include Jupyter notebooks in your.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/SamLau95/nbinteract">nbinteract</a></b> (🥉18 ·  ⭐ 240 · 💀) - Create interactive webpages from Jupyter Notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/nteract/bookstore">bookstore</a></b> (🥉17 ·  ⭐ 200 · 💀) - Notebook storage and publishing workflows for the masses. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/elehcimd/pynb">pynb</a></b> (🥉15 ·  ⭐ 250 · 💀) - Jupyter Notebooks as plain Python code with embedded Markdown text. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/line/jnotebook_reader">jnotebook-reader</a></b> (🥉9 ·  ⭐ 100 · 💀) - An awesome viewer to browse and render Jupyter.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
</details>
<br>

## Notebook Tools

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries and tools that work with or can be used within notebook files._

<details><summary><b><a href="https://github.com/jupyter/nbformat">nbformat</a></b> (🥇34 ·  ⭐ 300) - Reference implementation of the Jupyter Notebook format. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/nbformat) (👨‍💻 80 · 🔀 160 · 📥 560 · 📦 370K · 📋 150 - 45% open · ⏱️ 16.05.2025):

	```
	git clone https://github.com/jupyter/nbformat
	```
- [PyPi](https://pypi.org/project/nbformat) (📥 38M / month · 📦 1.9K · ⏱️ 04.04.2024):
	```
	pip install nbformat
	```
- [Conda](https://anaconda.org/conda-forge/nbformat) (📥 29M · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge nbformat
	```
- [npm](https://www.npmjs.com/package/nbformat-schema) (📥 48 / month · 📦 5 · ⏱️ 04.04.2024):
	```
	npm install nbformat-schema
	```
</details>
<details><summary><b><a href="https://github.com/AnswerDotAI/nbdev">nbdev</a></b> (🥇33 ·  ⭐ 5.1K) - Create delightful software with Jupyter Notebooks. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/AnswerDotAI/nbdev) (👨‍💻 63 · 🔀 510 · 📦 2.8K · 📋 920 - 18% open · ⏱️ 03.04.2025):

	```
	git clone https://github.com/fastai/nbdev
	```
- [PyPi](https://pypi.org/project/nbdev) (📥 87K / month · 📦 390 · ⏱️ 03.04.2025):
	```
	pip install nbdev
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/jupyter_client">Jupyter Client</a></b> (🥇32 ·  ⭐ 430) - Jupyter protocol client APIs. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/jupyter_client) (👨‍💻 140 · 🔀 290 · 📥 2.3K · 📋 410 - 49% open · ⏱️ 25.04.2025):

	```
	git clone https://github.com/jupyter/jupyter_client
	```
- [PyPi](https://pypi.org/project/jupyter-client) (📥 43M / month · 📦 1.2K · ⏱️ 17.09.2024):
	```
	pip install jupyter-client
	```
- [Conda](https://anaconda.org/conda-forge/jupyter_client) (📥 30M · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge jupyter_client
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/nbclient">nbclient</a></b> (🥇32 ·  ⭐ 170) - A client library for executing notebooks. Formally nbconverts.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/nbclient) (👨‍💻 40 · 🔀 58 · 📥 730 · 📦 240K · 📋 120 - 42% open · ⏱️ 19.12.2024):

	```
	git clone https://github.com/jupyter/nbclient
	```
- [PyPi](https://pypi.org/project/nbclient) (📥 38M / month · 📦 470 · ⏱️ 19.12.2024):
	```
	pip install nbclient
	```
- [Conda](https://anaconda.org/conda-forge/nbclient) (📥 19M · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge nbclient
	```
</details>
<details><summary><b><a href="https://github.com/computationalmodelling/nbval">nbval</a></b> (🥈27 ·  ⭐ 450) - A py.test plugin to validate Jupyter notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/computationalmodelling/nbval) (👨‍💻 34 · 🔀 51 · 📦 3.7K · 📋 120 - 41% open · ⏱️ 31.03.2025):

	```
	git clone https://github.com/computationalmodelling/nbval
	```
- [PyPi](https://pypi.org/project/nbval) (📥 240K / month · 📦 540 · ⏱️ 04.03.2024):
	```
	pip install nbval
	```
- [Conda](https://anaconda.org/conda-forge/nbval) (📥 570K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge nbval
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/jupyter-sphinx">Jupyter Sphinx</a></b> (🥈27 ·  ⭐ 190 · 💤) - Sphinx extension for rendering of Jupyter interactive.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/jupyter-sphinx) (👨‍💻 28 · 🔀 65 · 📦 2.9K · 📋 160 - 32% open · ⏱️ 17.06.2024):

	```
	git clone https://github.com/jupyter/jupyter-sphinx
	```
- [PyPi](https://pypi.org/project/jupyter_sphinx) (📥 120K / month · 📦 530 · ⏱️ 28.12.2023):
	```
	pip install jupyter_sphinx
	```
- [Conda](https://anaconda.org/conda-forge/jupyter_sphinx) (📥 340K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge jupyter_sphinx
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/repo2docker">repo2docker</a></b> (🥈26 ·  ⭐ 1.7K) - Turn repositories into Jupyter-enabled Docker images. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/repo2docker) (👨‍💻 130 · 🔀 360 · 📋 560 - 31% open · ⏱️ 12.05.2025):

	```
	git clone https://github.com/jupyterhub/repo2docker
	```
- [PyPi](https://pypi.org/project/jupyter-repo2docker) (📥 2.9K / month · 📦 29 · ⏱️ 01.07.2024):
	```
	pip install jupyter-repo2docker
	```
</details>
<details><summary><b><a href="https://github.com/nbQA-dev/nbQA">nbQA</a></b> (🥈26 ·  ⭐ 1.1K) - Run ruff, isort, pyupgrade, mypy, pylint, flake8, and more on Jupyter.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nbQA-dev/nbQA) (👨‍💻 36 · 🔀 44 · 📥 160 · 📋 300 - 5% open · ⏱️ 05.06.2025):

	```
	git clone https://github.com/nbQA-dev/nbQA
	```
- [PyPi](https://pypi.org/project/nbqa) (📥 270K / month · 📦 110 · ⏱️ 10.11.2024):
	```
	pip install nbqa
	```
- [Conda](https://anaconda.org/conda-forge/nbqa) (📥 210K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge nbqa
	```
</details>
<details><summary><b><a href="https://github.com/chmp/ipytest">ipytest</a></b> (🥉22 ·  ⭐ 330) - Pytest in IPython notebooks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/chmp/ipytest) (👨‍💻 6 · 🔀 20 · 📦 620 · 📋 70 - 5% open · ⏱️ 16.02.2025):

	```
	git clone https://github.com/chmp/ipytest
	```
- [PyPi](https://pypi.org/project/ipytest) (📥 92K / month · 📦 25 · ⏱️ 16.02.2025):
	```
	pip install ipytest
	```
</details>
<details><summary><b><a href="https://github.com/nteract/testbook">testbook</a></b> (🥉21 ·  ⭐ 430 · 💤) - Unit test your Jupyter Notebooks the right way. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/nteract/testbook) (👨‍💻 16 · 🔀 38 · 📦 530 · 📋 95 - 48% open · ⏱️ 25.08.2024):

	```
	git clone https://github.com/nteract/testbook
	```
- [PyPi](https://pypi.org/project/nteract-testbook) (📥 16 / month · ⏱️ 11.08.2020):
	```
	pip install nteract-testbook
	```
- [Conda](https://anaconda.org/conda-forge/testbook) (📥 84K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge testbook
	```
</details>
<details><summary><b><a href="https://github.com/mljar/mercury">mercury</a></b> (🥉20 ·  ⭐ 4.2K) - Convert Jupyter Notebooks to Web Apps. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/mljar/mercury) (👨‍💻 16 · 🔀 270 · 📦 170 · 📋 440 - 19% open · ⏱️ 06.12.2024):

	```
	git clone https://github.com/mljar/mercury
	```
- [PyPi](https://pypi.org/project/mljar-mercury) (⏱️ 02.09.2022):
	```
	pip install mljar-mercury
	```
</details>
<details><summary><b><a href="https://github.com/tweag/jupyenv">JupyterWith</a></b> (🥉17 ·  ⭐ 710) - Declarative and reproducible Jupyter environments - powered by Nix. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/tweag/jupyenv) (👨‍💻 39 · 🔀 140 · 📋 210 - 18% open · ⏱️ 03.12.2024):

	```
	git clone https://github.com/tweag/jupyterWith
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-naas/naas">naas</a></b> (🥉17 ·  ⭐ 280 · 💤) - Low-code Python library to safely use notebooks in production:.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/jupyter-naas/naas) (👨‍💻 21 · 🔀 26 · 📦 6 · 📋 190 - 18% open · ⏱️ 23.07.2024):

	```
	git clone https://github.com/jupyter-naas/naas
	```
- [PyPi](https://pypi.org/project/naas) (📥 110 / month · ⏱️ 23.07.2024):
	```
	pip install naas
	```
</details>
<details><summary>Show 13 hidden projects...</summary>

- <b><a href="https://github.com/twosigma/beakerx">BeakerX</a></b> (🥈28 ·  ⭐ 2.8K · 💀) - Beaker Extensions for Jupyter Notebook. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/ipython/ipyparallel">ipyparallel</a></b> (🥈28 ·  ⭐ 2.6K) - IPython Parallel: Interactive Parallel Computing in Python. <code>❗Unlicensed</code>
- <b><a href="https://github.com/pixiedust/pixiedust">PixieDust</a></b> (🥈27 ·  ⭐ 1K · 💀) - Python Helper library for Jupyter Notebooks. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/fastai/fastpages">fastpages</a></b> (🥉23 ·  ⭐ 3.5K · 💀) - An easy to use blogging platform, with enhanced support for.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/ReviewNB/treon">treon</a></b> (🥉19 ·  ⭐ 310 · 💀) - Easy to use test framework for Jupyter Notebooks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/QuantEcon/sphinxcontrib-jupyter">sphinxcontrib.jupyter</a></b> (🥉19 ·  ⭐ 77 · 💀) - A Sphinx Extension for Generating Jupyter Notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/takluyver/nbopen">nbopen</a></b> (🥉18 ·  ⭐ 310 · 💀) - Open a Jupyter notebook in the best available server. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/stas00/ipyexperiments">ipyexperiments</a></b> (🥉15 ·  ⭐ 220 · 💀) - Automatic GPU+CPU memory profiling, re-use and memory.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/takluyver/jupyter_kernel_mgmt">Kernel Management</a></b> (🥉14 ·  ⭐ 15 · 💀) - Experimental new kernel management framework for Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/treebeardtech/nbmake-action">nbmake-action</a></b> (🥉11 ·  ⭐ 150 · 💀) - GitHub Action for testing notebooks. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/datitran/jupyter2slides">jupyter2slides</a></b> (🥉10 ·  ⭐ 790 · 💀) - Cloud Native Presentation Slides with Jupyter Notebook +.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/krassowski/jupyter-helpers">Jupyter Helpers</a></b> (🥉8 ·  ⭐ 47 · 💀) - A collection of helpers for Jupyter/IPython. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/Invictify/Jupter-Notebook-REST-API">Jupter-Notebook-REST-API</a></b> (🥉4 ·  ⭐ 82 · 💀) - Run your jupyter notebooks as a REST API endpoint... <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## JupyterLab Renderer

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Extensions that can render and display files of specific MIME types._

<details><summary><b><a href="https://github.com/jupyterlab/jupyter-renderers">JupyterLab Renderers</a></b> (🥇24 ·  ⭐ 500) - Renderers and renderer extensions for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyter-renderers) (👨‍💻 32 · 🔀 78 · 📦 39 · 📋 120 - 36% open · ⏱️ 20.02.2025):

	```
	git clone https://github.com/jupyterlab/jupyter-renderers
	```
- [PyPi](https://pypi.org/project/jupyterlab-katex) (📥 580 / month · 📦 2 · ⏱️ 23.05.2023):
	```
	pip install jupyterlab-katex
	```
- [Conda](https://anaconda.org/conda-forge/jupyterlab-vega3) (📥 6.6K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge jupyterlab-vega3
	```
- [npm](https://www.npmjs.com/package/@jupyterlab/geojson-extension) (📥 14K / month · 📦 10 · ⏱️ 01.08.2023):
	```
	npm install @jupyterlab/geojson-extension
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-latex">JupyterLab Latex</a></b> (🥈21 ·  ⭐ 650 · 💤) - JupyterLab extension for live editing of LaTeX documents. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab-latex) (👨‍💻 26 · 🔀 73 · 📥 190 · 📦 8 · 📋 97 - 29% open · ⏱️ 27.09.2024):

	```
	git clone https://github.com/jupyterlab/jupyterlab-latex
	```
- [PyPi](https://pypi.org/project/jupyterlab_latex) (📥 2.4K / month · 📦 1 · ⏱️ 27.09.2024):
	```
	pip install jupyterlab_latex
	```
- [Conda](https://anaconda.org/conda-forge/jupyterlab-latex) (📥 27K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge jupyterlab-latex
	```
- [npm](https://www.npmjs.com/package/@jupyterlab/latex) (📥 190 / month · 📦 5 · ⏱️ 27.09.2024):
	```
	npm install @jupyterlab/latex
	```
</details>
<details><summary>Show 6 hidden projects...</summary>

- <b><a href="https://github.com/QuantStack/jupyterlab-drawio">JupyterLab Drawio</a></b> (🥈23 ·  ⭐ 610 · 💀) - A standalone embedding of the FOSS drawio / mxgraph.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/plotly/jupyterlab-dash">JupyterLab Dash</a></b> (🥉19 ·  ⭐ 960 · 💀) - An Extension for the Interactive development of Dash apps in.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/quigleyj97/jupyterlab-spreadsheet">JupyterLab Spreadsheet</a></b> (🥉15 ·  ⭐ 200 · 💀) - JupyterLab plugin for viewing spreadsheets, such as.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jupytercalpoly/jupyterlab-tabular-data-editor">jupyterlab-tabular-data-editor</a></b> (🥉15 ·  ⭐ 140 · 💀) - Manipulate your tabular data responsively and.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/plotly/jupyterlab-chart-editor">JupyterLab Chart Editor</a></b> (🥉14 ·  ⭐ 220 · 💀) - JupyterLab extension for Plotlys react-chart-editor. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/altair-viz/jupyterlab_voyager">JupyterLab Voyager</a></b> (🥉13 ·  ⭐ 300 · 💀) - JupyterLab extension visualize data with Voyager. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
</details>
<br>

## JupyterLab Themes

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Extensions that can customize the appearance of JupyterLab._

<details><summary><b><a href="https://github.com/oriolmirosa/jupyterlab_materialdarker">Material Darker Theme</a></b> (🥈14 ·  ⭐ 170) - The Material Darker theme for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/oriolmirosa/jupyterlab_materialdarker) (👨‍💻 2 · 🔀 18 · 📋 21 - 28% open · ⏱️ 27.01.2025):

	```
	git clone https://github.com/oriolmirosa/jupyterlab_materialdarker
	```
- [PyPi](https://pypi.org/project/jupyterlab-materialdarker) (📥 600 / month · ⏱️ 27.01.2025):
	```
	pip install jupyterlab-materialdarker
	```
- [npm](https://www.npmjs.com/package/@oriolmirosa/jupyterlab_materialdarker) (📥 38 / month · 📦 5 · ⏱️ 16.12.2022):
	```
	npm install @oriolmirosa/jupyterlab_materialdarker
	```
</details>
<details><summary><b><a href="https://github.com/AllanChain/jupyterlab-theme-solarized-dark">jupyterlab-theme-solarized-dark</a></b> (🥉11 ·  ⭐ 110) - JupyterLab Theme Solarized Dark. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/AllanChain/jupyterlab-theme-solarized-dark) (👨‍💻 2 · 🔀 13 · 📥 81 · 📦 3 · 📋 4 - 50% open · ⏱️ 13.12.2024):

	```
	git clone https://github.com/AllanChain/jupyterlab-theme-solarized-dark
	```
- [PyPi](https://pypi.org/project/jupyterlab_theme_solarized_dark) (📥 5.2K / month · ⏱️ 18.01.2024):
	```
	pip install jupyterlab_theme_solarized_dark
	```
- [npm](https://www.npmjs.com/package/jupyterlab-theme-solarized-dark) (📥 770 / month · 📦 3 · ⏱️ 18.01.2024):
	```
	npm install jupyterlab-theme-solarized-dark
	```
</details>
<details><summary>Show 7 hidden projects...</summary>

- <b><a href="https://github.com/telamonian/theme-darcula">Darcula Theme</a></b> (🥇21 ·  ⭐ 220 · 💀) - A handsome Darcula theme for Jupyterlab. The first jlab.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/yeebc/jupyterlab-neon-theme">Neon Theme</a></b> (🥈13 ·  ⭐ 160 · 💀) - A flat, 80s neon inspired theme for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/dunovank/jupyterlab_darkside_ui">jupyterlab_darkside_ui</a></b> (🥈12 ·  ⭐ 120 · 💀) - Darkside ui and syntax theme for jupyterlab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/mohirio/jupyterlab-horizon-theme">Horizon Theme</a></b> (🥈12 ·  ⭐ 97 · 💀) - VSCode Horizon Theme port for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/Rahlir/theme-gruvbox">Gruvbox Theme</a></b> (🥈12 ·  ⭐ 52 · 💀) - Gruvbox dark theme for Jupyter Lab. Modeled on classic.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jtpio/jupyterlab-theme-toggle">Theme Toggle</a></b> (🥉10 ·  ⭐ 11 · 💤) - JupyterLab extension to toggle the theme in the Top Bar area. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/kenshohara/theme-nord-extension">Nord Theme</a></b> (🥉8 ·  ⭐ 26 · 💀) - JupyterLab - Nord Theme. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
</details>
<br>

## JupyterLab Extensions

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Application plugins that extend the functionality of JupyterLab itself._

<details><summary><b><a href="https://github.com/finos/perspective">Perspective</a></b> (🥇34 ·  ⭐ 9.2K) - A data visualization and analytics component, especially well-.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/finos/perspective) (👨‍💻 100 · 🔀 1.2K · 📥 12K · 📦 180 · 📋 880 - 12% open · ⏱️ 27.05.2025):

	```
	git clone https://github.com/finos/perspective
	```
- [PyPi](https://pypi.org/project/perspective-python) (📥 14K / month · 📦 30 · ⏱️ 01.05.2025):
	```
	pip install perspective-python
	```
- [Conda](https://anaconda.org/conda-forge/perspective) (📥 2.1M · ⏱️ 07.05.2025):
	```
	conda install -c conda-forge perspective
	```
- [npm](https://www.npmjs.com/package/@finos/perspective-jupyterlab) (📥 190 / month · 📦 6 · ⏱️ 01.05.2025):
	```
	npm install @finos/perspective-jupyterlab
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-git">JupyterLab Git</a></b> (🥇32 ·  ⭐ 1.5K) - A Git extension for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab-git) (👨‍💻 100 · 🔀 340 · 📥 520 · 📦 3.2K · 📋 620 - 17% open · ⏱️ 03.04.2025):

	```
	git clone https://github.com/jupyterlab/jupyterlab-git
	```
- [PyPi](https://pypi.org/project/jupyterlab-git) (📥 210K / month · 📦 41 · ⏱️ 03.04.2025):
	```
	pip install jupyterlab-git
	```
- [Conda](https://anaconda.org/conda-forge/jupyterlab-git) (📥 710K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge jupyterlab-git
	```
- [npm](https://www.npmjs.com/package/@jupyterlab/git) (📥 21K / month · 📦 9 · ⏱️ 03.04.2025):
	```
	npm install @jupyterlab/git
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-lsp/jupyterlab-lsp">JupyterLab LSP</a></b> (🥇31 ·  ⭐ 1.9K) - Coding assistance for JupyterLab (code navigation + hover.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-lsp/jupyterlab-lsp) (👨‍💻 52 · 🔀 150 · 📦 2.6K · 📋 590 - 35% open · ⏱️ 28.05.2025):

	```
	git clone https://github.com/jupyter-lsp/jupyterlab-lsp
	```
- [PyPi](https://pypi.org/project/jupyterlab-lsp) (📥 120K / month · 📦 57 · ⏱️ 29.05.2025):
	```
	pip install jupyterlab-lsp
	```
- [Conda](https://anaconda.org/conda-forge/jupyter-lsp) (📥 4.2M · ⏱️ 29.05.2025):
	```
	conda install -c conda-forge jupyter-lsp
	```
- [npm](https://www.npmjs.com/package/@krassowski/jupyterlab-lsp) (📥 250 / month · 📦 7 · ⏱️ 26.08.2022):
	```
	npm install @krassowski/jupyterlab-lsp
	```
</details>
<details><summary><b><a href="https://github.com/elyra-ai/elyra">elyra</a></b> (🥇29 ·  ⭐ 1.9K) - Elyra extends JupyterLab with an AI centric approach. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/elyra-ai/elyra) (👨‍💻 68 · 🔀 350 · 📦 74 · 📋 1.6K - 15% open · ⏱️ 23.05.2025):

	```
	git clone https://github.com/elyra-ai/elyra
	```
- [PyPi](https://pypi.org/project/elyra) (📥 2.3K / month · 📦 4 · ⏱️ 17.03.2025):
	```
	pip install elyra
	```
- [Conda](https://anaconda.org/conda-forge/elyra) (📥 70K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge elyra
	```
- [npm](https://www.npmjs.com/package/@elyra/services) (📥 1 / month · 📦 10 · ⏱️ 29.03.2023):
	```
	npm install @elyra/services
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab-contrib/jupyterlab-variableInspector">Variable Inspector</a></b> (🥈24 ·  ⭐ 1.2K) - Variable Inspector extension for Jupyterlab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab-contrib/jupyterlab-variableInspector) (👨‍💻 25 · 🔀 98 · 📥 340 · 📦 6 · 📋 180 - 27% open · ⏱️ 20.02.2025):

	```
	git clone https://github.com/lckr/jupyterlab-variableInspector
	```
- [PyPi](https://pypi.org/project/lckr-jupyterlab-variableinspector) (📥 12K / month · 📦 4 · ⏱️ 05.09.2024):
	```
	pip install lckr-jupyterlab-variableinspector
	```
- [Conda](https://anaconda.org/conda-forge/jupyterlab-variableinspector) (📥 85K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge jupyterlab-variableinspector
	```
- [npm](https://www.npmjs.com/package/@lckr/jupyterlab_variableinspector) (📥 18K / month · 📦 5 · ⏱️ 05.09.2024):
	```
	npm install @lckr/jupyterlab_variableinspector
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab-contrib/jupyterlab_code_formatter">Code Formatter</a></b> (🥈24 ·  ⭐ 880) - A JupyterLab plugin to facilitate invocation of code formatters. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jupyterlab-contrib/jupyterlab_code_formatter) (👨‍💻 46 · 🔀 60 · 📥 65 · 📦 2 · 📋 210 - 16% open · ⏱️ 21.05.2025):

	```
	git clone https://github.com/ryantam626/jupyterlab_code_formatter
	```
- [PyPi](https://pypi.org/project/jupyterlab_code_formatter) (📥 120K / month · 📦 52 · ⏱️ 14.08.2024):
	```
	pip install jupyterlab_code_formatter
	```
- [Conda](https://anaconda.org/conda-forge/jupyterlab_code_formatter) (📥 810K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge jupyterlab_code_formatter
	```
- [npm](https://www.npmjs.com/package/@ryantam626/jupyterlab_code_formatter) (📥 1.1K / month · 📦 5 · ⏱️ 16.04.2023):
	```
	npm install @ryantam626/jupyterlab_code_formatter
	```
</details>
<details><summary><b><a href="https://github.com/rapidsai/jupyterlab-nvdashboard">GPU Dashboards</a></b> (🥈23 ·  ⭐ 650) - A JupyterLab extension for displaying dashboards of GPU usage. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/rapidsai/jupyterlab-nvdashboard) (👨‍💻 25 · 🔀 79 · 📦 3 · 📋 90 - 41% open · ⏱️ 29.05.2025):

	```
	git clone https://github.com/rapidsai/jupyterlab-nvdashboard
	```
- [PyPi](https://pypi.org/project/jupyterlab-nvdashboard) (📥 7.5K / month · 📦 3 · ⏱️ 03.03.2025):
	```
	pip install jupyterlab-nvdashboard
	```
- [Conda](https://anaconda.org/conda-forge/jupyterlab-nvdashboard) (📥 57K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge jupyterlab-nvdashboard
	```
- [npm](https://www.npmjs.com/package/jupyterlab-nvdashboard) (📥 71 / month · 📦 5 · ⏱️ 27.04.2021):
	```
	npm install jupyterlab-nvdashboard
	```
</details>
<details><summary><b><a href="https://github.com/bokeh/jupyter_bokeh">Jupyter Bokeh</a></b> (🥈23 ·  ⭐ 260) - An extension for rendering Bokeh content in JupyterLab notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/bokeh/jupyter_bokeh) (👨‍💻 21 · 🔀 50 · 📦 6 · 📋 110 - 21% open · ⏱️ 10.03.2025):

	```
	git clone https://github.com/bokeh/jupyter_bokeh
	```
- [PyPi](https://pypi.org/project/jupyter-bokeh) (📥 82K / month · 📦 57 · ⏱️ 14.03.2023):
	```
	pip install jupyter-bokeh
	```
- [Conda](https://anaconda.org/conda-forge/jupyter_bokeh) (📥 160K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge jupyter_bokeh
	```
- [npm](https://www.npmjs.com/package/@bokeh/jupyter_bokeh) (📥 2.5K / month · 📦 5 · ⏱️ 03.06.2024):
	```
	npm install @bokeh/jupyter_bokeh
	```
</details>
<details><summary><b><a href="https://github.com/jtpio/ipylab">ipylab</a></b> (🥈23 ·  ⭐ 210 · 💤) - Control JupyterLab from Python Notebooks with Jupyter Widgets. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jtpio/ipylab) (👨‍💻 7 · 🔀 15 · 📥 250 · 📦 460 · 📋 51 - 56% open · ⏱️ 19.11.2024):

	```
	git clone https://github.com/jtpio/ipylab
	```
- [PyPi](https://pypi.org/project/ipylab) (📥 160K / month · 📦 40 · ⏱️ 11.08.2023):
	```
	pip install ipylab
	```
- [Conda](https://anaconda.org/conda-forge/ipylab) (📥 57K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge ipylab
	```
- [npm](https://www.npmjs.com/package/ipylab) (📥 960 / month · 📦 5 · ⏱️ 11.08.2023):
	```
	npm install ipylab
	```
</details>
<details><summary><b><a href="https://github.com/jpmorganchase/jupyter-fs">jupyter-fs</a></b> (🥈22 ·  ⭐ 220) - A filesystem-like contents manager for multiple backends in.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/jpmorganchase/jupyter-fs) (👨‍💻 18 · 🔀 37 · 📦 15 · 📋 99 - 17% open · ⏱️ 01.06.2025):

	```
	git clone https://github.com/jpmorganchase/jupyter-fs
	```
- [PyPi](https://pypi.org/project/jupyter-fs) (📥 1.1K / month · 📦 3 · ⏱️ 11.02.2025):
	```
	pip install jupyter-fs
	```
- [Conda](https://anaconda.org/conda-forge/jupyter-fs) (📥 19K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge jupyter-fs
	```
</details>
<details><summary><b><a href="https://github.com/finos/jupyterlab_templates">JupyterLab Templates</a></b> (🥈21 ·  ⭐ 410) - Support for jupyter notebook templates in jupyterlab. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/finos/jupyterlab_templates) (👨‍💻 21 · 🔀 69 · 📦 8 · 📋 96 - 11% open · ⏱️ 01.04.2025):

	```
	git clone https://github.com/jpmorganchase/jupyterlab_templates
	```
- [PyPi](https://pypi.org/project/jupyterlab_templates) (📥 25K / month · 📦 12 · ⏱️ 27.03.2024):
	```
	pip install jupyterlab_templates
	```
- [Conda](https://anaconda.org/conda-forge/jupyterlab_templates) (📥 40K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge jupyterlab_templates
	```
- [npm](https://www.npmjs.com/package/jupyterlab_templates) (📥 1.4K / month · 📦 5 · ⏱️ 12.02.2024):
	```
	npm install jupyterlab_templates
	```
</details>
<details><summary><b><a href="https://github.com/deshaw/jupyterlab-execute-time">jupyterlab-execute-time</a></b> (🥈21 ·  ⭐ 380) - A JupyterLab extension for displaying cell timings. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/deshaw/jupyterlab-execute-time) (👨‍💻 19 · 🔀 49 · 📦 4 · 📋 76 - 17% open · ⏱️ 19.12.2024):

	```
	git clone https://github.com/deshaw/jupyterlab-execute-time
	```
- [PyPi](https://pypi.org/project/jupyterlab-execute-time) (📥 78K / month · 📦 11 · ⏱️ 12.09.2024):
	```
	pip install jupyterlab-execute-time
	```
- [Conda](https://anaconda.org/conda-forge/jupyterlab_execute_time) (📥 110K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge jupyterlab_execute_time
	```
- [npm](https://www.npmjs.com/package/jupyterlab-execute-time) (📥 18K / month · 📦 5 · ⏱️ 18.01.2021):
	```
	npm install jupyterlab-execute-time
	```
</details>
<details><summary><b><a href="https://github.com/dask/dask-labextension">dask-labextension</a></b> (🥈21 ·  ⭐ 320) - JupyterLab extension for Dask. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/dask/dask-labextension) (👨‍💻 26 · 🔀 65 · 📦 3 · 📋 150 - 30% open · ⏱️ 02.06.2025):

	```
	git clone https://github.com/dask/dask-labextension
	```
- [PyPi](https://pypi.org/project/dask-labextension) (📥 5K / month · 📦 16 · ⏱️ 04.08.2023):
	```
	pip install dask-labextension
	```
- [Conda](https://anaconda.org/conda-forge/dask-labextension) (📥 1M · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge dask-labextension
	```
- [npm](https://www.npmjs.com/package/dask-labextension) (📥 160 / month · 📦 5 · ⏱️ 21.06.2022):
	```
	npm install dask-labextension
	```
</details>
<details><summary><b><a href="https://github.com/timkpaine/jupyterlab_iframe">JupyterLab IFrame</a></b> (🥈19 ·  ⭐ 110) - View html as an embedded iframe in JupyterLab. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/jupyterlab_iframe) (👨‍💻 5 · 🔀 21 · 📦 11 · 📋 70 - 8% open · ⏱️ 20.02.2025):

	```
	git clone https://github.com/timkpaine/jupyterlab_iframe
	```
- [PyPi](https://pypi.org/project/jupyterlab_iframe) (📥 2K / month · ⏱️ 16.07.2023):
	```
	pip install jupyterlab_iframe
	```
- [Conda](https://anaconda.org/conda-forge/jupyterlab_iframe) (📥 43K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge jupyterlab_iframe
	```
- [npm](https://www.npmjs.com/package/jupyterlab_iframe) (📥 75 / month · 📦 2 · ⏱️ 16.07.2023):
	```
	npm install jupyterlab_iframe
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-widgets/jupyterlab-sidecar">JupyterLab SideCar</a></b> (🥈18 ·  ⭐ 260) - A sidecar output widget for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-widgets/jupyterlab-sidecar) (👨‍💻 17 · 🔀 41 · 📦 7 · 📋 53 - 73% open · ⏱️ 28.03.2025):

	```
	git clone https://github.com/jupyter-widgets/jupyterlab-sidecar
	```
- [PyPi](https://pypi.org/project/sidecar) (📥 25K / month · 📦 23 · ⏱️ 30.08.2023):
	```
	pip install sidecar
	```
- [Conda](https://anaconda.org/conda-forge/sidecar) (📥 31K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge sidecar
	```
- [npm](https://www.npmjs.com/package/@jupyter-widgets/jupyterlab-sidecar) (📥 62 / month · 📦 5 · ⏱️ 05.07.2021):
	```
	npm install @jupyter-widgets/jupyterlab-sidecar
	```
</details>
<details><summary><b><a href="https://github.com/jpmorganchase/nbcelltests">nbcelltests</a></b> (🥉17 ·  ⭐ 94) - Cell-by-cell testing for production Jupyter notebooks in.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/jpmorganchase/nbcelltests) (👨‍💻 8 · 🔀 23 · 📦 5 · 📋 120 - 25% open · ⏱️ 01.04.2025):

	```
	git clone https://github.com/jpmorganchase/nbcelltests
	```
- [PyPi](https://pypi.org/project/nbcelltests) (📥 60 / month · ⏱️ 05.06.2024):
	```
	pip install nbcelltests
	```
- [Conda](https://anaconda.org/conda-forge/nbcelltests) (📥 15K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge nbcelltests
	```
- [npm](https://www.npmjs.com/package/jupyterlab_celltests) (📥 25 / month · 📦 5 · ⏱️ 05.10.2020):
	```
	npm install jupyterlab_celltests
	```
</details>
<details><summary><b><a href="https://github.com/timkpaine/jupyterlab_autoversion">JupyterLab Autoversion</a></b> (🥉17 ·  ⭐ 86) - Automatically version jupyter notebooks in JupyterLab. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/jupyterlab_autoversion) (👨‍💻 5 · 🔀 10 · 📋 37 - 13% open · ⏱️ 01.06.2025):

	```
	git clone https://github.com/timkpaine/jupyterlab_autoversion
	```
- [PyPi](https://pypi.org/project/jupyterlab_autoversion) (📥 97 / month · ⏱️ 19.06.2024):
	```
	pip install jupyterlab_autoversion
	```
- [Conda](https://anaconda.org/conda-forge/jupyterlab_autoversion) (📥 31K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge jupyterlab_autoversion
	```
- [npm](https://www.npmjs.com/package/jupyterlab_autoversion) (📥 23 / month · 📦 5 · ⏱️ 19.06.2024):
	```
	npm install jupyterlab_autoversion
	```
</details>
<details><summary><b><a href="https://github.com/vatlab/jupyterlab-sos">jupyterlab-sos</a></b> (🥉17 ·  ⭐ 75 · 💤) - Jupyterlab extension for SoS Polyglot Notebook and Workflow.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/vatlab/jupyterlab-sos) (👨‍💻 4 · 🔀 7 · 📦 3 · 📋 68 - 19% open · ⏱️ 18.10.2024):

	```
	git clone https://github.com/vatlab/jupyterlab-sos
	```
- [PyPi](https://pypi.org/project/jupyterlab-sos) (📥 280 / month · ⏱️ 17.10.2024):
	```
	pip install jupyterlab-sos
	```
- [Conda](https://anaconda.org/conda-forge/jupyterlab-sos) (📥 51K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge jupyterlab-sos
	```
- [npm](https://www.npmjs.com/package/jupyterlab-sos) (📥 76 / month · 📦 5 · ⏱️ 14.01.2021):
	```
	npm install jupyterlab-sos
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab-contrib/jupyterlab-kernelspy">JupyterLab Kernelspy</a></b> (🥉16 ·  ⭐ 85) - A Jupyter Lab extension for inspecting messages to/from.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab-contrib/jupyterlab-kernelspy) (👨‍💻 6 · 🔀 12 · 📥 56 · 📦 7 · 📋 16 - 31% open · ⏱️ 20.02.2025):

	```
	git clone https://github.com/jupyterlab-contrib/jupyterlab-kernelspy
	```
- [PyPi](https://pypi.org/project/jupyterlab-kernelspy) (📥 350 / month · ⏱️ 30.08.2023):
	```
	pip install jupyterlab-kernelspy
	```
- [Conda](https://anaconda.org/conda-forge/jupyterlab-kernelspy) (📥 19K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge jupyterlab-kernelspy
	```
- [npm](https://www.npmjs.com/package/jupyterlab-kernelspy) (📥 58 / month · 📦 5 · ⏱️ 30.08.2023):
	```
	npm install jupyterlab-kernelspy
	```
</details>
<details><summary><b><a href="https://github.com/timkpaine/lantern">Lantern</a></b> (🥉15 ·  ⭐ 350 · 💤) - Data exploration glue. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/lantern) (👨‍💻 3 · 🔀 20 · 📋 200 - 2% open · ⏱️ 18.11.2024):

	```
	git clone https://github.com/timkpaine/lantern
	```
- [PyPi](https://pypi.org/project/pylantern) (📥 29 / month · 📦 2 · ⏱️ 02.02.2020):
	```
	pip install pylantern
	```
</details>
<details><summary><b><a href="https://github.com/tkp-archive/knowledgelab">KnowledgeLab</a></b> (🥉15 ·  ⭐ 48 · 💤) - KnowledgeRepo + JupyterLab. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/tkp-archive/knowledgelab) (👨‍💻 3 · 🔀 6 · 📦 6 · 📋 30 - 16% open · ⏱️ 18.11.2024):

	```
	git clone https://github.com/timkpaine/knowledgelab
	```
- [PyPi](https://pypi.org/project/knowledgelab) (📥 7 / month · ⏱️ 19.10.2017):
	```
	pip install knowledgelab
	```
- [npm](https://www.npmjs.com/package/knowledgelab) (📥 20 / month · 📦 5 · ⏱️ 16.10.2018):
	```
	npm install knowledgelab
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab-contrib/jupyterlab-quickopen">JupyterLab Quickopen</a></b> (🥉14 ·  ⭐ 85) - Quickly open a file in JupyterLab by typing part of its.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab-contrib/jupyterlab-quickopen) (👨‍💻 8 · 🔀 15 · 📥 44 · 📦 27 · 📋 13 - 46% open · ⏱️ 08.12.2024):

	```
	git clone https://github.com/parente/jupyterlab-quickopen
	```
- [PyPi](https://pypi.org/project/jupyterlab-quickopen) (📥 700 / month · ⏱️ 21.10.2024):
	```
	pip install jupyterlab-quickopen
	```
- [npm](https://www.npmjs.com/package/@parente/jupyterlab-quickopen) (📥 2 / month · 📦 5 · ⏱️ 20.03.2020):
	```
	npm install @parente/jupyterlab-quickopen
	```
</details>
<details><summary><b><a href="https://github.com/timkpaine/jupyterlab_commands">jupyterlab_commands</a></b> (🥉14 ·  ⭐ 61) - Add arbitrary python commands to the jupyterlab.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/jupyterlab_commands) (👨‍💻 2 · 🔀 6 · 📋 24 - 4% open · ⏱️ 20.02.2025):

	```
	git clone https://github.com/timkpaine/jupyterlab_commands
	```
- [PyPi](https://pypi.org/project/jupyterlab-commands) (📥 78 / month · ⏱️ 12.07.2023):
	```
	pip install jupyterlab-commands
	```
- [Conda](https://anaconda.org/conda-forge/jupyterlab_commands) (📥 18K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge jupyterlab_commands
	```
</details>
<details><summary><b><a href="https://github.com/timkpaine/jupyterlab_email">JupyterLab Flake8</a></b> (🥉12 ·  ⭐ 110) - A jupyterlab extension to email notebooks directly from.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/jupyterlab_email) (👨‍💻 2 · 🔀 10 · 📦 2 · 📋 38 - 5% open · ⏱️ 20.02.2025):

	```
	git clone https://github.com/timkpaine/jupyterlab_email
	```
- [PyPi](https://pypi.org/project/jupyterlab-email) (📥 25 / month · ⏱️ 17.08.2023):
	```
	pip install jupyterlab-email
	```
- [npm](https://www.npmjs.com/package/jupyterlab-flake8) (📥 65 / month · 📦 5 · ⏱️ 16.09.2021):
	```
	npm install jupyterlab-flake8
	```
</details>
<details><summary><b><a href="https://github.com/ReviewNB/jupyterlab-gitplus">jupyterlab-gitplus</a></b> (🥉11 ·  ⭐ 120 · 💤) - JupyterLab extension to create GitHub commits & pull.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/ReviewNB/jupyterlab-gitplus) (👨‍💻 3 · 🔀 13 · 📦 3 · 📋 19 - 52% open · ⏱️ 25.06.2024):

	```
	git clone https://github.com/ReviewNB/jupyterlab-gitplus
	```
- [PyPi](https://pypi.org/project/jupyterlab_gitplus) (📥 73 / month · ⏱️ 25.06.2024):
	```
	pip install jupyterlab_gitplus
	```
- [npm](https://www.npmjs.com/package/@reviewnb/jupyterlab_gitplus) (📥 5 / month · 📦 5 · ⏱️ 28.02.2023):
	```
	npm install @reviewnb/jupyterlab_gitplus
	```
</details>
<details><summary><b><a href="https://github.com/timkpaine/jupyterlab_email">JupyterLab Email</a></b> (🥉11 ·  ⭐ 60) - A jupyterlab extension to email notebooks directly from.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/jupyterlab_email) (👨‍💻 2 · 🔀 2 · 📦 2 · 📋 38 - 5% open · ⏱️ 20.02.2025):

	```
	git clone https://github.com/timkpaine/jupyterlab_email
	```
- [PyPi](https://pypi.org/project/jupyterlab_email) (📥 25 / month · ⏱️ 17.08.2023):
	```
	pip install jupyterlab_email
	```
- [npm](https://www.npmjs.com/package/jupyterlab_email) (📥 29 / month · 📦 5 · ⏱️ 17.08.2023):
	```
	npm install jupyterlab_email
	```
</details>
<details><summary>Show 26 hidden projects...</summary>

- <b><a href="https://github.com/jupyterlab/debugger">JupyterLab Debugger</a></b> (🥇29 ·  ⭐ 15K · 💀) - A visual debugger for Jupyter notebooks, consoles,.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jupyterlab/jupyterlab-toc">JupyterLab TOC</a></b> (🥇28 ·  ⭐ 15K · 💀) - Table of Contents extension for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jtpio/jupyterlab-system-monitor">JupyterLab System Monitor</a></b> (🥈22 ·  ⭐ 300 · 💀) - JupyterLab extension to display system metrics. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jupyterlab-contrib/spellchecker">JupyterLab Spellchecker</a></b> (🥈22 ·  ⭐ 210 · 💀) - Spellchecker for JupyterLab notebook markdown cells.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jupyterlab/jupyterlab-github">JupyterLab GitHub</a></b> (🥈20 ·  ⭐ 420 · 💀) - GitHub integration for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jupyterlab/jupyterlab-google-drive">JupyterLab Google Drive</a></b> (🥈18 ·  ⭐ 400 · 💀) - Cloud storage for JupyterLab using Google Drive. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jupyterlab/jupyterlab-data-explorer">JupyterLab Data Explorer</a></b> (🥈18 ·  ⭐ 180 · 💀) - First class datasets in JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/chesterli29/jupyterlab_tensorboard">JupyterLab Tensorboard</a></b> (🥉17 ·  ⭐ 320 · 💀) - Tensorboard extension for jupyterlab. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/pbugnion/jupyterlab-sql">JupyterLab SQL</a></b> (🥉16 ·  ⭐ 430 · 💀) - SQL GUI for JupyterLab. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/jupytercalpoly/jupyterlab-interactive-dashboard-editor">jupyterlab-interactive-dashboard-editor</a></b> (🥉16 ·  ⭐ 220 · 💀) - A drag-and-drop dashboard editor for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/aquirdTurtle/Collapsible_Headings">Collapsible Headings</a></b> (🥉16 ·  ⭐ 190 · 💀) - Implements Collapsible Headers for Jupyter Lab.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jupyterlab/jupyterlab-hdf5">JupyterLab HDF5</a></b> (🥉16 ·  ⭐ 120 · 💀) - Open and explore HDF5 files in JupyterLab. Can handle very.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/mlshapiro/jupyterlab-flake8">jupyterlab-flake8</a></b> (🥉16 ·  ⭐ 110 · 💀) - Jupyterlab python linter for notebooks and text files.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jwkvam/jupyterlab-vim">JupyterLab Vim</a></b> (🥉15 ·  ⭐ 980 · 💀) - Vim notebook cell bindings for JupyterLab. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/jupyterlab/jupyterlab-commenting">JupyterLab Commenting</a></b> (🥉15 ·  ⭐ 100 · 💀) - Commenting and annotation for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/microsoft/gather">nbgather</a></b> (🥉14 ·  ⭐ 530 · 💀) - Spit shine for Jupyter notebooks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/krassowski/jupyterlab-go-to-definition">JupyterLab Go-To-Definition</a></b> (🥉14 ·  ⭐ 230 · 💀) - Navigate to variables definition with a click in.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/itsjafer/jupyterlab-sparkmonitor">jupyterlab-sparkmonitor</a></b> (🥉14 ·  ⭐ 92 · 💀) - JupyterLab extension that enables monitoring launched.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/jtpio/jupyterlab-python-file">JupyterLab Python Files</a></b> (🥉14 ·  ⭐ 51 · 💀) - JupyterLab extension to create Python files. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jtpio/jupyterlab-topbar">JupyterLab Top Bar</a></b> (🥉14 ·  ⭐ 6 · 💀) - JupyterLab Top Bar extension. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/xiaohk/stickyland">StickyLand</a></b> (🥉13 ·  ⭐ 570 · 💀) - Break the linear presentation of Jupyter Notebooks with sticky.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jupyterlab/jupyterlab-shortcutui">JupyterLab Shortcutui</a></b> (🥉13 ·  ⭐ 54 · 💀) - A JupyterLab extension for managing keyboard shortcuts. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jupyterlab/jupyterlab-celltags">jupyterlab-celltags</a></b> (🥉10 ·  ⭐ 110 · 💀) - A JupyterLab extension for notebook cell tags. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jtpio/jupyterlab-python-bytecode">JupyterLab Bytecode</a></b> (🥉10 ·  ⭐ 62 · 💀) - JupyterLab extension to explore CPython Bytecode. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/gavincyi/jupyterlab-executor">jupyterlab-executor</a></b> (🥉10 ·  ⭐ 16 · 💀) - JupyterLab extension to execute the scripts from the.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/manuzhang/jupyterlab_spark">JupyterLab Spark</a></b> (🥉9 ·  ⭐ 10 · 💀) - Spark Application UI extension for JupyterLab. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
</details>
<br>

## JupyterHub Authenticators

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Authentication modules that manage and control how users can access the JupyterHub deployment._

<details><summary><b><a href="https://github.com/jupyterhub/oauthenticator">OAuthenticator</a></b> (🥇28 ·  ⭐ 430) - OAuth + JupyterHub Authenticator = OAuthenticator. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/oauthenticator) (👨‍💻 130 · 🔀 370 · 📦 510 · 📋 320 - 16% open · ⏱️ 03.06.2025):

	```
	git clone https://github.com/jupyterhub/oauthenticator
	```
- [PyPi](https://pypi.org/project/oauthenticator) (📥 76K / month · 📦 32 · ⏱️ 11.12.2024):
	```
	pip install oauthenticator
	```
- [Conda](https://anaconda.org/conda-forge/oauthenticator) (📥 79K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge oauthenticator
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/ldapauthenticator">LDAP Authenticator</a></b> (🥇25 ·  ⭐ 210 · 💤) - LDAP Authenticator Plugin for Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/ldapauthenticator) (👨‍💻 36 · 🔀 180 · 📦 160 · 📋 170 - 8% open · ⏱️ 06.11.2024):

	```
	git clone https://github.com/jupyterhub/ldapauthenticator
	```
- [PyPi](https://pypi.org/project/jupyterhub-ldapauthenticator) (📥 12K / month · ⏱️ 06.11.2024):
	```
	pip install jupyterhub-ldapauthenticator
	```
- [Conda](https://anaconda.org/conda-forge/jupyterhub-ldapauthenticator) (📥 43K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge jupyterhub-ldapauthenticator
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/nativeauthenticator">Native Authenticator</a></b> (🥈21 ·  ⭐ 75) - JupyterHub-native User Authenticator. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/nativeauthenticator) (👨‍💻 24 · 🔀 69 · 📦 110 · 📋 110 - 30% open · ⏱️ 03.06.2025):

	```
	git clone https://github.com/jupyterhub/nativeauthenticator
	```
- [PyPi](https://pypi.org/project/jupyterhub-nativeauthenticator) (📥 10K / month · ⏱️ 17.09.2024):
	```
	pip install jupyterhub-nativeauthenticator
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/firstuseauthenticator">First Use Authenticator</a></b> (🥈18 ·  ⭐ 50) - JupyterHub Authenticator that lets users set.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/firstuseauthenticator) (👨‍💻 14 · 🔀 34 · 📦 120 · 📋 27 - 33% open · ⏱️ 28.03.2025):

	```
	git clone https://github.com/jupyterhub/firstuseauthenticator
	```
- [PyPi](https://pypi.org/project/jupyterhub-firstuseauthenticator) (📥 5.1K / month · ⏱️ 28.03.2025):
	```
	pip install jupyterhub-firstuseauthenticator
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/ltiauthenticator">LTI Authenticator</a></b> (🥈17 ·  ⭐ 72) - A JupyterHub authenticator for LTI. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/ltiauthenticator) (👨‍💻 18 · 🔀 54 · 📋 53 - 9% open · ⏱️ 04.12.2024):

	```
	git clone https://github.com/jupyterhub/ltiauthenticator
	```
- [PyPi](https://pypi.org/project/jupyterhub-ltiauthenticator) (📥 2.8K / month · ⏱️ 04.01.2024):
	```
	pip install jupyterhub-ltiauthenticator
	```
</details>
<details><summary><b><a href="https://github.com/HewlettPackard/jupyterhub-samlauthenticator">SAML Authenticator</a></b> (🥈17 ·  ⭐ 39) - jupyterhub-samlauthenticator. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/HewlettPackard/jupyterhub-samlauthenticator) (👨‍💻 7 · 🔀 26 · 📥 27 · 📦 3 · 📋 38 - 57% open · ⏱️ 25.01.2025):

	```
	git clone https://github.com/HewlettPackard/jupyterhub-samlauthenticator
	```
- [PyPi](https://pypi.org/project/jupyterhub-samlauthenticator) (📥 1.1K / month · ⏱️ 25.01.2025):
	```
	pip install jupyterhub-samlauthenticator
	```
</details>
<details><summary>Show 9 hidden projects...</summary>

- <b><a href="https://github.com/cwaldbieser/jhub_remote_user_authenticator">Remote User Auth</a></b> (🥉13 ·  ⭐ 42 · 💀) - REMOTE_USER authenticator for Jupyterhub. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/jupyterhub/dummyauthenticator">dummyauthenticator</a></b> (🥉13 ·  ⭐ 29 · 💀) - A Dummy JupyterHub Authenticator to make testing easy. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/mogthesprog/jwtauthenticator">JWT Authenticator</a></b> (🥉12 ·  ⭐ 54 · 💀) - A Token Authenticator for JupyterHub. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/ucphhpc/jhub-authenticators">Remote Authenticator</a></b> (🥉11 ·  ⭐ 2) - A collection of JupyterHub Authenticators, including.. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/cwaldbieser/jhub_cas_authenticator">CAS Authenticator</a></b> (🥉10 ·  ⭐ 23 · 💀) - CAS authenticator for Jupyterhub. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/jupyterhub/nullauthenticator">Null Authenticator</a></b> (🥉10 ·  ⭐ 9 · 💀) - Null Authenticator for JupyterHub instances that should.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/thedataincubator/jupyterhub-hashauthenticator">Hash Authenticator</a></b> (🥉10 ·  ⭐ 4 · 💀) - Authenticate users with passwords generated from their.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jupyterhub/kerberosauthenticator">Keberos Authenticator</a></b> (🥉8 ·  ⭐ 11 · 💀) - A JupyterHub authenticator using Kerberos. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/andreas-h/sshauthenticator">SSH Authenticator</a></b> (🥉4 ·  ⭐ 8 · 💀) - A simple SSH authenticator for JupyterHub. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
</details>
<br>

## JupyterHub Spawners

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Spawner modules that start, monitor, and stop single-user notebook servers._

<details><summary><b><a href="https://github.com/jupyterhub/dockerspawner">DockerSpawner</a></b> (🥇30 ·  ⭐ 520) - Spawns JupyterHub single user servers in Docker containers. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/dockerspawner) (👨‍💻 72 · 🔀 310 · 📦 240 · 📋 280 - 9% open · ⏱️ 14.05.2025):

	```
	git clone https://github.com/jupyterhub/dockerspawner
	```
- [PyPi](https://pypi.org/project/dockerspawner) (📥 70K / month · 📦 12 · ⏱️ 12.02.2025):
	```
	pip install dockerspawner
	```
- [Conda](https://anaconda.org/conda-forge/dockerspawner) (📥 28K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge dockerspawner
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/kubespawner">KubeSpawner</a></b> (🥈27 ·  ⭐ 580) - Kubernetes spawner for JupyterHub. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/kubespawner) (👨‍💻 90 · 🔀 300 · 📦 190 · 📋 390 - 23% open · ⏱️ 03.06.2025):

	```
	git clone https://github.com/jupyterhub/kubespawner
	```
- [PyPi](https://pypi.org/project/jupyterhub-kubespawner) (📥 16K / month · 📦 10 · ⏱️ 25.10.2024):
	```
	pip install jupyterhub-kubespawner
	```
- [Conda](https://anaconda.org/conda-forge/jupyterhub-kubespawner) (📥 36K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge jupyterhub-kubespawner
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/systemdspawner">SystemdSpawner</a></b> (🥉21 ·  ⭐ 97 · 💤) - Spawn JupyterHub single-user notebook servers with systemd. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/systemdspawner) (👨‍💻 21 · 🔀 49 · 📦 52 · 📋 75 - 33% open · ⏱️ 20.10.2024):

	```
	git clone https://github.com/jupyterhub/systemdspawner
	```
- [PyPi](https://pypi.org/project/jupyterhub-systemdspawner) (📥 3.3K / month · 📦 2 · ⏱️ 20.10.2024):
	```
	pip install jupyterhub-systemdspawner
	```
- [Conda](https://anaconda.org/conda-forge/jupyterhub-systemdspawner) (📥 67K · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge jupyterhub-systemdspawner
	```
</details>
<details><summary>Show 5 hidden projects...</summary>

- <b><a href="https://github.com/jupyterhub/batchspawner">BatchSpawner</a></b> (🥈22 ·  ⭐ 200 · 💀) - Custom Spawner for Jupyterhub to start servers in batch.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jupyterhub/sudospawner">SudoSpawner</a></b> (🥉18 ·  ⭐ 51 · 💀) - Spawn JupyterHub single-user servers with sudo. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jupyterhub/wrapspawner">WrapSpawner</a></b> (🥉13 ·  ⭐ 62 · 💀) - Mechanism for runtime configuration of spawners for JupyterHub. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/uktrade/fargatespawner">FargateSpawner</a></b> (🥉12 ·  ⭐ 41 · 💀) - Spawns JupyterHub single user servers in Docker containers.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/jupyterhub/yarnspawner">YarnSpawner</a></b> (🥉11 ·  ⭐ 19) - Spawn JupyterHub single user notebook servers in Hadoop/YARN.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
</details>
<br>

## Jupyter Components

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Core components of the Jupyter architecture._

<details><summary><b><a href="https://github.com/ipython/ipython">ipython</a></b> (🥇47 ·  ⭐ 16K) - Official repository for IPython itself. Other repos in the IPython.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/ipython/ipython) (👨‍💻 1K · 🔀 4.4K · 📥 320K · 📦 720K · 📋 7.5K - 20% open · ⏱️ 31.05.2025):

	```
	git clone https://github.com/ipython/ipython
	```
- [PyPi](https://pypi.org/project/ipython) (📥 75M / month · 📦 12K · ⏱️ 31.05.2025):
	```
	pip install ipython
	```
- [Conda](https://anaconda.org/conda-forge/ipython) (📥 39M · ⏱️ 31.05.2025):
	```
	conda install -c conda-forge ipython
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-server/jupyter_server">jupyter_server</a></b> (🥉37 ·  ⭐ 530) - The backendi.e. core services, APIs, and REST endpointsto.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-server/jupyter_server) (👨‍💻 530 · 🔀 340 · 📥 4.2K · 📋 520 - 41% open · ⏱️ 12.05.2025):

	```
	git clone https://github.com/jupyter-server/jupyter_server
	```
- [PyPi](https://pypi.org/project/jupyter_server) (📥 34M / month · 📦 1K · ⏱️ 12.05.2025):
	```
	pip install jupyter_server
	```
- [Conda](https://anaconda.org/conda-forge/jupyter_server) (📥 16M · ⏱️ 12.05.2025):
	```
	conda install -c conda-forge jupyter_server
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/jupyter/jupyter-packaging">jupyter-packaging</a></b> (🥉24 ·  ⭐ 65 · 💀) - Tools to help build and install Jupyter Python packages. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
</details>
<br>

## Others

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/spyder-ide/qtconsole">qtconsole</a></b> (🥇34 ·  ⭐ 430) - Jupyter Qt Console. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/spyder-ide/qtconsole) (👨‍💻 130 · 🔀 200 · 📦 200K · 📋 350 - 32% open · ⏱️ 18.02.2025):

	```
	git clone https://github.com/jupyter/qtconsole
	```
- [PyPi](https://pypi.org/project/qtconsole) (📥 2.5M / month · 📦 370 · ⏱️ 28.10.2024):
	```
	pip install qtconsole
	```
- [Conda](https://anaconda.org/conda-forge/qtconsole) (📥 5.2M · ⏱️ 22.04.2025):
	```
	conda install -c conda-forge qtconsole
	```
</details>
<details><summary><b><a href="https://github.com/abhishekkrthakur/colabcode">colabcode</a></b> (🥉19 ·  ⭐ 2.1K · 💤) - Run VSCode (codeserver) on Google Colab or Kaggle Notebooks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/abhishekkrthakur/colabcode) (👨‍💻 8 · 🔀 300 · 📋 95 - 65% open · ⏱️ 14.09.2024):

	```
	git clone https://github.com/abhishekkrthakur/colabcode
	```
- [PyPi](https://pypi.org/project/colabcode) (📥 9.7K / month · ⏱️ 11.06.2021):
	```
	pip install colabcode
	```
</details>
<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/jupyter/jupyter_console">jupyter-console</a></b> (🥈28 ·  ⭐ 260 · 💀) - Jupyter Terminal Console. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/datapane/datapane">datapane</a></b> (🥉22 ·  ⭐ 1.4K · 💀) - Build and share data reports in 100% Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
</details>

---

## Related Resources

- [**Best-of lists**](https://best-of.org): Discover other best-of lists with awesome open-source projects on all kinds of topics.
- [**best-of-ml-python**](https://github.com/ml-tooling/best-of-ml-python): A ranked list of awesome machine learning python libraries.
- [**awesome-jupyter**](https://github.com/markusschanta/awesome-jupyter): A curated list of awesome Jupyter projects, libraries and resources.
- [**awesome-jupyterlab**](https://github.com/mauhai/awesome-jupyterlab): A curated list of awesome JupyterLab extensions and resources.

## Contribution

Contributions are encouraged and always welcome! If you like to add or update projects, choose one of the following ways:

- Open an issue by selecting one of the provided categories from the [issue page](https://github.com/ml-tooling/best-of-jupyter/issues/new/choose) and fill in the requested information.
- Modify the [projects.yaml](https://github.com/ml-tooling/best-of-jupyter/blob/main/projects.yaml) with your additions or changes, and submit a pull request. This can also be done directly via the [Github UI](https://github.com/ml-tooling/best-of-jupyter/edit/main/projects.yaml).

If you like to contribute to or share suggestions regarding the project metadata collection or markdown generation, please refer to the [best-of-generator](https://github.com/best-of-lists/best-of-generator) repository. If you like to create your own best-of list, we recommend to follow [this guide](https://github.com/best-of-lists/best-of/blob/main/create-best-of-list.md).

For more information on how to add or update projects, please read the [contribution guidelines](https://github.com/ml-tooling/best-of-jupyter/blob/main/CONTRIBUTING.md). By participating in this project, you agree to abide by its [Code of Conduct](https://github.com/ml-tooling/best-of-jupyter/blob/main/.github/CODE_OF_CONDUCT.md).

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
