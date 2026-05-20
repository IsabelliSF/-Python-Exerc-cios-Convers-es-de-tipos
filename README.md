"# -Python-Exerc-cios-Convers-es-de-tipos" 
# EX1
# O usuário digitou "25" como sua idade em um formulário.
# Converta para inteiro e calcule a idade que ele terá
# daqui a 5 anos.
print("EXERCÍCIO 1")
idade = int(25)
idade_final = idade + 5
print("Idade Final: ", idade_final)
# EX2
# Converta o número de ponto flutuante 7.999
# para inteiro e observe o resultado.
print("EXERCÍCIO 2")
numero = int(7.999)
print(type(numero))
# EX 3
# Converta a string "-3.14" para float
# e multiplique o resultado por 2.
print("EXERCÍCIO 3")
num = float("-3.14")
resultado = num * 2
print(resultado)
# EX4
# Tente converter a string "cento e vinte"
# para inteiro e observe o que acontece.
print("EXERCÍCIO 4")
valor1 =  "cento e vinte"
print(valor1)
print(type(valor1))
valor2 = int("120")
print('int("120"):', valor2)
print("tipo:", type(valor2))
# EX5
# Converta o número 42 para string
# e concatene com a palavra " respostas".
print("EXERCÍCIO 5")
numero1 = str(42)
print(numero1, "respostas.")
# EX6
# Use a função complex() para criar
# um número complexo com parte real 3
# e parte imaginária 5.
print("EXERCÍCIO 6")
numerocomplexo = 3 + 5j
print(numerocomplexo.real)
# EX7
# Converta o número 0 para booleano
# e mostre o resultado.
print("EXERCÍCIO 7")
zero = True
print("Resultado: ", zero)
# EX8
# Converta o número -100 para booleano
# e mostre o resultado.
print("EXERCÍCIO 8")
numero2 = -100
resultado = bool(numero2)
print("Resultado: ", numero2)
# EX9
# Converta o número 3.1415 para inteiro
# e depois para string, tudo em uma única linha.
print ("EXERCÍCIO 9")
numero3 = str(int(3.1415))
print(numero3)
# EX10
# Some um número inteiro (5) com um float (2.3)
# e verifique qual é o tipo do resultado.
print("EXERCÍCIO 10")
numerointeiro = 5
resultado1 = numerointeiro + 3,14
print(type(resultado))
