# Angel-Alejandro-Sepulveda-Gonzalez-3W-1215-pr13

# Imprime el nombre completo, el grupo y el número en pantalla

print("Angel Alejandro Sepulveda Gonzalez,3W,1215")

# Define una función recursiva llamada tri_recursion que toma un argumento k

# La función calcula la suma acumulativa de todos los números enteros desde k hasta 0

def tri_recursion(k):

  if k > 0:
  
  resultado = k + tri_recursion(k - 1)  # Realiza una llamada recursiva
  
  print(resultado)  # Imprime el resultado acumulado en cada paso
  
  else:
  
  resultado = 0  # Caso base: cuando k es 0
   
  return resultado  # Devuelve el resultado acumulado

# Mensaje informativo antes de realizar la llamada a la función

print("\n\nResultados de ejemplo de recursividad:")

# Llama a la función tri_recursion con el argumento 6

tri_recursion(6)

![image](https://github.com/user-attachments/assets/fa42f36f-6cd4-4f5a-8d17-c3caa0b5326f)
![image](https://github.com/user-attachments/assets/98a72f9e-7dac-4780-9bc3-75aec26eb80c)
![image](https://github.com/user-attachments/assets/59fdcd81-6dc5-4faf-ab88-cc8f8c104fbc)


