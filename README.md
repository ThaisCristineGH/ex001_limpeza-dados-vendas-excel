# 📊 Projeto de Limpeza de Dados de Vendas (Excel)

Este repositório contém um projeto prático de **Data Cleaning** (Limpeza de Dados), onde transformei uma base de dados de vendas bruta e inconsistente em uma estrutura organizada, funcional e pronta para análise.

## 📁 Estrutura do Projeto
- **`data/`**: Contém os arquivos em formato CSV para visualização rápida no GitHub.
  - `raw_vendas.csv`: Dados originais com erros.
  - `processed_vendas.csv`: Dados após o tratamento.
- **`img/`**: Capturas de tela para comparação visual.
- **`Excel_Vendas_Final...xlsx`**: Planilha completa com fórmulas, cores e gráficos.

## 🧹 O que foi realizado no tratamento:
1. **Padronização de Texto**: Uso da função `MAIÚSCULA` para uniformizar as colunas de Clientes e Cidades.
2. **Correção de Tipagem**: O valor "cinquenta" foi convertido para o número `50` para permitir cálculos financeiros.
3. **Tratamento de Nulos**: Identificação e preenchimento de quantidades vazias.
4. **Eliminação de Duplicatas**: Remoção de registros repetidos (como o ID 1002).
5. **Automação de Cálculos**: Criação da fórmula de TOTAL e somatória do rodapé.

## 📈 Comparação Visual
Abaixo, você pode ver a diferença entre a base bruta e a base tratada:

### Antes (Dados Sujos)
![Antes](./img/antes.png)

### Depois (Dados Limpos e Formatados)
![Depois](./img/depois.png)

## 🛠️ Tecnologias
- **Microsoft Excel**: Limpeza, fórmulas e formatação.
- **GitHub**: Hospedagem e documentação do projeto.
