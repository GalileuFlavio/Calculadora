# Calculadora
Calculadora de IMC em Python


def calcular_imc(peso, altura):
    imc = peso / (altura ** 2)
    return imc

peso = float(input("Digite o seu peso em kg: "))
altura = float(input("Digite a sua altura em metros: "))

resultado_imc = calcular_imc(peso, altura)
print("Seu IMC é:", resultado_imc)
