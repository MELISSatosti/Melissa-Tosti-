# Melissa-Tosti-
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=melissatosti&hide=contribs,prs)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&size_weight=0.5&count_weight=0.5)

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
