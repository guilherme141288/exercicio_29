# exercicio_29

#Calculating price of a trip according to distance


dist = int( input ('\033[0;30;47mQual a distância de sua viagem?  \033[m'))
print ('voce esta prestes a comecar uma viagem de {}km' .format (dist))

if dist <= 150:
    print ('E o preco de sua passagem será de R${}' .format(dist / 2))
else:
    print ('E o preco de sua passagem será de R${}' .format((dist - 150) * 1/4 + 75))
