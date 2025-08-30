# Actividad 2 – Pandas.
#filtros

import pandas as pd

#Crear un DataFrame

data = {
    "Nombre": ["Ana", "Luis", "Marta", "Pedro"],
    "Edad": [23, 30, 18, 25],
    "Ciudad": ["Bogotá", "Medellín", "Cali", "Bogotá"]
}

df = pd.DataFrame(data)

#Filtrar personas mayores de 20 años

print(df[df["Edad"] > 20])

#Adjunto imagen de codigo + salida

<img width="352" height="331" alt="image" src="https://github.com/user-attachments/assets/81fbf7ba-4d11-4db0-b0b3-5f3d620f5f27" />

#GroupBy (agrupamiento de datos)

#Agrupar por ciudad y calcular promedio de edad

print(df.groupby("Ciudad")["Edad"].mean())

# Adjunto imagen de codigo + salida

<img width="360" height="129" alt="image" src="https://github.com/user-attachments/assets/5ef3fdbb-8e19-4a77-8ba0-d4eeb621d1f1" />

# Merge/Join (unir DataFrames)

# Crear dos DataFrames

notas = pd.DataFrame({
    "Nombre": ["Ana", "Luis", "Marta"],
    "Nota": [4.5, 3.8, 4.9]
})

#Unir con df usando la columna "Nombre"

df_merge = pd.merge(df, notas, on="Nombre", how="inner")

print(df_merge)

<img width="406" height="216" alt="image" src="https://github.com/user-attachments/assets/bcab8203-1fe1-4a46-a4b1-a757a95634f3" />

#Manejo de valores nulo

#Crear DataFrame con valores nulos

data_null = {
    "Nombre": ["Ana", "Luis", "Marta"],
    "Edad": [23, None, 19]
}
df_null = pd.DataFrame(data_null)

#Reemplazar nulos con valor fijo

print(df_null.fillna(0))

#Eliminar filas con valores nulos

print(df_null.dropna())

<img width="291" height="323" alt="image" src="https://github.com/user-attachments/assets/075ac2a6-de1e-4c5d-8656-0def7230e2eb" />

#Exportación e importación de datos

# Importar desde CSV

df_importado = pd.read_csv("personas.csv")

print(df_importado)

<img width="353" height="217" alt="image" src="https://github.com/user-attachments/assets/9af1f844-72dd-431b-a98b-5123e075069a" />

