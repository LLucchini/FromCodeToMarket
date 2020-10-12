## [From Code To Market: Network of developers and correlated returns of cryptocurrencies](https://arxiv.org/abs/2004.07290)

__Code development and market time series analysis for cryptocurrencies developed on GitHub__

_Code will be released shortly in this repo_  
_Code is written in python 3.4 and will be released in the form of IPython notebooks_


1. Notebook 1 process github data and market time series to build the linked pairs network. Process the development activity from the GitHubArchive dataset and the market activity from CryptoCompare and CoinGecko datasets. It also produce a network (dataframe) of cryptocurrency projects edited by the same developer and a dataframe o timeseries where columns are crypto assets (one dataframe is created per each market measure).
2. This notebook run correlation experiments. Experiments are performed for robustness over multiple window and for multiple measure. All the computations were performed on 4 different set of pairs as explained in the manuscript.
3. Notebook 3 draws most of the figures presented in the main text as well as those in the Supplementary Information.

### NOTE
__If you use this code or any of its parts, please cite the following: [https://arxiv.org/abs/2004.07290](https://arxiv.org/abs/2004.07290)__
