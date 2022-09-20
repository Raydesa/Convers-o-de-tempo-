# Convers-o-de-tempo-
segundos = int(input("Digite o número de segundos menor que 1000: "))
tempo1 = segundos // 60
tempo2 = segundos % 60

print("O tempo total é de " + str(tempo1) + "m e " + str(tempo2) + "s")
