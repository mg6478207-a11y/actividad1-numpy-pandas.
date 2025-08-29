# Datasheet de NumPy y Pandas

Este documento contiene ejemplos básicos de NumPy y Pandas ejecutados en Google Colab.
# Imprimir numeros
import numpy as np
arr = np.array([3,2,1,2,5,0,9,8,5,7])
print("Array:", arr)
Array: [3 2 1 2 5 0 9 8 5 7]

# Edades participantes
import pandas as pd
df = pd.DataFrame({"Nombre": ["Nata", "Cami","Aleja"], "Edad": [19,18,23]})
print(df)
  Nombre  Edad
0   Nata    19
1   Cami    18
2  Aleja    23

import numpy as np

# Crear arrays
a = np.array([10, 20, 30])
b = np.array([1, 2, 3])

print("Array a:", a)
print("Array b:", b)

# Suma
print("Suma:", a + b)

# Resta
print("Resta:", a - b)

# Multiplicación
print("Multiplicación:", a * b)

# División
print("División:", a / b)

Array a: [10 20 30]
Array b: [1 2 3]
Suma: [11 22 33]
Resta: [ 9 18 27]
Multiplicación: [10 40 90]
División: [10. 10. 10.]
