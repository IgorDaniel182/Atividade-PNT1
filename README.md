# Atividade-PNT1
Uma atividade da escola técnica estadual porto digital, que contem exercícios e desafios em python
print('Olá ETE PORTO DIGITAL')

numero = input('me diga um numero:')
print('O numero informado é:', numero, 'acertei?')

n1 = int(input('Digite um número:'))
n2 = int(input('Digite mais um número:'))
s = n1+n2
print('A soma vale', s)

n1 = float(input('Digite sua primeira nota:'))
n2 = float(input('Digite sua segunda nota:'))
n3 = float(input('Digite sua terceira nota:'))
n4 = float(input('Digite sua quarta nota:'))
s = n1+n2+n3+n4
d = s/4
print('A sua nota é:', d)

n1 = float(input('Digite um numero em metros para trasnformar para centimetros:'))
t = n1*100
print('O seu numero transformado em centímetros é:', t)

n1 = float(input('Digite o raio do circulo que você esta calculando'))
m = n1*2*3.14
print('A area desse circulo é:', m,)

n1 = float(input('Digite a medida do lado do seu quadrado:'))
m = n1*2*2
print('O resultado de 2 quadrados com mesma área que obtivemos é:', m)

n1 = float(input('Digite o quanto de dinheiro você ganha em uma hora de trabalho:'))
n2 = float(input('Digite quantas horas você trabalha em um mês:'))
m = n1*n2
print('O dinheiro que você ganhará no final do mês é de:', m)

n1 = float(input('Digite um numero'))
if n1 > 0:
    print('Este numero é positivo')
else:
    print('Este numero é negativo')
