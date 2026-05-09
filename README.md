# Análise de Dados: Mercado Imobiliário Residencial (Rio de Janeiro) 📊🏠

Este projeto realiza uma Análise Exploratória de Dados (EDA) completa sobre o mercado de aluguéis residenciais na cidade do Rio de Janeiro, utilizando Python e a biblioteca Pandas.

## 🎯 Objetivo
O objetivo principal foi transformar uma base bruta com mais de 32 mil registros em insights acionáveis para o setor imobiliário, focando em identificar padrões de preços por tipo de imóvel e localização.

## 🛠️ Tecnologias Utilizadas
* **Linguagem:** Python
* **Bibliotecas de Dados:** Pandas
* **Visualização:** Matplotlib e Seaborn
* **Ambiente:** VS Code com Jupyter Notebooks

## ⚙️ Etapas do Projeto (Pipeline de Dados)
1.  **Ingestão de Dados:** Leitura de base remota via URL.
2.  **Limpeza e Filtragem:** Identificação e remoção de imóveis de caráter comercial/industrial (Galpões, Lojas, Prédios Comerciais) para focar estritamente no mercado residencial.
3.  **Tratamento de Dados Nulos (NaN):** * Preenchimento inteligente de taxas (Condomínio e IPTU) com valor 0 quando ausentes.
    * Remoção de registros sem valor de aluguel.
4.  **Análise e Visualização:** Criação de agrupamentos (Groupby) e gráficos para responder perguntas de negócio.

## 📈 Principais Insights
* **Valor Agregado:** Casas de Condomínio possuem a maior média de aluguel residencial, refletindo a demanda por segurança e infraestrutura.
* **Exclusividade Local:** O bairro do Joá foi identificado como o mais caro da base, seguido por outras áreas nobres da Zona Sul e Barra.
* **Qualidade de Dados:** A base foi reduzida de 32.960 para 22.580 registros após a limpeza, garantindo uma média de preços muito mais fiel à realidade do morador carioca.

*Projeto desenvolvido como parte do meu portfólio de Análise de Dados e Desenvolvimento.*
