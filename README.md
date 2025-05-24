
def soma (a, b):
    return a + b

def subtracao(a, b):
    return a - b

def multiplicacao(a, b):
    return a * b

def divisao(a, b):
    return a / b




from modulos_e_bibliotecas import *


while True:
        opcao = int(input('''
                    MENU:
                    digite 1 para somar
                    digite 2 para subtrair
                    digite 3 para multiplicar
                    digite 4 para dividir 
                    digite 5 para sair '''))
        
        num1 = int(input('digite um numero'))
        num2 = int(input('digite outro numero'))

        if opcao == 5:
             print('Saindo')
             break
        elif opcao == 1:
            print(soma(a=num1, b=num2))
        elif opcao == 2:
            print(subtracao(a=num1, b=num2))
        elif opcao == 3:
            print(multiplicacao(a=num1, b=num2))
        else:
            print(divisao(a=num1, b=num2))
