B) NumPy – Operaciones estadísticas y funciones avanzadas


# 1. MEAN → MEDIA ARITMÉTICA

# CODIGO

import numpy as np

data = [10, 20, 30, 40, 50]

media = np.mean(data)

print("Media:", media)   # 30.0

# ADJUNTO DE IMAGEN

IMAGEN CODIGO <img width="1912" height="402" alt="image" src="https://github.com/user-attachments/assets/bb7432be-bfbb-4d9b-a65c-a518c1a3f742" />
IMAGEN CODIGO <img width="1915" height="407" alt="image" src="https://github.com/user-attachments/assets/e4ede553-2bdb-4ca9-97ee-36ad08a75ddf" />


# 2. STD → DESVIACIÓN ESTÁNDAR

# PRIMER CODIGO DE EJEMPLO 
import numpy as np

#Temperaturas de una semana en Ciudad A (muy parecidas)

ciudad_A = [22, 23, 22, 23, 22, 23, 22]

#Temperaturas de una semana en Ciudad B (muy dispersas)

ciudad_B = [18, 25, 20, 30, 15, 28, 22]

#Calculamos desviación estándar

desv_A = np.std(ciudad_A)

desv_B = np.std(ciudad_B)

print("Desviación estándar Ciudad A:", desv_A)  # pequeña

print("Desviación estándar Ciudad B:", desv_B)  # grande


# SEGUNDO CODIGO DE EJEMPLO 

Altura de plantas en un experimento (cm)

Grupo 1: plantas uniformes

plantas_1 = [30, 31, 30, 32, 31]

Grupo 2: plantas con mucha variación

plantas_2 = [25, 40, 30, 35, 45]

#Desviación estándar

desv_1 = np.std(plantas_1)

desv_2 = np.std(plantas_2)

print("Desviación estándar Grupo 1:", desv_1)  # pequeña

print("Desviación estándar Grupo 2:", desv_2)  # grande

# ADJUNTO DE IMAGEN

IMAGEN CODIGO 1  <img width="1918" height="616" alt="image" src="https://github.com/user-attachments/assets/2f3fd1bd-0525-4225-b3aa-edf918e564cf" />

IMAGEN CODIGO 2  <img width="1893" height="632" alt="image" src="https://github.com/user-attachments/assets/b7782b59-d933-4b1f-8e8f-ff8c663569f4" />

# 3. SUM → SUMA DE ELEMENTOS

# PRIMER CODIGO DE EJEMPLO 

import numpy as np

#Ventas de una tienda durante la semana 1

ventas_semana1 = [100, 150, 120, 130, 110]

#Ventas de la semana 2
ventas_semana2 = [200, 180, 220, 210, 190]

#Suma total de ventas

total_semana1 = np.sum(ventas_semana1)

total_semana2 = np.sum(ventas_semana2)

print("Total ventas semana 1:", total_semana1)

print("Total ventas semana 2:", total_semana2)

# SEGUNDO CODIGO DE EJEMPLO 

import numpy as np

#Puntos de un jugador en 5 partidos

puntos_partidos1 = [10, 15, 12, 18, 20]

#Otro jugador

puntos_partidos2 = [8, 20, 15, 12, 25]

#Suma total de puntos

total_jugador1 = np.sum(puntos_partidos1)

total_jugador2 = np.sum(puntos_partidos2)

print("Total puntos jugador 1:", total_jugador1)

print("Total puntos jugador 2:", total_jugador2)


# ADJUNTO DE IMAGEN

IMAGEN CODIGO 1.1 <img width="1917" height="593" alt="image" src="https://github.com/user-attachments/assets/afbe232c-bb23-402f-a175-d0c78ed03f64" />
IMAGEN CODIGO 1.2 <img width="1916" height="585" alt="image" src="https://github.com/user-attachments/assets/4010a2d9-e1a7-49f7-9984-0451a1ec3748" />
IMAGEN CODIGO 2.1 <img width="1861" height="475" alt="image" src="https://github.com/user-attachments/assets/8a479ab1-f10b-4754-882f-798204a82c67" />
IMAGEN CODIGO 2.2 <img width="1913" height="587" alt="image" src="https://github.com/user-attachments/assets/192a2b15-040d-46de-9765-84bf825c105d" />



# 4. ARANGE → RANGO DE VALORES

# PRIMER CODIGO DE EJEMPLO 

import numpy as np

rango1 = np.arange(0, 11, 2)

rango2 = np.arange(1, 11, 2)  # Números impares

print("Números pares:", rango1)

print("Números impares:", rango2))


