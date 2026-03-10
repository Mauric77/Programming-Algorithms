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




lista 2


Exercício 01
n1 = float(input("Digite o primeiro número: "))
n2 = float(input("Digite o segundo número: "))
if n1 > n2:
    print("O maior número é:", n1)
else:
    print("O maior número é:", n2)


Exercício 02


num = float(input("Digite um número: "))

if num >= 0:
    print("Positivo")
else:
    print("Negativo")
Exercício 03
letra = input("Digite F ou M: ").upper()

if letra == "F":
    print("F - Feminino")
elif letra == "M":
    print("M - Masculino")
else:
    print("Sexo Inválido")
Exercício 04
letra = input("Digite uma letra: ").lower()

if letra in "aeiou":
    print("Vogal")
else:
    print("Consoante")
Exercício 05
nota1 = float(input("Nota 1: "))
nota2 = float(input("Nota 2: "))

media = (nota1 + nota2) / 2

if media == 10:
    print("Aprovado com Distinção")
elif media >= 7:
    print("Aprovado")
else:
    print("Reprovado")
Exercício 06
n1 = float(input("Número 1: "))
n2 = float(input("Número 2: "))
n3 = float(input("Número 3: "))

if n1 >= n2 and n1 >= n3:
    print("Maior:", n1)
elif n2 >= n1 and n2 >= n3:
    print("Maior:", n2)
else:
    print("Maior:", n3)
Exercício 07
n1 = float(input("Número 1: "))
n2 = float(input("Número 2: "))
n3 = float(input("Número 3: "))

maior = max(n1, n2, n3)
menor = min(n1, n2, n3)

print("Maior:", maior)
print("Menor:", menor)
Exercício 08
p1 = float(input("Preço produto 1: "))
p2 = float(input("Preço produto 2: "))
p3 = float(input("Preço produto 3: "))

menor = min(p1, p2, p3)

print("Você deve comprar o produto que custa:", menor)
Exercício 09
n1 = float(input("Número 1: "))
n2 = float(input("Número 2: "))
n3 = float(input("Número 3: "))

lista = [n1, n2, n3]
lista.sort(reverse=True)

print("Ordem decrescente:", lista)
Exercício 10
turno = input("Digite o turno (M/V/N): ").upper()

if turno == "M":
    print("Bom Dia!")
elif turno == "V":
    print("Boa Tarde!")
elif turno == "N":
    print("Boa Noite!")
else:
    print("Valor Inválido!")
Exercício 11
salario = float(input("Digite o salário: "))

if salario <= 280:
    percentual = 20
elif salario <= 700:
    percentual = 15
elif salario <= 1500:
    percentual = 10
else:
    percentual = 5

aumento = salario * percentual / 100
novo_salario = salario + aumento

print("Salário antes do reajuste:", salario)
print("Percentual de aumento:", percentual, "%")
print("Valor do aumento:", aumento)
print("Novo salário:", novo_salario)
Exercício 12
valor_hora = float(input("Valor da hora: "))
horas = float(input("Horas trabalhadas: "))

salario_bruto = valor_hora * horas

if salario_bruto <= 900:
    ir = 0
elif salario_bruto <= 1500:
    ir = salario_bruto * 0.05
elif salario_bruto <= 2500:
    ir = salario_bruto * 0.10
else:
    ir = salario_bruto * 0.20

inss = salario_bruto * 0.10
fgts = salario_bruto * 0.11
sindicato = salario_bruto * 0.03

descontos = ir + inss + sindicato
salario_liquido = salario_bruto - descontos

print("Salário Bruto:", salario_bruto)
print("IR:", ir)
print("INSS:", inss)
print("FGTS:", fgts)
print("Total de descontos:", descontos)
print("Salário Líquido:", salario_liquido)
Exercício 13
dia = int(input("Digite um número de 1 a 7: "))

dias = ["Domingo","Segunda","Terça","Quarta","Quinta","Sexta","Sábado"]

if 1 <= dia <= 7:
    print(dias[dia-1])
else:
    print("Valor inválido")
Exercício 14
nota1 = float(input("Nota 1: "))
nota2 = float(input("Nota 2: "))

media = (nota1 + nota2) / 2

if media >= 9:
    conceito = "A"
elif media >= 7.5:
    conceito = "B"
elif media >= 6:
    conceito = "C"
elif media >= 4:
    conceito = "D"
else:
    conceito = "E"

print("Notas:", nota1, nota2)
print("Média:", media)
print("Conceito:", conceito)

if conceito in ["A","B","C"]:
    print("APROVADO")
else:
    print("REPROVADO")
Exercício 15
a = float(input("Lado 1: "))
b = float(input("Lado 2: "))
c = float(input("Lado 3: "))

if a + b > c and a + c > b and b + c > a:
    if a == b == c:
        print("Triângulo Equilátero")
    elif a == b or a == c or b == c:
        print("Triângulo Isósceles")
    else:
        print("Triângulo Escaleno")
