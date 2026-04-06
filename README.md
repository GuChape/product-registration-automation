# Automação de Cadastro de Produtos com Python

## Descrição
Projeto de automação desenvolvido em Python para cadastro automático de produtos em sistema web, utilizando PyAutoGUI e leitura de dados com Pandas.

## Funcionalidades
- Automação de login em sistema web
- Leitura de dados de arquivo CSV
- Preenchimento automático de formulários
- Execução repetitiva para múltiplos registros

## Tecnologias utilizadas
- Python
- PyAutoGUI
- Pandas

## Estrutura do projeto
- `main.py`: script principal de automação
- `pegar_posicao.py`: captura coordenadas do mouse
- `produtos.csv`: base de dados

## Como executar
1. Instale as dependências:
pip install -r requirements.txt


2. Execute o script:
python main.py

## Problema resolvido
Automatiza o cadastro manual de produtos em sistemas web, reduzindo tempo e erros humanos.

## Observações
- As coordenadas do mouse podem variar conforme a resolução da tela
- Ajustes podem ser necessários para diferentes ambientes
- Use pegar_posicao.py para determinar as posicoes da tela

## Aprendizados
- Automação de processos com Python
- Manipulação de dados com Pandas
- Interação com interface gráfica via código
