# ENEM – Análise Territorial, Socioeconômica e de Desempenho por NTE - Bahia

## Pergunta central do projeto
**Como indicadores socioeconômicos e territoriais se associam aos padrões de desempenho no ENEM entre os Núcleos Territoriais de Educação (NTE) da Bahia?**

Este repositório reúne análises exploratórias, estatísticas e experimentais aplicadas aos microdados do ENEM dos anos de **2019 - 2024**, com foco na relação entre **condições socioeconômicas**, **recortes territoriais (NTE)** e **indicadores de desempenho dos participantes**.

O projeto tem como objetivo **extrair informações acionáveis para apoio à tomada de decisão, a partir de dados públicos educacionais**, utilizando técnicas de análise de dados, estatística e inteligência artificial (machine learning), com ênfase na leitura das desigualdades territoriais.

---

## Estrutura do Projeto

```text
│ enem-bahia-territorial-socioeconomic-performance/
│
├── README.md
├── requirements.txt
├── .gitignore
│
├── data/
│   ├── raw/
│   └── processed/
│
├── 01_exploratory_data_analysis/
│   ├── README.md
│   ├── enem2019.ipynb
│   ├── enem2020.ipynb
│   ├── enem2021.ipynb
│   ├── enem2022.ipynb
│   ├── enem2023.ipynb
│   └── enem2024.ipynb
│
├── 02_modeling
│   ├── README.md
│   └── feature_engineering.ipynb
│
├── 03_socioeconomic_statistical_correlations/
│   ├── README.md
│   └── statistical_analysis.R
│
└── outputs/
    ├── README.md
    ├── figures/
    └── reports/
	
 ``` 

---

## Descrição das Etapas

### 01_exploratory_data_analysis 
Neste módulo, realizamos uma análise exploratória detalhada dos microdados do Exame Nacional do Ensino Médio (2019–2024), com foco em compreender o perfil socioeconômico dos participantes e os indicadores de desempenho acadêmico vinculados aos Núcleos Territoriais de Educação (NTE) do estado da Bahia, especialmente aqueles com menor desempenho.

Ao final da análise de cada ano, serão gerados arquivos CSV estruturados, que servirão como entrada para os módulos subsequentes do projeto.

### 02_modeling
  
Neste módulo, utilizamos os arquivos CSV gerados na análise exploratória (Exames Nacionais do Ensino Médio 2019–2024) para preparar os dados e treinar modelos de aprendizagem de máquina.
O objetivo é selecionar o modelo com melhor performance preditiva para mitigar lacunas decorrentes das limitações observadas nos dados do ENEM 2024.

Ao final do módulo, serão gerados novos arquivos CSV estruturados, que servirão como entrada para o próximo módulo do projeto.

### 03_socioeconomic_statistical_correlations

Neste módulo, os dados são analisados para investigar a relação entre indicadores socioeconômicos e métricas de desempenho no Exame Nacional do Ensino Médio, incluindo faixas de desempenho, proporções por faixa de nota e padrões espaciais de desempenho.

São aplicadas técnicas como:
- estatística descritiva;
- correlação de Spearman;
- visualização gráfica de padrões territoriais.

O objetivo final é produzir análises detalhadas e fornecer recomendações de políticas públicas, oferecendo insights para apoiar decisões educacionais baseadas em evidências.

---

## Considerações Metodológicas

As interpretações são fundamentadas em padrões observados nos dados e em técnicas estatísticas consolidadas.

Além disso, este portfólio prioriza:
- coerência metodológica,
- transparência analítica,
- reprodutibilidade dos procedimentos.

---

## Evolução Arquitetural e Técnica

O projeto encontra-se em processo contínuo de refinamento estrutural, com foco em aprimorar organização, eficiência e reprodutibilidade. Sua concepção modular permite evolução incremental e desenvolvimento colaborativo, preservando consistência metodológica e clareza analítica.

Entre os ajustes em avaliação estão:

- consolidação dos notebooks anuais em estruturas parametrizadas, reduzindo redundância e promovendo maior modularidade;
- reorganização de rotinas repetitivas em scripts reutilizáveis;
- fortalecimento do pipeline de processamento de dados;
- ampliação da integração entre Python e R, assegurando coerência entre modelagem e inferência estatística;
- padronização adicional de outputs e relatórios técnicos.

Essa diretriz de aprimoramento contínuo busca fortalecer a robustez técnica do projeto e ampliar suas possibilidades analíticas.


---

## Status do Projeto

- 🟢 **Módulo 01 – Análise Exploratória (Python):** Realizado
- 🟢 **Módulo 02 –  Análise Temporal e Modelagem Exploratória (Python):** Em desenvolvimento  
- 🟡 **Módulo 03 – Correlação Renda × Desempenho (R):** Planejada

  ---
## Licença

Este projeto está licenciado sob a MIT License.
Os dados utilizados são públicos e disponibilizados pelo INEP. Este repositório licencia apenas o código sob MIT License

  ---
📌 Referência
Perfil GitHub:
https://github.com/PauloRochaXx
