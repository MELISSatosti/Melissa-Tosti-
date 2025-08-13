# Melissa-Tosti-
•🎓 ***universitaria*** em análise desenvolvimento de sistemas 

•📚 cursando ***ml e ia***

•🤸🏽‍♀️ amo esportes

•💻 atualmente focada em:


<img width="48" height="48" src="https://img.icons8.com/color/48/python--v1.png" alt="python--v1"/> <img width="64" height="64" src="https://img.icons8.com/hatch/64/xbox-r.png" alt="xbox-r"/> <img width="48" height="48" src="https://img.icons8.com/color/48/power-bi.png" alt="power-bi"/>


![Anurag's GitHub stats]
advinha.py 
```markdown
#import random

def adivinha_numero():
    print("Bem-vindo ao jogo de adivinhação de números!")
    numero_secreto = random.randint(1, 100)
    tentativas = 0
    
    while True:
        palpite = int(input("Adivinhe um número entre 1 e 100: "))
        tentativas += 1
        
        if palpite < numero_secreto:
            print("Muito baixo! Tente novamente.")
        elif palpite > numero_secreto:
            print("Muito alto! Tente novamente.")
        else:
            print(f"Parabéns! Você adivinhou o número {numero_secreto} em {tentativas} tentativas.")
            break

adivinha_numero()
