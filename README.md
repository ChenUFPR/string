#exercício para codificar o nome em formato de escada vertical
nome = input("Nome=")
for x in range(0,len(nome)):
  print(nome[0:x+1], end="\n")
