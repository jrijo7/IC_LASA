# Análise e Filtragem de Dados de Mortalidade

## Descrição
Este repositório contém um código para carregamento, filtragem e análise de dados de mortalidade do **Sistema de Informação sobre Mortalidade (SIM)**. O código processa arquivos CSV para extrair informações relevantes e realizar análises específicas.

## Funcionalidades
- **Carregamento de Dados**: Lê múltiplos arquivos CSV do diretório especificado.
- **Filtragem de Dados**: Seleciona colunas relevantes, como município de ocorrência, idade, sexo e causa do óbito.
- **Processamento e Análise**:
  - Filtra registros com base em critérios específicos (exemplo: município do Rio de Janeiro).
  - Agrupa e resume dados, como óbitos de pessoas acima de 75 anos por município.

## Como Utilizar
1. **Instale as dependências**:
   ```bash
   pip install pandas
   ```
2. **Defina o diretório contendo os arquivos CSV** no código.
3. **Execute o notebook** para processar e analisar os dados.

## Estrutura do Código
1. **Importação de bibliotecas** necessárias.
2. **Carregamento de múltiplos arquivos CSV** e concatenação dos dados.
3. **Filtragem de colunas e registros** relevantes.
4. **Agrupamento e análise** de dados de mortalidade.

## Requisitos
- Python 3.x
- Pandas
- os
- glob

## Objetivos
- Futuramente o objetivo é criar um alarme para temperaturas críticas

Caso tenha dúvidas ou sugestões, sinta-se à vontade para contribuir.
