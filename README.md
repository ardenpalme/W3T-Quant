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
4. Start notebook within virtual python environment `jupyter notebook`

Notes: Install missing packages within the virtual env with `uv pip install <pkg_name>`
