
# (PLANEJAMENTO)Pipeline do Modelo Preditivo de Desempenho (ENEM)

## 1. Extract
- Carregamento dos microdados ENEM 2019–2023 (base de treino).
- Carregamento dos dados socioeconômicos ENEM 2024 (base de aplicação).

---

## 2. Validação Estrutural
- Verificação da padronização dos nomes das colunas em ambas as bases.
- Conferência das variáveis socioeconômicas selecionadas.
- Verificação da presença da variável alvo **faixa_de_desempenho** na base de treino.

---

## 3. Tratamento dos Dados

### Base de treino (2019–2023)
- Identificação de valores ausentes.
- Remoção de registros com **faixa_de_desempenho ausente**.
- Remoção de registros duplicados.

### Base de aplicação (2024)
- Identificação de valores ausentes nas variáveis socioeconômicas.
- Remoção ou tratamento de registros inconsistentes.
- Garantia de que as mesmas variáveis usadas no treinamento estejam presentes.

---

## 4. Preparação para Modelagem
- Separação entre:
  - **Variáveis explicativas (X)** — variáveis socioeconômicas
  - **Variável alvo (y)** — faixa_de_desempenho
- Verificação da distribuição das classes da variável alvo.

---

## 5. Treinamento dos Modelos
- Treinamento de modelos de classificação supervisionada.
- Avaliação comparativa de desempenho entre modelos.
- Seleção do modelo com melhor desempenho preditivo.

---

## 6. Aplicação do Modelo
- Aplicação do modelo selecionado aos dados socioeconômicos do ENEM 2024.
- Geração das probabilidades de pertencimento a cada **faixa_de_desempenho**.

---

## 7. Load / Output Analítico
- Geração do dataset final com as probabilidades previstas.
- Exportação do resultado para análise posterior.
