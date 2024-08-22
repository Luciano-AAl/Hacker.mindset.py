# Hacker.mindset.py
ATIVIDADE DA AULA DIA 15/8 "PYTHON PARA HACKERS"

try:     

    with open ("teste.txt" , "r") as arquivo: 

    dados = arquivo.readlines() 

except fileNotFoundError: 

    print("Arquivo não existente!") 

except: 

    print("erro") 


    


