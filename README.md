# Python_exceptions
Exemplos exceptions em Python para Tratamento de Erros

![image](https://user-images.githubusercontent.com/82824988/119206327-3e0c5b00-ba71-11eb-856d-1595bce9d1c3.png)

# print(divisor.resultado)
def dividir(dividendo, divisor):
    return dividendo/divisor

def testa_divisao(divisor):
    try:
        resultado = dividir(10,divisor)
        print(f"O resultado da divisão de 10 por {divisor} é {resultado}")
    except ZeroDivisionError:
        print ("Erro de divisão por 0 tratado")

try:
    testa_divisao(0)
except AttributeError:
    print("Erro de atributo tratado")

print("Programa encerrado")
