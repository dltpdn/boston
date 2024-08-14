<h1>Bonston Housing Price DataSet for Regression</h1>

* Kor: `sklearn.datasets.load_boston()`가 v1.2 부터 제거되서 이것을 그대로 재구성했습니다.

* Eng: `sklearn.datasets.load_boston()` was removed from v1.2, so I rebuilt it as is.

# Install
`pip install boston`

# Usage
```
from boston import load_boston
import pandas as pd

boston = load_boston()
df = pd.DataFrame(boston.data, columns=boston.feature_names)
df['target'] = boston.target
df
```
