# 💰 Deyson Investimento - Simulador de Renda Passiva

Este projeto é uma planilha em Excel para simular investimentos mensais com rendimento composto. Ideal para quem deseja ter uma visão clara sobre o crescimento do seu patrimônio e renda passiva ao longo dos anos.

---

## 📦 Arquivo

- [`Deyson(2).xltx`](./Deyson(2).xltx): Planilha modelo para simular investimentos com aportes mensais e cálculo de dividendos.

---

## ⚙️ Como usar

1. Abra a planilha no **Microsoft Excel** (ou Google Sheets, se preferir).
2. Na seção **CONFIGURAÇÕES**:
   - Insira seu **salário mensal**
   - Defina a **taxa de rendimento mensal esperada** (ex: 1,03%)
   - A planilha calculará automaticamente quanto investir com base nessa taxa
3. Na seção **INVESTIMENTO MENSAL**:
   - Informe o número de anos que deseja investir
   - Veja o **patrimônio acumulado** e o **dividendo mensal estimado**
4. Veja os **cenários prontos** (2 anos, 5 anos) com projeções de dividendos

---

## 📈 Fórmulas e lógica

### Juros compostos:

\[
FV = P \times \frac{(1 + i)^n - 1}{i}
\]

- `P`: Valor investido mensalmente
- `i`: Taxa de rendimento mensal (ex: 1,03% = 0.0103)
- `n`: Número de meses (anos × 12)

### Renda passiva (dividendos):

\[
Renda = Patrimônio \times Rendimento
\]

---

## 🛠️ Requisitos

- Microsoft Excel 2013 ou superior (recomendado)
- Ou: Google Sheets (pode haver pequenas diferenças nas fórmulas)

---

## 📌 Exemplos

- Investindo R$ 423,60 por mês durante 5 anos, com rendimento de 1,03% ao mês, o patrimônio acumulado será de R$ 34.930,91, com dividendos mensais de aproximadamente R$ 359,79.

---

## 📝 Licença

Este projeto está licenciado sob a licença MIT.

---

## 🤝 Contribuições

Sugestões e melhorias são muito bem-vindas! Abra uma *issue* ou envie um *pull request*.

