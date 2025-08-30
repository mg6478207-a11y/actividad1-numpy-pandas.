B) NumPy – Operaciones estadísticas y funciones avanzadas


1. MEAN → MEDIA ARITMÉTICA

CODIGO

import numpy as np

data = [10, 20, 30, 40, 50]

media = np.mean(data)

print("Media:", media)   # 30.0

ADJUNTO DE IMAGEN

<img width="1912" height="402" alt="image" src="https://github.com/user-attachments/assets/bb7432be-bfbb-4d9b-a65c-a518c1a3f742" />
<img width="1915" height="407" alt="image" src="https://github.com/user-attachments/assets/e4ede553-2bdb-4ca9-97ee-36ad08a75ddf" />


2. STD → DESVIACIÓN ESTÁNDAR

CODIGO
import numpy as np

# Temperaturas de una semana en Ciudad A (muy parecidas)
ciudad_A = [22, 23, 22, 23, 22, 23, 22]

# Temperaturas de una semana en Ciudad B (muy dispersas)
ciudad_B = [18, 25, 20, 30, 15, 28, 22]

# Calculamos desviación estándar
desv_A = np.std(ciudad_A)
desv_B = np.std(ciudad_B)

print("Desviación estándar Ciudad A:", desv_A)  # pequeña
print("Desviación estándar Ciudad B:", desv_B)  # grande


SEGUNDO CODIGO DE EJEMPLO 
# Altura de plantas en un experimento (cm)

# Grupo 1: plantas uniformes
plantas_1 = [30, 31, 30, 32, 31]

# Grupo 2: plantas con mucha variación
plantas_2 = [25, 40, 30, 35, 45]

# Desviación estándar
desv_1 = np.std(plantas_1)
desv_2 = np.std(plantas_2)

print("Desviación estándar Grupo 1:", desv_1)  # pequeña
print("Desviación estándar Grupo 2:", desv_2)  # grande

IMAGEN CODIGO 1  <img width="1918" height="616" alt="image" src="https://github.com/user-attachments/assets/2f3fd1bd-0525-4225-b3aa-edf918e564cf" />
IMAGEN CODIGO 2  <img width="1893" height="632" alt="image" src="https://github.com/user-attachments/assets/b7782b59-d933-4b1f-8e8f-ff8c663569f4" />






