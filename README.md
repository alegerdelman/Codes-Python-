# Codes-Python-
Codes that I did on python

1 - Band Generator
print ("Welcome to the Band Name Generator")
pet = input ("What is the name of your pet? ")
son = input("What is the name of your son? ")
print("You band name could be " + pet +  " " + son)


2 - Tip calculator
conta = float (input ("Qual o total da sua conta? R$ "))

porcentagem = int( input  ("Qual a porcentagem da gorjeta? 10 ou 12 ? "))

pessoas = int (input  ("Quantas pessoas comeram? "))


conta_inicial = (conta / pessoas * porcentagem / 100  )
conta_total = round(conta_inicial, 2)
print (f"Cada pessoa deve pagar {conta_total} reais ")




3 - Bmi calculator
altura = float (input ("Qual a sua altura? " ))

peso = float ( input("Qual o seu peso? " ))

imc = round(peso / altura **2)
if imc < 18.5:
print (f"Seu imc e {imc}")


4 - Game: Treasure hunt
print('''
*******************************************************************************
          |                   |                  |                     |
 _________|________________.=""_;=.______________|_____________________|_______
|                   |  ,-"_,=""     `"=.|                  |
|___________________|__"=._o`"-._        `"=.______________|___________________
          |                `"=._o`"=._      _`"=._                     |
 _________|_____________________:=._o "=._."_.-="'"=.__________________|_______
|                   |    __.--" , ; `"=._o." ,-"""-._ ".   |
|___________________|_._"  ,. .` ` `` ,  `"-._"-._   ". '__|___________________
          |           |o`"=._` , "` `; .". ,  "-._"-._; ;              |
 _________|___________| ;`-.o`"=._; ." ` '`."\` . "-._ /_______________|_______
|                   | |o;    `"-.o`"=._``  '` " ,__.--o;   |
|___________________|_| ;     (#) `-.o `"=.`_.--"_o.-; ;___|___________________
____/______/______/___|o;._    "      `".o|o_.--"    ;o;____/______/______/____
/______/______/______/_"=._o--._        ; | ;        ; ;/______/______/______/_
____/______/______/______/__"=._o--._   ;o|o;     _._;o;____/______/______/____
/______/______/______/______/____"=._o._; | ;_.--"o.--"_/______/______/______/_
____/______/______/______/______/_____"=.o|o_.--""___/______/______/______/____
/______/______/______/______/______/______/______/______/______/______/_____ /
*******************************************************************************
''')
print("Bem vindo a ilha do tesouro ")
print("A missao do jogo e achar o tesouro ")

direita_esquerda = input ("Quer ir para a direita ou para a esquerda? ")

if direita_esquerda == "direita":
        print("Voce caiu no buraco, game over")

else:
    print("Voce escolheu o caminho certo")
restartt = input("Deseja continuar ou esta com medo? ")
if restartt == "sim":
        print("ok, proxima fase")


nadar_esperar = input  ("Voce esta vendo um rio na sua frente, voce quer atravessa-lo nadando, ou vai esperar o barco? Digite nadando ou esperar ")
if nadar_esperar == "nadando":
    print (" Voce foi comido por um tubarao, game over")
else:
    print("Voce esperou o barco e conseguiu atravessar ")

restart = input("Deseja continuar, tem certeza?")
if restart == "sim":
    print("Ok, proxima fase")


portas = input("Voce esta vendo tres portas, vermelha, rouxa e a azul, qual voce escolhe?")

if portas == "vermelha":
    print("A sala esta pegando fogo, voce morreu")

elif portas == "roxa":
    print("a porta estava cheia de aranhas venenosas,e uma te picou e voce morreu, game over")
else:
    print("PARABENS!!!! VOCE ACHOU O TESOURO!!!")








5 - Odd or even 
number = int(input("Qual numero voce quer saber? "))
# 🚨 Don't change the code above 👆

#Write your code below this line 👇

if number % 2 == 0:
  print("Numero par ")
else: 
  print ("Numero impar ")



6 - Roller coaster

print("Bem vindo a montanha russa ! ")
height = float(input("Qual a sua altura "))
conta = 0
if height >= 1.50:
  print("Pode ir, mas pera ")
  idade = int(input("Qual a sua idade? "))
  if idade < 12 :
    conta = 5
    print("Seu bilhete custa R$5.00, pirralho ")
  elif idade <= 18:
    conta = 7
    print ( "Seu bilhete custa R$10.00")
  elif idade >=45 and idade <=55:
    print("Seu bilhete nao precisa pagar")

  else:
    conta = 12
    print ( "Seu bilhete custa R$ 12.00, quem mandou ser velho(a) ")
  fotos = input ("Voce vai querer fotos? S para sim e N para nao ")

  if fotos == "S":
    conta += 3

  print (f"Sua valor final e de R$ {conta}")




