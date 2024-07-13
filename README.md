# SkyWalk-docs

[![Python](https://img.shields.io/pypi/pyversions/SkyWalk-docs)](https://img.shields.io/pypi/pyversions/SkyWalk-docs)
[![Pypi](https://img.shields.io/pypi/v/SkyWalk-docs)](https://pypi.org/project/SkyWalk-docs/)
[![Docs](https://img.shields.io/badge/Sphinx-Docs-Green)](https://erdogant.github.io/SkyWalk-docs/)
[![LOC](https://sloc.xyz/github/erdogant/SkyWalk-docs/?category=code)](https://github.com/erdogant/SkyWalk-docs/)
[![Downloads](https://static.pepy.tech/personalized-badge/SkyWalk-docs?period=month&units=international_system&left_color=grey&right_color=brightgreen&left_text=PyPI%20downloads/month)](https://pepy.tech/project/SkyWalk-docs)
[![Downloads](https://static.pepy.tech/personalized-badge/SkyWalk-docs?period=total&units=international_system&left_color=grey&right_color=brightgreen&left_text=Downloads)](https://pepy.tech/project/SkyWalk-docs)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](https://github.com/erdogant/SkyWalk-docs/blob/master/LICENSE)
[![Forks](https://img.shields.io/github/forks/erdogant/SkyWalk-docs.svg)](https://github.com/erdogant/SkyWalk-docs/network)
[![Issues](https://img.shields.io/github/issues/erdogant/SkyWalk-docs.svg)](https://github.com/erdogant/SkyWalk-docs/issues)
[![Project Status](http://www.repostatus.org/badges/latest/active.svg)](http://www.repostatus.org/#active)
[![DOI](https://zenodo.org/badge/228166657.svg)](https://zenodo.org/badge/latestdoi/228166657)
[![Medium](https://img.shields.io/badge/Medium-Blog-green)](https://towardsdatascience.com/what-are-SkyWalk-docs-loadings-and-biplots-9a7897f2e559)
[![Colab](https://colab.research.google.com/assets/colab-badge.svg?logo=github%20sponsors)](https://erdogant.github.io/SkyWalk-docs/pages/html/Documentation.html#colab-notebook)
![GitHub Repo stars](https://img.shields.io/github/stars/erdogant/SkyWalk-docs)
![GitHub repo size](https://img.shields.io/github/repo-size/erdogant/SkyWalk-docs)
[![Donate](https://img.shields.io/badge/Support%20this%20project-grey.svg?logo=github%20sponsors)](https://erdogant.github.io/SkyWalk-docs/pages/html/Documentation.html#)
<!---[![BuyMeCoffee](https://img.shields.io/badge/buymea-coffee-yellow.svg)](https://www.buymeacoffee.com/erdogant)-->
<!---[![Coffee](https://img.shields.io/badge/coffee-black-grey.svg)](https://erdogant.github.io/donate/?currency=USD&amount=5)-->





<!---[![BuyMeCoffee](https://img.shields.io/badge/buymea-coffee-yellow.svg)](https://www.buymeacoffee.com/erdogant)-->
<!---[![Coffee](https://img.shields.io/badge/coffee-black-grey.svg)](https://erdogant.github.io/donate/?currency=USD&amount=5)-->

* ``SkyWalk-docs`` is Python package

# 
**Star this repo if you like it! ⭐️**
#


## Blog/Documentation

* [**SkyWalk-docs documentation pages (Sphinx)**](https://erdogant.github.io/SkyWalk-docs/)
* [**Notebook with examples**](https://colab.research.google.com/github/erdogant/SkyWalk-docs/blob/master/notebooks/SkyWalk-docs.ipynb)
* [**Read more details and usage about SkyWalk-docs in this blog!**](https://towardsdatascience.com/SkyWalk-docs)

* <a href="https://erdogant.github.io/SkyWalk-docs/"> <img src="https://img.shields.io/badge/Sphinx-Docs-Green" alt="Open documentation pages"/> </a> SkyWalk-docs documentation pages 
* <a href="https://colab.research.google.com/github/erdogant/SkyWalk-docs/blob/master/notebooks/SkyWalk-docs.ipynb"> <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open example In Colab"/> </a> Notebook example 
* <a href="https://towardsdatascience.com/a-step-by-step-guide-for-clustering-images-4b45f9906128"> <img src="https://img.shields.io/badge/Medium-Blog-blue" alt="Open Blog"/> </a> Blog: A step-by-step guide for clustering images 


### Contents
- [Installation](#-installation)
- [Contribute](#-contribute)
- [Citation](#-citation)
- [Maintainers](#-maintainers)
- [License](#-copyright)

### Installation
* Install SkyWalk-docs from PyPI (recommended). SkyWalk-docs is compatible with Python 3.6+ and runs on Linux, MacOS X and Windows. 
* A new environment can be created as following:

```bash
conda create -n env_SkyWalk-docs python=3.8
conda activate env_SkyWalk-docs
```

```bash
pip install SkyWalk-docs            # normal install
pip install --upgrade SkyWalk-docs # or update if needed
```

* Alternatively, you can install from the GitHub source:
```bash
# Directly install from github source
pip install -e git://github.com/erdogant/SkyWalk-docs.git@0.1.0#egg=master
pip install git+https://github.com/erdogant/SkyWalk-docs#egg=master
pip install git+https://github.com/erdogant/SkyWalk-docs

# By cloning
git clone https://github.com/erdogant/SkyWalk-docs.git
cd SkyWalk-docs
pip install -U .
```  

#### Import SkyWalk-docs package
```python
import SkyWalk-docs as SkyWalk-docs
```

#### Example:
```python
df = pd.read_csv('https://github.com/erdogant/hnet/blob/master/SkyWalk-docs/data/example_data.csv')
model = SkyWalk-docs.fit(df)
G = SkyWalk-docs.plot(model)
```
<p align="center">
  <img src="https://github.com/erdogant/SkyWalk-docs/blob/master/docs/figs/fig1.png" width="600" />
  
</p>


#### References
* https://github.com/erdogant/SkyWalk-docs

#### Citation
Please cite in your publications if this is useful for your research (see citation).
   
### Maintainers
* Erdogan Taskesen, github: [erdogant](https://github.com/erdogant)

### Contribute
* All kinds of contributions are welcome!
* If you wish to buy me a <a href="https://www.buymeacoffee.com/erdogant">Coffee</a> for this work, it is very appreciated :)

### Licence
See [LICENSE](LICENSE) for details.
