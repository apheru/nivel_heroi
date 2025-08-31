# 🦸‍♂️ Desafio Classificador de Nível de Herói  

Este projeto foi desenvolvido como parte de uma atividade prática da **[DIO.me](https://www.dio.me/)**, com o objetivo de praticar conceitos fundamentais de **Python**, além de consolidar o uso de **Git** e **GitHub** no fluxo de desenvolvimento.  

---

## 📖 Descrição  

O programa tem como objetivo classificar o **nível de um herói** com base em sua quantidade de experiência (**XP**).  
De acordo com o valor informado, o herói recebe uma classificação dentro da hierarquia:  

- **Ferro** → XP menor que 1.000  
- **Bronze** → 1.001 a 2.000  
- **Prata** → 2.001 a 5.000  
- **Ouro** → 5.001 a 7.000  
- **Platina** → 7.001 a 8.000  
- **Ascendente** → 8.001 a 9.000  
- **Imortal** → 9.001 a 10.000  
- **Radiante** → XP maior ou igual a 10.001  

---

## 💻 Código  

```python
nome_heroi = "Apheru"
xp_heroi = 6000

if xp_heroi < 1000:
    nivel = "Ferro"
elif xp_heroi >= 1001 and xp_heroi <= 2000:
    nivel = "Bronze"
elif xp_heroi >= 2001 and xp_heroi <= 5000:
    nivel = "Prata"
elif xp_heroi >= 5001 and xp_heroi <= 7000:
    nivel = "Ouro"
elif xp_heroi >= 7001 and xp_heroi <= 8000:
    nivel = "Platina"
elif xp_heroi >= 8001 and xp_heroi <= 9000:
    nivel = "Ascendente"
elif xp_heroi >= 9001 and xp_heroi <= 10000:
    nivel = "Imortal"
else:
    nivel = "Radiante"

print(f"O Herói de nome {nome_heroi} está no nível de {nivel}")

```
---

## 🚀 Exemplo de Saída

```
O Herói de nome Apheru está no nível de Ouro
```

---

🛠️ Tecnologias

Python 3 – Lógica e implementação

Git – Controle de versão

GitHub – Hospedagem e compartilhamento do repositório

---
📌 Autor

Desenvolvido por Lucas (Apheru)

Projeto feito como parte do Bootcamp da DIO.me.