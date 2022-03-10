# Survival_ca_prostate


Se inicia por cargar la librería y obtener la información que posee el dataset.

```{python}
from datetime import datetime
import pandas as pd
import numpy as np
import math
import re

df_ca=pd.read_excel("D:\MDS\Pandas\EjercicioOpcional\patient_survival_ca_prostate_00-10.xlsx",na_values= np.nan)
```

```{python, echo=FALSE}
pd.set_option('display.max_rows', 25)
pd.set_option('display.max_columns', 100)
# pd.set_option('display.width', 70)
pd.set_option("precision", 4)
pd.set_option("large_repr", "truncate")
pd.set_option("max_colwidth", 25)
pd.set_option("chop_threshold", None)
pd.set_option("colheader_justify", "center")

```

## Exploración de datos

Para visualizar la estructura del dataset, así como también la información que posee, se utiliza dataframe.head().

```{python}
df_ca.info()
```
