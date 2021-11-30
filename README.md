# Crypto_Performance_Clusters

![Picture of coins representing three cryptocurrencies, Bitcoin, Ethereum Classic, and Cardano.](https://static.news.bitcoin.com/wp-content/uploads/2021/07/ada-eth-btc.jpg)

### This program uses the K-Means Clustering along with Pricipal Component Analysis(PCA) to scale, analyze, and compare a number of crypto currencies and their price change on different timeframes.

---

## Technologies:
This program runs on Python 3.7 and utilizes the following packages:

* [Jupyter Lab](https://jupyter.org/)

* [pandas](https://pandas.pydata.org/)

* [hvplot](https://hvplot.holoviz.org/)

* [sklearn](https://scikit-learn.org/)

---
## Installation Guide:
Make sure you have all the packages installed. To make sure, run the following in your local terminal:

```
pip install jupyterlab
pip install pandas
pip install hvplot
pip install scikit-learn
```

This progam can run in Jupyter Lab where the following imports are required:

```python
import pandas as pd
import hvplot.pandas
from path import Path
from sklearn.cluster import KMeans
from sklearn.decomposition import PCA
from sklearn.preprocessing import StandardScaler
```


---
## Usage:
Once `crypto_performance_clusters.ipynb` is opened in jupyter lab and the cells are ran, the user will begin to see some of the following outputs:

![Screen shot of Crypto Market Data](https://user-images.githubusercontent.com/89755088/143978623-de2d25a2-47f0-4529-84c4-9548b53e3516.png)

![Screen shot of the Elbow Curve](https://user-images.githubusercontent.com/89755088/143978479-56522a39-66b6-4667-ad9f-fa25460270f9.png)

![Screen shot of a cluster plot](https://user-images.githubusercontent.com/89755088/143978545-56485d2e-5e6d-4abd-83db-78396b4c8641.png)

---
## Contributors:
Code was written by Thomas Leahy, thomasleahy6@gmail.com, In conjunction with © 2020 - 2021 Trilogy Education Services, a 2U, Inc. brand.

---
## Licence:
MIT

2021 Thomas Leahy