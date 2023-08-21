# PROGRAMA ESPECIALIZADO CIENCIA DE DATOS CON PYTHON

## PROYECTO No 02

### Librerias

```python
import pandas as pd
import seaborn as sns
import statistics as stats
import numpy as np
import scipy
import matplotlib.pyplot as plt
import libraryFunc.libFunc as lib
import warnings
warnings.simplefilter('ignore')
from statsmodels.graphics.gofplots import qqplot
from scipy.stats import shapiro
from scipy.stats import kstest
from scipy.stats import zscore
from sklearn.preprocessing import MinMaxScaler
from sklearn.linear_model import LinearRegression
from sklearn.metrics import r2_score
from sklearn.metrics import mean_squared_error
import statsmodels.api as sm
```


### Estructura del proyecto
1. data
   * Carpeta que contiene la data en formato csv. En la carpeta cleaned se encuentra la data ya limpia con las nuevas variables categoricas
2. notebooks
   * Scripts de exploracion, limpieza o analisis.
   * En el notebook de Exploration se encuentra el EDA creado
   * En el notebook de Analysis se encuentra en analisis inferencial
3. results
   * Script de resultados finales o graficos.
4. scripts
   * Libreria propia de funciones para implementar en el proyecto
5. test
   * Pruebas unitarias


### Video de youtube

[Explicacion del proyecto 3](https://youtu.be/DZvvAlseiAU)

### Documentacion

* [Video tutorial](https://www.youtube.com/watch?v=JLRQaQRbr9w)
* [Clases impartidas]()