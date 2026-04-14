Foi feita solicitado a IA que fizesse uma calculadora em Java, que tivesse interface gráfica.
Esse foi o prompt utilizado: Faça uma calculadora básica, que contenha as 4 operações, faça usando python.
Esse foi o resultado obtido:
def soma(num1, num2):
    return a + b

def subtracao(a, b):
    return a - b

def multiplicacao(a, b):
    return a * b

def divisao(a, b):
    if b == 0:
        return "Erro: divisão por zero!"
    return a / b

print("=== Calculadora Básica ===")

num1 = float(input("Digite o primeiro número: "))
num2 = float(input("Digite o segundo número: "))

print("\nEscolha a operação:")
print("1 - Soma")
print("2 - Subtração")
print("3 - Multiplicação")
print("4 - Divisão")

opcao = input("Digite a opção (1/2/3/4): ")

if opcao == "1":
    print("Resultado:", soma(num1, num2))
elif opcao == "2":
    print("Resultado:", subtracao(num1, num2))
elif opcao == "3":
    print("Resultado:", multiplicacao(num1, num2))
elif opcao == "4":
    print("Resultado:", divisao(num1, num2))
else:
    print("Opção inválida!")

Segue print da interação:

[Atividade 01 - Unidade II.pdf](https://github.com/user-attachments/files/26730831/Atividade.01.-.Unidade.II.pdf)
