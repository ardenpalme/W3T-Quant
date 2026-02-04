# W3T-Quant

## Overview
This repo houses jupyter notebooks with strategies to use as a boilerplate for more advanced strategies 

*please fork this repo - do not make changes to main*

## Setup 
1. Install `uv` package manager [link](https://docs.astral.sh/uv/getting-started/installation/)
2. Create and activate environment `uv venv vectorbt` `source vectorbt/bin/activate`
3. Install [vectorbt-pro](https://github.com/polakowo/vectorbt) with `uv pip install "vectorbtpro[base] @ git+https://ardenpalme.com/repos/vectorbt.pro.git"`
4. Add dependencies with `uv add notebook` (may need other packages for the ML notebook)
5. Start notebook within virtual python environment `jupyter notebook`
