![Crypto](https://blockchainstock.azureedge.net/features/7B13862B8D05A4CC0C48D1875635B6A884C93AA9A49282FA4793E28ABACB729A.jpg)
# crypto_clustering
Cluster Cryptocurrencies by their performance in different time periods using original data from a csv file as well as PCA data. 
---
## Technologies
This analysis leverages python 3.7 with the following packages and libraries:
* [pandas](https://github.com/pandas-dev/pandas)
* [hvplot](https://github.com/holoviz/hvplot)
* [pathlib](https://github.com/python/cpython/blob/main/Lib/pathlib.py)
* [scikit-learn](https://github.com/scikit-learn/scikit-learn)

---
## Installations
```python
import pandas as pd
import hvplot.pandas
from pathlib import Path
from sklearn.cluster import KMeans
from sklearn.decomposition import PCA
from sklearn.preprocessing import StandardScaler
```
---
## Contributors
[Noah Beito](https://www.linkedin.com/in/noah-beito/)
---
## License
[MIT](https://github.com/git/git-scm.com/blob/main/MIT-LICENSE.txt)