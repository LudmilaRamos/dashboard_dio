# Dashboard_dio
Dashboard do trabalho final da aula de Excell com copilot 

# Dashboard de Vendas - Xbox

## Descrição do Projeto

Este projeto consiste em um dashboard de vendas criado no Excel, com foco na organização e visualização de dados. O objetivo é transformar dados brutos em informações visuais claras e úteis, permitindo uma análise eficaz do desempenho de vendas e a tomada de decisões baseadas em dados.

O dashboard contém os seguintes componentes:
- Faturamento Total de Vendas de Planos Anuais.
- Faturamento Total de Vendas de Planos Anuais (Separados por Auto-renovação e Não-Auto-renovação).
- Total de Vendas de Assinaturas do EA Play.
- Total de Vendas de Assinaturas do Minecraft Season Pass.

## Dados Utilizados

Os dados utilizados para a criação do dashboard estão contidos no arquivo `base.xlsx`. Ele contém as informações de vendas brutas que foram analisadas e transformadas em gráficos e indicadores no Excel.

## Perguntas de Negócio Respondidas

1. **Qual o faturamento total de vendas de planos anuais (contendo todas as assinaturas agregadas)?**

   O faturamento total de vendas de planos anuais foi calculado considerando todas as assinaturas agregadas, como descrito abaixo:

   - **Rótulos de Linha:** Soma de Total Value
     - Não: R$ 806,00
     - Sim: R$ 1.502,00
     - Total Geral: R$ 2.308,00

2. **Qual o faturamento total de vendas de planos anuais, separado por auto-renovação e não auto-renovação?**

   A separação entre auto-renovação e não auto-renovação foi realizada e o faturamento foi calculado conforme:

   - **Auto-renovação (Sim):** R$ 1.502,00
   - **Não auto-renovação (Não):** R$ 806,00

3. **Total de vendas de Assinatura do EA Play:**

   O total de vendas de Assinatura do EA Play é de R$ 990,00, com o detalhamento:

   - **Rótulos de Linha:** Soma de EA Play Season Pass
     - Core: R$ 0,00
     - Standard: R$ 0,00
     - Ultimate: R$ 990,00
     - **Total Geral:** R$ 990,00

4. **Total de vendas de Assinaturas do Minecraft Season Pass:**

   O total de vendas de Assinaturas do Minecraft Season Pass foi calculado da seguinte forma:

   - **Rótulos de Linha:** Soma de Minecraft Season Pass Price
     - Core: R$ 0,00
     - Standard: R$ 480,00
     - Ultimate: R$ 660,00
     - **Total Geral:** R$ 1.140,00

## Como Executar o Projeto

Para visualizar o dashboard, basta abrir o arquivo `dashboard_xbox_finalizado.xlsx` no Excel. O arquivo contém todos os gráficos e análises feitas com base nos dados do arquivo `base.xlsx`.

### Pré-requisitos

- Microsoft Excel ou software compatível.
- Acesso ao arquivo `base.xlsx` para realizar ajustes nos dados, se necessário.

## Como Reproduzir

1. Faça o download dos arquivos deste repositório.
2. Abra o arquivo `base.xlsx` no Excel.
3. Importe os dados brutos, crie as tabelas dinâmicas e gráficos conforme o modelo.
4. Salve o dashboard finalizado como `dashboard_xbox_finalizado.xlsx`.

