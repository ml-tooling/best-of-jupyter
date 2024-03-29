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

This curated list contains 300 awesome open-source projects with a total of 380K stars grouped into 13 categories. All projects are ranked by a project-quality score, which is calculated based on various metrics automatically collected from GitHub and different package managers. If you like to add or update projects, feel free to open an [issue](https://github.com/ml-tooling/best-of-jupyter/issues/new/choose), submit a [pull request](https://github.com/ml-tooling/best-of-jupyter/pulls), or directly edit the [projects.yaml](https://github.com/ml-tooling/best-of-jupyter/edit/main/projects.yaml). Contributions are very welcome!

---

<p align="center">
     🧙‍♂️&nbsp; Discover other <a href="https://best-of.org">best-of lists</a> or create <a href="https://github.com/best-of-lists/best-of/blob/main/create-best-of-list.md">your own</a>.<br>
    📫&nbsp; Subscribe to our <a href="https://mltooling.substack.com/subscribe">newsletter</a> for updates and trending projects.
</p>

---


## Contents

- [Notebook Environments](#notebook-environments) _16 projects_
- [Interactive Widgets & Visualization](#interactive-widgets--visualization) _56 projects_
- [Jupyter Extensions](#jupyter-extensions) _25 projects_
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

<details><summary><b><a href="https://github.com/jupyter/notebook">Jupyter</a></b> (🥇45 ·  ⭐ 12K) - Jupyter Interactive Notebook. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/notebook) (👨‍💻 650 · 🔀 4.5K · 📥 17K · 📦 270K · 📋 4.8K - 39% open · ⏱️ 13.03.2024):

	```
	git clone https://github.com/jupyter/notebook
	```
- [PyPi](https://pypi.org/project/notebook) (📥 24M / month · 📦 9.1K · ⏱️ 26.02.2024):
	```
	pip install notebook
	```
- [Conda](https://anaconda.org/conda-forge/jupyter) (📥 4.1M · ⏱️ 02.10.2023):
	```
	conda install -c conda-forge jupyter
	```
- [Docker Hub](https://hub.docker.com/r/jupyter/datascience-notebook) (📥 32M · ⭐ 1.1K · ⏱️ 20.10.2023):
	```
	docker pull jupyter/datascience-notebook
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/jupyterhub">JupyterHub</a></b> (🥇37 ·  ⭐ 7.9K) - Multi-user server for Jupyter notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/jupyterhub) (👨‍💻 360 · 🔀 2K · 📦 2.8K · 📋 2.4K - 7% open · ⏱️ 13.03.2024):

	```
	git clone https://github.com/jupyterhub/jupyterhub
	```
- [PyPi](https://pypi.org/project/jupyterhub) (📥 140K / month · 📦 400 · ⏱️ 10.08.2023):
	```
	pip install jupyterhub
	```
- [Conda](https://anaconda.org/conda-forge/jupyterhub) (📥 1.1M · ⏱️ 10.08.2023):
	```
	conda install -c conda-forge jupyterhub
	```
- [Docker Hub](https://hub.docker.com/r/jupyterhub/jupyterhub) (📥 5.1M · ⭐ 330 · ⏱️ 13.03.2024):
	```
	docker pull jupyterhub/jupyterhub
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/vscode-jupyter">VSCode Jupyter</a></b> (🥈32 ·  ⭐ 1.2K) - VS Code Jupyter extension. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/vscode-jupyter) (👨‍💻 270 · 🔀 250 · 📦 3 · 📋 9.6K - 3% open · ⏱️ 14.03.2024):

	```
	git clone https://github.com/microsoft/vscode-jupyter
	```
- [Conda](https://anaconda.org/conda-forge/vscode-jupyter) (📥 64K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge vscode-jupyter
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab">JupyterLab</a></b> (🥈31 ·  ⭐ 14K) - JupyterLab computational environment. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab) (👨‍💻 480 · 🔀 3K):

	```
	git clone https://github.com/jupyterlab/jupyterlab
	```
- [PyPi](https://pypi.org/project/jupyterlab) (📥 18M / month · 📦 2.5K · ⏱️ 07.03.2024):
	```
	pip install jupyterlab
	```
- [Conda](https://anaconda.org/conda-forge/jupyterlab) (📥 9.8M · ⏱️ 07.03.2024):
	```
	conda install -c conda-forge jupyterlab
	```
- [npm](https://www.npmjs.com/package/@jupyterlab/ui-components) (📥 230K / month · 📦 390 · ⏱️ 07.03.2024):
	```
	npm install @jupyterlab/ui-components
	```
</details>
<details><summary><b><a href="https://github.com/nteract/nteract">nteract</a></b> (🥈31 ·  ⭐ 6.1K) - The interactive computing suite for you!. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/nteract/nteract) (👨‍💻 180 · 🔀 550 · 📥 1.5M · 📦 3 · 📋 1.7K - 11% open · ⏱️ 30.12.2023):

	```
	git clone https://github.com/nteract/nteract
	```
- [PyPi](https://pypi.org/project/nteract_on_jupyter) (📥 1.1K / month · 📦 5 · ⏱️ 16.07.2019):
	```
	pip install nteract_on_jupyter
	```
- [npm](https://www.npmjs.com/package/@nteract/messaging) (📥 61K / month · 📦 37 · ⏱️ 22.10.2021):
	```
	npm install @nteract/messaging
	```
</details>
<details><summary><b><a href="https://github.com/vatlab/sos">sos</a></b> (🥈30 ·  ⭐ 260) - SoS workflow system for daily data analysis. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/vatlab/sos) (👨‍💻 36 · 🔀 40 · 📦 5.5K · 📋 1.5K - 4% open · ⏱️ 17.02.2024):

	```
	git clone https://github.com/vatlab/SOS
	```
- [PyPi](https://pypi.org/project/sos-notebook) (📥 1.6K / month · 📦 36 · ⏱️ 25.09.2023):
	```
	pip install sos-notebook
	```
- [Conda](https://anaconda.org/conda-forge/sos) (📥 170K · ⏱️ 19.02.2024):
	```
	conda install -c conda-forge sos
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/docker-stacks">Docker Stacks</a></b> (🥈26 ·  ⭐ 7.7K · 📉) - Ready-to-run Docker images containing Jupyter applications. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/docker-stacks) (👨‍💻 240 · 🔀 3K · 📦 21 · 📋 880 - 1% open · ⏱️ 04.03.2024):

	```
	git clone https://github.com/jupyter/docker-stacks
	```
- [Docker Hub](https://hub.docker.com/r/jupyter/scipy-notebook):
	```
	docker pull jupyter/scipy-notebook
	```
</details>
<details><summary><b><a href="https://github.com/Kaggle/docker-python">docker-python</a></b> (🥈26 ·  ⭐ 2.5K) - Kaggle Python docker image. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Kaggle/docker-python) (👨‍💻 160 · 🔀 960 · 📋 350 - 9% open · ⏱️ 08.03.2024):

	```
	git clone https://github.com/kaggle/docker-python
	```
- [Docker Hub](https://hub.docker.com/r/kaggle/python) (📥 200K · ⭐ 180 · ⏱️ 22.02.2024):
	```
	docker pull kaggle/python
	```
</details>
<details><summary><b><a href="https://github.com/ml-tooling/ml-workspace">ML Workspace</a></b> (🥉17 ·  ⭐ 3.3K · 📉) - All-in-one web-based IDE specialized for machine learning.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ml-tooling/ml-workspace) (👨‍💻 12 · 🔀 420 · 📋 94 - 2% open · ⏱️ 14.11.2023):

	```
	git clone https://github.com/ml-tooling/ml-workspace
	```
- [Docker Hub](https://hub.docker.com/r/mltooling/ml-workspace):
	```
	docker pull mltooling/ml-workspace
	```
</details>
<details><summary><b><a href="https://github.com/iot-salzburg/gpu-jupyter">gpu-jupyter</a></b> (🥉17 ·  ⭐ 640) - GPU-Jupyter: Leverage the flexibility of Jupyterlab through the.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/iot-salzburg/gpu-jupyter) (👨‍💻 15 · 🔀 220 · 📋 89 - 5% open · ⏱️ 24.01.2024):

	```
	git clone https://github.com/iot-salzburg/gpu-jupyter
	```
</details>
<details><summary><b><a href="https://github.com/jtpio/jupyterlite">jupyterlite</a></b> (🥉12 ·  ⭐ 87) - Wasm powered Jupyter running in the browser. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jtpio/jupyterlite) (👨‍💻 58 · 🔀 6 · ⏱️ 01.03.2024):

	```
	git clone https://github.com/jtpio/jupyterlite
	```
</details>
<details><summary>Show 5 hidden projects...</summary>

- <b><a href="https://github.com/googledatalab/datalab">DataLab</a></b> (🥈26 ·  ⭐ 980 · 💀) - Interactive tools and developer experiences for Big Data on.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/nteract/hydrogen">Hydrogen</a></b> (🥉22 ·  ⭐ 3.9K · 💀) - Run code interactively, inspect data, and plot. All the power of.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/jupyter-server/jupyverse">jupyverse</a></b> (🥉20 ·  ⭐ 180) - A Jupyter server based on FastAPI. <code><a href="https://tldrlegal.com/search?q=BSD-1-Clause">❗️BSD-1-Clause</a></code>
- <b><a href="https://github.com/jupyterlab/retrolab">retrolab</a></b> (🥉19 ·  ⭐ 280 · 💀) - JupyterLab distribution with a retro look and feel. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/ml-tooling/ml-hub">ML Hub</a></b> (🥉14 ·  ⭐ 290 · 💀) - Multi-user development platform for machine learning teams. Simple.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
</details>
<br>

## Interactive Widgets & Visualization

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Extensions that provide interactive UI-widgets and visualization tools._

🔗&nbsp;<b><a href="https://github.com/ml-tooling/best-of-ml-python#data-visualization">best-of-ml-python - Data Visualization</a></b>  - Python-based data visualization libraries.

<details><summary><b><a href="https://github.com/bokeh/bokeh">bokeh</a></b> (🥇43 ·  ⭐ 19K) - Interactive Data Visualization in the browser, from Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/bokeh/bokeh) (👨‍💻 690 · 🔀 4.1K · 📦 85K · 📋 7.6K - 9% open · ⏱️ 14.03.2024):

	```
	git clone https://github.com/bokeh/bokeh
	```
- [PyPi](https://pypi.org/project/bokeh) (📥 4.7M / month):
	```
	pip install bokeh
	```
- [Conda](https://anaconda.org/conda-forge/bokeh) (📥 13M · ⏱️ 25.01.2024):
	```
	conda install -c conda-forge bokeh
	```
- [npm](https://www.npmjs.com/package/@bokeh/bokehjs) (📥 11K / month):
	```
	npm install @bokeh/bokehjs
	```
</details>
<details><summary><b><a href="https://github.com/holoviz/panel">panel</a></b> (🥇39 ·  ⭐ 4K) - Panel: The powerful data exploration & web app framework for Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/holoviz/panel) (👨‍💻 170 · 🔀 440 · 📦 10K · 📋 3.3K - 30% open · ⏱️ 14.03.2024):

	```
	git clone https://github.com/holoviz/panel
	```
- [PyPi](https://pypi.org/project/panel) (📥 770K / month · 📦 220 · ⏱️ 13.03.2024):
	```
	pip install panel
	```
- [Conda](https://anaconda.org/conda-forge/panel) (📥 1.3M · ⏱️ 27.01.2024):
	```
	conda install -c conda-forge panel
	```
- [npm](https://www.npmjs.com/package/@holoviz/panel) (📥 53K / month · 📦 3 · ⏱️ 13.03.2024):
	```
	npm install @holoviz/panel
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-widgets/ipywidgets">ipywidgets</a></b> (🥇38 ·  ⭐ 3K) - Interactive Widgets for the Jupyter Notebook. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-widgets/ipywidgets) (👨‍💻 210 · 🔀 930 · 📦 3 · 📋 2.1K - 36% open · ⏱️ 08.02.2024):

	```
	git clone https://github.com/jupyter-widgets/ipywidgets
	```
- [PyPi](https://pypi.org/project/ipywidgets) (📥 17M / month · 📦 9.7K · ⏱️ 08.02.2024):
	```
	pip install ipywidgets
	```
- [Conda](https://anaconda.org/conda-forge/ipywidgets) (📥 13M · ⏱️ 08.02.2024):
	```
	conda install -c conda-forge ipywidgets
	```
- [npm](https://www.npmjs.com/package/@jupyter-widgets/jupyterlab-manager) (📥 80K / month · 📦 98 · ⏱️ 08.02.2024):
	```
	npm install @jupyter-widgets/jupyterlab-manager
	```
</details>
<details><summary><b><a href="https://github.com/ydataai/ydata-profiling">pandas-profiling</a></b> (🥇37 ·  ⭐ 12K) - 1 Line of code data quality profiling & exploratory data.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ydataai/ydata-profiling) (👨‍💻 120 · 🔀 1.6K · 📥 68 · 📦 2.6K · 📋 770 - 27% open · ⏱️ 13.03.2024):

	```
	git clone https://github.com/pandas-profiling/pandas-profiling
	```
- [PyPi](https://pypi.org/project/pandas-profiling) (📥 520K / month · 📦 200 · ⏱️ 03.02.2023):
	```
	pip install pandas-profiling
	```
- [Conda](https://anaconda.org/conda-forge/pandas-profiling) (📥 420K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge pandas-profiling
	```
</details>
<details><summary><b><a href="https://github.com/evidentlyai/evidently">evidently</a></b> (🥇36 ·  ⭐ 4.5K) - Evaluate and monitor ML models from validation to production... <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/evidentlyai/evidently) (👨‍💻 59 · 🔀 500 · 📥 17 · 📦 3.1K · 📋 330 - 40% open · ⏱️ 14.03.2024):

	```
	git clone https://github.com/evidentlyai/evidently
	```
- [PyPi](https://pypi.org/project/evidently) (📥 3.9M / month · 📦 7 · ⏱️ 22.02.2024):
	```
	pip install evidently
	```
- [Conda](https://anaconda.org/conda-forge/evidently) (📥 14K · ⏱️ 09.02.2024):
	```
	conda install -c conda-forge evidently
	```
</details>
<details><summary><b><a href="https://github.com/nteract/papermill">papermill</a></b> (🥇34 ·  ⭐ 5.6K) - Parameterize, execute, and analyze notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/nteract/papermill) (👨‍💻 120 · 🔀 400 · 📦 5.8K · 📋 390 - 34% open · ⏱️ 08.02.2024):

	```
	git clone https://github.com/nteract/papermill
	```
- [PyPi](https://pypi.org/project/papermill) (📥 1.5M / month · 📦 250 · ⏱️ 01.11.2023):
	```
	pip install papermill
	```
- [Conda](https://anaconda.org/conda-forge/papermill) (📥 560K · ⏱️ 29.02.2024):
	```
	conda install -c conda-forge papermill
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-widgets/ipyleaflet">ipyleaflet</a></b> (🥇34 ·  ⭐ 1.4K) - A Jupyter - Leaflet.js bridge. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jupyter-widgets/ipyleaflet) (👨‍💻 88 · 🔀 360 · 📦 7.7K · 📋 620 - 43% open · ⏱️ 01.03.2024):

	```
	git clone https://github.com/jupyter-widgets/ipyleaflet
	```
- [PyPi](https://pypi.org/project/ipyleaflet) (📥 140K / month · 📦 170 · ⏱️ 23.01.2024):
	```
	pip install ipyleaflet
	```
- [Conda](https://anaconda.org/conda-forge/ipyleaflet) (📥 1.1M · ⏱️ 23.01.2024):
	```
	conda install -c conda-forge ipyleaflet
	```
- [npm](https://www.npmjs.com/package/jupyter-leaflet) (📥 13K / month · 📦 6 · ⏱️ 23.01.2024):
	```
	npm install jupyter-leaflet
	```
</details>
<details><summary><b><a href="https://github.com/matplotlib/ipympl">jupyter-matplotlib</a></b> (🥈31 ·  ⭐ 1.5K) - Matplotlib Jupyter Integration. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/matplotlib/ipympl) (👨‍💻 33 · 🔀 220 · 📦 11K · 📋 310 - 48% open · ⏱️ 12.03.2024):

	```
	git clone https://github.com/matplotlib/ipympl
	```
- [PyPi](https://pypi.org/project/ipympl) (📥 280K / month · 📦 200 · ⏱️ 15.02.2023):
	```
	pip install ipympl
	```
- [Conda](https://anaconda.org/conda-forge/ipympl) (📥 1.5M · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge ipympl
	```
- [npm](https://www.npmjs.com/package/jupyter-matplotlib) (📥 9.8K / month · 📦 4 · ⏱️ 15.02.2023):
	```
	npm install jupyter-matplotlib
	```
</details>
<details><summary><b><a href="https://github.com/bqplot/bqplot">bqplot</a></b> (🥈30 ·  ⭐ 3.5K) - Plotting library for IPython/Jupyter notebooks. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/bqplot/bqplot) (👨‍💻 64 · 🔀 480 · 📦 55 · 📋 620 - 40% open · ⏱️ 04.10.2023):

	```
	git clone https://github.com/bqplot/bqplot
	```
- [PyPi](https://pypi.org/project/bqplot) (📥 120K / month · 📦 110 · ⏱️ 19.02.2024):
	```
	pip install bqplot
	```
- [Conda](https://anaconda.org/conda-forge/bqplot) (📥 1.3M · ⏱️ 19.02.2024):
	```
	conda install -c conda-forge bqplot
	```
- [npm](https://www.npmjs.com/package/bqplot) (📥 3.3K / month · 📦 17 · ⏱️ 17.10.2023):
	```
	npm install bqplot
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/responsible-ai-toolbox">responsible-ai-widgets</a></b> (🥈30 ·  ⭐ 1.2K) - Responsible AI Toolbox is a suite of tools providing.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/responsible-ai-toolbox) (👨‍💻 42 · 🔀 300 · 📦 90 · 📋 270 - 17% open · ⏱️ 05.03.2024):

	```
	git clone https://github.com/microsoft/responsible-ai-toolbox
	```
- [PyPi](https://pypi.org/project/raiwidgets) (📥 4.7K / month):
	```
	pip install raiwidgets
	```
</details>
<details><summary><b><a href="https://github.com/PAIR-code/facets">facets-overview</a></b> (🥈28 ·  ⭐ 7.3K · 💤) - Visualizations for machine learning datasets. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/PAIR-code/facets) (👨‍💻 31 · 🔀 910 · 📦 220 · 📋 160 - 50% open · ⏱️ 24.05.2023):

	```
	git clone https://github.com/pair-code/facets
	```
- [PyPi](https://pypi.org/project/facets-overview) (📥 280K / month · 📦 8 · ⏱️ 24.05.2023):
	```
	pip install facets-overview
	```
</details>
<details><summary><b><a href="https://github.com/InsightSoftwareConsortium/itkwidgets">itkwidgets</a></b> (🥈28 ·  ⭐ 570) - An elegant Python interface for visualization on the web platform.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/InsightSoftwareConsortium/itkwidgets) (👨‍💻 27 · 🔀 83 · 📥 88 · 📦 290 · 📋 280 - 41% open · ⏱️ 08.03.2024):

	```
	git clone https://github.com/InsightSoftwareConsortium/itkwidgets
	```
- [PyPi](https://pypi.org/project/itkwidgets) (📥 12K / month · 📦 18 · ⏱️ 08.03.2024):
	```
	pip install itkwidgets
	```
- [Conda](https://anaconda.org/conda-forge/itkwidgets) (📥 350K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge itkwidgets
	```
- [npm](https://www.npmjs.com/package/itkwidgets) (📥 500 / month · 📦 3 · ⏱️ 02.03.2023):
	```
	npm install itkwidgets
	```
</details>
<details><summary><b><a href="https://github.com/plotly/jupyter-dash">jupyter-dash</a></b> (🥈27 ·  ⭐ 940 · 💤) - OBSOLETE - Dash v2.11+ has Jupyter support built in!. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/plotly/jupyter-dash) (👨‍💻 10 · 🔀 240 · 📥 99 · 📦 3.7K · 📋 81 - 64% open · ⏱️ 11.08.2023):

	```
	git clone https://github.com/plotly/jupyter-dash
	```
- [PyPi](https://pypi.org/project/jupyter-dash) (📥 150K / month · 📦 73 · ⏱️ 01.04.2022):
	```
	pip install jupyter-dash
	```
- [Conda](https://anaconda.org/conda-forge/jupyter-dash) (📥 360K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge jupyter-dash
	```
- [npm](https://www.npmjs.com/package/jupyterlab-dash) (📥 2.1K / month · 📦 3 · ⏱️ 22.01.2021):
	```
	npm install jupyterlab-dash
	```
</details>
<details><summary><b><a href="https://github.com/widgetti/ipyvuetify">ipyvuetify</a></b> (🥈27 ·  ⭐ 330) - Jupyter widgets based on vuetify UI components. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/widgetti/ipyvuetify) (👨‍💻 14 · 🔀 54 · 📦 1.1K · 📋 200 - 32% open · ⏱️ 14.03.2024):

	```
	git clone https://github.com/mariobuikhuizen/ipyvuetify
	```
- [PyPi](https://pypi.org/project/ipyvuetify) (📥 120K / month):
	```
	pip install ipyvuetify
	```
- [Conda](https://anaconda.org/conda-forge/ipyvuetify) (📥 160K · ⏱️ 14.03.2024):
	```
	conda install -c conda-forge ipyvuetify
	```
- [npm](https://www.npmjs.com/package/jupyter-vuetify) (📥 12K / month):
	```
	npm install jupyter-vuetify
	```
</details>
<details><summary><b><a href="https://github.com/spacetelescope/jdaviz">jdaviz</a></b> (🥈27 ·  ⭐ 120) - JWST astronomical data analysis tools in the Jupyter platform. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/spacetelescope/jdaviz) (👨‍💻 32 · 🔀 56 · 📦 41 · 📋 990 - 32% open · ⏱️ 13.03.2024):

	```
	git clone https://github.com/spacetelescope/jdaviz
	```
- [PyPi](https://pypi.org/project/jdaviz) (📥 1.8K / month · 📦 3 · ⏱️ 23.02.2024):
	```
	pip install jdaviz
	```
</details>
<details><summary><b><a href="https://github.com/mwouts/itables">itables</a></b> (🥈26 ·  ⭐ 570) - Pandas DataFrames as Interactive DataTables. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mwouts/itables) (👨‍💻 6 · 🔀 46 · 📦 440 · 📋 120 - 19% open · ⏱️ 05.03.2024):

	```
	git clone https://github.com/mwouts/itables
	```
- [PyPi](https://pypi.org/project/itables) (📥 180K / month · 📦 23 · ⏱️ 14.03.2024):
	```
	pip install itables
	```
- [Conda](https://anaconda.org/conda-forge/itables) (📥 42K · ⏱️ 06.03.2024):
	```
	conda install -c conda-forge itables
	```
</details>
<details><summary><b><a href="https://github.com/lux-org/lux">lux</a></b> (🥈25 ·  ⭐ 4.9K · 💤) - Automatically visualize your pandas dataframe via a single print!. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/lux-org/lux) (👨‍💻 21 · 🔀 350 · 📦 180 · 📋 240 - 33% open · ⏱️ 04.07.2023):

	```
	git clone https://github.com/lux-org/lux
	```
- [PyPi](https://pypi.org/project/lux-api) (📥 3.7K / month · 📦 2 · ⏱️ 19.02.2022):
	```
	pip install lux-api
	```
- [Conda](https://anaconda.org/conda-forge/lux-api) (📥 22K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge lux-api
	```
- [npm](https://www.npmjs.com/package/luxwidget) (📥 300 / month · 📦 2 · ⏱️ 17.02.2022):
	```
	npm install luxwidget
	```
</details>
<details><summary><b><a href="https://github.com/finos/ipyregulartable">ipyregulartable</a></b> (🥈25 ·  ⭐ 3K · 📈) - High performance, editable, stylable datagrids in.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/finos/ipyregulartable) (👨‍💻 5 · 🔀 930 · 📦 13 · 📋 27 - 37% open · ⏱️ 05.02.2024):

	```
	git clone https://github.com/jpmorganchase/ipyregulartable
	```
- [PyPi](https://pypi.org/project/ipyregulartable) (📥 140 / month · 📦 2 · ⏱️ 08.01.2021):
	```
	pip install ipyregulartable
	```
- [Conda](https://anaconda.org/conda-forge/ipyregulartable) (📥 5.8K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge ipyregulartable
	```
- [npm](https://www.npmjs.com/package/@jupyter-widgets/jupyterlab-manager) (📥 80K / month · 📦 98 · ⏱️ 08.02.2024):
	```
	npm install @jupyter-widgets/jupyterlab-manager
	```
</details>
<details><summary><b><a href="https://github.com/timkpaine/ipydagred3">ipydagred3</a></b> (🥈25 ·  ⭐ 3K · 📈) - ipywidgets library for drawing directed acyclic graphs in.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/ipydagred3) (👨‍💻 3 · 🔀 930 · 📦 3 · 📋 24 - 20% open · ⏱️ 05.02.2024):

	```
	git clone https://github.com/timkpaine/ipydagred3
	```
- [PyPi](https://pypi.org/project/ipydagred3) (📥 680 / month · 📦 3 · ⏱️ 31.10.2023):
	```
	pip install ipydagred3
	```
- [Conda](https://anaconda.org/conda-forge/ipydagred3) (📥 28K · ⏱️ 01.11.2023):
	```
	conda install -c conda-forge ipydagred3
	```
- [npm](https://www.npmjs.com/package/@jupyter-widgets/jupyterlab-manager) (📥 80K / month · 📦 98 · ⏱️ 08.02.2024):
	```
	npm install @jupyter-widgets/jupyterlab-manager
	```
</details>
<details><summary><b><a href="https://github.com/widgetti/ipyvolume">ipyvolume</a></b> (🥈25 ·  ⭐ 1.9K · 💤) - 3d plotting for Python in the Jupyter notebook based on IPython.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/widgetti/ipyvolume) (👨‍💻 45 · 🔀 240 · 📦 16 · 📋 320 - 58% open · ⏱️ 07.07.2023):

	```
	git clone https://github.com/maartenbreddels/ipyvolume
	```
- [PyPi](https://pypi.org/project/ipyvolume) (📥 40K / month · 📦 53 · ⏱️ 02.06.2023):
	```
	pip install ipyvolume
	```
- [Conda](https://anaconda.org/conda-forge/ipyvolume) (📥 460K · ⏱️ 05.06.2023):
	```
	conda install -c conda-forge ipyvolume
	```
- [npm](https://www.npmjs.com/package/ipyvolume) (📥 1K / month · 📦 6 · ⏱️ 02.06.2023):
	```
	npm install ipyvolume
	```
</details>
<details><summary><b><a href="https://github.com/bloomberg/ipydatagrid">ipydatagrid</a></b> (🥈25 ·  ⭐ 490) - Fast Datagrid widget for the Jupyter Notebook and JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/bloomberg/ipydatagrid) (👨‍💻 21 · 🔀 47 · 📦 130 · 📋 140 - 44% open · ⏱️ 14.03.2024):

	```
	git clone https://github.com/bloomberg/ipydatagrid
	```
- [PyPi](https://pypi.org/project/ipydatagrid) (📥 13K / month · 📦 12 · ⏱️ 26.01.2024):
	```
	pip install ipydatagrid
	```
- [Conda](https://anaconda.org/conda-forge/ipydatagrid) (📥 58K · ⏱️ 26.01.2024):
	```
	conda install -c conda-forge ipydatagrid
	```
- [npm](https://www.npmjs.com/package/ipydatagrid) (📥 3.5K / month · 📦 3 · ⏱️ 19.02.2024):
	```
	npm install ipydatagrid
	```
</details>
<details><summary><b><a href="https://github.com/cytoscape/ipycytoscape">ipycytoscape</a></b> (🥈25 ·  ⭐ 260 · 💤) - A Cytoscape Jupyter widget. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/cytoscape/ipycytoscape) (👨‍💻 32 · 🔀 61 · 📥 4 · 📦 200 · 📋 160 - 38% open · ⏱️ 23.05.2023):

	```
	git clone https://github.com/cytoscape/ipycytoscape
	```
- [PyPi](https://pypi.org/project/ipycytoscape) (📥 28K / month):
	```
	pip install ipycytoscape
	```
- [Conda](https://anaconda.org/conda-forge/ipycytoscape) (📥 370K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge ipycytoscape
	```
- [npm](https://www.npmjs.com/package/jupyter-cytoscape) (📥 690 / month):
	```
	npm install jupyter-cytoscape
	```
</details>
<details><summary><b><a href="https://github.com/vizzuhq/ipyvizzu">ipyvizzu</a></b> (🥉24 ·  ⭐ 910) - Build animated charts in Jupyter Notebook and similar environments.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/vizzuhq/ipyvizzu) (👨‍💻 21 · 🔀 89 · 📥 120 · 📦 110 · 📋 91 - 15% open · ⏱️ 26.02.2024):

	```
	git clone https://github.com/vizzuhq/ipyvizzu
	```
- [PyPi](https://pypi.org/project/ipyvizzu) (📥 740 / month · 📦 3 · ⏱️ 21.12.2023):
	```
	pip install ipyvizzu
	```
</details>
<details><summary><b><a href="https://github.com/vega/ipyvega">vega</a></b> (🥉23 ·  ⭐ 370) - IPython/Jupyter notebook module for Vega and Vega-Lite. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/vega/ipyvega) (👨‍💻 15 · 🔀 62 · 📦 4 · 📋 100 - 12% open · ⏱️ 01.02.2024):

	```
	git clone https://github.com/vega/ipyvega
	```
- [PyPi](https://pypi.org/project/vega) (📥 24K / month · 📦 83 · ⏱️ 12.04.2023):
	```
	pip install vega
	```
- [Conda](https://anaconda.org/conda-forge/vega) (📥 580K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge vega
	```
</details>
<details><summary><b><a href="https://github.com/maartenbreddels/ipywebrtc">ipywebrtc</a></b> (🥉23 ·  ⭐ 230) - WebRTC for Jupyter notebook/lab. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/maartenbreddels/ipywebrtc) (👨‍💻 10 · 🔀 38 · 📦 1K · 📋 62 - 54% open · ⏱️ 06.02.2024):

	```
	git clone https://github.com/maartenbreddels/ipywebrtc
	```
- [PyPi](https://pypi.org/project/ipywebrtc) (📥 39K / month · 📦 13 · ⏱️ 29.03.2021):
	```
	pip install ipywebrtc
	```
- [Conda](https://anaconda.org/conda-forge/ipywebrtc) (📥 330K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge ipywebrtc
	```
- [npm](https://www.npmjs.com/package/jupyter-webrtc) (📥 370 / month · 📦 4 · ⏱️ 29.03.2021):
	```
	npm install jupyter-webrtc
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-widgets-contrib/ipysheet">ipysheet</a></b> (🥉21 ·  ⭐ 540) - Jupyter handsontable integration. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jupyter-widgets-contrib/ipysheet) (👨‍💻 14 · 🔀 69 · 📦 7 · 📋 120 - 51% open · ⏱️ 04.01.2024):

	```
	git clone https://github.com/QuantStack/ipysheet
	```
- [PyPi](https://pypi.org/project/ipysheet) (📥 95K / month · 📦 28 · ⏱️ 28.11.2022):
	```
	pip install ipysheet
	```
- [Conda](https://anaconda.org/conda-forge/ipysheet) (📥 110K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge ipysheet
	```
- [npm](https://www.npmjs.com/package/ipysheet) (📥 830 / month · 📦 3 · ⏱️ 28.11.2022):
	```
	npm install ipysheet
	```
</details>
<details><summary><b><a href="https://github.com/widgetti/ipyvue">ipyvue</a></b> (🥉21 ·  ⭐ 63) - Jupyter widgets base for Vue libraries. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/widgetti/ipyvue) (👨‍💻 6 · 🔀 17 · 📦 740 · 📋 14 - 35% open · ⏱️ 27.02.2024):

	```
	git clone https://github.com/mariobuikhuizen/ipyvue
	```
- [PyPi](https://pypi.org/project/ipyvue) (📥 120K / month):
	```
	pip install ipyvue
	```
- [Conda](https://anaconda.org/conda-forge/ipyvue) (📥 120K · ⏱️ 28.02.2024):
	```
	conda install -c conda-forge ipyvue
	```
- [npm](https://www.npmjs.com/package/jupyter-vue) (📥 4.5K / month):
	```
	npm install jupyter-vue
	```
</details>
<details><summary><b><a href="https://github.com/PAIR-code/what-if-tool">What-If Tool</a></b> (🥉20 ·  ⭐ 880) - Source code/webpage/demos for the What-If Tool. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/PAIR-code/what-if-tool) (👨‍💻 20 · 🔀 160 · 📦 2 · 📋 120 - 54% open · ⏱️ 01.02.2024):

	```
	git clone https://github.com/PAIR-code/what-if-tool
	```
- [PyPi](https://pypi.org/project/witwidget) (📥 3.7K / month):
	```
	pip install witwidget
	```
- [Conda](https://anaconda.org/conda-forge/tensorboard-plugin-wit) (📥 2.1M · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge tensorboard-plugin-wit
	```
- [npm](https://www.npmjs.com/package/wit-widget) (📥 1.4K / month):
	```
	npm install wit-widget
	```
</details>
<details><summary><b><a href="https://github.com/lgpage/nbtutor">nbtutor</a></b> (🥉20 ·  ⭐ 450 · 💤) - Visualize Python code execution (line-by-line) in Jupyter Notebook.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/lgpage/nbtutor) (👨‍💻 4 · 🔀 39 · 📦 39 · 📋 43 - 44% open · ⏱️ 14.04.2023):

	```
	git clone https://github.com/lgpage/nbtutor
	```
- [PyPi](https://pypi.org/project/nbtutor) (📥 230 / month · 📦 3 · ⏱️ 19.04.2022):
	```
	pip install nbtutor
	```
- [Conda](https://anaconda.org/conda-forge/nbtutor) (📥 140K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge nbtutor
	```
</details>
<details><summary><b><a href="https://github.com/medialab/ipysigma">ipysigma</a></b> (🥉19 ·  ⭐ 160) - A Jupyter widget using sigma.js to render interactive networks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/medialab/ipysigma) (👨‍💻 6 · 🔀 12 · 📦 28 · 📋 200 - 23% open · ⏱️ 20.10.2023):

	```
	git clone https://github.com/Yomguithereal/ipysigma
	```
- [PyPi](https://pypi.org/project/ipysigma) (📥 960 / month · 📦 1 · ⏱️ 08.06.2022):
	```
	pip install ipysigma
	```
- [npm](https://www.npmjs.com/package/ipysigma) (📥 280 / month · 📦 3 · ⏱️ 15.06.2023):
	```
	npm install ipysigma
	```
</details>
<details><summary><b><a href="https://github.com/altair-viz/altair_viewer">Altair Viewer</a></b> (🥉17 ·  ⭐ 80 · 💤) - Viewer for Altair and Vega-Lite visualizations. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/altair-viz/altair_viewer) (👨‍💻 3 · 🔀 11 · 📋 13 - 61% open · ⏱️ 02.05.2023):

	```
	git clone https://github.com/altair-viz/altair_viewer
	```
- [PyPi](https://pypi.org/project/altair_viewer) (📥 36K / month · 📦 15 · ⏱️ 06.11.2021):
	```
	pip install altair_viewer
	```
- [Conda](https://anaconda.org/conda-forge/altair_viewer) (📥 81K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge altair_viewer
	```
</details>
<details><summary><b><a href="https://github.com/martinRenou/ipycanvas">ipycanvas</a></b> (🥉16 · 💤) - Interactive Canvas in Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/martinRenou/ipycanvas) (👨‍💻 21 · 📦 8 · ⏱️ 20.07.2023):

	```
	git clone https://github.com/martinRenou/ipycanvas
	```
- [PyPi](https://pypi.org/project/ipycanvas) (📥 32K / month · 📦 33 · ⏱️ 29.08.2022):
	```
	pip install ipycanvas
	```
- [Conda](https://anaconda.org/conda-forge/ipycanvas) (📥 190K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge ipycanvas
	```
- [npm](https://www.npmjs.com/package/ipycanvas) (📥 850 / month · 📦 4 · ⏱️ 29.08.2022):
	```
	npm install ipycanvas
	```
</details>
<details><summary><b><a href="https://github.com/timkpaine/tributary">tributary</a></b> (🥉15 ·  ⭐ 410) - Streaming reactive and dataflow graphs in Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/tributary) (👨‍💻 7 · 🔀 36 · ⏱️ 10.02.2024):

	```
	git clone https://github.com/timkpaine/tributary
	```
- [PyPi](https://pypi.org/project/tributary) (📥 310 / month · ⏱️ 10.05.2023):
	```
	pip install tributary
	```
- [Conda](https://anaconda.org/conda-forge/tributary) (📥 35K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge tributary
	```
</details>
<details><summary>Show 22 hidden projects...</summary>

- <b><a href="https://github.com/man-group/dtale">D-Tale</a></b> (🥈31 ·  ⭐ 4.5K) - Visualizer for Pandas Data Structures. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1">❗️LGPL-2.1</a></code>
- <b><a href="https://github.com/jupyter-widgets/pythreejs">pythreejs</a></b> (🥈27 ·  ⭐ 920 · 💀) - A Jupyter - Three.js bridge. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/quantopian/qgrid">qgrid</a></b> (🥈26 ·  ⭐ 3K · 💀) - An interactive grid for sorting, filtering, and editing DataFrames.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/pbugnion/gmaps">gmaps</a></b> (🥉24 ·  ⭐ 760 · 💀) - Google maps for Jupyter notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/mapbox/mapboxgl-jupyter">Mapbox GL</a></b> (🥉24 ·  ⭐ 650 · 💀) - Use Mapbox GL JS to visualize data in a Python Jupyter notebook. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/nglviewer/nglview">nglview</a></b> (🥉23 ·  ⭐ 770) - Jupyter widget to interactively view molecular structures and.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/nicolaskruchten/jupyter_pivottablejs">pivottablejs</a></b> (🥉22 ·  ⭐ 640 · 💀) - Dragndrop Pivot Tables and Charts for Jupyter/IPython Notebook,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/vidartf/ipydatawidgets">ipydatawidgets</a></b> (🥉19 ·  ⭐ 39 · 💤) - A set of widgets to help facilitate reuse of large.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/jupyter-widgets-contrib/ipytree">ipytree</a></b> (🥉18 ·  ⭐ 120 · 💀) - A Tree Widget using Jupyter-widgets protocol and jsTree. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/OpenGeoscience/geonotebook">geonotebook</a></b> (🥉16 ·  ⭐ 1.1K · 💀) - A Jupyter notebook extension for geospatial visualization.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/g2nb/igv-jupyter">igv.js widget</a></b> (🥉16 ·  ⭐ 150 · 💀) - Extension for Jupyter which integrates igv.js. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/CermakM/jupyter-datatables">Jupyter DataTables</a></b> (🥉15 ·  ⭐ 230 · 💀) - Jupyter Notebook extension leveraging pandas DataFrames.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/nipy/niwidgets">niwidgets</a></b> (🥉15 ·  ⭐ 83 · 💀) - Neuroimaging widgets for jupyter notebooks. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/DGothrek/ipyaggrid">ipyaggrid</a></b> (🥉15 ·  ⭐ 46 · 💀) - Jupyter widget - ag-grid in the notebook. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/vidartf/ipyscales">ipyscales</a></b> (🥉14 ·  ⭐ 13 · 💀) - A widget library for scales. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/maartenbreddels/ipymaterialui">ipymaterialui</a></b> (🥉13 ·  ⭐ 85 · 💀) - Jupyter Widgets based on React Material UI components. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/leifwalsh/perfume">perfume</a></b> (🥉13 ·  ⭐ 33 · 💀) - Interactive performance benchmarking in Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/agermanidis/pigeon">pigeon</a></b> (🥉11 ·  ⭐ 760 · 💀) - Quickly annotate data from the comfort of your Jupyter notebook. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/GianniBalistreri/easyexplore">easyexplore</a></b> (🥉10 ·  ⭐ 5 · 💤) - Toolbox for easy and effective data exploration in Python. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/jtpio/ipyp5">ipyp5</a></b> (🥉9 ·  ⭐ 38 · 💀) - p5.js Jupyter Widget. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/ipyannotate/ipyannotate">ipyannotate</a></b> (🥉8 ·  ⭐ 140 · 💀) - Jupyter Widget for data annotation. <code>❗Unlicensed</code>
- <b><a href="https://github.com/asvcode/Vision_UI">Vision UI</a></b> (🥉7 ·  ⭐ 250 · 💀) - UI visual interface for fastai - now compatible with Google.. <code>❗Unlicensed</code>
</details>
<br>

## Jupyter Extensions

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Application plugins that extend the functionality of Jupyter itself._

<details><summary><b><a href="https://github.com/jupyter/nbgrader">nbgrader</a></b> (🥇29 ·  ⭐ 1.3K) - A system for assigning and grading notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/nbgrader) (👨‍💻 100 · 🔀 320 · 📥 320 · 📦 530 · 📋 920 - 28% open · ⏱️ 05.03.2024):

	```
	git clone https://github.com/jupyter/nbgrader
	```
- [PyPi](https://pypi.org/project/nbgrader) (📥 8.7K / month · 📦 22 · ⏱️ 05.09.2023):
	```
	pip install nbgrader
	```
- [Conda](https://anaconda.org/conda-forge/nbgrader) (📥 160K · ⏱️ 13.09.2023):
	```
	conda install -c conda-forge nbgrader
	```
</details>
<details><summary><b><a href="https://github.com/dunovank/jupyter-themes">Jupyter Themes</a></b> (🥈26 ·  ⭐ 9.7K) - Custom Jupyter Notebook Themes. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/dunovank/jupyter-themes) (👨‍💻 43 · 🔀 1.1K · 📦 21 · 📋 400 - 49% open · ⏱️ 18.10.2023):

	```
	git clone https://github.com/dunovank/jupyter-themes
	```
- [PyPi](https://pypi.org/project/jupyterthemes) (📥 110K / month):
	```
	pip install jupyterthemes
	```
</details>
<details><summary><b><a href="https://github.com/Jupyter-contrib/jupyter_nbextensions_configurator">NBextensions Configurator</a></b> (🥈26 ·  ⭐ 960) - A jupyter notebook serverextension providing config.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Jupyter-contrib/jupyter_nbextensions_configurator) (👨‍💻 24 · 🔀 120 · 📦 570 · 📋 100 - 64% open · ⏱️ 29.09.2023):

	```
	git clone https://github.com/jupyter-contrib/jupyter_nbextensions_configurator
	```
- [PyPi](https://pypi.org/project/jupyter_nbextensions_configurator) (📥 570K / month · 📦 19 · ⏱️ 05.05.2023):
	```
	pip install jupyter_nbextensions_configurator
	```
- [Conda](https://anaconda.org/conda-forge/jupyter_nbextensions_configurator) (📥 1.6M · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge jupyter_nbextensions_configurator
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/jupyter-server-proxy">jupyter-server-proxy</a></b> (🥈26 ·  ⭐ 320) - Jupyter notebook server extension to proxy web services. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/jupyter-server-proxy) (👨‍💻 71 · 🔀 140 · 📦 4 · 📋 200 - 36% open · ⏱️ 13.03.2024):

	```
	git clone https://github.com/jupyterhub/jupyter-server-proxy
	```
- [PyPi](https://pypi.org/project/jupyter-server-proxy) (📥 160K / month · 📦 140 · ⏱️ 13.03.2024):
	```
	pip install jupyter-server-proxy
	```
- [Conda](https://anaconda.org/conda-forge/jupyter-server-proxy) (📥 1.5M · ⏱️ 13.03.2024):
	```
	conda install -c conda-forge jupyter-server-proxy
	```
- [npm](https://www.npmjs.com/package/@jupyterlab/server-proxy) (📥 3.7K / month · 📦 4 · ⏱️ 13.03.2024):
	```
	npm install @jupyterlab/server-proxy
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-server/jupyter-resource-usage">Resource Usage</a></b> (🥈25 ·  ⭐ 440) - Jupyter Notebook Extension for monitoring your own Resource.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/jupyter-server/jupyter-resource-usage) (👨‍💻 34 · 🔀 100 · 📥 270 · 📦 570 · 📋 95 - 50% open · ⏱️ 12.03.2024):

	```
	git clone https://github.com/jupyter-server/jupyter-resource-usage
	```
- [PyPi](https://pypi.org/project/jupyter-resource-usage) (📥 44K / month · 📦 8 · ⏱️ 12.03.2024):
	```
	pip install jupyter-resource-usage
	```
- [Conda](https://anaconda.org/conda-forge/nbresuse) (📥 560K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge nbresuse
	```
- [npm](https://www.npmjs.com/package/@jupyter-server/resource-usage) (📥 2.3K / month · 📦 3 · ⏱️ 12.03.2024):
	```
	npm install @jupyter-server/resource-usage
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/nbgitpuller">nbgitpuller</a></b> (🥈24 ·  ⭐ 200) - Jupyter server extension to sync a git repository one-way to a.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/nbgitpuller) (👨‍💻 31 · 🔀 80 · 📦 750 · 📋 160 - 44% open · ⏱️ 05.02.2024):

	```
	git clone https://github.com/jupyterhub/nbgitpuller
	```
- [PyPi](https://pypi.org/project/nbgitpuller) (📥 24K / month · 📦 19 · ⏱️ 07.08.2023):
	```
	pip install nbgitpuller
	```
- [Conda](https://anaconda.org/conda-forge/nbgitpuller) (📥 85K · ⏱️ 07.08.2023):
	```
	conda install -c conda-forge nbgitpuller
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/jupyter-rsession-proxy">Rsession Proxy</a></b> (🥈23 ·  ⭐ 110) - Jupyter extensions for running an RStudio rsession proxy. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/jupyter-rsession-proxy) (👨‍💻 22 · 🔀 84 · 📦 48 · 📋 82 - 41% open · ⏱️ 13.03.2024):

	```
	git clone https://github.com/jupyterhub/jupyter-rsession-proxy
	```
- [PyPi](https://pypi.org/project/jupyter-rsession-proxy) (📥 31K / month · 📦 1 · ⏱️ 13.03.2024):
	```
	pip install jupyter-rsession-proxy
	```
- [Conda](https://anaconda.org/conda-forge/jupyter-rsession-proxy) (📥 24K · ⏱️ 13.03.2024):
	```
	conda install -c conda-forge jupyter-rsession-proxy
	```
</details>
<details><summary><b><a href="https://github.com/oschuett/appmode">Appmode</a></b> (🥈22 ·  ⭐ 430 · 💤) - A Jupyter extensions that turns notebooks into web applications. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/oschuett/appmode) (👨‍💻 9 · 🔀 70 · 📦 360 · 📋 61 - 11% open · ⏱️ 18.05.2023):

	```
	git clone https://github.com/oschuett/appmode
	```
- [PyPi](https://pypi.org/project/appmode) (📥 1.5K / month · 📦 22 · ⏱️ 18.05.2023):
	```
	pip install appmode
	```
- [Conda](https://anaconda.org/conda-forge/appmode) (📥 220K · ⏱️ 05.02.2024):
	```
	conda install -c conda-forge appmode
	```
</details>
<details><summary><b><a href="https://github.com/mamba-org/gator">gator</a></b> (🥉19 ·  ⭐ 250) - Conda environment and package management extension from within Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mamba-org/gator) (👨‍💻 26 · 🔀 26 · 📥 2 · 📦 5 · 📋 57 - 24% open · ⏱️ 27.02.2024):

	```
	git clone https://github.com/mamba-org/gator
	```
- [PyPi](https://pypi.org/project/mamba-gator) (📥 120 / month):
	```
	pip install mamba-gator
	```
- [Conda](https://anaconda.org/conda-forge/mamba_gator) (📥 40K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge mamba_gator
	```
- [npm](https://www.npmjs.com/package/@mamba-org/gator-lab) (📥 26 / month):
	```
	npm install @mamba-org/gator-lab
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab-contrib/jupyter-archive">jupyter-archive</a></b> (🥉19 ·  ⭐ 70) - A Jupyter/Jupyterlab extension to make, download and extract.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab-contrib/jupyter-archive) (👨‍💻 10 · 🔀 14 · 📥 3.3K · 📦 140 · 📋 39 - 7% open · ⏱️ 21.02.2024):

	```
	git clone https://github.com/jupyterlab-contrib/jupyter-archive
	```
- [PyPi](https://pypi.org/project/jupyter-archive) (📥 29K / month):
	```
	pip install jupyter-archive
	```
- [Conda](https://anaconda.org/conda-forge/jupyter-archive) (📥 60K · ⏱️ 16.08.2023):
	```
	conda install -c conda-forge jupyter-archive
	```
- [npm](https://www.npmjs.com/package/@hadim/jupyter-archive) (📥 90 / month):
	```
	npm install @hadim/jupyter-archive
	```
</details>
<details><summary><b><a href="https://github.com/drillan/jupyter-black">Jupyter Black</a></b> (🥉8 ·  ⭐ 440 · 💀) - Black formatter for Jupyter Notebook. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/drillan/jupyter-black) (👨‍💻 2 · 🔀 24 · 📋 25 - 44% open · ⏱️ 01.02.2020):

	```
	git clone https://github.com/drillan/jupyter-black
	```
</details>
<details><summary>Show 14 hidden projects...</summary>

- <b><a href="https://github.com/ipython-contrib/jupyter_contrib_nbextensions">Contrib NBextensions</a></b> (🥇31 ·  ⭐ 5.2K · 💀) - A collection of various notebook extensions for.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/man-group/dtale">dtale</a></b> (🥇31 ·  ⭐ 4.5K) - Visualizer for pandas data structures. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1">❗️LGPL-2.1</a></code>
- <b><a href="https://github.com/googlecolab/jupyter_http_over_ws">HTTP-over-WebSocket</a></b> (🥉19 ·  ⭐ 270 · 💀) - Jupyter support for HTTP-over-ws. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/lspvic/jupyter_tensorboard">jupyter-tensorboard</a></b> (🥉18 ·  ⭐ 460 · 💀) - Start Tensorboard in Jupyter Notebook. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/krishnan-r/sparkmonitor">Spark Monitor</a></b> (🥉18 ·  ⭐ 170 · 💀) - Monitor Apache Spark from Jupyter Notebook. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/8080labs/pyforest">pyforest</a></b> (🥉17 ·  ⭐ 1.1K · 💀) - pyforest - feel the bliss of automated imports. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/Anaconda-Platform/nb_conda">nb_conda</a></b> (🥉17 ·  ⭐ 140 · 💀) - Conda environment and package access extension from within Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jupyter-incubator/contentmanagement">Content Management</a></b> (🥉17 ·  ⭐ 77 · 💀) - Jupyter Content Management Extensions. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/codota/jupyter-tabnine">jupyter-tabnine</a></b> (🥉16 ·  ⭐ 790 · 💀) - Autocompletion with Deep Learning on Jupyter Notebook. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/data-8/nbzip">nbzip</a></b> (🥉16 ·  ⭐ 85 · 💀) - Zips and downloads all the contents of a jupyter notebook. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/mozilla/jupyter-spark">Jupyter Spark</a></b> (🥉15 ·  ⭐ 190 · 💀) - Jupyter Notebook extension for Apache Spark integration. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code>
- <b><a href="https://github.com/thoth-station/jupyter-nbrequirements">jupyter-nbrequirements</a></b> (🥉14 ·  ⭐ 17 · 💤) - Dependency management and optimization in Jupyter.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/paypal/PPExtensions">PPExtensions</a></b> (🥉13 ·  ⭐ 50 · 💀) - Set of iPython and Jupyter extensions to improve user.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/willkessler/jupyterterminals">jupyterterminals</a></b> (🥉8 ·  ⭐ 9 · 💀) - Jupyter plugin to support inline terminal shells along with.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Jupyter Magic

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Extensions that provide magic commands to access convenient functionality within a notebook._

<details><summary><b><a href="https://github.com/catherinedevlin/ipython-sql">ipython-sql</a></b> (🥇30 ·  ⭐ 1.8K · 💤) - %%sql magic for IPython, hopefully evolving into full SQL client. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/catherinedevlin/ipython-sql) (👨‍💻 55 · 🔀 300 · 📦 6.1K · 📋 150 - 72% open · ⏱️ 21.04.2023):

	```
	git clone https://github.com/catherinedevlin/ipython-sql
	```
- [PyPi](https://pypi.org/project/ipython-sql) (📥 180K / month · 📦 68 · ⏱️ 27.02.2023):
	```
	pip install ipython-sql
	```
- [Conda](https://anaconda.org/conda-forge/ipython-sql) (📥 250K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge ipython-sql
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-incubator/sparkmagic">sparkmagic</a></b> (🥇30 ·  ⭐ 1.3K) - Jupyter magics and kernels for working with remote Spark clusters. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-incubator/sparkmagic) (👨‍💻 64 · 🔀 440 · 📦 330 · 📋 450 - 33% open · ⏱️ 13.03.2024):

	```
	git clone https://github.com/jupyter-incubator/sparkmagic
	```
- [PyPi](https://pypi.org/project/sparkmagic) (📥 46K / month · 📦 22 · ⏱️ 13.09.2023):
	```
	pip install sparkmagic
	```
- [Conda](https://anaconda.org/conda-forge/sparkmagic) (📥 110K · ⏱️ 23.09.2023):
	```
	conda install -c conda-forge sparkmagic
	```
</details>
<details><summary><b><a href="https://github.com/rasbt/watermark">watermark</a></b> (🥈22 ·  ⭐ 860 · 💤) - An IPython magic extension for printing date and time stamps,.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/rasbt/watermark) (👨‍💻 19 · 🔀 88 · 📦 2.2K · 📋 47 - 40% open · ⏱️ 02.07.2023):

	```
	git clone https://github.com/rasbt/watermark
	```
- [PyPi](https://pypi.org/project/watermark) (📥 28K / month · 📦 99 · ⏱️ 02.07.2023):
	```
	pip install watermark
	```
- [Conda](https://anaconda.org/conda-forge/watermark) (📥 280K · ⏱️ 02.07.2023):
	```
	conda install -c conda-forge watermark
	```
</details>
<details><summary><b><a href="https://github.com/dnanhkhoa/nb_black">nb_black</a></b> (🥉15 ·  ⭐ 62 · 💤) - A simple extension for Jupyter Notebook and Jupyter Lab to beautify.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/dnanhkhoa/nb_black) (🔀 7):

	```
	git clone https://github.com/dnanhkhoa/nb_black
	```
- [PyPi](https://pypi.org/project/nb_black) (📥 15K / month · 📦 24 · ⏱️ 30.11.2019):
	```
	pip install nb_black
	```
- [Conda](https://anaconda.org/conda-forge/nb_black) (📥 130K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge nb_black
	```
</details>
<details><summary>Show 8 hidden projects...</summary>

- <b><a href="https://github.com/nteract/pick">pick</a></b> (🥈20 ·  ⭐ 620 · 💀) - Customize your kernels on Launch!. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/csurfer/pyheatmagic">heat</a></b> (🥈17 ·  ⭐ 1K · 💀) - IPython magic command to profile and view your python code as a heat map. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/csurfer/blackcellmagic">blackcellmagic</a></b> (🥈17 ·  ⭐ 300 · 💀) - IPython magic command to format python code in cell using.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/ShopRunner/jupyter-notify">jupyter-notify</a></b> (🥉15 ·  ⭐ 580 · 💀) - A Jupyter Notebook magic for browser notifications of cell.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/rossant/ipycache">ipycache</a></b> (🥉15 ·  ⭐ 140 · 💀) - Defines a %%cache cell magic in the IPython notebook to cache.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/ResidentMario/py_d3">py_d3</a></b> (🥉14 ·  ⭐ 450 · 💀) - D3 block magic for Jupyter notebook. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/tmthyjames/SQLCell">SQLCell</a></b> (🥉14 ·  ⭐ 150 · 💀) - SQLCell is a magic function for the Jupyter Notebook that executes.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/krassowski/jupyter-manim">jupyter-manim</a></b> (🥉11 ·  ⭐ 190 · 💀) - manim cell magic for IPython/Jupyter to show the output video. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Jupyter Kernels

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Jupyter kernels that run and introspect the user's code in a given language._

<details><summary><b><a href="https://github.com/ipython/ipykernel">IPython Kernel</a></b> (🥇40 ·  ⭐ 600) - IPython Kernel for Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/ipython/ipykernel) (👨‍💻 180 · 🔀 370 · 📥 2.2K · 📦 340K · 📋 510 - 52% open · ⏱️ 12.03.2024):

	```
	git clone https://github.com/ipython/ipykernel
	```
- [PyPi](https://pypi.org/project/ipykernel) (📥 26M / month · 📦 11K · ⏱️ 26.02.2024):
	```
	pip install ipykernel
	```
- [Conda](https://anaconda.org/anaconda/ipykernel) (📥 870K · 📦 39 · ⏱️ 22.01.2024):
	```
	conda install -c anaconda ipykernel
	```
</details>
<details><summary><b><a href="https://github.com/lfortran/lfortran">LFortran</a></b> (🥇28 ·  ⭐ 850) - Official main repository for LFortran. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/lfortran/lfortran) (👨‍💻 76 · 🔀 120 · 📥 790 · 📋 1.8K - 54% open · ⏱️ 14.03.2024):

	```
	git clone https://github.com/lfortran/lfortran
	```
- [PyPi](https://pypi.org/project/lfortran) (📥 61 / month · ⏱️ 31.07.2020):
	```
	pip install lfortran
	```
- [Conda](https://anaconda.org/conda-forge/lfortran) (📥 80K · ⏱️ 31.01.2024):
	```
	conda install -c conda-forge lfortran
	```
</details>
<details><summary><b><a href="https://github.com/evcxr/evcxr">Evcxr</a></b> (🥇26 ·  ⭐ 5.1K) - An evaluation context for Rust, including a Jupyter Kernel. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/evcxr/evcxr) (👨‍💻 49 · 🔀 210 · 📥 3.9K · 📦 160 · 📋 240 - 40% open · ⏱️ 06.03.2024):

	```
	git clone https://github.com/evcxr/evcxr
	```
</details>
<details><summary><b><a href="https://github.com/Calysto/metakernel">Metakernel</a></b> (🥇25 ·  ⭐ 330) - Jupyter/IPython Kernel Tools. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Calysto/metakernel) (👨‍💻 34 · 🔀 86 · 📥 160 · 📦 850 · 📋 150 - 21% open · ⏱️ 12.02.2024):

	```
	git clone https://github.com/Calysto/metakernel
	```
- [PyPi](https://pypi.org/project/metakernel) (📥 31K / month · 📦 78 · ⏱️ 11.09.2023):
	```
	pip install metakernel
	```
- [Conda](https://anaconda.org/conda-forge/metakernel) (📥 770K · ⏱️ 11.09.2023):
	```
	conda install -c conda-forge metakernel
	```
</details>
<details><summary><b><a href="https://github.com/dotnet/interactive">.NET Interactive</a></b> (🥈24 ·  ⭐ 2.7K) - .NET Interactive combines the power of .NET with many other.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/dotnet/interactive) (👨‍💻 120 · 🔀 360 · 📥 450 · 📋 1.5K - 33% open · ⏱️ 04.03.2024):

	```
	git clone https://github.com/dotnet/interactive
	```
</details>
<details><summary><b><a href="https://github.com/IRkernel/IRkernel">IRkernel</a></b> (🥈24 ·  ⭐ 1.7K · 💤) - R kernel for Jupyter. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/IRkernel/IRkernel) (👨‍💻 43 · 🔀 290 · 📋 590 - 11% open · ⏱️ 06.03.2023):

	```
	git clone https://github.com/IRkernel/IRkernel
	```
- [Conda](https://anaconda.org/r/r-irkernel) (📥 150K · ⏱️ 16.01.2024):
	```
	conda install -c r r-irkernel
	```
- [Docker Hub](https://hub.docker.com/r/jupyter/r-notebook) (📥 1.8M · ⭐ 59 · ⏱️ 20.10.2023):
	```
	docker pull jupyter/r-notebook
	```
</details>
<details><summary><b><a href="https://github.com/almond-sh/almond">almond</a></b> (🥈24 ·  ⭐ 1.6K) - A Scala kernel for Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/almond-sh/almond) (👨‍💻 40 · 🔀 240 · 📥 2.3K · 📋 340 - 38% open · ⏱️ 23.02.2024):

	```
	git clone https://github.com/almond-sh/almond
	```
- [Docker Hub](https://hub.docker.com/r/almondsh/almond) (📥 19K · ⭐ 6 · ⏱️ 19.10.2023):
	```
	docker pull almondsh/almond
	```
</details>
<details><summary><b><a href="https://github.com/takluyver/bash_kernel">Bash Kernel</a></b> (🥈24 ·  ⭐ 670) - A bash kernel for IPython. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/takluyver/bash_kernel) (👨‍💻 20 · 🔀 140 · 📦 210 · 📋 100 - 34% open · ⏱️ 24.11.2023):

	```
	git clone https://github.com/takluyver/bash_kernel
	```
- [PyPi](https://pypi.org/project/bash_kernel) (📥 35K / month · 📦 31 · ⏱️ 24.11.2023):
	```
	pip install bash_kernel
	```
- [Conda](https://anaconda.org/conda-forge/bash_kernel) (📥 160K · ⏱️ 25.11.2023):
	```
	conda install -c conda-forge bash_kernel
	```
</details>
<details><summary><b><a href="https://github.com/IHaskell/IHaskell">IHaskell</a></b> (🥈23 ·  ⭐ 2.5K) - A Haskell kernel for the Jupyter project. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/IHaskell/IHaskell) (👨‍💻 110 · 🔀 260 · 📋 780 - 5% open · ⏱️ 13.03.2024):

	```
	git clone https://github.com/gibiansky/IHaskell
	```
- [npm](https://www.npmjs.com/package/ihaskell_jupyterlab) (📥 6 / month · 📦 3 · ⏱️ 01.08.2018):
	```
	npm install ihaskell_jupyterlab
	```
</details>
<details><summary><b><a href="https://github.com/gopherdata/gophernotes">gophernotes</a></b> (🥈22 ·  ⭐ 3.7K) - The Go kernel for Jupyter notebooks and nteract. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/gopherdata/gophernotes) (👨‍💻 29 · 🔀 260 · 📥 44 · 📦 15 · 📋 180 - 28% open · ⏱️ 03.11.2023):

	```
	git clone https://github.com/gopherdata/gophernotes
	```
- [Docker Hub](https://hub.docker.com/r/gopherdata/gophernotes) (📥 87K · ⭐ 7 · ⏱️ 22.12.2018):
	```
	docker pull gopherdata/gophernotes
	```
- [Go](https://pkg.go.dev/github.com/gopherdata/gophernotes) (📦 1 · ⏱️ 31.05.2022):
	```
	go install github.com/gopherdata/gophernotes
	```
</details>
<details><summary><b><a href="https://github.com/apache/incubator-toree">Apache Toree</a></b> (🥈22 ·  ⭐ 730) - Jupyter kernel for Apache Spark. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/apache/incubator-toree) (👨‍💻 110 · 🔀 220 · ⏱️ 01.10.2023):

	```
	git clone https://github.com/apache/incubator-toree
	```
- [PyPi](https://pypi.org/project/toree) (📥 7.4K / month · 📦 9 · ⏱️ 21.04.2022):
	```
	pip install toree
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-xeus/xeus-cling">xeus-cling</a></b> (🥈21 ·  ⭐ 2.9K · 💤) - Jupyter kernel for the C++ programming language. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-xeus/xeus-cling) (👨‍💻 26 · 🔀 280 · 📋 290 - 57% open · ⏱️ 05.08.2023):

	```
	git clone https://github.com/jupyter-xeus/xeus-cling
	```
- [Conda](https://anaconda.org/conda-forge/xeus-cling) (📥 230K · ⏱️ 11.11.2023):
	```
	conda install -c conda-forge xeus-cling
	```
</details>
<details><summary><b><a href="https://github.com/SciRuby/iruby">IRuby</a></b> (🥈21 ·  ⭐ 830) - Official gem repository: Ruby kernel for Jupyter/IPython Notebook. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/SciRuby/iruby) (👨‍💻 47 · 🔀 24 · 📥 15 · 📦 230 · 📋 190 - 23% open · ⏱️ 08.02.2024):

	```
	git clone https://github.com/SciRuby/iruby
	```
- [Docker Hub](https://hub.docker.com/r/rubydata/datascience-notebook) (📥 2.1K · ⭐ 5 · ⏱️ 03.02.2023):
	```
	docker pull rubydata/datascience-notebook
	```
</details>
<details><summary><b><a href="https://github.com/Anaconda-Platform/nb_conda_kernels">nb_conda_kernels</a></b> (🥈21 ·  ⭐ 560) - Package for managing conda environment-based kernels inside.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Anaconda-Platform/nb_conda_kernels) (👨‍💻 18 · 🔀 67 · 📋 150 - 4% open · ⏱️ 07.03.2024):

	```
	git clone https://github.com/Anaconda-Platform/nb_conda_kernels
	```
- [Conda](https://anaconda.org/conda-forge/nb_conda_kernels) (📥 1.3M · ⏱️ 20.02.2024):
	```
	conda install -c conda-forge nb_conda_kernels
	```
</details>
<details><summary><b><a href="https://github.com/JuliaLang/IJulia.jl">IJulia.jl</a></b> (🥉20 ·  ⭐ 2.7K) - Julia kernel for Jupyter. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/JuliaLang/IJulia.jl) (👨‍💻 110 · 🔀 410 · 📋 850 - 16% open · ⏱️ 08.03.2024):

	```
	git clone https://github.com/JuliaLang/IJulia.jl
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-xeus/xeus-python">xeus-python</a></b> (🥉20 ·  ⭐ 410 · 📉) - Jupyter kernel for the Python programming language. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-xeus/xeus-python) (👨‍💻 23 · 🔀 68 · 📋 190 - 33% open · ⏱️ 14.03.2024):

	```
	git clone https://github.com/jupyter-xeus/xeus-python
	```
- [PyPi](https://pypi.org/project/xeus-python) (📥 14K / month):
	```
	pip install xeus-python
	```
- [Conda](https://anaconda.org/conda-forge/xeus-python) (📥 1.4M · ⏱️ 14.03.2024):
	```
	conda install -c conda-forge xeus-python
	```
</details>
<details><summary><b><a href="https://github.com/akabe/ocaml-jupyter">OCaml Kernel</a></b> (🥉19 ·  ⭐ 280 · 💤) - An OCaml kernel for Jupyter (IPython) notebook. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/akabe/ocaml-jupyter) (👨‍💻 23 · 🔀 38 · 📥 120K · 📋 80 - 8% open · ⏱️ 11.08.2023):

	```
	git clone https://github.com/akabe/ocaml-jupyter
	```
</details>
<details><summary><b><a href="https://github.com/clojupyter/clojupyter">clojupyter</a></b> (🥉17 ·  ⭐ 810) - a Jupyter kernel for Clojure. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/clojupyter/clojupyter) (👨‍💻 26 · 🔀 82 · 📋 100 - 14% open · ⏱️ 29.12.2023):

	```
	git clone https://github.com/clojupyter/clojupyter
	```
- [Conda](https://anaconda.org/simplect/clojupyter) (📥 3.5K · ⏱️ 20.07.2023):
	```
	conda install -c simplect clojupyter
	```
- [Docker Hub](https://hub.docker.com/r/simplect/clojupyter) (📥 420 · ⏱️ 25.04.2019):
	```
	docker pull simplect/clojupyter
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-xeus/xeus-sqlite">xeus-sqlite</a></b> (🥉15 ·  ⭐ 160) - Jupyter kernel for SQLite. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-xeus/xeus-sqlite) (👨‍💻 13 · 🔀 25 · 📋 46 - 32% open · ⏱️ 08.12.2023):

	```
	git clone https://github.com/jupyter-xeus/xeus-sqlite
	```
- [Conda](https://anaconda.org/conda-forge/xeus-sqlite) (📥 34K · ⏱️ 08.12.2023):
	```
	conda install -c conda-forge xeus-sqlite
	```
</details>
<details><summary><b><a href="https://github.com/pprzetacznik/IElixir">IElixir</a></b> (🥉13 ·  ⭐ 350) - Jupyters kernel for Elixir programming language. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/pprzetacznik/IElixir) (👨‍💻 19 · 🔀 41 · 📋 31 - 35% open · ⏱️ 03.03.2024):

	```
	git clone https://github.com/pprzetacznik/IElixir
	```
- [npm](https://www.npmjs.com/package/jupyterlab-ielixir) (📥 4 / month · 📦 2 · ⏱️ 11.05.2021):
	```
	npm install jupyterlab-ielixir
	```
- [Docker Hub](https://hub.docker.com/r/pprzetacznik/ielixir) (📥 350 · ⭐ 1 · ⏱️ 20.03.2021):
	```
	docker pull pprzetacznik/ielixir
	```
</details>
<details><summary>Show 24 hidden projects...</summary>

- <b><a href="https://github.com/xonsh/xonsh">xonsh</a></b> (🥇32 ·  ⭐ 7.9K) - Python-powered, cross-platform, Unix-gazing shell. <code><a href="https://github.com/xonsh/xonsh/blob/main/license">❗️Custom</a></code>
- <b><a href="https://github.com/n-riesco/ijavascript">IJavascript</a></b> (🥇25 ·  ⭐ 2.1K · 💀) - IJavascript is a javascript kernel for the Jupyter notebook. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jupyter-server/kernel_gateway">Kernel Gateway</a></b> (🥇25 ·  ⭐ 480) - Jupyter Kernel Gateway. <code>❗Unlicensed</code>
- <b><a href="https://github.com/jupyter-server/enterprise_gateway">Enterprise Gateway</a></b> (🥈23 ·  ⭐ 600) - A lightweight, multi-tenant, scalable and secure.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/Calysto/octave_kernel">Octave Kernel</a></b> (🥈23 ·  ⭐ 440 · 💀) - An Octave kernel for IPython. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/ansible/ansible-jupyter-kernel">Ansible Kernel</a></b> (🥉20 ·  ⭐ 530 · 💀) - Jupyter Notebook Kernel for running Ansible Tasks and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/vericast/spylon-kernel">Spylon Kernel</a></b> (🥉20 ·  ⭐ 180 · 💀) - Jupyter kernel for scala and spark. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/SpencerPark/IJava">IJava</a></b> (🥉19 ·  ⭐ 1K · 💀) - A Jupyter kernel for executing Java code. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/Calysto/matlab_kernel">Matlab Kernel</a></b> (🥉19 ·  ⭐ 460 · 💀) - Jupyter Kernel for Matlab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jorgehpo/notebookJS">notebookJS</a></b> (🥉18 ·  ⭐ 260 · 💀) - notebookJS: seamless JavaScript integration in Python Notebooks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/sassoftware/sas_kernel">SAS Kernel</a></b> (🥉18 ·  ⭐ 200 · 💀) - A Jupyter kernel for SAS. This opens up all the data.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/scijava/scijava-jupyter-kernel">SciJava Kernel</a></b> (🥉18 ·  ⭐ 180 · 💀) - [RETIRED] Try IJava or BeakerX. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/fsprojects/IfSharp">F# Kernel</a></b> (🥉17 ·  ⭐ 440 · 💀) - F# for Jupyter Notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/Cadair/jupyter_environment_kernels">Kernel Detection</a></b> (🥉17 ·  ⭐ 150 · 💀) - An Jupyter plugin to enable the automatic detection of.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code>
- <b><a href="https://github.com/WolframResearch/WolframLanguageForJupyter">Wolfram Kernel</a></b> (🥉15 ·  ⭐ 960 · 💀) - Wolfram Language kernel for Jupyter notebooks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/yunabe/lgo">lgo</a></b> (🥉14 ·  ⭐ 2.4K · 💀) - Interactive Go programming with Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/NII-cloud-operation/sshkernel">SSH Kernel</a></b> (🥉13 ·  ⭐ 64 · 💀) - SSH Kernel for Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/deathbeds/pidgy">pidgy</a></b> (🥉13 ·  ⭐ 42 · 💀) - Interactive computing in Markdown. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/minrk/allthekernels">allthekernels</a></b> (🥉12 ·  ⭐ 75 · 💀) - A multiplexer kernel for Jupyter. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/hugetim/nbstata">nbstata</a></b> (🥉11 ·  ⭐ 19) - A Jupyter kernel for Stata built on pystata. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/tdaff/remote_ikernel">remote_ikernel</a></b> (🥉11 ·  ⭐ 15 · 💀) - All your Jupyter kernels, on all your machines, in one place. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code>
- <b><a href="https://github.com/bernhard-42/ssh_ipykernel">ssh_ipykernel</a></b> (🥉11 ·  ⭐ 12 · 💀) - A remote jupyter kernel via ssh. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/zabirauf/icsharp">ICSharp</a></b> (🥉10 ·  ⭐ 280 · 💀) - C# kernel for Jupyter. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/nteract/kernel-relay">kernel-relay</a></b> (🥉4 ·  ⭐ 12 · 💀) - kernel-relay is a GraphQL service for interfacing with.. <code>❗Unlicensed</code>
</details>
<br>

## Notebook Sharing & Conversion

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Tools to share, convert and simplify collaboration (e.g., via git) with notebook files._

<details><summary><b><a href="https://github.com/jupyter/nbconvert">nbconvert</a></b> (🥇40 ·  ⭐ 1.6K) - Jupyter Notebook Conversion. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/nbconvert) (👨‍💻 270 · 🔀 540 · 📥 1.1K · 📦 260K · 📋 1.2K - 45% open · ⏱️ 10.03.2024):

	```
	git clone https://github.com/jupyter/nbconvert
	```
- [PyPi](https://pypi.org/project/nbconvert) (📥 25M / month · 📦 8.8K · ⏱️ 04.03.2024):
	```
	pip install nbconvert
	```
- [Conda](https://anaconda.org/conda-forge/nbconvert) (📥 16M · ⏱️ 04.03.2024):
	```
	conda install -c conda-forge nbconvert
	```
</details>
<details><summary><b><a href="https://github.com/mwouts/jupytext">Jupytext</a></b> (🥇35 ·  ⭐ 6.4K) - Jupyter Notebooks as Markdown Documents, Julia, Python or R scripts. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mwouts/jupytext) (👨‍💻 85 · 🔀 390 · 📦 6.9K · 📋 660 - 18% open · ⏱️ 13.01.2024):

	```
	git clone https://github.com/mwouts/jupytext
	```
- [PyPi](https://pypi.org/project/jupytext) (📥 630K / month · 📦 290 · ⏱️ 13.01.2024):
	```
	pip install jupytext
	```
- [Conda](https://anaconda.org/conda-forge/jupytext) (📥 760K · ⏱️ 13.01.2024):
	```
	conda install -c conda-forge jupytext
	```
- [npm](https://www.npmjs.com/package/jupyterlab-jupytext) (📥 5.7K / month · 📦 3 · ⏱️ 13.01.2024):
	```
	npm install jupyterlab-jupytext
	```
</details>
<details><summary><b><a href="https://github.com/executablebooks/jupyter-book">Jupyter Book</a></b> (🥇34 ·  ⭐ 3.6K) - Create beautiful, publication-quality books and documents from.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/executablebooks/jupyter-book) (👨‍💻 140 · 🔀 650 · 📦 13K · 📋 1.3K - 44% open · ⏱️ 11.03.2024):

	```
	git clone https://github.com/executablebooks/jupyter-book
	```
- [PyPi](https://pypi.org/project/jupyter-book) (📥 87K / month · 📦 160 · ⏱️ 26.01.2024):
	```
	pip install jupyter-book
	```
- [Conda](https://anaconda.org/conda-forge/jupyter-book) (📥 120K · ⏱️ 21.02.2024):
	```
	conda install -c conda-forge jupyter-book
	```
</details>
<details><summary><b><a href="https://github.com/voila-dashboards/voila">Voila</a></b> (🥈33 ·  ⭐ 5.1K) - Voil turns Jupyter notebooks into standalone web applications. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/voila-dashboards/voila) (👨‍💻 68 · 🔀 490 · 📥 1.1K · 📦 11K · 📋 720 - 40% open · ⏱️ 07.02.2024):

	```
	git clone https://github.com/voila-dashboards/voila
	```
- [PyPi](https://pypi.org/project/voila) (📥 73K / month · 📦 88 · ⏱️ 31.10.2023):
	```
	pip install voila
	```
- [Conda](https://anaconda.org/conda-forge/voila) (📥 320K · ⏱️ 31.10.2023):
	```
	conda install -c conda-forge voila
	```
- [npm](https://www.npmjs.com/package/@jupyter-voila/jupyterlab-preview) (📥 220 / month · 📦 3 · ⏱️ 19.05.2020):
	```
	npm install @jupyter-voila/jupyterlab-preview
	```
</details>
<details><summary><b><a href="https://github.com/getnikola/nikola">nikola</a></b> (🥈33 ·  ⭐ 2.5K) - A static website and blog generator. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/getnikola/nikola) (👨‍💻 240 · 🔀 440 · 📥 100 · 📦 510 · 📋 2.2K - 2% open · ⏱️ 02.03.2024):

	```
	git clone https://github.com/getnikola/nikola
	```
- [PyPi](https://pypi.org/project/nikola) (📥 2.7K / month · 📦 140 · ⏱️ 10.01.2024):
	```
	pip install nikola
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/nbdime">nbdime</a></b> (🥈31 ·  ⭐ 2.6K) - Tools for diffing and merging of Jupyter notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/nbdime) (👨‍💻 50 · 🔀 160 · 📥 100 · 📦 140 · 📋 340 - 22% open · ⏱️ 21.11.2023):

	```
	git clone https://github.com/jupyter/nbdime
	```
- [PyPi](https://pypi.org/project/nbdime) (📥 200K / month · 📦 150 · ⏱️ 21.11.2023):
	```
	pip install nbdime
	```
- [Conda](https://anaconda.org/conda-forge/nbdime) (📥 980K · ⏱️ 21.11.2023):
	```
	conda install -c conda-forge nbdime
	```
- [npm](https://www.npmjs.com/package/nbdime-jupyterlab) (📥 29K / month · 📦 5 · ⏱️ 21.11.2023):
	```
	npm install nbdime-jupyterlab
	```
</details>
<details><summary><b><a href="https://github.com/stencila/stencila">Stencila</a></b> (🥈29 ·  ⭐ 760) - Programmable, reproducible, interactive documents. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/stencila/stencila) (👨‍💻 43 · 🔀 49 · 📥 4.2K · 📦 20 · 📋 720 - 13% open · ⏱️ 14.03.2024):

	```
	git clone https://github.com/stencila/stencila
	```
- [npm](https://www.npmjs.com/package/stencila) (📥 92 / month · 📦 10 · ⏱️ 06.11.2020):
	```
	npm install stencila
	```
- [Docker Hub](https://hub.docker.com/r/stencila/cloud) (📥 16K · ⏱️ 08.04.2019):
	```
	docker pull stencila/cloud
	```
</details>
<details><summary><b><a href="https://github.com/damianavila/RISE">RISE</a></b> (🥈28 ·  ⭐ 3.6K) - RISE: Live Reveal.js Jupyter/IPython Slideshow Extension. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/damianavila/RISE) (👨‍💻 44 · 🔀 410 · 📦 2.8K · 📋 450 - 34% open · ⏱️ 29.10.2023):

	```
	git clone https://github.com/damianavila/RISE
	```
- [PyPi](https://pypi.org/project/RISE) (📥 11K / month · 📦 170 · ⏱️ 03.11.2022):
	```
	pip install RISE
	```
- [Conda](https://anaconda.org/conda-forge/rise) (📥 290K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge rise
	```
- [npm](https://www.npmjs.com/package/rise-reveal) (📥 8 / month · 📦 2 · ⏱️ 03.07.2019):
	```
	npm install rise-reveal
	```
</details>
<details><summary><b><a href="https://github.com/airbnb/knowledge-repo">Knowledge Repo</a></b> (🥈25 ·  ⭐ 5.4K · 💤) - A next-generation curated knowledge sharing platform.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/airbnb/knowledge-repo) (👨‍💻 73 · 🔀 710 · 📦 21 · 📋 300 - 44% open · ⏱️ 17.04.2023):

	```
	git clone https://github.com/airbnb/knowledge-repo
	```
- [PyPi](https://pypi.org/project/knowledge-repo) (📥 700 / month · 📦 1 · ⏱️ 22.02.2023):
	```
	pip install knowledge-repo
	```
</details>
<details><summary><b><a href="https://github.com/danielfrg/mkdocs-jupyter">mkdocs-jupyter</a></b> (🥈25 ·  ⭐ 320) - Use Jupyter Notebook in mkdocs. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/danielfrg/mkdocs-jupyter) (👨‍💻 21 · 🔀 37 · 📦 2.1K · 📋 110 - 18% open · ⏱️ 14.02.2024):

	```
	git clone https://github.com/danielfrg/mkdocs-jupyter
	```
- [PyPi](https://pypi.org/project/mkdocs-jupyter) (📥 140K / month):
	```
	pip install mkdocs-jupyter
	```
- [Conda](https://anaconda.org/conda-forge/mkdocs-jupyter) (📥 55K · ⏱️ 15.10.2023):
	```
	conda install -c conda-forge mkdocs-jupyter
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/binderhub">BinderHub</a></b> (🥉24 ·  ⭐ 2.5K) - Run your code in the cloud, with technology so advanced, it feels.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/binderhub) (👨‍💻 95 · 🔀 390 · 📦 9 · 📋 710 - 31% open · ⏱️ 06.03.2024):

	```
	git clone https://github.com/jupyterhub/binderhub
	```
- [PyPi](https://pypi.org/project/binderhub) (📥 41 / month · ⏱️ 07.11.2018):
	```
	pip install binderhub
	```
</details>
<details><summary><b><a href="https://github.com/executablebooks/thebe">ThebeLab</a></b> (🥉23 ·  ⭐ 370) - Turn static HTML pages into live documents with Jupyter kernels. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/executablebooks/thebe) (👨‍💻 29 · 🔀 67 · 📦 10 · 📋 230 - 45% open · ⏱️ 21.12.2023):

	```
	git clone https://github.com/executablebooks/thebe
	```
- [npm](https://www.npmjs.com/package/thebe) (📥 10K / month · 📦 1 · ⏱️ 21.12.2023):
	```
	npm install thebe
	```
</details>
<details><summary><b><a href="https://github.com/SamLau95/nbinteract">nbinteract</a></b> (🥉21 ·  ⭐ 230) - Create interactive webpages from Jupyter Notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/SamLau95/nbinteract) (👨‍💻 8 · 🔀 22 · 📦 4 · 📋 110 - 61% open · ⏱️ 13.02.2024):

	```
	git clone https://github.com/SamLau95/nbinteract
	```
- [PyPi](https://pypi.org/project/nbinteract) (📥 5.1K / month · 📦 39 · ⏱️ 05.01.2021):
	```
	pip install nbinteract
	```
- [npm](https://www.npmjs.com/package/nbinteract) (📥 8 / month · 📦 3 · ⏱️ 05.01.2021):
	```
	npm install nbinteract
	```
</details>
<details><summary><b><a href="https://github.com/danielfrg/jupyter-flex">jupyter-flex</a></b> (🥉20 ·  ⭐ 310) - Build dashboards using Jupyter Notebooks. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/danielfrg/jupyter-flex) (👨‍💻 4 · 🔀 54 · 📦 46 · 📋 63 - 19% open · ⏱️ 10.02.2024):

	```
	git clone https://github.com/danielfrg/jupyter-flex
	```
- [PyPi](https://pypi.org/project/jupyter-flex) (📥 1.6K / month):
	```
	pip install jupyter-flex
	```
- [Conda](https://anaconda.org/conda-forge/jupyter-flex) (📥 17K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge jupyter-flex
	```
- [npm](https://www.npmjs.com/package/@danielfrg/jupyter-flex) (📥 19 / month):
	```
	npm install @danielfrg/jupyter-flex
	```
</details>
<details><summary><b><a href="https://github.com/greenape/mknotebooks">mknotebooks</a></b> (🥉20 ·  ⭐ 120 · 💤) - A plugin for mkdocs to help you include Jupyter notebooks in your.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/greenape/mknotebooks) (👨‍💻 14 · 🔀 20 · 📦 520 · 📋 39 - 33% open · ⏱️ 11.08.2023):

	```
	git clone https://github.com/greenape/mknotebooks
	```
- [PyPi](https://pypi.org/project/mknotebooks) (📥 20K / month):
	```
	pip install mknotebooks
	```
</details>
<details><summary><b><a href="https://github.com/nbgallery/nbgallery">nbgallery</a></b> (🥉16 ·  ⭐ 150 · 📉) - Enterprise Jupyter notebook sharing and collaboration app. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nbgallery/nbgallery) (👨‍💻 25 · 🔀 35 · 📋 490 - 6% open · ⏱️ 29.02.2024):

	```
	git clone https://github.com/nbgallery/nbgallery
	```
- [Docker Hub](https://hub.docker.com/r/nbgallery/nbgallery):
	```
	docker pull nbgallery/nbgallery
	```
</details>
<details><summary>Show 8 hidden projects...</summary>

- <b><a href="https://github.com/aaren/notedown">notedown</a></b> (🥉22 ·  ⭐ 850 · 💀) - Markdown = IPython Notebook. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code>
- <b><a href="https://github.com/nteract/scrapbook">scrapbook</a></b> (🥉22 ·  ⭐ 280 · 💀) - A library for recording and reading data in notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jupyter/nbviewer">nbviewer</a></b> (🥉21 ·  ⭐ 2.2K · 💀) - nbconvert as a web service: Render Jupyter Notebooks as static web.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/nteract/commuter">commuter</a></b> (🥉20 ·  ⭐ 6.1K · 💀) - Notebook sharing hub. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/nteract/bookstore">bookstore</a></b> (🥉18 ·  ⭐ 200 · 💀) - Notebook storage and publishing workflows for the masses. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/ideonate/cdsdashboards">cdsdashboards</a></b> (🥉17 ·  ⭐ 200 · 💀) - JupyterHub extension for ContainDS Dashboards. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/elehcimd/pynb">pynb</a></b> (🥉13 ·  ⭐ 240 · 💀) - Jupyter Notebooks as plain Python code with embedded Markdown text. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/line/jnotebook_reader">jnotebook-reader</a></b> (🥉9 ·  ⭐ 100 · 💀) - An awesome viewer to browse and render Jupyter.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
</details>
<br>

## Notebook Tools

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries and tools that work with or can be used within notebook files._

<details><summary><b><a href="https://github.com/jupyter/jupyter_client">Jupyter Client</a></b> (🥇34 ·  ⭐ 350) - Jupyter protocol client APIs. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/jupyter_client) (👨‍💻 130 · 🔀 270 · 📥 1.5K · 📋 390 - 48% open · ⏱️ 12.03.2024):

	```
	git clone https://github.com/jupyter/jupyter_client
	```
- [PyPi](https://pypi.org/project/jupyter-client) (📥 29M / month · 📦 2.5K · ⏱️ 12.03.2024):
	```
	pip install jupyter-client
	```
- [Conda](https://anaconda.org/conda-forge/jupyter_client) (📥 21M · ⏱️ 12.03.2024):
	```
	conda install -c conda-forge jupyter_client
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/nbformat">nbformat</a></b> (🥇34 ·  ⭐ 240) - Reference implementation of the Jupyter Notebook format. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/nbformat) (👨‍💻 80 · 🔀 160 · 📥 230 · 📦 270K · 📋 150 - 44% open · ⏱️ 13.03.2024):

	```
	git clone https://github.com/jupyter/nbformat
	```
- [PyPi](https://pypi.org/project/nbformat) (📥 23M / month · 📦 9K · ⏱️ 12.03.2024):
	```
	pip install nbformat
	```
- [Conda](https://anaconda.org/conda-forge/nbformat) (📥 21M · ⏱️ 12.03.2024):
	```
	conda install -c conda-forge nbformat
	```
- [npm](https://www.npmjs.com/package/nbformat-schema) (📥 57 / month · 📦 3 · ⏱️ 12.03.2024):
	```
	npm install nbformat-schema
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/nbclient">nbclient</a></b> (🥇31 ·  ⭐ 130) - A client library for executing notebooks. Formally nbconverts.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/nbclient) (👨‍💻 38 · 🔀 53 · 📥 430 · 📦 150K · 📋 110 - 36% open · ⏱️ 13.03.2024):

	```
	git clone https://github.com/jupyter/nbclient
	```
- [PyPi](https://pypi.org/project/nbclient) (📥 19M / month · 📦 200 · ⏱️ 13.03.2024):
	```
	pip install nbclient
	```
- [Conda](https://anaconda.org/conda-forge/nbclient) (📥 14M · ⏱️ 13.03.2024):
	```
	conda install -c conda-forge nbclient
	```
</details>
<details><summary><b><a href="https://github.com/fastai/nbdev">nbdev</a></b> (🥈29 ·  ⭐ 4.7K) - Create delightful software with Jupyter Notebooks. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/fastai/nbdev) (👨‍💻 94 · 🔀 470 · 📋 860 - 16% open · ⏱️ 04.03.2024):

	```
	git clone https://github.com/fastai/nbdev
	```
- [PyPi](https://pypi.org/project/nbdev) (📥 70K / month · 📦 160 · ⏱️ 19.10.2023):
	```
	pip install nbdev
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/repo2docker">repo2docker</a></b> (🥈29 ·  ⭐ 1.6K) - Turn repositories into Jupyter-enabled Docker images. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/repo2docker) (👨‍💻 120 · 🔀 350 · 📦 200 · 📋 540 - 32% open · ⏱️ 06.02.2024):

	```
	git clone https://github.com/jupyterhub/repo2docker
	```
- [PyPi](https://pypi.org/project/jupyter-repo2docker) (📥 7.8K / month · 📦 28 · ⏱️ 13.06.2023):
	```
	pip install jupyter-repo2docker
	```
</details>
<details><summary><b><a href="https://github.com/computationalmodelling/nbval">nbval</a></b> (🥈28 ·  ⭐ 430) - A py.test plugin to validate Jupyter notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/computationalmodelling/nbval) (👨‍💻 33 · 🔀 51 · 📦 2.9K · 📋 110 - 42% open · ⏱️ 04.03.2024):

	```
	git clone https://github.com/computationalmodelling/nbval
	```
- [PyPi](https://pypi.org/project/nbval) (📥 170K / month · 📦 370 · ⏱️ 04.03.2024):
	```
	pip install nbval
	```
- [Conda](https://anaconda.org/conda-forge/nbval) (📥 420K · ⏱️ 04.03.2024):
	```
	conda install -c conda-forge nbval
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/jupyter-sphinx">Jupyter Sphinx</a></b> (🥈28 ·  ⭐ 180) - Sphinx extension for rendering of Jupyter interactive widgets. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/jupyter-sphinx) (👨‍💻 28 · 🔀 65 · 📋 170 - 35% open · ⏱️ 11.03.2024):

	```
	git clone https://github.com/jupyter/jupyter-sphinx
	```
- [PyPi](https://pypi.org/project/jupyter_sphinx) (📥 73K / month · 📦 290 · ⏱️ 28.12.2023):
	```
	pip install jupyter_sphinx
	```
- [Conda](https://anaconda.org/conda-forge/jupyter_sphinx) (📥 240K · ⏱️ 27.01.2024):
	```
	conda install -c conda-forge jupyter_sphinx
	```
</details>
<details><summary><b><a href="https://github.com/mljar/mercury">mercury</a></b> (🥈25 ·  ⭐ 3.7K) - Convert Jupyter Notebooks to Web Apps. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/mljar/mercury) (👨‍💻 13 · 🔀 240 · 📦 100 · 📋 400 - 15% open · ⏱️ 13.03.2024):

	```
	git clone https://github.com/mljar/mercury
	```
- [PyPi](https://pypi.org/project/mljar-mercury) (📥 300 / month · ⏱️ 02.09.2022):
	```
	pip install mljar-mercury
	```
</details>
<details><summary><b><a href="https://github.com/nbQA-dev/nbQA">nbQA</a></b> (🥉24 ·  ⭐ 940) - Run ruff, isort, pyupgrade, mypy, pylint, flake8, and more on Jupyter Notebooks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nbQA-dev/nbQA) (👨‍💻 26 · 🔀 37 · 📋 290 - 2% open · ⏱️ 12.03.2024):

	```
	git clone https://github.com/nbQA-dev/nbQA
	```
- [PyPi](https://pypi.org/project/nbqa) (📥 150K / month):
	```
	pip install nbqa
	```
- [Conda](https://anaconda.org/conda-forge/nbqa) (📥 140K · ⏱️ 08.03.2024):
	```
	conda install -c conda-forge nbqa
	```
</details>
<details><summary><b><a href="https://github.com/chmp/ipytest">ipytest</a></b> (🥉24 ·  ⭐ 280) - Pytest in IPython notebooks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/chmp/ipytest) (👨‍💻 5 · 🔀 17 · 📦 380 · 📋 59 - 3% open · ⏱️ 18.02.2024):

	```
	git clone https://github.com/chmp/ipytest
	```
- [PyPi](https://pypi.org/project/ipytest) (📥 53K / month · 📦 22 · ⏱️ 18.02.2024):
	```
	pip install ipytest
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-naas/naas">naas</a></b> (🥉19 ·  ⭐ 270) - Low-code Python library to safely use notebooks in production: schedule.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code></summary>

- [GitHub](https://github.com/jupyter-naas/naas) (👨‍💻 20 · 🔀 23 · 📦 4 · 📋 180 - 21% open · ⏱️ 15.01.2024):

	```
	git clone https://github.com/jupyter-naas/naas
	```
- [PyPi](https://pypi.org/project/naas) (📥 1.2K / month · ⏱️ 15.01.2024):
	```
	pip install naas
	```
</details>
<details><summary><b><a href="https://github.com/tweag/jupyenv">JupyterWith</a></b> (🥉17 ·  ⭐ 580) - Declarative and reproducible Jupyter environments - powered by Nix. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/tweag/jupyenv) (👨‍💻 37 · 🔀 120 · 📋 190 - 21% open · ⏱️ 17.10.2023):

	```
	git clone https://github.com/tweag/jupyterWith
	```
</details>
<details><summary><b><a href="https://github.com/takluyver/nbopen">nbopen</a></b> (🥉17 ·  ⭐ 300) - Open a Jupyter notebook in the best available server. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/takluyver/nbopen) (👨‍💻 11 · 🔀 56 · 📦 130 · 📋 65 - 58% open · ⏱️ 08.09.2023):

	```
	git clone https://github.com/takluyver/nbopen
	```
- [PyPi](https://pypi.org/project/nbopen) (📥 1.9K / month):
	```
	pip install nbopen
	```
</details>
<details><summary><b><a href="https://github.com/stas00/ipyexperiments">ipyexperiments</a></b> (🥉16 ·  ⭐ 180) - Automatic GPU+CPU memory profiling, re-use and memory leaks.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/stas00/ipyexperiments) (👨‍💻 3 · 🔀 12 · 📦 8 · ⏱️ 15.12.2023):

	```
	git clone https://github.com/stas00/ipyexperiments
	```
- [PyPi](https://pypi.org/project/ipyexperiments) (📥 120 / month · 📦 2 · ⏱️ 15.12.2023):
	```
	pip install ipyexperiments
	```
</details>
<details><summary>Show 12 hidden projects...</summary>

- <b><a href="https://github.com/ipython/ipyparallel">ipyparallel</a></b> (🥈30 ·  ⭐ 2.5K) - IPython Parallel: Interactive Parallel Computing in Python. <code>❗Unlicensed</code>
- <b><a href="https://github.com/twosigma/beakerx">BeakerX</a></b> (🥈29 ·  ⭐ 2.8K · 💀) - Beaker Extensions for Jupyter Notebook. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/pixiedust/pixiedust">PixieDust</a></b> (🥈27 ·  ⭐ 1K · 💀) - Python Helper library for Jupyter Notebooks. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/fastai/fastpages">fastpages</a></b> (🥉23 ·  ⭐ 3.5K · 💀) - An easy to use blogging platform, with enhanced support for.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/nteract/testbook">testbook</a></b> (🥉20 ·  ⭐ 400 · 💀) - Unit test your Jupyter Notebooks the right way. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/ReviewNB/treon">treon</a></b> (🥉19 ·  ⭐ 290 · 💀) - Easy to use test framework for Jupyter Notebooks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/QuantEcon/sphinxcontrib-jupyter">sphinxcontrib.jupyter</a></b> (🥉18 ·  ⭐ 74 · 💀) - A Sphinx Extension for Generating Jupyter Notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/takluyver/jupyter_kernel_mgmt">Kernel Management</a></b> (🥉14 ·  ⭐ 15 · 💀) - Experimental new kernel management framework for Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/treebeardtech/nbmake-action">nbmake-action</a></b> (🥉13 ·  ⭐ 150 · 💀) - GitHub Action for testing notebooks. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/datitran/jupyter2slides">jupyter2slides</a></b> (🥉10 ·  ⭐ 790 · 💀) - Cloud Native Presentation Slides with Jupyter Notebook +.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/krassowski/jupyter-helpers">Jupyter Helpers</a></b> (🥉9 ·  ⭐ 45 · 💀) - A collection of helpers for Jupyter/IPython. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/Invictify/Jupter-Notebook-REST-API">Jupter-Notebook-REST-API</a></b> (🥉5 ·  ⭐ 75 · 💀) - Run your jupyter notebooks as a REST API endpoint... <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## JupyterLab Renderer

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Extensions that can render and display files of specific MIME types._

<details><summary><b><a href="https://github.com/jupyterlab/jupyter-renderers">JupyterLab Renderers</a></b> (🥈20 ·  ⭐ 480) - Renderers and renderer extensions for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyter-renderers) (👨‍💻 31 · 🔀 75 · 📋 110 - 35% open · ⏱️ 04.03.2024):

	```
	git clone https://github.com/jupyterlab/jupyter-renderers
	```
- [PyPi](https://pypi.org/project/jupyterlab-katex) (📥 880 / month · 📦 1 · ⏱️ 23.05.2023):
	```
	pip install jupyterlab-katex
	```
- [Conda](https://anaconda.org/conda-forge/jupyterlab-vega3) (📥 3.7K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge jupyterlab-vega3
	```
- [npm](https://www.npmjs.com/package/@jupyterlab/geojson-extension) (📥 660 / month · 📦 4 · ⏱️ 01.08.2023):
	```
	npm install @jupyterlab/geojson-extension
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-latex">JupyterLab Latex</a></b> (🥉19 ·  ⭐ 600) - JupyterLab extension for live editing of LaTeX documents. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab-latex) (👨‍💻 23 · 🔀 67 · 📋 95 - 40% open · ⏱️ 31.10.2023):

	```
	git clone https://github.com/jupyterlab/jupyterlab-latex
	```
- [PyPi](https://pypi.org/project/jupyterlab_latex) (📥 2K / month · 📦 2 · ⏱️ 15.09.2021):
	```
	pip install jupyterlab_latex
	```
- [Conda](https://anaconda.org/conda-forge/jupyterlab-latex) (📥 13K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge jupyterlab-latex
	```
- [npm](https://www.npmjs.com/package/@jupyterlab/latex) (📥 440 / month · 📦 3 · ⏱️ 06.07.2021):
	```
	npm install @jupyterlab/latex
	```
</details>
<details><summary>Show 6 hidden projects...</summary>

- <b><a href="https://github.com/QuantStack/jupyterlab-drawio">JupyterLab Drawio</a></b> (🥇22 ·  ⭐ 590 · 💀) - A standalone embedding of the FOSS drawio / mxgraph.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/plotly/jupyterlab-dash">JupyterLab Dash</a></b> (🥈21 ·  ⭐ 880 · 💀) - An Extension for the Interactive development of Dash apps in.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/plotly/jupyterlab-chart-editor">JupyterLab Chart Editor</a></b> (🥉17 ·  ⭐ 220 · 💀) - JupyterLab extension for Plotlys react-chart-editor. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jupytercalpoly/jupyterlab-tabular-data-editor">jupyterlab-tabular-data-editor</a></b> (🥉15 ·  ⭐ 130 · 💀) - Manipulate your tabular data responsively and.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/altair-viz/jupyterlab_voyager">JupyterLab Voyager</a></b> (🥉14 ·  ⭐ 290 · 💀) - JupyterLab extension visualize data with Voyager. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/quigleyj97/jupyterlab-spreadsheet">JupyterLab Spreadsheet</a></b> (🥉14 ·  ⭐ 190 · 💀) - JupyterLab plugin for viewing spreadsheets, such as.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
</details>
<br>

## JupyterLab Themes

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Extensions that can customize the appearance of JupyterLab._

<details><summary><b><a href="https://github.com/mohirio/jupyterlab-horizon-theme">Horizon Theme</a></b> (🥈15 ·  ⭐ 82) - VSCode Horizon Theme port for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mohirio/jupyterlab-horizon-theme) (👨‍💻 3 · 🔀 8 · 📥 32 · 📦 3 · 📋 9 - 11% open · ⏱️ 22.11.2023):

	```
	git clone https://github.com/mohirio/jupyterlab-horizon-theme
	```
- [PyPi](https://pypi.org/project/jupyterlab-horizon-theme) (📥 1.3K / month · ⏱️ 22.11.2023):
	```
	pip install jupyterlab-horizon-theme
	```
- [npm](https://www.npmjs.com/package/@mohirio/jupyterlab-horizon-theme) (📥 230 / month · 📦 2 · ⏱️ 22.11.2023):
	```
	npm install @mohirio/jupyterlab-horizon-theme
	```
</details>
<details><summary><b><a href="https://github.com/AllanChain/jupyterlab-theme-solarized-dark">jupyterlab-theme-solarized-dark</a></b> (🥈14 ·  ⭐ 89) - JupyterLab Theme Solarized Dark. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/AllanChain/jupyterlab-theme-solarized-dark) (👨‍💻 2 · 🔀 10 · 📥 31 · 📦 3 · 📋 4 - 50% open · ⏱️ 21.02.2024):

	```
	git clone https://github.com/AllanChain/jupyterlab-theme-solarized-dark
	```
- [PyPi](https://pypi.org/project/jupyterlab_theme_solarized_dark) (📥 9.1K / month · ⏱️ 18.01.2024):
	```
	pip install jupyterlab_theme_solarized_dark
	```
- [npm](https://www.npmjs.com/package/jupyterlab-theme-solarized-dark) (📥 2.3K / month · 📦 3 · ⏱️ 18.01.2024):
	```
	npm install jupyterlab-theme-solarized-dark
	```
</details>
<details><summary><b><a href="https://github.com/dunovank/jupyterlab_darkside_ui">jupyterlab_darkside_ui</a></b> (🥉10 ·  ⭐ 120) - Darkside ui and syntax theme for jupyterlab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/dunovank/jupyterlab_darkside_ui) (👨‍💻 6 · 🔀 10 · ⏱️ 18.09.2023):

	```
	git clone https://github.com/dunovank/jupyterlab_darkside_ui
	```
- [PyPi](https://pypi.org/project/jupyterlab_darkside_ui) (📥 430 / month):
	```
	pip install jupyterlab_darkside_ui
	```
</details>
<details><summary>Show 6 hidden projects...</summary>

- <b><a href="https://github.com/telamonian/theme-darcula">Darcula Theme</a></b> (🥇20 ·  ⭐ 200 · 💀) - A handsome Darcula theme for Jupyterlab. The first jlab.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/oriolmirosa/jupyterlab_materialdarker">Material Darker Theme</a></b> (🥈14 ·  ⭐ 150 · 💀) - The Material Darker theme for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/yeebc/jupyterlab-neon-theme">Neon Theme</a></b> (🥈14 ·  ⭐ 150 · 💀) - A flat, 80s neon inspired theme for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/Rahlir/theme-gruvbox">Gruvbox Theme</a></b> (🥉12 ·  ⭐ 51 · 💀) - Gruvbox dark theme for Jupyter Lab. Modeled on classic.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jtpio/jupyterlab-theme-toggle">Theme Toggle</a></b> (🥉10 ·  ⭐ 11 · 💀) - JupyterLab extension to toggle the theme in the Top Bar area. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/kenshohara/theme-nord-extension">Nord Theme</a></b> (🥉8 ·  ⭐ 26 · 💀) - JupyterLab - Nord Theme. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
</details>
<br>

## JupyterLab Extensions

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Application plugins that extend the functionality of JupyterLab itself._

<details><summary><b><a href="https://github.com/finos/perspective">Perspective</a></b> (🥇31 ·  ⭐ 7.4K) - A data visualization and analytics component, especially well-.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/finos/perspective) (👨‍💻 93 · 🔀 940 · 📥 2.4K · 📦 120 · 📋 720 - 12% open · ⏱️ 12.03.2024):

	```
	git clone https://github.com/finos/perspective
	```
- [PyPi](https://pypi.org/project/perspective-python) (📥 8K / month):
	```
	pip install perspective-python
	```
- [Conda](https://anaconda.org/conda-forge/perspective) (📥 520K · ⏱️ 12.03.2024):
	```
	conda install -c conda-forge perspective
	```
- [npm](https://www.npmjs.com/package/@finos/perspective-jupyterlab) (📥 590 / month):
	```
	npm install @finos/perspective-jupyterlab
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-lsp/jupyterlab-lsp">JupyterLab LSP</a></b> (🥇31 ·  ⭐ 1.7K) - Coding assistance for JupyterLab (code navigation + hover.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-lsp/jupyterlab-lsp) (👨‍💻 52 · 🔀 140 · 📦 1.8K · 📋 550 - 33% open · ⏱️ 05.03.2024):

	```
	git clone https://github.com/jupyter-lsp/jupyterlab-lsp
	```
- [PyPi](https://pypi.org/project/jupyterlab-lsp) (📥 45K / month · 📦 25 · ⏱️ 26.02.2024):
	```
	pip install jupyterlab-lsp
	```
- [Conda](https://anaconda.org/conda-forge/jupyter-lsp) (📥 1.3M · ⏱️ 05.03.2024):
	```
	conda install -c conda-forge jupyter-lsp
	```
- [npm](https://www.npmjs.com/package/@krassowski/jupyterlab-lsp) (📥 930 / month · 📦 5 · ⏱️ 26.08.2022):
	```
	npm install @krassowski/jupyterlab-lsp
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-git">JupyterLab Git</a></b> (🥇31 ·  ⭐ 1.4K) - A Git extension for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab-git) (👨‍💻 94 · 🔀 280 · 📥 180 · 📦 2.6K · 📋 580 - 15% open · ⏱️ 21.02.2024):

	```
	git clone https://github.com/jupyterlab/jupyterlab-git
	```
- [PyPi](https://pypi.org/project/jupyterlab-git) (📥 120K / month):
	```
	pip install jupyterlab-git
	```
- [Conda](https://anaconda.org/conda-forge/jupyterlab-git) (📥 530K · ⏱️ 07.02.2024):
	```
	conda install -c conda-forge jupyterlab-git
	```
- [npm](https://www.npmjs.com/package/@jupyterlab/git) (📥 17K / month):
	```
	npm install @jupyterlab/git
	```
</details>
<details><summary><b><a href="https://github.com/elyra-ai/elyra">elyra</a></b> (🥇28 ·  ⭐ 1.8K) - Elyra extends JupyterLab with an AI centric approach. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/elyra-ai/elyra) (👨‍💻 63 · 🔀 320 · 📦 54 · 📋 1.6K - 15% open · ⏱️ 08.03.2024):

	```
	git clone https://github.com/elyra-ai/elyra
	```
- [PyPi](https://pypi.org/project/elyra) (📥 4.9K / month):
	```
	pip install elyra
	```
- [Conda](https://anaconda.org/conda-forge/elyra) (📥 44K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge elyra
	```
- [npm](https://www.npmjs.com/package/@elyra/services) (📥 200 / month):
	```
	npm install @elyra/services
	```
</details>
<details><summary><b><a href="https://github.com/finos/jupyterlab_templates">JupyterLab Templates</a></b> (🥇24 ·  ⭐ 370) - Support for jupyter notebook templates in jupyterlab. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/finos/jupyterlab_templates) (👨‍💻 21 · 🔀 64 · 📦 8 · 📋 91 - 8% open · ⏱️ 19.02.2024):

	```
	git clone https://github.com/jpmorganchase/jupyterlab_templates
	```
- [PyPi](https://pypi.org/project/jupyterlab_templates) (📥 18K / month · 📦 7 · ⏱️ 12.02.2024):
	```
	pip install jupyterlab_templates
	```
- [Conda](https://anaconda.org/conda-forge/jupyterlab_templates) (📥 19K · ⏱️ 17.08.2023):
	```
	conda install -c conda-forge jupyterlab_templates
	```
- [npm](https://www.npmjs.com/package/jupyterlab_templates) (📥 3.3K / month · 📦 3 · ⏱️ 12.02.2024):
	```
	npm install jupyterlab_templates
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab-contrib/jupyterlab-variableInspector">Variable Inspector</a></b> (🥈23 ·  ⭐ 1K) - Variable Inspector extension for Jupyterlab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab-contrib/jupyterlab-variableInspector) (👨‍💻 22 · 🔀 87 · 📥 47 · 📦 6 · 📋 170 - 23% open · ⏱️ 21.02.2024):

	```
	git clone https://github.com/lckr/jupyterlab-variableInspector
	```
- [PyPi](https://pypi.org/project/lckr-jupyterlab-variableinspector) (📥 15K / month):
	```
	pip install lckr-jupyterlab-variableinspector
	```
- [Conda](https://anaconda.org/conda-forge/jupyterlab-variableinspector) (📥 25K · ⏱️ 23.01.2024):
	```
	conda install -c conda-forge jupyterlab-variableinspector
	```
- [npm](https://www.npmjs.com/package/@lckr/jupyterlab_variableinspector) (📥 2K / month):
	```
	npm install @lckr/jupyterlab_variableinspector
	```
</details>
<details><summary><b><a href="https://github.com/deshaw/jupyterlab-execute-time">jupyterlab-execute-time</a></b> (🥈22 ·  ⭐ 320) - A JupyterLab extension for displaying cell timings. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/deshaw/jupyterlab-execute-time) (👨‍💻 17 · 🔀 45 · 📦 4 · 📋 64 - 12% open · ⏱️ 14.02.2024):

	```
	git clone https://github.com/deshaw/jupyterlab-execute-time
	```
- [PyPi](https://pypi.org/project/jupyterlab-execute-time) (📥 59K / month · 📦 4 · ⏱️ 14.02.2024):
	```
	pip install jupyterlab-execute-time
	```
- [Conda](https://anaconda.org/conda-forge/jupyterlab_execute_time) (📥 60K · ⏱️ 15.02.2024):
	```
	conda install -c conda-forge jupyterlab_execute_time
	```
- [npm](https://www.npmjs.com/package/jupyterlab-execute-time) (📥 1.2K / month · 📦 3 · ⏱️ 18.01.2021):
	```
	npm install jupyterlab-execute-time
	```
</details>
<details><summary><b><a href="https://github.com/dask/dask-labextension">dask-labextension</a></b> (🥈22 ·  ⭐ 300 · 💤) - JupyterLab extension for Dask. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/dask/dask-labextension) (👨‍💻 24 · 🔀 61 · 📦 3 · 📋 150 - 31% open · ⏱️ 04.08.2023):

	```
	git clone https://github.com/dask/dask-labextension
	```
- [PyPi](https://pypi.org/project/dask-labextension) (📥 7.7K / month · 📦 8 · ⏱️ 04.08.2023):
	```
	pip install dask-labextension
	```
- [Conda](https://anaconda.org/conda-forge/dask-labextension) (📥 950K · ⏱️ 04.08.2023):
	```
	conda install -c conda-forge dask-labextension
	```
- [npm](https://www.npmjs.com/package/dask-labextension) (📥 290 / month · 📦 3 · ⏱️ 21.06.2022):
	```
	npm install dask-labextension
	```
</details>
<details><summary><b><a href="https://github.com/jtpio/ipylab">ipylab</a></b> (🥈22 ·  ⭐ 170) - Control JupyterLab from Python Notebooks with Jupyter Widgets. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jtpio/ipylab) (👨‍💻 7 · 🔀 13 · 📥 130 · 📦 99 · 📋 47 - 53% open · ⏱️ 09.10.2023):

	```
	git clone https://github.com/jtpio/ipylab
	```
- [PyPi](https://pypi.org/project/ipylab) (📥 110K / month · 📦 14 · ⏱️ 11.08.2023):
	```
	pip install ipylab
	```
- [Conda](https://anaconda.org/conda-forge/ipylab) (📥 29K · ⏱️ 11.08.2023):
	```
	conda install -c conda-forge ipylab
	```
- [npm](https://www.npmjs.com/package/ipylab) (📥 420 / month · 📦 3 · ⏱️ 11.08.2023):
	```
	npm install ipylab
	```
</details>
<details><summary><b><a href="https://github.com/ryantam626/jupyterlab_code_formatter">Code Formatter</a></b> (🥈21 ·  ⭐ 790 · 💤) - A JupyterLab plugin to facilitate invocation of code.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ryantam626/jupyterlab_code_formatter) (👨‍💻 42 · 🔀 53 · 📋 190 - 14% open · ⏱️ 18.06.2023):

	```
	git clone https://github.com/ryantam626/jupyterlab_code_formatter
	```
- [PyPi](https://pypi.org/project/jupyterlab_code_formatter) (📥 71K / month):
	```
	pip install jupyterlab_code_formatter
	```
- [Conda](https://anaconda.org/conda-forge/jupyterlab_code_formatter) (📥 700K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge jupyterlab_code_formatter
	```
- [npm](https://www.npmjs.com/package/@ryantam626/jupyterlab_code_formatter) (📥 1.4K / month):
	```
	npm install @ryantam626/jupyterlab_code_formatter
	```
</details>
<details><summary><b><a href="https://github.com/jtpio/jupyterlab-system-monitor">JupyterLab System Monitor</a></b> (🥈21 ·  ⭐ 300 · 💤) - JupyterLab extension to display system metrics. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jtpio/jupyterlab-system-monitor) (👨‍💻 7 · 🔀 30 · 📦 170 · 📋 71 - 38% open · ⏱️ 28.07.2023):

	```
	git clone https://github.com/jtpio/jupyterlab-system-monitor
	```
- [PyPi](https://pypi.org/project/jupyterlab-system-monitor) (📥 6.6K / month · 📦 2 · ⏱️ 04.02.2021):
	```
	pip install jupyterlab-system-monitor
	```
- [Conda](https://anaconda.org/conda-forge/jupyterlab-system-monitor) (📥 32K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge jupyterlab-system-monitor
	```
- [npm](https://www.npmjs.com/package/jupyterlab-system-monitor) (📥 1.6K / month · 📦 2 · ⏱️ 23.11.2020):
	```
	npm install jupyterlab-system-monitor
	```
</details>
<details><summary><b><a href="https://github.com/bokeh/jupyter_bokeh">Jupyter Bokeh</a></b> (🥈21 ·  ⭐ 230) - An extension for rendering Bokeh content in JupyterLab notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/bokeh/jupyter_bokeh) (👨‍💻 18 · 🔀 46 · 📦 3 · 📋 110 - 20% open · ⏱️ 22.02.2024):

	```
	git clone https://github.com/bokeh/jupyter_bokeh
	```
- [PyPi](https://pypi.org/project/jupyter-bokeh) (📥 41K / month · 📦 26 · ⏱️ 14.03.2023):
	```
	pip install jupyter-bokeh
	```
- [Conda](https://anaconda.org/conda-forge/jupyter_bokeh) (📥 79K · ⏱️ 29.02.2024):
	```
	conda install -c conda-forge jupyter_bokeh
	```
- [npm](https://www.npmjs.com/package/@bokeh/jupyter_bokeh) (📥 4.5K / month · 📦 3 · ⏱️ 22.02.2024):
	```
	npm install @bokeh/jupyter_bokeh
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab-contrib/spellchecker">JupyterLab Spellchecker</a></b> (🥈21 ·  ⭐ 200 · 💤) - Spellchecker for JupyterLab notebook markdown cells.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab-contrib/spellchecker) (👨‍💻 6 · 🔀 19 · 📦 230 · 📋 57 - 31% open · ⏱️ 28.07.2023):

	```
	git clone https://github.com/jupyterlab-contrib/spellchecker
	```
- [PyPi](https://pypi.org/project/jupyterlab-spellchecker) (📥 5.6K / month):
	```
	pip install jupyterlab-spellchecker
	```
- [Conda](https://anaconda.org/conda-forge/jupyterlab-spellchecker) (📥 110K · ⏱️ 28.07.2023):
	```
	conda install -c conda-forge jupyterlab-spellchecker
	```
- [npm](https://www.npmjs.com/package/@ijmbarr/jupyterlab_spellchecker) (📥 280 / month):
	```
	npm install @ijmbarr/jupyterlab_spellchecker
	```
</details>
<details><summary><b><a href="https://github.com/rapidsai/jupyterlab-nvdashboard">GPU Dashboards</a></b> (🥈20 ·  ⭐ 540) - A JupyterLab extension for displaying dashboards of GPU usage. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/rapidsai/jupyterlab-nvdashboard) (👨‍💻 20 · 🔀 73 · 📦 3 · 📋 77 - 45% open · ⏱️ 01.03.2024):

	```
	git clone https://github.com/rapidsai/jupyterlab-nvdashboard
	```
- [PyPi](https://pypi.org/project/jupyterlab-nvdashboard) (📥 9.9K / month · 📦 2 · ⏱️ 04.12.2023):
	```
	pip install jupyterlab-nvdashboard
	```
- [Conda](https://anaconda.org/conda-forge/jupyterlab-nvdashboard) (📥 39K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge jupyterlab-nvdashboard
	```
- [npm](https://www.npmjs.com/package/jupyterlab-nvdashboard) (📥 220 / month · 📦 3 · ⏱️ 27.04.2021):
	```
	npm install jupyterlab-nvdashboard
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-github">JupyterLab GitHub</a></b> (🥈19 ·  ⭐ 400 · 💤) - GitHub integration for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab-github) (👨‍💻 17 · 🔀 99 · 📥 30 · 📦 6 · 📋 62 - 33% open · ⏱️ 03.08.2023):

	```
	git clone https://github.com/jupyterlab/jupyterlab-github
	```
- [PyPi](https://pypi.org/project/jupyterlab-github) (📥 2.4K / month):
	```
	pip install jupyterlab-github
	```
- [npm](https://www.npmjs.com/package/@jupyterlab/github) (📥 580 / month):
	```
	npm install @jupyterlab/github
	```
</details>
<details><summary><b><a href="https://github.com/timkpaine/lantern">Lantern</a></b> (🥈19 ·  ⭐ 340) - Data exploration glue. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/lantern) (👨‍💻 3 · 🔀 21 · 📦 19 · 📋 200 - 2% open · ⏱️ 05.02.2024):

	```
	git clone https://github.com/timkpaine/lantern
	```
- [PyPi](https://pypi.org/project/pylantern) (📥 120 / month):
	```
	pip install pylantern
	```
</details>
<details><summary><b><a href="https://github.com/jpmorganchase/jupyter-fs">jupyter-fs</a></b> (🥈19 ·  ⭐ 180) - A filesystem-like contents manager for multiple backends in.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/jpmorganchase/jupyter-fs) (👨‍💻 15 · 🔀 34 · 📦 5 · 📋 76 - 23% open · ⏱️ 11.11.2023):

	```
	git clone https://github.com/jpmorganchase/jupyter-fs
	```
- [PyPi](https://pypi.org/project/jupyter-fs) (📥 700 / month · 📦 1 · ⏱️ 11.11.2023):
	```
	pip install jupyter-fs
	```
- [Conda](https://anaconda.org/conda-forge/jupyter-fs) (📥 9.1K · ⏱️ 12.11.2023):
	```
	conda install -c conda-forge jupyter-fs
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-google-drive">JupyterLab Google Drive</a></b> (🥈18 ·  ⭐ 400 · 💤) - Cloud storage for JupyterLab using Google Drive. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab-google-drive) (👨‍💻 17 · 🔀 74 · 📦 5 · ⏱️ 03.08.2023):

	```
	git clone https://github.com/jupyterlab/jupyterlab-google-drive
	```
- [npm](https://www.npmjs.com/package/@jupyterlab/google-drive) (📥 310 / month):
	```
	npm install @jupyterlab/google-drive
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-widgets/jupyterlab-sidecar">JupyterLab SideCar</a></b> (🥈18 ·  ⭐ 240 · 💤) - A sidecar output widget for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-widgets/jupyterlab-sidecar) (👨‍💻 16 · 🔀 40 · 📦 7 · 📋 50 - 74% open · ⏱️ 30.08.2023):

	```
	git clone https://github.com/jupyter-widgets/jupyterlab-sidecar
	```
- [PyPi](https://pypi.org/project/sidecar) (📥 8K / month · 📦 9 · ⏱️ 30.08.2023):
	```
	pip install sidecar
	```
- [Conda](https://anaconda.org/conda-forge/sidecar) (📥 22K · ⏱️ 30.08.2023):
	```
	conda install -c conda-forge sidecar
	```
- [npm](https://www.npmjs.com/package/@jupyter-widgets/jupyterlab-sidecar) (📥 170 / month · 📦 3 · ⏱️ 05.07.2021):
	```
	npm install @jupyter-widgets/jupyterlab-sidecar
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-data-explorer">JupyterLab Data Explorer</a></b> (🥈18 ·  ⭐ 180 · 💤) - First class datasets in JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab-data-explorer) (👨‍💻 10 · 🔀 36 · 📦 14 · 📋 150 - 38% open · ⏱️ 08.08.2023):

	```
	git clone https://github.com/jupyterlab/jupyterlab-data-explorer
	```
- [npm](https://www.npmjs.com/package/@jupyterlab/dataregistry-extension) (📥 24 / month · 📦 7 · ⏱️ 03.10.2019):
	```
	npm install @jupyterlab/dataregistry-extension
	```
</details>
<details><summary><b><a href="https://github.com/timkpaine/jupyterlab_iframe">JupyterLab IFrame</a></b> (🥉17 ·  ⭐ 100) - View html as an embedded iframe in JupyterLab. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/jupyterlab_iframe) (👨‍💻 5 · 🔀 18 · 📦 6 · 📋 68 - 5% open · ⏱️ 06.02.2024):

	```
	git clone https://github.com/timkpaine/jupyterlab_iframe
	```
- [PyPi](https://pypi.org/project/jupyterlab_iframe) (📥 1K / month):
	```
	pip install jupyterlab_iframe
	```
- [Conda](https://anaconda.org/conda-forge/jupyterlab_iframe) (📥 28K · ⏱️ 16.07.2023):
	```
	conda install -c conda-forge jupyterlab_iframe
	```
- [npm](https://www.npmjs.com/package/jupyterlab_iframe) (📥 140 / month):
	```
	npm install jupyterlab_iframe
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-hdf5">JupyterLab HDF5</a></b> (🥉16 ·  ⭐ 120) - Open and explore HDF5 files in JupyterLab. Can handle very.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab-hdf5) (👨‍💻 9 · 🔀 24 · 📦 3 · 📋 50 - 28% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/jupyterlab/jupyterlab-hdf5
	```
- [PyPi](https://pypi.org/project/jupyterlab_hdf) (📥 480 / month · 📦 1 · ⏱️ 21.02.2022):
	```
	pip install jupyterlab_hdf
	```
- [npm](https://www.npmjs.com/package/@jupyterlab/hdf5) (📥 66 / month · 📦 2 · ⏱️ 08.03.2023):
	```
	npm install @jupyterlab/hdf5
	```
</details>
<details><summary><b><a href="https://github.com/vatlab/jupyterlab-sos">jupyterlab-sos</a></b> (🥉16 ·  ⭐ 68) - Jupyterlab extension for SoS Polyglot Notebook and Workflow.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/vatlab/jupyterlab-sos) (👨‍💻 4 · 🔀 6 · 📦 3 · 📋 64 - 18% open · ⏱️ 30.09.2023):

	```
	git clone https://github.com/vatlab/jupyterlab-sos
	```
- [PyPi](https://pypi.org/project/jupyterlab-sos) (📥 240 / month · ⏱️ 24.10.2023):
	```
	pip install jupyterlab-sos
	```
- [Conda](https://anaconda.org/conda-forge/jupyterlab-sos) (📥 33K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge jupyterlab-sos
	```
- [npm](https://www.npmjs.com/package/jupyterlab-sos) (📥 78 / month · 📦 2 · ⏱️ 14.01.2021):
	```
	npm install jupyterlab-sos
	```
</details>
<details><summary><b><a href="https://github.com/xiaohk/stickyland">StickyLand</a></b> (🥉15 ·  ⭐ 500) - Break the linear presentation of Jupyter Notebooks with sticky cells!. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/xiaohk/stickyland) (👨‍💻 2 · 🔀 34 · 📥 17 · 📦 4 · 📋 15 - 13% open · ⏱️ 24.12.2023):

	```
	git clone https://github.com/xiaohk/stickyland
	```
- [PyPi](https://pypi.org/project/jupyterlab-stickyland) (📥 460 / month · 📦 1 · ⏱️ 24.12.2023):
	```
	pip install jupyterlab-stickyland
	```
- [npm](https://www.npmjs.com/package/jupyterlab-stickyland) (📥 13 / month · 📦 2 · ⏱️ 23.11.2021):
	```
	npm install jupyterlab-stickyland
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab-contrib/jupyterlab-kernelspy">JupyterLab Kernelspy</a></b> (🥉15 ·  ⭐ 78) - A Jupyter Lab extension for inspecting messages to/from.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab-contrib/jupyterlab-kernelspy) (👨‍💻 6 · 🔀 12 · 📥 29 · 📦 7 · 📋 13 - 15% open · ⏱️ 08.10.2023):

	```
	git clone https://github.com/jupyterlab-contrib/jupyterlab-kernelspy
	```
- [PyPi](https://pypi.org/project/jupyterlab-kernelspy) (📥 510 / month · ⏱️ 30.08.2023):
	```
	pip install jupyterlab-kernelspy
	```
- [Conda](https://anaconda.org/conda-forge/jupyterlab-kernelspy) (📥 12K · ⏱️ 30.08.2023):
	```
	conda install -c conda-forge jupyterlab-kernelspy
	```
- [npm](https://www.npmjs.com/package/jupyterlab-kernelspy) (📥 61 / month · 📦 3 · ⏱️ 30.08.2023):
	```
	npm install jupyterlab-kernelspy
	```
</details>
<details><summary><b><a href="https://github.com/timkpaine/jupyterlab_autoversion">JupyterLab Autoversion</a></b> (🥉15 ·  ⭐ 71) - Automatically version jupyter notebooks in JupyterLab. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/jupyterlab_autoversion) (👨‍💻 5 · 🔀 9 · 📋 35 - 17% open · ⏱️ 27.02.2024):

	```
	git clone https://github.com/timkpaine/jupyterlab_autoversion
	```
- [PyPi](https://pypi.org/project/jupyterlab_autoversion) (📥 220 / month · ⏱️ 11.04.2022):
	```
	pip install jupyterlab_autoversion
	```
- [Conda](https://anaconda.org/conda-forge/jupyterlab_autoversion) (📥 18K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge jupyterlab_autoversion
	```
- [npm](https://www.npmjs.com/package/jupyterlab_autoversion) (📥 48 / month · 📦 2 · ⏱️ 11.04.2022):
	```
	npm install jupyterlab_autoversion
	```
</details>
<details><summary><b><a href="https://github.com/jupyterlab/jupyterlab-shortcutui">JupyterLab Shortcutui</a></b> (🥉14 ·  ⭐ 54 · 💤) - A JupyterLab extension for managing keyboard shortcuts. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterlab/jupyterlab-shortcutui) (👨‍💻 9 · 🔀 15 · 📦 3 · 📋 22 - 36% open · ⏱️ 08.08.2023):

	```
	git clone https://github.com/jupyterlab/jupyterlab-shortcutui
	```
- [npm](https://www.npmjs.com/package/@jupyterlab/shortcutui) (📥 190 / month · 📦 2 · ⏱️ 17.01.2020):
	```
	npm install @jupyterlab/shortcutui
	```
</details>
<details><summary><b><a href="https://github.com/timkpaine/jupyterlab_commands">jupyterlab_commands</a></b> (🥉14 ·  ⭐ 50) - Add arbitrary python commands to the jupyterlab.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/jupyterlab_commands) (👨‍💻 2 · 🔀 6 · 📋 24 - 4% open · ⏱️ 05.02.2024):

	```
	git clone https://github.com/timkpaine/jupyterlab_commands
	```
- [PyPi](https://pypi.org/project/jupyterlab-commands) (📥 140 / month · ⏱️ 12.07.2023):
	```
	pip install jupyterlab-commands
	```
- [Conda](https://anaconda.org/conda-forge/jupyterlab_commands) (📥 12K · ⏱️ 13.07.2023):
	```
	conda install -c conda-forge jupyterlab_commands
	```
</details>
<details><summary><b><a href="https://github.com/timkpaine/knowledgelab">KnowledgeLab</a></b> (🥉14 ·  ⭐ 47) - KnowledgeRepo + JupyterLab. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/knowledgelab) (👨‍💻 3 · 🔀 6 · 📦 6 · 📋 29 - 17% open · ⏱️ 01.03.2024):

	```
	git clone https://github.com/timkpaine/knowledgelab
	```
- [PyPi](https://pypi.org/project/knowledgelab) (📥 4 / month · ⏱️ 19.10.2017):
	```
	pip install knowledgelab
	```
- [npm](https://www.npmjs.com/package/knowledgelab) (📥 8 / month · 📦 2 · ⏱️ 16.10.2018):
	```
	npm install knowledgelab
	```
</details>
<details><summary><b><a href="https://github.com/timkpaine/jupyterlab_email">JupyterLab Email</a></b> (🥉13 ·  ⭐ 53) - A jupyterlab extension to email notebooks directly from.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/jupyterlab_email) (👨‍💻 2 · 🔀 2 · 📦 1 · 📋 38 - 5% open · ⏱️ 06.02.2024):

	```
	git clone https://github.com/timkpaine/jupyterlab_email
	```
- [PyPi](https://pypi.org/project/jupyterlab_email) (📥 82 / month · ⏱️ 17.08.2023):
	```
	pip install jupyterlab_email
	```
- [npm](https://www.npmjs.com/package/jupyterlab_email) (📥 28 / month · 📦 2 · ⏱️ 17.08.2023):
	```
	npm install jupyterlab_email
	```
</details>
<details><summary><b><a href="https://github.com/timkpaine/jupyterlab_email">JupyterLab Flake8</a></b> (🥉12 ·  ⭐ 53) - A jupyterlab extension to email notebooks directly from.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/timkpaine/jupyterlab_email) (👨‍💻 2 · 🔀 2 · 📦 1 · 📋 38 - 5% open · ⏱️ 06.02.2024):

	```
	git clone https://github.com/timkpaine/jupyterlab_email
	```
- [PyPi](https://pypi.org/project/jupyterlab-email) (📥 82 / month):
	```
	pip install jupyterlab-email
	```
- [npm](https://www.npmjs.com/package/jupyterlab-flake8) (📥 53 / month):
	```
	npm install jupyterlab-flake8
	```
</details>
<details><summary>Show 21 hidden projects...</summary>

- <b><a href="https://github.com/jupyterlab/debugger">JupyterLab Debugger</a></b> (🥇29 ·  ⭐ 14K · 💀) - A visual debugger for Jupyter notebooks, consoles,.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jupyterlab/jupyterlab-toc">JupyterLab TOC</a></b> (🥈19 ·  ⭐ 720 · 💀) - Table of Contents extension for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/itsjafer/jupyterlab-sparkmonitor">jupyterlab-sparkmonitor</a></b> (🥉17 ·  ⭐ 92 · 💀) - JupyterLab extension that enables monitoring launched.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/aquirdTurtle/Collapsible_Headings">Collapsible Headings</a></b> (🥉16 ·  ⭐ 170 · 💀) - Implements Collapsible Headers for Jupyter Lab.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jtpio/jupyterlab-topbar">JupyterLab Top Bar</a></b> (🥉16 ·  ⭐ 5) - JupyterLab Top Bar extension. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jwkvam/jupyterlab-vim">JupyterLab Vim</a></b> (🥉15 ·  ⭐ 960 · 💀) - Vim notebook cell bindings for JupyterLab. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/jupyterlab/jupyterlab-commenting">JupyterLab Commenting</a></b> (🥉15 ·  ⭐ 99 · 💀) - Commenting and annotation for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jpmorganchase/nbcelltests">nbcelltests</a></b> (🥉15 ·  ⭐ 81 · 💀) - Cell-by-cell testing for production Jupyter notebooks in.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/chesterli29/jupyterlab_tensorboard">JupyterLab Tensorboard</a></b> (🥉14 ·  ⭐ 310 · 💀) - Tensorboard extension for jupyterlab. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/krassowski/jupyterlab-go-to-definition">JupyterLab Go-To-Definition</a></b> (🥉14 ·  ⭐ 220 · 💀) - Navigate to variables definition with a click in.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jupytercalpoly/jupyterlab-interactive-dashboard-editor">jupyterlab-interactive-dashboard-editor</a></b> (🥉14 ·  ⭐ 210 · 💀) - A drag-and-drop dashboard editor for JupyterLab. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/mlshapiro/jupyterlab-flake8">jupyterlab-flake8</a></b> (🥉14 ·  ⭐ 110 · 💀) - Jupyterlab python linter for notebooks and text files.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jtpio/jupyterlab-python-file">JupyterLab Python Files</a></b> (🥉14 ·  ⭐ 52 · 💀) - JupyterLab extension to create Python files. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/pbugnion/jupyterlab-sql">JupyterLab SQL</a></b> (🥉13 ·  ⭐ 410 · 💀) - SQL GUI for JupyterLab. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/microsoft/gather">nbgather</a></b> (🥉12 ·  ⭐ 520 · 💀) - Spit shine for Jupyter notebooks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/parente/jupyterlab-quickopen">JupyterLab Quickopen</a></b> (🥉12 ·  ⭐ 76 · 💀) - Quickly open a file in JupyterLab by typing part of.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/ReviewNB/jupyterlab-gitplus">jupyterlab-gitplus</a></b> (🥉11 ·  ⭐ 110 · 💀) - JupyterLab extension to create GitHub commits & pull.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code>
- <b><a href="https://github.com/jupyterlab/jupyterlab-celltags">jupyterlab-celltags</a></b> (🥉10 ·  ⭐ 110 · 💀) - A JupyterLab extension for notebook cell tags. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jtpio/jupyterlab-python-bytecode">JupyterLab Bytecode</a></b> (🥉9 ·  ⭐ 61 · 💀) - JupyterLab extension to explore CPython Bytecode. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/manuzhang/jupyterlab_spark">JupyterLab Spark</a></b> (🥉9 ·  ⭐ 9 · 💀) - Spark Application UI extension for JupyterLab. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/gavincyi/jupyterlab-executor">jupyterlab-executor</a></b> (🥉8 ·  ⭐ 13) - JupyterLab extension to execute the scripts from the file.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
</details>
<br>

## JupyterHub Authenticators

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Authentication modules that manage and control how users can access the JupyterHub deployment._

<details><summary><b><a href="https://github.com/jupyterhub/oauthenticator">OAuthenticator</a></b> (🥇30 ·  ⭐ 400) - OAuth + JupyterHub Authenticator = OAuthenticator. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/oauthenticator) (👨‍💻 120 · 🔀 360 · 📦 410 · 📋 300 - 17% open · ⏱️ 13.02.2024):

	```
	git clone https://github.com/jupyterhub/oauthenticator
	```
- [PyPi](https://pypi.org/project/oauthenticator) (📥 38K / month · 📦 49 · ⏱️ 27.11.2023):
	```
	pip install oauthenticator
	```
- [Conda](https://anaconda.org/conda-forge/oauthenticator) (📥 47K · ⏱️ 28.11.2023):
	```
	conda install -c conda-forge oauthenticator
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/ldapauthenticator">LDAP Authenticator</a></b> (🥇24 ·  ⭐ 200) - LDAP Authenticator Plugin for Jupyter. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/ldapauthenticator) (👨‍💻 32 · 🔀 170 · 📦 130 · 📋 150 - 46% open · ⏱️ 06.02.2024):

	```
	git clone https://github.com/jupyterhub/ldapauthenticator
	```
- [PyPi](https://pypi.org/project/jupyterhub-ldapauthenticator) (📥 11K / month · 📦 7 · ⏱️ 28.08.2020):
	```
	pip install jupyterhub-ldapauthenticator
	```
- [Conda](https://anaconda.org/conda-forge/jupyterhub-ldapauthenticator) (📥 34K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge jupyterhub-ldapauthenticator
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/nativeauthenticator">Native Authenticator</a></b> (🥈22 ·  ⭐ 69) - JupyterHub-native User Authenticator. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/nativeauthenticator) (👨‍💻 22 · 🔀 63 · 📦 75 · 📋 110 - 31% open · ⏱️ 06.02.2024):

	```
	git clone https://github.com/jupyterhub/nativeauthenticator
	```
- [PyPi](https://pypi.org/project/jupyterhub-nativeauthenticator) (📥 12K / month · ⏱️ 09.09.2022):
	```
	pip install jupyterhub-nativeauthenticator
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/ltiauthenticator">LTI Authenticator</a></b> (🥈22 ·  ⭐ 63) - A JupyterHub authenticator for LTI. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/ltiauthenticator) (👨‍💻 18 · 🔀 50 · 📦 110 · 📋 51 - 7% open · ⏱️ 06.03.2024):

	```
	git clone https://github.com/jupyterhub/ltiauthenticator
	```
- [PyPi](https://pypi.org/project/jupyterhub-ltiauthenticator) (📥 3.3K / month · 📦 9 · ⏱️ 04.01.2024):
	```
	pip install jupyterhub-ltiauthenticator
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/firstuseauthenticator">First Use Authenticator</a></b> (🥈17 ·  ⭐ 48 · 💤) - JupyterHub Authenticator that lets users set.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/firstuseauthenticator) (👨‍💻 12 · 🔀 28 · 📦 98 · 📋 26 - 34% open · ⏱️ 30.06.2023):

	```
	git clone https://github.com/jupyterhub/firstuseauthenticator
	```
- [PyPi](https://pypi.org/project/jupyterhub-firstuseauthenticator) (📥 6.7K / month · 📦 3 · ⏱️ 28.10.2021):
	```
	pip install jupyterhub-firstuseauthenticator
	```
</details>
<details><summary>Show 10 hidden projects...</summary>

- <b><a href="https://github.com/HewlettPackard/jupyterhub-samlauthenticator">SAML Authenticator</a></b> (🥈14 ·  ⭐ 36 · 💀) - jupyterhub-samlauthenticator. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/mogthesprog/jwtauthenticator">JWT Authenticator</a></b> (🥉13 ·  ⭐ 53 · 💀) - A Token Authenticator for JupyterHub. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/jupyterhub/nullauthenticator">Null Authenticator</a></b> (🥉13 ·  ⭐ 9 · 💀) - Null Authenticator for JupyterHub instances that should.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jupyterhub/dummyauthenticator">dummyauthenticator</a></b> (🥉12 ·  ⭐ 28 · 💀) - A Dummy JupyterHub Authenticator to make testing easy. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/cwaldbieser/jhub_cas_authenticator">CAS Authenticator</a></b> (🥉11 ·  ⭐ 22 · 💤) - CAS authenticator for Jupyterhub. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/cwaldbieser/jhub_remote_user_authenticator">Remote User Auth</a></b> (🥉10 ·  ⭐ 40 · 💀) - REMOTE_USER authenticator for Jupyterhub. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/jupyterhub/kerberosauthenticator">Keberos Authenticator</a></b> (🥉9 ·  ⭐ 11 · 💀) - A JupyterHub authenticator using Kerberos. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/thedataincubator/jupyterhub-hashauthenticator">Hash Authenticator</a></b> (🥉9 ·  ⭐ 4) - Authenticate users with passwords generated from their.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/ucphhpc/jhub-authenticators">Remote Authenticator</a></b> (🥉8 ·  ⭐ 1 · 💤) - A collection of JupyterHub Authenticators, including.. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/andreas-h/sshauthenticator">SSH Authenticator</a></b> (🥉4 ·  ⭐ 6 · 💀) - A simple SSH authenticator for JupyterHub. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
</details>
<br>

## JupyterHub Spawners

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Spawner modules that start, monitor, and stop single-user notebook servers._

<details><summary><b><a href="https://github.com/jupyterhub/kubespawner">KubeSpawner</a></b> (🥇29 ·  ⭐ 510) - Kubernetes spawner for JupyterHub. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/kubespawner) (👨‍💻 84 · 🔀 300 · 📦 160 · 📋 370 - 23% open · ⏱️ 06.02.2024):

	```
	git clone https://github.com/jupyterhub/kubespawner
	```
- [PyPi](https://pypi.org/project/jupyterhub-kubespawner) (📥 15K / month · 📦 15 · ⏱️ 23.11.2023):
	```
	pip install jupyterhub-kubespawner
	```
- [Conda](https://anaconda.org/conda-forge/jupyterhub-kubespawner) (📥 21K · ⏱️ 23.11.2023):
	```
	conda install -c conda-forge jupyterhub-kubespawner
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/dockerspawner">DockerSpawner</a></b> (🥇29 ·  ⭐ 470) - Spawns JupyterHub single user servers in Docker containers. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/dockerspawner) (👨‍💻 69 · 🔀 310 · 📦 180 · 📋 280 - 9% open · ⏱️ 01.02.2024):

	```
	git clone https://github.com/jupyterhub/dockerspawner
	```
- [PyPi](https://pypi.org/project/dockerspawner) (📥 80K / month · 📦 28 · ⏱️ 21.11.2023):
	```
	pip install dockerspawner
	```
- [Conda](https://anaconda.org/conda-forge/dockerspawner) (📥 21K · ⏱️ 21.11.2023):
	```
	conda install -c conda-forge dockerspawner
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/batchspawner">BatchSpawner</a></b> (🥈22 ·  ⭐ 170) - Custom Spawner for Jupyterhub to start servers in batch scheduled.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/batchspawner) (👨‍💻 47 · 🔀 130 · 📦 32 · 📋 160 - 47% open · ⏱️ 08.03.2024):

	```
	git clone https://github.com/jupyterhub/batchspawner
	```
- [PyPi](https://pypi.org/project/batchspawner) (📥 4.2K / month · 📦 4 · ⏱️ 05.10.2022):
	```
	pip install batchspawner
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/systemdspawner">SystemdSpawner</a></b> (🥉20 ·  ⭐ 88) - Spawn JupyterHub single-user notebook servers with systemd. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/systemdspawner) (👨‍💻 21 · 🔀 47 · 📦 41 · 📋 76 - 35% open · ⏱️ 01.02.2024):

	```
	git clone https://github.com/jupyterhub/systemdspawner
	```
- [PyPi](https://pypi.org/project/jupyterhub-systemdspawner) (📥 4.4K / month · 📦 1 · ⏱️ 08.06.2023):
	```
	pip install jupyterhub-systemdspawner
	```
- [Conda](https://anaconda.org/conda-forge/jupyterhub-systemdspawner) (📥 32K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge jupyterhub-systemdspawner
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/sudospawner">SudoSpawner</a></b> (🥉17 ·  ⭐ 50) - Spawn JupyterHub single-user servers with sudo. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/sudospawner) (👨‍💻 15 · 🔀 39 · 📦 65 · 📋 40 - 45% open · ⏱️ 14.12.2023):

	```
	git clone https://github.com/jupyterhub/sudospawner
	```
- [PyPi](https://pypi.org/project/sudospawner) (📥 990 / month · 📦 4 · ⏱️ 19.06.2018):
	```
	pip install sudospawner
	```
</details>
<details><summary><b><a href="https://github.com/jupyterhub/wrapspawner">WrapSpawner</a></b> (🥉14 ·  ⭐ 60 · 💤) - Mechanism for runtime configuration of spawners for JupyterHub. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyterhub/wrapspawner) (👨‍💻 17 · 🔀 56 · 📦 11 · 📋 33 - 57% open · ⏱️ 05.04.2023):

	```
	git clone https://github.com/jupyterhub/wrapspawner
	```
</details>
<details><summary>Show 2 hidden projects...</summary>

- <b><a href="https://github.com/uktrade/fargatespawner">FargateSpawner</a></b> (🥉14 ·  ⭐ 44 · 💀) - Spawns JupyterHub single user servers in Docker containers.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/jupyterhub/yarnspawner">YarnSpawner</a></b> (🥉10 ·  ⭐ 19 · 💀) - Spawn JupyterHub single user notebook servers in Hadoop/YARN.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
</details>
<br>

## Jupyter Components

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Core components of the Jupyter architecture._

<details><summary><b><a href="https://github.com/ipython/ipython">ipython</a></b> (🥇47 ·  ⭐ 16K) - Official repository for IPython itself. Other repos in the IPython.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/ipython/ipython) (👨‍💻 980 · 🔀 4.4K · 📥 320K · 📦 520K · 📋 7.3K - 22% open · ⏱️ 07.03.2024):

	```
	git clone https://github.com/ipython/ipython
	```
- [PyPi](https://pypi.org/project/ipython) (📥 42M / month · 📦 37K · ⏱️ 04.03.2024):
	```
	pip install ipython
	```
- [Conda](https://anaconda.org/conda-forge/ipython) (📥 26M · ⏱️ 04.03.2024):
	```
	conda install -c conda-forge ipython
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-server/jupyter_server">jupyter_server</a></b> (🥉32 ·  ⭐ 440) - The backendi.e. core services, APIs, and REST endpointsto.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter-server/jupyter_server) (👨‍💻 520 · 🔀 260 · 📥 2.7K · 📋 430 - 34% open · ⏱️ 13.03.2024):

	```
	git clone https://github.com/jupyter-server/jupyter_server
	```
- [PyPi](https://pypi.org/project/jupyter_server) (📥 28M / month):
	```
	pip install jupyter_server
	```
- [Conda](https://anaconda.org/conda-forge/jupyter_server) (📥 10M · ⏱️ 04.03.2024):
	```
	conda install -c conda-forge jupyter_server
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/jupyter-packaging">jupyter-packaging</a></b> (🥉20 ·  ⭐ 61) - Tools to help build and install Jupyter Python packages. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/jupyter-packaging) (👨‍💻 30 · 🔀 46 · 📥 62 · 📋 41 - 26% open · ⏱️ 02.01.2024):

	```
	git clone https://github.com/jupyter/jupyter-packaging
	```
- [PyPi](https://pypi.org/project/jupyter-packaging) (📥 420K / month):
	```
	pip install jupyter-packaging
	```
- [Conda](https://anaconda.org/conda-forge/jupyter-packaging) (📥 550K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge jupyter-packaging
	```
</details>
<br>

## Others

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/jupyter/qtconsole">qtconsole</a></b> (🥇34 ·  ⭐ 390) - Jupyter Qt Console. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/qtconsole) (👨‍💻 120 · 🔀 190 · 📦 170K · 📋 340 - 31% open · ⏱️ 25.11.2023):

	```
	git clone https://github.com/jupyter/qtconsole
	```
- [PyPi](https://pypi.org/project/qtconsole) (📥 5.4M / month):
	```
	pip install qtconsole
	```
- [Conda](https://anaconda.org/conda-forge/qtconsole) (📥 4.6M · ⏱️ 16.11.2023):
	```
	conda install -c conda-forge qtconsole
	```
</details>
<details><summary><b><a href="https://github.com/jupyter/jupyter_console">jupyter-console</a></b> (🥈23 ·  ⭐ 240 · 💤) - Jupyter Terminal Console. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jupyter/jupyter_console) (👨‍💻 60 · 🔀 140 · 📥 370 · 📋 160 - 39% open · ⏱️ 06.03.2023):

	```
	git clone https://github.com/jupyter/jupyter_console
	```
- [PyPi](https://pypi.org/project/jupyter-console) (📥 4.5M / month):
	```
	pip install jupyter-console
	```
- [Conda](https://anaconda.org/conda-forge/jupyter_console) (📥 4.3M · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge jupyter_console
	```
</details>
<details><summary><b><a href="https://github.com/datapane/datapane">datapane</a></b> (🥉21 ·  ⭐ 1.3K) - Build and share data reports in 100% Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/datapane/datapane) (👨‍💻 16 · 🔀 100 · ⏱️ 07.09.2023):

	```
	git clone https://github.com/datapane/datapane
	```
- [PyPi](https://pypi.org/project/datapane) (📥 35K / month · 📦 14 · ⏱️ 07.09.2023):
	```
	pip install datapane
	```
- [Conda](https://anaconda.org/conda-forge/datapane) (📥 82K · ⏱️ 07.09.2023):
	```
	conda install -c conda-forge datapane
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/abhishekkrthakur/colabcode">colabcode</a></b> (🥉19 ·  ⭐ 2K · 💀) - Run VSCode (codeserver) on Google Colab or Kaggle Notebooks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
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
