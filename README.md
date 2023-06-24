# Exercicio043.py


peso = float(input('Digite seu peso: '))
altura = float(input('Digite sua altura: '))
imc = peso / (altura**2)
if imc < 18.5:
    print('abaixo do peso ideal')
elif 18.5 <= imc < 25:
    print('Esta na faixa de peso ideal')
elif 25 <= imc < 30:
    print('esta com sobrepeso')
elif 30 <= imc < 40:
    print('esta com obesidade')
else:
    print('Obesidade morbida')
    
