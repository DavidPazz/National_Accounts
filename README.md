# National_Accounts
# 📊 Análise Econômica da Região Centro-Oeste (2012–2023)

Repositório dedicado ao armazenamento da base de dados, planilhas de cálculo, gráficos e relatório técnico desenvolvidos para a disciplina de **Contabilidade Nacional** (Universidade Federal do Ceará – UFC).

---

## 🎯 Objetivo do Projeto
Analisar a evolução macroeconômica e a estrutura produtiva da **Região Centro-Oeste** do Brasil e de suas quatro unidades federativas (**Distrito Federal, Goiás, Mato Grosso e Mato Grosso do Sul**), avaliando tanto o crescimento nominal quanto o desempenho real descontado o efeito inflacionário.

---

## 📈 Escopo e Metodologia

* **Agregados Analisados:**
  * **Produto Interno Bruto (PIB):** Série histórica de **2012 a 2023**.
  * **Valor Adicionado Bruto (VAB) Setorial:** Desagregado em *Agropecuária*, *Indústria* e *Serviços* (exclusive administração, defesa, educação e saúde públicas), compreendendo o período de **2012 a 2021**.
* **Deflacionamento (Ano-Base 2019 = 1,00):**
  * Conversão das séries de preços correntes para **preços constantes de 2019** utilizando o índice acumulado da variação anual do **IPCA**.
  * Fator de deflacionamento calculado pela razão $\frac{\text{Índice Acumulado}_{2019}}{\text{Índice Acumulado}_{\text{Ano}}}$.

---

## 🔍 Principais Resultados

* **PIB Regional (2012–2023):** Crescimento nominal acumulado de **160,9%** (de R$ 444,54 bi para R$ 1,16 tri) e crescimento real de **38,7%** a preços de 2019 (de R$ 656,59 bi para R$ 910,97 bi).
* **Ilusão Inflacionária Pós-2020:** Forte descolamento entre as curvas nominal (+58,6%) e real (+24,6%) entre 2019 e 2023, refletindo o repique inflacionário do período.
* **Protagonismo do Agronegócio:** O VAB da Agropecuária apresentou expansão real de **121,4%** (2012–2021), liderado por Mato Grosso (51% do setor regional) e atuando como amortecedor anticíclico durante a crise de 2015–2016 e a pandemia de 2020.
* **Dinâmica Urbana (Indústria e Serviços):** Retração real nos anos de choque doméstico (2015 e 2020), com posterior recuperação liderada por Goiás na Indústria e pelo eixo Distrito Federal–Goiás no setor de Serviços.

---

## 🗂️ Estrutura do Repositório

* `/dados` – Planilhas com as séries originais (preços correntes), cálculo do deflator IPCA e séries deflacionadas (preços constantes de 2019).
* `/graficos` – Visualizações comparativas da evolução regional, estadual e setorial.
* `/relatorio` – Documento técnico completo em PDF formatado nas normas ABNT/UFC.

---

## 📚 Fontes de Dados

* **IBGE / SIDRA (Tabela 5938):** Produto Interno Bruto e Valor Adicionado Bruto por atividade econômica (Referência 2010).
* **IPEA / Ipeadata:** Índice Nacional de Preços ao Consumidor Amplo (IPCA – taxa de variação anual % a.a.).

---

## 👤 Autor

* **David Batista Paz** – Universidade Federal do Ceará (UFC)
* **Orientação / Disciplina:** Prof. Dr. Mário Martins – Contabilidade Nacional (2026)