else:
    print("Não forma triângulo")
Exercício 16
import math

a = float(input("Digite A: "))

if a == 0:
    print("Não é equação de segundo grau")
else:
    b = float(input("Digite B: "))
    c = float(input("Digite C: "))

    delta = b**2 - 4*a*c

    if delta < 0:
        print("Não possui raízes reais")
    elif delta == 0:
        x = -b/(2*a)
        print("Uma raiz:", x)
    else:
        x1 = (-b + math.sqrt(delta))/(2*a)
        x2 = (-b - math.sqrt(delta))/(2*a)
        print("Duas raízes:", x1, x2)
Exercício 17
ano = int(input("Digite um ano: "))

if (ano % 4 == 0 and ano % 100 != 0) or (ano % 400 == 0):
    print("Ano bissexto")
else:
    print("Não é bissexto")
Exercício 18
data = input("Digite a data (dd/mm/aaaa): ")

d,m,a = map(int,data.split("/"))

if 1 <= d <= 31 and 1 <= m <= 12 and a > 0:
    print("Data válida")
else:
    print("Data inválida")
Exercício 19
num = int(input("Digite um número menor que 1000: "))

centena = num // 100
dezena = (num % 100) // 10
unidade = num % 10

print(centena,"centenas,",dezena,"dezenas e",unidade,"unidades")
Exercício 20
n1 = float(input("Nota 1: "))
n2 = float(input("Nota 2: "))
n3 = float(input("Nota 3: "))

media = (n1+n2+n3)/3

if media == 10:
    print("Aprovado com Distinção",media)
elif media >= 7:
    print("Aprovado",media)
else:
    print("Reprovado",media)
Exercício 21
valor = int(input("Valor do saque: "))

if valor < 10 or valor > 600:
    print("Valor inválido")
else:
    n100 = valor // 100
    valor %= 100

    n50 = valor // 50
    valor %= 50

    n10 = valor // 10
    valor %= 10

    n5 = valor // 5
    valor %= 5

    n1 = valor

    print("Notas 100:",n100)
    print("Notas 50:",n50)
    print("Notas 10:",n10)
    print("Notas 5:",n5)
    print("Notas 1:",n1)
Exercício 22
num = int(input("Digite um número: "))

if num % 2 == 0:
    print("Par")
else:
    print("Ímpar")
Exercício 23
num = float(input("Digite um número: "))

if num == int(num):
    print("Inteiro")
else:
    print("Decimal")
Exercício 24
n1 = float(input("Número 1: "))
n2 = float(input("Número 2: "))

op = input("Operação (+ - * /): ")

if op == "+":
    res = n1+n2
elif op == "-":
    res = n1-n2
elif op == "*":
    res = n1*n2
elif op == "/":
    res = n1/n2

print("Resultado:",res)

if res % 2 == 0:
    print("Par")
else:
    print("Ímpar")

if res >= 0:
    print("Positivo")
else:
    print("Negativo")

if res == int(res):
    print("Inteiro")
else:
    print("Decimal")
Exercício 25
pontos = 0

for i in range(5):
    resp = input("Responda s/n: ")
    if resp.lower() == "s":
        pontos += 1

if pontos == 2:
    print("Suspeita")
elif 3 <= pontos <= 4:
    print("Cúmplice")
elif pontos == 5:
    print("Assassino")
else:
    print("Inocente")
Exercício 26
litros = float(input("Litros: "))
tipo = input("A-Álcool G-Gasolina: ").upper()

if tipo == "A":
    preco = 1.9
    if litros <= 20:
        desc = 0.03
    else:
        desc = 0.05
else:
    preco = 2.5
    if litros <= 20:
        desc = 0.04
    else:
        desc = 0.06

total = litros * preco
desconto = total * desc

print("Valor a pagar:", total - desconto)
Exercício 27
morango = float(input("Kg morango: "))
maca = float(input("Kg maçã: "))

if morango <= 5:
    pm = 2.5
else:
    pm = 2.2

if maca <= 5:
    pa = 1.8
else:
    pa = 1.5

total = morango*pm + maca*pa
peso = morango + maca

if peso > 8 or total > 25:
    total *= 0.9

print("Valor a pagar:",total)


tipo = input("Tipo carne (F-File, A-Alcatra, P-Picanha): ").upper()
kg = float(input("Quantidade kg: "))
cartao = input("Cartão Tabajara? (s/n): ")

if tipo == "F":
    preco = 4.9 if kg <=5 else 5.8
elif tipo == "A":
    preco = 5.9 if kg <=5 else 6.8
else:
    preco = 6.9 if kg <=5 else 7.8

total = kg * preco

desconto = 0
if cartao.lower() == "s":
    desconto = total * 0.05

print("Tipo:",tipo)
print("Quantidade:",kg)
print("Total:",total)
print("Desconto:",desconto)
print("Valor a pagar:",total-desconto)
