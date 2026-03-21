# FNDR — Coeficientes Individuais de Participação

> Fórmula dos coeficientes (70% FPE + 30% população); competência do TCU para regulamentar e calcular; impacto regional esperado; base de dados; comparação com a distribuição atual do FPE.

**Bases normativas principais:**
- EC 132/2023, art. 159-A, §§4º e 5º (CF/1988)
- LC 62/1989 (coeficientes do FPE — base dos 70%)
- IBGE (população — base dos 30%)

---

## 1. Fórmula constitucional — art. 159-A, §§4º e 5º

**Art. 159-A, §4º da CF/1988** *(inserido pela EC 132/2023)*

> "Para fins dos coeficientes de participação de que trata o §3º, cada Estado e o Distrito Federal observarão os seguintes critérios:
>
> I — **percentual da população** de cada Estado ou do Distrito Federal em relação ao total nacional, com **peso de 30% (trinta por cento)**; e
>
> II — **coeficiente individual de participação** do Estado ou do Distrito Federal nos recursos de que trata o art. 159, I, "a" (FPE), com **peso de 70% (setenta por cento)**."

**Art. 159-A, §5º da CF/1988**

> "O **Tribunal de Contas da União** será o órgão responsável por **regulamentar e calcular** os coeficientes individuais de participação de que trata o §4º."

---

## 2. Os dois componentes da fórmula

### 2.1 Componente FPE — 70% do coeficiente

O **Fundo de Participação dos Estados (FPE)** tem seus coeficientes definidos pela **LC 62/1989** com base em um critério composto de: (i) inverso da renda per capita e (ii) área geográfica. Isso resulta em uma distribuição altamente concentrada nas regiões menos desenvolvidas.

**Distribuição aproximada dos coeficientes do FPE por região:**

| Região | Participação no FPE (aprox.) |
|---|---|
| **Norte** | ~25,4% |
| **Nordeste** | ~52,5% |
| **Centro-Oeste** | ~6,9% |
| **Sul** | ~6,5% |
| **Sudeste** | ~8,7% |

Como o componente FPE tem peso de **70%** no coeficiente do FNDR, as regiões Norte e Nordeste juntas receberão, só por esse componente, aproximadamente 55% dos recursos do FNDR.

### 2.2 Componente população — 30% do coeficiente

O percentual da população de cada Estado (ou DF) em relação à população total do Brasil, apurado pelo **IBGE** com base no Censo Demográfico ou na PNAD Contínua.

O componente demográfico beneficia os Estados mais populosos — o que inclui São Paulo, Minas Gerais e Rio de Janeiro (Sudeste), parcialmente compensando a concentração do FPE nas regiões menos desenvolvidas.

---

## 3. Cálculo do coeficiente individual

**Fórmula:**

```
Coeficiente_FNDR(Estado_i) = 0,70 × CoefFPE(Estado_i) + 0,30 × Pop(Estado_i)/PopTotal
```

Onde:
- `CoefFPE(Estado_i)` = coeficiente do Estado i no FPE (LC 62/1989)
- `Pop(Estado_i)` = população do Estado i (IBGE)
- `PopTotal` = população total do Brasil (IBGE)

---

## 4. Papel do TCU — regulamentação e cálculo

**Art. 159-A, §5º da CF/1988** atribui ao TCU dupla função:

**Regulamentar:** Definir a metodologia de apuração dos coeficientes, inclusive:
- Qual edição do FPE usar (anual ou média de vários anos);
- Qual fonte de dados populacionais utilizar (Censo, PNAD, estimativas anuais do IBGE);
- Critérios para tratamento de eventuais revisões de dados populacionais.

**Calcular:** Apurar os coeficientes individuais de cada Estado e do DF, publicando-os anualmente até a data definida em lei complementar (analogamente ao prazo de 30 de abril fixado no art. 161 da CF para os coeficientes do FPE).

**Vigência dos coeficientes:** Calculados anualmente, os coeficientes vigoram para o exercício seguinte.

---

## 5. Impacto regional esperado

Com base na fórmula constitucional, a distribuição do FNDR concentra-se nas regiões Norte e Nordeste:

| Região | Participação estimada no FNDR |
|---|---|
| **Norte** | ~20–22% |
| **Nordeste** | ~42–45% |
| **Centro-Oeste** | ~8–10% |
| **Sul** | ~10–12% |
| **Sudeste** | ~14–16% |

As estimativas acima são aproximadas, pois dependem dos coeficientes definitivos do FPE (que podem ser revisados por lei complementar) e dos dados populacionais do IBGE atualizados. A soma das regiões Norte + Nordeste + Centro-Oeste deve ficar em torno de **70–77%** dos recursos totais do FNDR.

**Maiores beneficiários absolutos esperados:**
- Bahia (alta população + alto FPE)
- Minas Gerais (alta população, embora com FPE menor)
- Ceará, Maranhão, Pará e Pernambuco (FPE alto)

---

## 6. Comparação FNDR × FPE × FPM

| Aspecto | FPE | FPM | FNDR |
|---|---|---|---|
| **Destinatários** | Estados e DF | Municípios | Estados e DF |
| **Fonte** | % do IR + IPI | % do IR + IPI | Aportes diretos da União |
| **Critério** | Renda per capita inversa + área | 10% igual + 90% proporcional à população | 70% FPE + 30% população |
| **Responsável pelo cálculo** | TCU (LC 62/89) | TCU (LC 62/89) | TCU (EC 132/2023, §5º) |
| **Objetivo** | Equalização fiscal | Equalização fiscal | Investimento regional |
| **Retenção por dívidas** | Permitida | Permitida | **Vedada** |
| **Início** | Permanente (desde 1988) | Permanente (desde 1988) | 2029 |

---

## 7. Quadro-resumo dos coeficientes

| Aspecto | Regra |
|---|---|
| **Componente 1** | 70% do coeficiente: FPE (art. 159, I, "a") |
| **Componente 2** | 30% do coeficiente: população relativa (IBGE) |
| **Responsável** | TCU — regulamenta e calcula |
| **Periodicidade** | Anual |
| **Vigência** | Exercício seguinte ao do cálculo |
| **Distribuição esperada** | Norte + Nordeste + Centro-Oeste ≈ 70–77% |
| **Base legal dos coeficientes FPE** | LC 62/1989 |
| **Base dos dados populacionais** | IBGE (Censo ou PNAD Contínua) |

---

*Consulte também: [fndr-visao-geral.md](fndr-visao-geral.md) · [fndr-sustentabilidade.md](fndr-sustentabilidade.md)*

*Atualizado com base na LC 227/2026 (publicada em 13/01/2026).*
