# Practica-3-2o-Parcial-Luis-Daniel-Molina-Leyva-1201-3W

#Actividad1

#Presentacion
print("Practica 3 2o Parcial de Luis Daniel Molina Leyva 1201 3W")

print(" ")
#Muestra lo escrito
thisdict = {
'Euro':'€',
'Dollar':'$', 
'Yen':'¥'
}
print(thisdict)
![image](https://github.com/user-attachments/assets/b17fac56-f709-494e-94d5-3837676e5090)

#Actividad2

#Presentacion
print("Practica 3 2o Parcial de Luis Daniel Molina Leyva 1201 3W")

print(" ")

#Permite escribir
x = input("Introducir tu nombre: ")
y = input("Introducir tu edad: ")
z = input("Introducir tu direccion: ")
w = input("Introducir tu numero de telefono: ")

print(" ")

#Muestra lo escrito
thisdict = {
'Nombre':x,
'Edad':y, 
'Direccion':z,
'Telefono':w
}
print(thisdict)
![image](https://github.com/user-attachments/assets/5d06a04b-df4f-483f-87f9-3dfe1d9abc3d)

#Actividad3

#Presentacion
print("Practica 3 2o Parcial de Luis Daniel Molina Leyva 1201 3W")

print(" ")

# Precios de las frutas
frutas = {'1': 20, '2': 15, '3': 23}

# Mostrar opciones
print("1: Manzana - $20/Kg\n2: Plátano - $15/Kg\n3: Naranjas - $23/Kg")

# Entrada del usuario
opcion = input("Elige una fruta (1, 2 o 3): ")
kilos = float(input("Kilos deseados: "))

# Calcular y mostrar el precio total
if opcion in frutas:
    print("Precio total: $", frutas[opcion] * kilos)
else:
    print("Opción no válida.")
![image](https://github.com/user-attachments/assets/6dd74a0c-804b-42f4-b30d-f8ebe95eea59)