# SEGUNDO CODIGO DE EJEMPLO 

import numpy as np

horas_dia = np.arange(0, 24, 3)  # 0, 3, 6, ..., 21

horas_noche = np.arange(0, 24, 6)  # 0, 6, 12, 18

print("Horas día (cada 3h):", horas_dia)

print("Horas noche (cada 6h):", horas_noche)

# ADJUNTO DE IMAGEN

IMAGEN CODIGO 1 <img width="1863" height="405" alt="image" src="https://github.com/user-attachments/assets/30d3ee1c-7305-4823-a64b-b92a7b3ac1d4" />
IMAGEN CODIGO 2 <img width="1890" height="408" alt="image" src="https://github.com/user-attachments/assets/a26ca0b8-0e52-402d-84e7-cf3b0b458c95" />


# 5. LINSPACE → VALORES EQUIESPACIADOS

# PRIMER CODIGO DE EJEMPLO 

import numpy as np

temp1 = np.linspace(0, 100, 5)   # 0, 25, 50, 75, 100

temp2 = np.linspace(0, 100, 11)  # cada 10 grados

print("Temperaturas 5 valores:", temp1)

print("Temperaturas 11 valores:", temp2)

# SEGUNDO CODIGO DE EJEMPLO 

import numpy as np

progreso1 = np.linspace(0, 1, 5)  # 0%, 25%, 50%, 75%, 100%

progreso2 = np.linspace(0, 1, 11) # 0%, 10%, ..., 100%

print("Progreso 5 pasos:", progreso1)

print("Progreso 11 pasos:", progreso2)

# ADJUNTO DE IMAGEN

IMAGEN CODIGO 1 <img width="1903" height="431" alt="image" src="https://github.com/user-attachments/assets/7e38f8a6-d813-4208-886b-f1de423c3257" />
IMAGEN CODIGO 2 <img width="1887" height="461" alt="image" src="https://github.com/user-attachments/assets/b6da7a0e-7b21-411c-8828-06dd78bef804" />


# 6. RANDOM → NÚMEROS ALEATORIOS

# PRIMER CODIGO DE EJEMPLO 

import numpy as np

aleatorio1 = np.random.rand(3, 2)

aleatorio2 = np.random.rand(2, 3)

print("Matriz 3x2:\n", aleatorio1)

print("Matriz 2x3:\n", aleatorio2)


# SEGUNDO CODIGO DE EJEMPLO 

import numpy as np

vector1 = np.random.rand(5)

vector2 = np.random.rand(5)

print("Vector 1:", vector1)

print("Vector 2:", vector2)

# ADJUNTO DE IMAGEN

IMAGEN CODIGO 1 <img width="1915" height="542" alt="image" src="https://github.com/user-attachments/assets/8bb51c41-be56-4745-8eec-f95287be4f14" />

IMAGEN CODIGO 2 <img width="1912" height="452" alt="image" src="https://github.com/user-attachments/assets/bb93fb57-189a-40b8-88e7-c6bb7c624bfc" />



# 7. ÁLGEBRA LINEAL (DOT) → PRODUCTO DE MATRICES

# PRIMER CODIGO DE EJEMPLO 

import numpy as np

A1 = np.array([[1, 2], [3, 4]])

B1 = np.array([[2, 0], [1, 2]])

producto1 = np.dot(A1, B1)

A2 = np.array([[0, 1], [1, 0]])

B2 = np.array([[1, 1], [1, 1]])

producto2 = np.dot(A2, B2)

print("Producto matrices 1:\n", producto1)

print("Producto matrices 2:\n", producto2)



# SEGUNDO CODIGO DE EJEMPLO 

import numpy as np

C1 = np.array([[1, 2], [3, 4], [5, 6]])

D1 = np.array([[1, 0, 1], [0, 1, 0]])

producto3 = np.dot(C1, D1)

C2 = np.array([[2, 1], [0, 1], [1, 0]])

D2 = np.array([[1, 2, 3], [4, 5, 6]])

producto4 = np.dot(C2, D2)

print("Producto matrices 3x2 y 2x3:", producto3)

print("Producto matrices 3x2 y 2x3:", producto4)


# ADJUNTO DE IMAGEN

IMAGEN CODIGO 1 <img width="1918" height="677" alt="image" src="https://github.com/user-attachments/assets/ad3488a1-3148-4ae6-a9b6-aeef3584c60a" />

IMAGEN CODIGO 2 <img width="1918" height="696" alt="image" src="https://github.com/user-attachments/assets/31201399-a1ad-4c84-b198-cd30096d2258" />

