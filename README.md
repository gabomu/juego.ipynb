# juego.ipynb
import random
numero_random = random.randint(1, 30)
print(f"valor seleccionado {numero_random}")

for i in range(3):


  valor_elegido = input("ingresa valor")
  print(f"el valor ingresado es {valor_elegido}")
  valor_elegido = int(valor_elegido)

  if numero_random < valor_elegido: # numero al azar es menor al numero seleccionado 
    print("menor que ")

  if valor_elegido < numero_random: # numero  al azar es mayor al numero seleccionado 
    print("mayor que ")   

  if valor_elegido == numero_random: # numero al azar es igual al numero seleccionado 
    print("Ganaste")    

  break
