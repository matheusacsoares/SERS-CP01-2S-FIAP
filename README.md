# SERS-CP01-2S-FIAP
Repositório com as atividades práticas de análise de dados do setor de energia, desenvolvidas para a disciplina **Soluções em Energias Renováveis e Sustentáveis** (Ciência da Computação — FIAP).

## Grupo

Giovanna Ferreira Almeida - RM571822

Lucas Bellezzo Figueiredo - RM569734

Maria Luiza Vieira de Freitas - RM571535

Matheus Arruda Camara Soares - RM571594

Matheus Sabino da Silva Guedes - RM572907





## Objetivo

Aplicar procedimentos de preparação, inspeção e análise de dados (Orange Data Mining e Python/Pandas) sobre conjuntos de dados reais do setor de energia, calculando indicadores, criando recortes por critérios definidos pela equipe e interpretando os resultados no contexto de cada situação-problema.

## Conteúdo do repositório

- **`CP3solucoes.ipynb`** — Resolução dos exercícios das Aulas 03 e 04, cobrindo os seis datasets propostos: preparação no Orange Data Mining (seleção de atributos, verificação de valores ausentes, amostragem) e análise no Python/Pandas (renomeação de atributos, indicadores estatísticos, limiares percentuais, recortes por múltiplos critérios e comparações).
- **`Desafio_Final_Energia_ONS_API_Final (1).ipynb`** — Desafio final: consulta à API pública de Carga Verificada do ONS, construção do DataFrame, cálculo de indicadores de carga elétrica, identificação de períodos de alta demanda, visualizações e relatório técnico com apoio de IA (validado criticamente pela equipe).
- **Amostras exportadas do Orange Data Mining** (usadas na Etapa B — Python/Pandas de cada dataset):
  - `EX_01_AMOSTRA (1).csv` — Dataset 1
  - `EX_02_AMOSTRA.csv` — Dataset 2
  - `tetouan_amostra.csv` — Dataset 3
  - `amostra_solar_20.csv` — Dataset 4
  - `amostra_dataset5.csv` — Dataset 5
  - `Dataset06-preprocessado.csv` — Dataset 6

## Fontes dos dados

**Desafio final — Carga Verificada, ONS (Operador Nacional do Sistema Elétrico):**
- API pública: `https://apicarga.ons.org.br/prd/cargaverificada`
- Portal de dados abertos: https://dados.ons.org.br/
- Conjunto de dados: https://dados.ons.org.br/dataset/carga-energia-verificada
- Recorte utilizado: área de carga SP (São Paulo), período de 01/08/2025 a 07/08/2025.

**Exercícios das Aulas 03/04 (UCI Machine Learning Repository e Kaggle):**
1. Appliances Energy Prediction — UCI (`energydata_complete.csv`)
2. Steel Industry Energy Consumption — UCI
3. Power Consumption of Tetouan City — UCI
4. Solar Power Generation Data — Kaggle
5. Wind & Solar Energy Production — Kaggle
6. Individual Household Electric Power Consumption — UCI

## Ferramentas

- **Orange Data Mining** — carregamento, inspeção, seleção de atributos, verificação de qualidade e amostragem dos dados.
- **Python / Pandas / Matplotlib / Seaborn** — organização dos dados, cálculo de indicadores, criação de recortes e visualizações.
- **Google Gemini API** (desafio final, etapa opcional) — apoio na geração do relatório técnico, com validação crítica da equipe.


