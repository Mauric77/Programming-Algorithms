# Programming-Algorithms
Desafios

# Programming-Algorithms
#Desafios lista 1   Lista de Exercícios – Estrutura Sequencial
#Respostas

#1
input (' Alô Mundo!!!!')

#2
n = input( 'digite um numero:')
print ('o numero informado foi : {}' .format (n))

#3
n1 = int(input("digite um numero: "))
n2 = int(input("digite outro numero: "))
s = n1 + n2
print (' a soma de {} + {} é igual a {}' .format (n1, n2, s))

#4
nota1 = float(input("Digite a primeira nota: "))
nota2 = float(input("Digite a segunda nota: "))
nota3 = float(input("Digite a terceira nota: "))
nota4 = float(input("Digite a quarta nota: "))
media = (nota1 + nota2 + nota3 + nota4)/4
print('A média das 4 notas é:   {:.2f}' .format( nota1, nota2, nota3, nota4, media))


#5
metros= float(input('digite quantos metros: '))
centimetros = metros*100
print( ' o valor em centimetros é {}' .format(centimetros))


#6
import math
raio = float(input("Digite o raio do círculo: "))
area = math.pi * raio ** 2
print("Área do círculo:", area


#7
lado = float(input("Digite o lado do quadrado: "))
area = lado ** 2
dobro = area * 2
print("Área do quadrado:", area)
print("Dobro da área:", dobro)

#8
valor_hora = float(input("Quanto você ganha por hora? "))
horas_mes = float(input("Quantas horas trabalhou no mês? "))
salario = valor_hora * horas_mes
print("Salário do mês: R$", salario)

#9
f = float(input("Digite a temperatura em Fahrenheit: "))
c = 5 * ((f - 32) / 9)
print("Temperatura em Celsius:", c)


#10
c = float(input("Digite a temperatura em Celsius: "))
f = (c * 9/5) + 32
print("Temperatura em Fahrenheit:", f)


#11
n1 = int(input("Digite o primeiro número inteiro: "))
n2 = int(input("Digite o segundo número inteiro: "))
n3 = float(input("Digite um número real: "))
a = (2 * n1) * (n2 / 2)
b = (3 * n1) + n3
c = n3 ** 3
print("Produto do dobro do primeiro com metade do segundo:", a)
print("Soma do triplo do primeiro com o terceiro:", b)
print("Terceiro elevado ao cubo:", c)


#12
gb = float(input("Digite o valor em Gigabytes: "))
mb = gb * 1024
print("Valor em Megabytes:", mb)


#13
gb = float(input("Digite o valor em Gigabytes: "))
mb = gb * 1024
kb = mb * 1024
print("Megabytes:", mb)
print("Kilobytes:", kb)


# 14
peso = float(input("Digite o peso dos peixes (kg): "))

limite = 50

if peso > limite:
excesso = peso - limite
multa = excesso * 4
else:
excesso = 0
multa = 0

print("Excesso:", excesso, "kg")
print("Multa: R$", multa)


#15

valor_hora = float(input("Valor ganho por hora: "))
horas = float(input("Horas trabalhadas no mês: "))

salario_bruto = valor_hora * horas

ir = salario_bruto * 0.11
inss = salario_bruto * 0.08
sindicato = salario_bruto * 0.05

descontos = ir + inss + sindicato
salario_liquido = salario_bruto - descontos

print("Salário bruto: R$", salario_bruto)
print("Desconto IR: R$", ir)
print("Desconto INSS: R$", inss)
print("Desconto Sindicato: R$", sindicato)
print("Salário líquido: R$", salario_liquido){}' .format (n1, n2, s))
