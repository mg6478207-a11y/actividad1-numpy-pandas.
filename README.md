# Actividad 2 – NumPy y Pandas
Este repositorio contiene el datasheet en formato Markdown.

import numpy as np

#Crear un arreglo

a = np.array([1, 2, 3, 4, 5])

print(a)

#Arreglo con matriz.

b= np.array([[1,2,3],[4,5,6]])

print(b)

#Adjunto imagen de codigo + salida.

![Imagen de WhatsApp 2025-08-29 a las 22 52 14_4ac5359d](https://github.com/user-attachments/assets/986aa5ee-4f1e-4338-82c7-a3453d93da12)

#Convertir un arreglo en matriz 2x3

import numpy as np

a = np.arange(6)

print(a.reshape(2,3))

#Convertir un arreglo en matriz 3x2

print(a.reshape(3,2))

#Adjunto imagen de codigo + salida

<img width="410" height="258" alt="image" src="https://github.com/user-attachments/assets/88b63d42-736f-45fb-8115-ba9721efd2da" />

#Concatenar 

import numpy as np

a = np.array([1,2,3])

b = np.array([4,5,6])

print(np.concatenate([a,b]))

#Adjunto imagen de codigo + salida 

<img width="481" height="192" alt="image" src="https://github.com/user-attachments/assets/d43632ff-fee9-4513-a957-1ce09ca08643" />

#Operaciones Basicas 

u = np.array([10, 20, 30, 40])

v = np.array([1, 2, 3, 4])

print("Suma:", u + v)

print("Resta:", u - v)

print("Multiplicación:", u * v)

print("División:", u / v)

print("\nBroadcasting (u + 10):", u + 10)

M = np.arange(6).reshape(2, 3)

print("\nMatriz M:\n", M)

print("\nM + 100:\n", M + 100)

#adjunto imagen de  codigo + salida.

<img width="256" height="405" alt="image" src="https://github.com/user-attachments/assets/dad94f6b-bc1d-4254-af24-2f33caab9d7d" />