else:
  print("Vai n tampinha")



7 - Getting a order of a pizza with python


print("Bem vindo a pizzaria do Ale ! ")
valor = 0
size = input("Qual tamanho da pizza voce quer? P, M ou G?  ")
add_pepperoni = input("Voce quer frango? S para sim e N para nao ")
extra_cheese = input("Voce quer queijo extra?  S para sim e N para nao ")

if size == "P":
  print("Ok, pizza pequena")
  valor = 5

elif size == "M":
  print("Ok, pizza media")
  valor =7
else:
  print("Ok, pizza grande ")
  valor = 9

if add_pepperoni == "S":
  print("Com frango")
  valor = 11
else:
  print("Sem frango ")

if extra_cheese == "S":
    print("E com queijo extra  ")
    valor = 13
else:
    print("E sem queijo extra")

print (f"Sua conta final deu {valor}")







8 - Naval battle
row1 = ["⬜️","⬜️","⬜️"]
row2 = ["⬜️","⬜️","⬜️"]
row3 = ["⬜️","⬜️","⬜️"]
map = [row1, row2, row3]
print(f"{row1}\n{row2}\n{row3}")
position = input("Where do you want to put the treasure? ")

horizontal = int(position[0])
vertical = int(position[1])

selected_row = map[vertical - 1]
selected_row[horizontal - 1 ] = "X"


9 - Head or tails

import random
random_interger = random.randint (0, 1)
if random_interger == 0:
  print("Cara")
else:
  print("Coroa")




  10 - Rock, paper and scissors
pedra = ('''_______
---'   ____)
      (_____)
      (_____)
      (____)
---.__(___)''')

papel = ('''_
               _  / |
              / \ | | /\
               \ \| |/ /
                \ Y | /___
              .-.) '. `__/
             (.-.   / /
                 | ' |
                 |___|
                [_____]
            |     |''')

tesoura = ('''.-.  _
    | | / )
    | |/ /
   _|__ /_
  / __)-' )
  \  `(.-')
   > ._>-'
  / \/''')

possible_answer = [pedra, papel, tesoura]

import random
ppt = input("pedra, papel ou tesoura? ")
if ppt == "pedra":
    print('''_______
---'   ____)
      (_____)
      (_____)
      (____)
---.__(___)''')

elif ppt == "papel":
    print(''' _
               _  / |
              / \ | | /\
               \ \| |/ /
                \ Y | /___
              .-.) '. `__/
             (.-.   / /
                 | ' |
                 |___|
                [_____]
            |     |''')
else:
    print('''.-.  _
    | | / )
    | |/ /
   _|__ /_
  / __)-' )
  \  `(.-')
   > ._>-'
  / \/''')

num_answer = len(ppt)

random_answer = random.choice(possible_answer)

print(random_answer)






11 - Password generator
#Password Generator Project
import random
letters = ['a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'i', 'j', 'k', 'l', 'm', 'n', 'o', 'p', 'q', 'r', 's', 't', 'u', 'v', 'w', 'x', 'y', 'z', 'A', 'B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z']
numbers = ['0', '1', '2', '3', '4', '5', '6', '7', '8', '9']
symbols = ['!', '#', '$', '%', '&', '(', ')', '*', '+']

print("Bem vindo ao gerador de senha")
nr_letters= int(input("Quantas letras voce quer na sua senha?\n"))
nr_symbols = int(input(f"Quantos simbolos voce quer na sua senha?\n"))
nr_numbers = int(input(f"Quantos numeros voce quer na sua senha?\n"))

senha = ""

for letra in range (1, nr_letters + 1):
    senha+= random.choice(letters)

for letra in range(1, nr_symbols + 1):
    senha += random.choice(symbols)

    for letra in range (1, nr_numbers +1 ):
        senha += random.choice(numbers)
print(senha)



12 - Avarage Height
student_heights = input("Input a list of student heights ").split()
for n in range(0, len(student_heights)):
  student_heights[n] = int(student_heights[n])

total_height = 0
for height in student_heights:
  total_height += height
#print(total_height)

number_of_students = 0
for students in student_heights:
  number_of_students += 1
#print(number_of_students)

avarage_height = round(total_height / number_of_students)
print(f"A media de altura e de {avarage_height} ")





