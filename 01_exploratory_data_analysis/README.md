# Análise exploratória dos dados do ENEM (2019–2024)

Este módulo integra o projeto **enem-nte-bahia-analysis** e reúne a análise exploratória inicial dos microdados do ENEM, desenvolvida em Python por meio de notebooks Jupyter.

O foco recai sobre o perfil socioeconômico e os indicadores de desempenho dos participantes vinculados aos Núcleos Territoriais de Educação (NTE) do estado da Bahia de menores desempenhos.

As bases e análises aqui neste módulo serão insumos para os módulos subsequentes do projeto, que aprofundam a relação entre território, condições socioeconômicas e desempenho no ENEM, incluindo abordagens estatísticas e técnicas de *machine learning* (inteligência artificial).

---

## Objetivo do módulo

- Construir bases analíticas a partir dos microdados nacionais do ENEM  
- Realizar recortes territoriais por estado (Bahia) e por NTE  
- Explorar variáveis socioeconômicas (raça/cor, sexo/gênero e renda familiar)  
- Produzir estatísticas descritivas e visualizações iniciais  

---

## Organização

- Importação e inspeção das bases nacionais do ENEM 2019, 2020, 2021, 2022, 2023 e 2024
- Filtragem dos participantes do estado da Bahia  
- Associação dos participantes aos respectivos NTEs  
- Análises descritivas e visualizações exploratórias
- Preparação de arquivos finais para módulos posteriores

---

## Observações sobre os dados

Os microdados de 2024 não estão no repositório devido ao tamanho. Eles podem ser baixados do site do INEP:
https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/microdados/enem

O arquivo de apoio territorial `tbl_nte_*.csv`, assim como os arquivos produzidos (saídas dos processos) se encontram disponíveis na pasta (https://drive.google.com/drive/u/1/folders/1AdZgn0coXcbEh2Zu4IOwXcz7fDQJ_lbO?hl=pt-br)

---

## Tecnologias utilizadas

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Jupyter Notebook  


