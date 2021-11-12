# Introducao-Computacao

#Faça um programa que leia um número inteiro e mostre na tela o seu sucessor e o seu antecessor.
from time import sleep

n = int(input("Digite um número: "))
print("Analisando o número {}...".format(n))
sleep(1)
print("Antecessor: {}".format(n-1))
print("Sucessor: {}".format(n+1))


#Faça um programa que leia um número e mostre na tela o dobro deste número, este número elevado ao cubo e a raiz quadrada do número digitado
print('=====DESAFIO 06=====\n')
print('Crie um algoritmo que leia um número e mostre o seu dobro, triplo e raiz quadrada\n')
num = int(input('Digite um número:'))
dob = num * 2
tri = num * 3
rai = num**(1/2)
print('\nO número escolhido foi: {}, o seu dobro é: {}, o seu triplo é: {} e o sua raiz é: {}'.format(num, dob, tri, rai))

#Faça um programa que leia um número e apresente a sua tabuada.
num = int(input('Digite um número:'))
counter = 0
tab = 10
while counter <= tab:
    res = num * counter #estando fora do loop a conta não funciona
    print('{} * {} = {}'.format(num, counter, res))
    counter += 1
