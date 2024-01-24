# quiz_proz
print(" Teste de Inglês - Nivelamento de Turmas - Boa Sorte! ")
answer_quiz = input(" Você está preparado(a)? Podemos começar o Teste S/N? ")

if answer_quiz != "S":
   quit()

score = 0   
   
print(" Iniciando teste Let's Go! .......") 
print(" Como se escreve reunião em Inglês ? \n (A) - meenting \n (B) - treffen \n (C) - ontmoenting \n")
answer_1 = input(" Resposta: ") 

if answer_1 == "A":
   print(" Correto! ")
   score = score + 1
else:
   print(" Incorreto! ") 

print(" Como se escreve nuvem em Inglês ? \n (A) - wolke \n (B) - cloud \n (C) - nuage \n")
answer_2 = input(" Resposta: ") 

if answer_2 == "B":
   print(" Correto! ")
   score = score + 1
else:
   print(" Incorreto! ")

print(" Como se escreve árvore em Inglês ? \n (A) - tree \n (B) - three \n (C) - baum \n")
answer_3 = input(" Resposta: ") 

if answer_3 == "A":
   print(" Correto! ")
   score = score + 1
else:
   print(" Incorreto! ") 

print(" Como se escreve negócio em Inglês ? \n (A) - commerciale \n (B) - geschfat \n (C) - business \n")
answer_4 = input(" Resposta: ") 

if answer_4 == "C":
   print(" Correto! ")
   score = score + 1
else:
   print(" Incorreto! ")

print(f" Final do Quiz - Pontuação: {score}/4")    
