# 🛠Calculadora Python
(Atividade realizada durante o curso AWS Cloud)

## Passos para produção:
- Apresentar a tabela de possibilidades de operações para o usuário
- Solicitar que o usuário escolha uma opção
- Armazenar a resposta
- Perguntar ao usuário os números da operação
- Armazenar a resposta
- Imprimir o resultado da operação realizada na tela

## Funcão de limpar tela:
import os

def limparTela():

    os.system("cls" if os.name == "nt" else "clear")

