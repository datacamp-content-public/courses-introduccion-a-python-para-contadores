---
title: 'Introducción a tablas'
description: 'Se establece el primer contacto con la plataforma.'
---

## Crear un DataFrame en pandas

```yaml
type: NormalExercise
key: e8c1edbe67
lang: python
xp: 100
skills: 2
```

Los DataFrames son estructuras de datos de dos dimensiones (rectangulares o tabulares). Se componen de columnas y filas y pueden contener datos de diferentes tipos.

`@instructions`
- Importar la librería de pandas.
- Crear una lista que contenga los números enteros: 0,1,2,3 y 4.
- Convertir la lista en un DataFrame.

`@hint`


`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
#1. Importar la librería de pandas y DataFrame.
import pandas as __
from pandas import DataFrame

#2. Crear una lista que contenga los números enteros: 0,1,2,3 y 4.
d=[_,1,_,3,_]
d
#3. Convertir la lista en un DataFrame e imprimir la tabla.
df=DataFrame(data=_)
df
```

`@solution`
```{python}
import pandas as pd
from pandas import DataFrame
d=[0,1,2,3,4]
d
df=DataFrame(data=d)
df
```

`@sct`
```{python}

```
