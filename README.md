# 👥 Dashboard de RH — Análise de Pessoas e Rotatividade

> Dashboard desenvolvido em Power BI para análise completa da força de trabalho de uma empresa,
> com foco em contratações, desligamentos, rotatividade e distribuição de colaboradores
> por área, cargo e localidade. Período analisado: **2010 a 2018**.

---

## 📌 Contexto do Projeto

O objetivo foi centralizar os principais indicadores de Recursos Humanos em um único painel visual,
permitindo uma leitura rápida e estratégica sobre a saúde do quadro de colaboradores ao longo de 8 anos.

**Perguntas que o dashboard responde:**
- Qual é o total de contratações e funcionários ativos no período?
- Qual a taxa de rotatividade da empresa?
- Como os funcionários estão distribuídos por cidade, área e cargo?
- Existe equilíbrio de gênero no quadro ativo?
- Quais áreas e localidades concentram mais desligamentos?
- Qual a folha salarial e as horas extras por cargo em cada área?

---

## 📈 Principais Indicadores

| Indicador | Valor |
|-----------|-------|
| Total de Contratações | 234 |
| Funcionários Ativos | 217 |
| Funcionários Desligados | 17 |
| **Taxa de Rotatividade** | **7,26%** |
| Distribuição de Gênero | 52,07% Masc. / 47,93% Fem. |

---

## 🔍 Insights Encontrados

- **Rotatividade elevada para o período:** Uma taxa de 7,26% ao longo de 8 anos (2010–2018) indica um nível de saída relevante. Para empresas do setor, taxas acima de 5% ao ano já acendem um sinal de atenção — esse dado sozinho justificaria uma investigação mais aprofundada de causas e padrões de saída.

- **São Paulo e Rio de Janeiro lideram desligamentos:** Com 3 desligamentos cada, essas praças concentram a maior parte das saídas. Por serem também as cidades com maior volume de funcionários ativos (49 e 28 respectivamente), o dado pode refletir maior rotatividade nos grandes centros ou maior pressão competitiva por talentos nessas regiões.

- **Área de Operações como ponto de atenção:** A área de Operações (40 funcionários ativos) apresentou pico de desligamentos, sugerindo possível sobrecarga, insatisfação ou perfil de cargo com maior rotatividade natural — hipótese que poderia ser validada com dados de pesquisa de clima.

- **Estagiários lideram em horas extras (8,9 mil horas):** Dado revelado pelo tooltip interativo do dashboard. Estagiários acumulam mais horas extras do que Analistas, Coordenadores e Gerentes — um padrão que pode indicar uso inadequado dessa categoria de colaborador e merece atenção do RH.

- **Gênero próximo do equilíbrio:** A distribuição de 52% masculino e 48% feminino indica uma composição relativamente equilibrada, o que é positivo para o indicador de diversidade da empresa.

---

## 🛠️ Ferramentas e Recursos Utilizados

| Recurso | Descrição |
|--------|-----------|
| Power BI Desktop | Desenvolvimento do dashboard e visualizações |
| DAX | Criação de medidas para KPIs e cálculos de rotatividade |
| Gráfico Sankey | Visualização do fluxo Funcionários Ativos → Área → Cargo |
| **Tooltip Personalizado** | Página de tooltip interativa com dados contextuais por filtro |

---

## ✨ Destaque Técnico — Tooltip Interativo

Um dos recursos mais avançados deste dashboard é a **página de tooltip personalizada**.

Ao passar o mouse sobre qualquer elemento do dashboard, o usuário visualiza automaticamente:
- **Total de contratações** filtradas pelo contexto selecionado
- **Folha salarial** correspondente à seleção
- **Horas extras por cargo** em gráfico de barras

O tooltip é **totalmente dinâmico** — responde aos filtros ativos de Área e Cargo, exibindo sempre os dados do contexto em que o usuário está navegando. Isso elimina a necessidade de páginas extras e enriquece a experiência de análise sem poluir o layout principal.

| Dashboard principal | Tooltip em ação |
|---|---|
| ![Dashboard Principal](https://raw.github.com/MateusSjunior/dashboard-RH/main/Planos%20de%20fundo%20e%20prints/Dashboard%20de%20RH.png) | ![Tooltip Interativo](https://raw.github.com/MateusSjunior/dashboard-RH/main/Planos%20de%20fundo%20e%20prints/Dashboard%20de%20RH%20Tooltip.png) |


> ⚠️ Os dados originais não estão disponíveis publicamente pois fazem parte de material de curso proprietário.
> O foco do projeto está na análise, nas visualizações e nos recursos técnicos desenvolvidos.

---

## 👤 Autor

**Mateus da Silva Junior**
Analista de Dados em formação | Power BI · Excel · SQL · Python

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mateus-junior-7ab55b144/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/MateusSjunior)

---

*Projeto desenvolvido como parte do meu portfólio de transição para a área de dados.*
