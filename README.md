# jornadadoheroidioone
## Objetivo  Crie uma variável para armazenar o nome e a quantidade de experiência (XP) de um herói, 

# Crie a pasta e navegue até ela
mkdir heroi-nivel-classificador
cd heroi-nivel-classificador

# Crie o arquivo de código
echo "
# Classificador de nível de Herói
nome_heroi = input('Digite o nome do herói: ')
xp_heroi = int(input('Digite a quantidade de XP do herói: '))

if xp_heroi < 1000:
    nivel = 'Ferro'
elif 1001 <= xp_heroi <= 2000:
    nivel = 'Bronze'
elif 2001 <= xp_heroi <= 5000:
    nivel = 'Prata'
elif 5001 <= xp_heroi <= 7000:
    nivel = 'Ouro'
elif 7001 <= xp_heroi <= 8000:
    nivel = 'Platina'
elif 8001 <= xp_heroi <= 9000:
    nivel = 'Ascendente'
elif 9001 <= xp_heroi <= 10000:
    nivel = 'Imortal'
else:
    nivel = 'Radiante'

print(f'O Herói de nome {nome_heroi} está no nível de {nivel}')
" > classificador_heroi.py
