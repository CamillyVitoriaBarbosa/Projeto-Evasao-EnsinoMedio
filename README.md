# 📊 Análise da Evasão Escolar no Ensino Médio no Brasil (2010–2020)

📅 **Período analisado:** 2010 a 2020  
📍 **Abrangência:** Todos os estados do Brasil  
📊 **Fonte dos dados:** INEP / Censo Escolar (Microdados da Educação Básica)  
🧑‍💻 **Autor(a):** Camilly Vitória Barbosa dos Santos  
📁 **Projeto desenvolvido em Python (Google Colab)**  
📚 **Disciplina ou contexto (opcional):** Trabalho Final - UBD

---

## 🎯 Tema do Projeto

Este projeto tem como objetivo analisar a evasão escolar no ensino médio no Brasil ao longo da última década, com foco especial na comparação entre os estados. A evasão escolar é um dos maiores desafios enfrentados pela educação básica brasileira, afetando diretamente a formação de jovens e o desenvolvimento social e econômico do país.

A partir dos dados do Censo Escolar disponibilizados pelo INEP, buscamos responder perguntas como:

- Quais estados apresentaram maiores taxas de evasão entre 2010 e 2020?
- Houve tendência de aumento ou redução da evasão ao longo dos anos?
- Existem padrões regionais nas taxas de evasão?
- Quais estados registraram melhorias consistentes?

## 🔎 Motivação

Compreender os padrões de evasão escolar é essencial para embasar políticas públicas que promovam a permanência estudantil e a conclusão do ensino médio. A evasão compromete o futuro dos jovens e perpetua ciclos de desigualdade social.

Este trabalho busca, por meio da análise de dados oficiais, fornecer uma visão objetiva e baseada em evidências sobre onde os desafios são mais intensos e onde houve avanços no combate à evasão escolar.

## 🗂️ Fonte dos Dados

Os dados utilizados neste estudo foram obtidos por meio dos Indicadores Educacionais do INEP, mais especificamente os arquivos referentes às Taxas de Transição, que incluem as taxas de aprovação, reprovação, abandono e evasão no ensino médio por unidade federativa e região.

- Repositório oficial dos dados:  
👉 [Taxas de Transição - INEP](https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/indicadores-educacionais/taxas-de-transicao)

## 🔧 Como Reproduzir o Projeto

### 1. Baixando os Dados

Os dados utilizados no projeto podem ser baixados diretamente do site do INEP:

1. Baixe as planilhas de **Taxas de Transição** dos anos de 2010 a 2020.

### 2. Rodando o Código

Este projeto foi desenvolvido utilizando o **Google Colab**, garantindo que você possa rodar o código diretamente no ambiente online.

1. Abra o arquivo `notebook.ipynb` no Google Colab.
2. Carregue os arquivos de dados baixados e siga as etapas descritas no notebook para reproduzir a análise.

### 3. Bibliotecas Necessárias

Certifique-se de que as seguintes bibliotecas estão instaladas no seu ambiente Python:

```bash
!pip install pandas matplotlib numpy requests
