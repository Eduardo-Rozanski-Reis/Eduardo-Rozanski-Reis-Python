# Eduardo-Rozanski-Reis-Python
numeros_pares = 0
numeros_impares = 0

for i in range(5):
    entrada = input('Digite um numero: ')

    numero = int(entrada)

    if numero % 2 == 0:
        contador_pares += 1
    else:
        contador_impares += 1

print('Quantidade pares:', numeros_pares)
print('Quantidade impares:', numeros_impares)
