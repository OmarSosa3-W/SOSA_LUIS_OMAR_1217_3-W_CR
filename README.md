# SOSA_LUIS_OMAR_1217_3-W_CR
# PROGRAMA 1:
def max(a, b):
    return a if a > b else b

print(max(3, 7))  # Salida: 7

![image](https://github.com/user-attachments/assets/77507a9e-01fd-4a7c-859a-a7840e46e20e)
![image](https://github.com/user-attachments/assets/0a6ecf06-0ec0-46a6-88f5-0505740ea83f)

# PROGRAMA 2:
def max_de_tres(a, b, c):
    return max(max(a, b), c)

print(max_de_tres(3, 7, 5))  # Salida: 7

![image](https://github.com/user-attachments/assets/00898b04-0fd1-45f1-ab35-509df898cca8)
![image](https://github.com/user-attachments/assets/b8f3e9ad-9bdf-4c45-935c-323e55c53a41)

# PROGRAMA 3:
def longitud(cadena_o_lista):
    contador = 0
    for _ in cadena_o_lista:
        contador += 1
    return contador

print(longitud("Hola"))  # Salida: 4
print(longitud([1, 2, 3, 4]))  # Salida: 4

![image](https://github.com/user-attachments/assets/a11d28dd-2541-443d-bb20-b0d49600f428)
![image](https://github.com/user-attachments/assets/3637d8af-dc01-406a-92e1-744bb4e8408e)

# PROGRAMA 4:
def es_vocal(caracter):
    return caracter.lower() in 'aeiou'

print(es_vocal('a'))  # Salida: True
print(es_vocal('b'))  # Salida: False

![image](https://github.com/user-attachments/assets/9b8ed7b1-95c1-4718-9ec5-926ba61ab719)
![image](https://github.com/user-attachments/assets/6a05dd7b-9852-48dd-a7cf-f4c1ec606d7e)

# PROGRAMA 5:
def sum(lista):
    total = 0
    for num in lista:
        total += num
    return total

def multip(lista):
    resultado = 1
    for num in lista:
        resultado *= num
    return resultado

print(sum([1, 2, 3, 4]))  # Salida: 10
print(multip([1, 2, 3, 4]))  # Salida: 24

![image](https://github.com/user-attachments/assets/265005f3-d862-486b-adbd-4bd01c3f9bb6)
![image](https://github.com/user-attachments/assets/5c80918d-5be1-4408-a2d7-37335018bdd6)

# PROGRAMA 6:
def inversa(cadena):
    return cadena[::-1]

print(inversa("estoy probando"))  # Salida: "odnaborp yotse"

![image](https://github.com/user-attachments/assets/6f1195bc-9019-4ed8-ad90-a721e2b05c41)
![image](https://github.com/user-attachments/assets/86a5923c-f7cc-45bc-9b55-9398279abfbd)

# PROGRAMA 7:
def es_palindromo(cadena):
    cadena = cadena.replace(" ", "").lower()
    return cadena == cadena[::-1]

print(es_palindromo("radar"))  # Salida: True
print(es_palindromo("hola"))  # Salida: False

![image](https://github.com/user-attachments/assets/215387ca-5ec3-4124-a74e-00b75e689d58)
![image](https://github.com/user-attachments/assets/dcd5007a-5e4f-4819-a207-081808f60906)

# PROGRAMA 8:
def superposicion(lista1, lista2):
    for elem1 in lista1:
        for elem2 in lista2:
            if elem1 == elem2:
                return True
    return False

print(superposicion([1, 2, 3], [4, 5, 3]))  # Salida: True
print(superposicion([1, 2, 3], [4, 5, 6]))  # Salida: False

![image](https://github.com/user-attachments/assets/f505b5a7-853c-4050-ab4f-7c911ecf6caa)
![image](https://github.com/user-attachments/assets/257c4448-6925-4db3-a4c6-3d683ac7d405)

# PROGRAMA 9:
def generar_n_caracteres(n, caracter):
    return caracter * n

print(generar_n_caracteres(5, "x"))  # Salida:

![image](https://github.com/user-attachments/assets/506f3b6c-4419-47e2-9435-4480bc65e458)
![image](https://github.com/user-attachments/assets/d84b1951-34a6-46d8-b523-ba7a6aa5c6ae)

# PROGRAMA 10:
def procedimiento(lista):
    for numero in lista:
        print('*' * numero)

procedimiento([4, 9, 7])
#salida:

![image](https://github.com/user-attachments/assets/274642f3-8701-42e1-9b2b-74cfecfebbac)
![image](https://github.com/user-attachments/assets/fb0970cf-5a81-4d23-89cd-38d858564acf)
