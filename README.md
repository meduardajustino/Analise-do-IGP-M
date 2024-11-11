# 📊 Análise Histórica do IGP-M (2004-2024) 📈

Este projeto realiza uma **análise histórica** do **Índice Geral de Preços - Mercado (IGP-M)** no período de **2004 a 2024**, utilizando dados econômicos coletados de fontes confiáveis. A análise aborda a evolução mensal do índice, o **acumulado no ano**, o **acumulado nos últimos 12 meses** e o **acumulado desde janeiro de 1993**. A partir dessa base, vamos explorar **tendências econômicas** e **analisar flutuações sazonais**, além de comparar os diferentes tipos de índices.

## 📝 O que será abordado no script

O script realiza as seguintes análises:

- **Leitura e preparação dos dados**: Importação dos dados históricos do IGP-M e organização dos dados em um formato adequado para análise.
  
- **Análise estatística**:
  - Cálculo e visualização das principais métricas descritivas dos dados, como média, mediana, desvio padrão, e quartis.
  - Cálculo das variações acumuladas ao longo do tempo para o **IGP-M acumulado no ano** e **IGP-M acumulado nos últimos 12 meses**.
  
- **Visualização de gráficos**:
  - **Evolução histórica do IGP-M** nos seguintes períodos:
    - 2004 a 2010
    - 2011 a 2017
    - 2018 a 2024
  - **Comparação entre o IGP-M acumulado no ano e nos últimos 12 meses** através de **boxplots**.
  - **Análise de longo prazo**: Acompanhamento da evolução do IGP-M de 2004 a 2024.
  
- **Exemplo prático de reajuste de aluguel 🏠**:
  - Demonstração de como o IGP-M pode ser utilizado para calcular o **reajuste de aluguel**, com base no **IGP-M acumulado nos últimos 12 meses** até agosto de 2024.

## 📚 Fontes de Dados

- Os dados foram coletados de fontes confiáveis como:
  - [Abacus Liquid - Histórico do IGP-M](https://abacusliquid.com/igp-m-historico/)
  - [FGV - Agosto 2024](https://portal.fgv.br/noticias/igp-m-agosto-2024)

- O **arquivo CSV** contendo os dados históricos do IGP-M está disponível no Google Drive:
  [Arquivo CSV do IGP-M](https://drive.google.com/file/d/1QkI7WXd2QOOPb6qRTr_IG2AqT1jOoeOF/view?usp=sharing)


## 🎯 Objetivo do Projeto

O principal objetivo deste projeto é **visualizar** e **compreender** as **flutuações e tendências do IGP-M** ao longo do tempo, com ênfase na **análise de longo prazo** e na comparação entre diferentes formas de cálculo do índice (**mensal, anual e acumulado dos últimos 12 meses**). Além disso, o projeto demonstra uma aplicação prática do IGP-M em **contratos de aluguel**, fornecendo uma **ferramenta útil** para quem deseja ajustar valores de locação com base na inflação.

## 📊 Resultados Esperados

A execução do script irá gerar os seguintes resultados:

### 1. **Gráficos de Evolução do IGP-M** 📈

- **2004 a 2010**: Exibição da variação mensal do **IGP-M** para o período de 2004 a 2010. Este gráfico revelará as flutuações do índice durante um período de recuperação pós-crise de 2008, onde as variações de preço podem ser mais evidentes devido a ajustes econômicos.
  
- **2011 a 2017**: Exibição da variação mensal do **IGP-M** para o período de 2011 a 2017. Este gráfico ajudará a observar o impacto da estabilização econômica e o comportamento do índice durante um período de crescimento moderado e de crises políticas no país.

- **2018 a 2024**: Exibição da variação mensal do **IGP-M** para o período de 2018 a 2024. Através deste gráfico, será possível analisar o impacto de eventos econômicos recentes, como a pandemia de COVID-19 e a recuperação econômica, no comportamento do índice.

Esses gráficos ajudam a **visualizar tendências de longo prazo** e a identificar **eventos específicos** que podem ter influenciado o índice, como crises econômicas ou inflação elevada.

### 2. **Boxplots de Comparação** 📦

- **Comparação entre o IGP-M acumulado no ano e o IGP-M acumulado nos últimos 12 meses**. Esses gráficos são fundamentais para entender a diferença entre a variação de preços ao longo de um ano versus o acumulado de 12 meses completos. O **IGP-M acumulado no ano** pode apresentar **flutuações mais bruscas**, enquanto o **IGP-M acumulado nos últimos 12 meses** suaviza as variações sazonais, oferecendo uma visão mais **estável** da evolução dos preços.
  
Esses boxplots são úteis para identificar **outliers** (valores extremos) e verificar a **distribuição** do índice ao longo do tempo. Por exemplo, se o IGP-M acumulado no ano tiver picos mais altos, isso pode ser indicativo de **inflação elevada** em determinados meses ou de **ajustes econômicos rápidos**.

O **boxplot** compara a **distribuição** do IGP-M ao longo de diferentes períodos. Ele permite visualizar a **variabilidade** e **tendências** do índice, mostrando:

- A **mediana** do IGP-M, que indica a tendência central da variação.
- Os **quartis**, que ajudam a entender a dispersão dos valores do índice.
- Os **valores extremos** (outliers), que podem indicar meses com variações anormais.

### 3. **Cálculo de Reajuste de Aluguel 🏠**

- **Exemplo prático de como o IGP-M pode ser utilizado para reajustar o aluguel**. O cálculo é feito com base no **IGP-M acumulado dos últimos 12 meses** até agosto de 2024. Este índice é amplamente utilizado no Brasil para reajustar contratos de aluguel, e a análise mostrará como o valor do aluguel pode ser ajustado conforme o aumento da inflação.

## 🛠️ Dependências

Este projeto foi desenvolvido utilizando a linguagem **Python** e algumas bibliotecas essenciais para manipulação e visualização de dados. As bibliotecas necessárias são:

```bash
pip install pandas matplotlib numpy
```

- `Pandas:` Para manipulação e análise de dados em formato de tabelas.
- `Matplotlib:` Para a criação de gráficos e visualizações.
- `NumPy:` Para operações matemáticas e estatísticas.

## 🚀 Contribua para o Projeto

Se você tem sugestões, melhorias ou encontrou algum erro, fique à vontade para abrir uma **issue** ou enviar um **pull request**.

## 📄 Licença

Este projeto está licenciado sob a **MIT License** - veja o arquivo **LICENSE** para mais detalhes.
