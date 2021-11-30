![Crypto](https://ripplecoinnews.com/wp-content/uploads/2021/08/cryptocurrency-22-1200x900.jpg)
# crypto_clustering
Cluster Cryptocurrencies by their performance in different time periods using original and PCA data pulled from a csv file. 
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
