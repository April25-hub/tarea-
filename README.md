# tarea-
Arzaba_Diaz_April_3W
# Funcion para obtener el menor de dos numeros
def obtener_menor(num1, num2):
    """
    
    Esta funcion recibe dos numeros y retorna el menor de ellos.
    
    """
    
    if num1 < num2:
    
        return num1
    else
    :
    
        return num2



# Funcion para sumar dos numeros

def sumar_numeros(num1, num2):

    """
    
    Esta funcion recibe dos numeros y retorna su suma.
    
    """
    return num1 + num2


# Captura de datos

def main():

    # Leer el primer numero
    
    valor1 = float(input("Ingresa el primer numero: "))
    
    # Leer el segundo numero
    
    valor2 = float(input("Ingresa el segundo numero: "))



    # Determinar y mostrar el menor
    
    menor = obtener_menor(valor1, valor2)
    
    print(f"El menor de los dos numeros es: {menor}")



    # Sumar los dos numeros y mostrar el resultado
    
    suma = sumar_numeros(valor1, valor2)
    print(f"La suma de los dos numeros es: {suma}")



# Llamar a la funcion principal

if __name__ == "__main__":

    main()
    ![image](https://github.com/user-attachments/assets/42d5b9ba-b5a8-426b-8e4f-0208dd825db0)



  
