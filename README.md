# W3T-Quant

## Overview
This repo houses jupyter notebooks with strategies to use as a boilerplate for more advanced strategies 

*please work within a branch of this repo - do not make changes to main*

## Setup 
### Basic
1. Code editor e.g. [VSCode](https://code.visualstudio.com/download)
2. Terminal: (Windows) Install [Powershell7](https://lazyadmin.nl/powershell/install-powershell-7/) (Mac) Install [Homebrew](https://brew.sh/)
### Project
1. Install `uv` package manager [link](https://docs.astral.sh/uv/getting-started/installation/)
2. Create and activate environment `uv venv vectorbt` `source vectorbt/bin/activate`
3. Install [vectorbt-pro](https://github.com/polakowo/vectorbt) with `uv pip install "vectorbtpro[base] @ git+https://ardenpalme.com/repos/vectorbt.pro.git"`
4. Add dependencies with `uv add notebook` (may need other packages for the ML notebook)
5. Start notebook within virtual python environment `jupyter notebook`

4. Start notebook within virtual python environment `jupyter notebook`

Notes: Install missing packages within the virtual env with `uv pip install <pkg_name>`

<span style="display: inline-flex; align-items: center; gap: 5%;">
<img src="images/index-finger-hand-pointing-clip-art.png" style="height: 20px; width: 40px;">
<div style="font-weight: bold; font-size: 15px;"> Disclaimer: </div>
</span>
PLEASE DO NOT DISTRIBUTE THIS CODE
