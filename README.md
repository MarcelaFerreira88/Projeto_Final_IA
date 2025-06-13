# 💧 Análise de Dados sobre Saneamento Básico no Brasil

Repositório da atividade final do curso de Inteligência Artificial da PretaLab.

## 🧩 Contexto

Este projeto tem como foco a análise de dados do Sistema Nacional de Informações sobre Saneamento (SNIS), principal fonte sobre saneamento básico no Brasil, abrangendo informações sobre água, esgoto, resíduos sólidos e drenagem urbana.

## 🎯 Objetivos

- Medir a cobertura de água potável e esgoto nos estados brasileiros entre 2018 e 2022.
- Simular e analisar a relação entre saneamento e indicadores de saúde pública.
- Identificar disparidades regionais e oportunidades para políticas públicas.

## ❓ Perguntas Orientadoras

- Qual é a cobertura de acesso à água potável e esgotamento sanitário nos estados brasileiros nos últimos 5 anos?
- Como os indicadores de saneamento se correlacionam com índices de saúde? (ex.: incidência de doenças)

## 🔬 Metodologia

### 📥 Coleta e Tratamento dos Dados
- Dados extraídos do **Sistema Nacional de Informações sobre Saneamento (SNIS)**, com foco nos últimos 5 anos e nos indicadores por estado.

### 📊 Análise Exploratória
- Identificação de padrões, inconsistências e possíveis correlações entre saneamento e saúde pública.

### 🧭 Visualizações
- Gráficos e mapas para análise temporal e geográfica da cobertura de saneamento.

### 🧮 Indicadores Criados
- **Índice de Doença Simulado:** `100 − (0.4 × Água + 0.6 × Esgoto) + ruído`
- **Economia na Saúde:** `(Investimento em Água + Esgoto) × 4`
  - Justificativa: O esgoto tem peso maior na correlação com doenças de veiculação hídrica.

### 🛠️ Ferramentas Utilizadas
- **Python:** Bibliotecas como Pandas, Seaborn e Plotly.
- **Jupyter Notebook**
- **GitHub**

## 📂 **Estrutura do Repositório**
```
📂 
├── 📁 data/ - Dados brutos e processados.
├── 📁 docs/ - Destinado a toda documentação do projeto, incluindo o PDF da apresentação.
├── 📁 notebooks/ - Notebooks Jupyter usados para análises e experimentos.
├── 📁 reports/ - Imagens dos gráficos.
└── 📄 README.md - Documentação principal.
```

## 📊 Análises e Resultados

- A cobertura de água potável aumentou de 69,5% em 2018 para quase 72% em 2022.
- A cobertura de esgoto permaneceu estagnada em torno de 64%, com grandes desigualdades regionais.
- O Norte e Nordeste apresentam os piores índices de coleta de esgoto, evidenciando a necessidade de políticas públicas regionais e priorização de investimentos.
- Simulações indicam que a coleta de esgoto é o fator mais decisivo para a redução de doenças de veiculação hídrica.

## 📈 Insights Extraídos

- **Regiões Sudeste, Sul e Centro-Oeste:** Lideram em cobertura de água potável (>75%), mas ainda apresentam desafios com a coleta de esgoto.
- **Regiões Norte e Nordeste:** Menores índices de saneamento, com coleta de esgoto frequentemente abaixo de 35%.
- **Correlação:** A coleta de esgoto tem a maior influência na redução de doenças (correlação de -0.997).

## 🛠️ Próximos Passos

- Substituir o índice simulado por dados reais de internações por doenças relacionadas ao saneamento.
- Aplicar regressões lineares e segmentações regionais.
- Criar dashboards interativos para prefeituras e gestores públicos.

## 👥 Membros do Grupo

| Nome               | GitHub                                                             |
|--------------------|--------------------------------------------------------------------|
| Bianca Souza       | [@bianca-nazare](https://github.com/bianca-nazare)                |
| Ellen Rodrigues    | [@ellendutra](https://github.com/ellendutra)                      |
| Erica Bernardes    | [@ericabernardeslanga](https://github.com/ericabernardeslanga)    |
| Julia de Almeida   | [@Julia0126](https://github.com/Julia0126)                        |
| Marcela Aparecida  | [@MarcelaFerreira88](https://github.com/MarcelaFerreira88)        |
| Seleste Sinete     | [@SelesteAra](https://github.com/SelesteAra)                      |

---
