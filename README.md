# Ponto-da-carne
Programa em Python que identifica o ponto da carne de acordo com a temperatura!

tempcarne=input('Qual e a temperatura da carne?')
tempcarne=int(tempcarne)


if  tempcarne >=48 and tempcarne<=53:
  print('A carne está selada')
elif tempcarne>=54 and tempcarne<=59:
  print('A carne está ao ponto para o mal')
elif tempcarne>=60 and tempcarne<=64:
  print('A carne está ao ponto')
elif tempcarne>=65 and tempcarne<=70:
  print('A carne está ao ponto para o bem')
elif tempcarne >= 71 and tempcarne<=79:
  print('Bem passada')
elif tempcarne <=47:
  print('Cozinhar um pouco mais!')
elif tempcarne == 80:
  print('Você queimou a carne')

else:
  print('Sua carne está super queimada!')
