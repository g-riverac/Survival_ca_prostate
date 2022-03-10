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
