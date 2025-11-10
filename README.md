# 📊 Screening de Ações – B3 (MetaTrader 5 + Python)

Este repositório contém notebooks em **Python (.ipynb)** para *screening* técnico de ações da B3, utilizando a biblioteca **MetaTrader5 (mt5)** para acesso aos dados de mercado.

Os códigos foram desenvolvidos para rodar de forma interativa no **Jupyter Notebook**, facilitando o ajuste de parâmetros e a análise visual dos resultados.

---

## 🧩 Projetos incluídos

### 1️⃣ `screening_tendencia.ipynb`
Scanner de **tendência**, identificando ativos:
- Com **preço acima das médias móveis** configuradas (ex: 9, 21, 50);
- Com **ADX acima de um limite mínimo** (ex: 35), indicando força direcional.

### 2️⃣ `screening_rompimentos.ipynb`
Scanner de **rompimentos relevantes**, detectando:
- **Rompimentos de máxima e mínima** confirmados pelo fechamento;
- **RSI de 14 períodos** no momento do rompimento;
- Compatível com qualquer timeframe (H1, H4, D1, etc.).

---

## 🧰 Dependências

Antes de rodar, instale as bibliotecas necessárias (de preferência em um ambiente virtual):

```bash
pip install MetaTrader5 pandas numpy pytz matplotlib ipython
