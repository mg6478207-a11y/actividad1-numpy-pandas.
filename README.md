**C) Pandas – Creación y manipulación de DataFrames y Series**

  import pandas as pd
  
  #Series
  
  s = pd.Series ([10,20,30], index=["a","b","c"])
  
  print(s)
  
  
  #Series
  
  print(s["b"])
  
  <img width="506" height="272" alt="image" src="https://github.com/user-attachments/assets/70c7e37b-6fe1-422f-ba43-bba210d144fc" />

  #DataFrame
  
  df = pd.DataFrame({
  
      "Nombre":["Camilo","Maria","Nataly"],
      
      "Edad":[20,23,21]
  })
  
  print(df)
  
  
  #DataFrame
  
  print(df["Edad"])
  
  <img width="524" height="361" alt="image" src="https://github.com/user-attachments/assets/4e7cfdfa-58ed-4170-ae99-b7b649adc230" />

  
  #Cargar datos desde diccionario
  
  data = {"A":[1,2,3], "B":[4,5,6]}
  
  df2 = pd.DataFrame(data)
  
  print(df2)

  <img width="367" height="186" alt="image" src="https://github.com/user-attachments/assets/3550f4eb-08dd-4d47-adaa-8bb72f31d6cf" />





