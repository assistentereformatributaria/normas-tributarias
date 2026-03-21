# Arrecadação e Distribuição do IBS — Split Payment

> Split payment: mecanismo de recolhimento automático do IBS e da CBS na liquidação financeira da operação pelos participantes dos arranjos de pagamento, com responsabilidades e penalidades específicas.

**Bases normativas principais:**
- LC 214/2025, arts. 31 a 35 (split payment)
- LC 214/2025, art. 471-D (penalidades do split payment)
- LC 227/2026, art. 2º, II (competência do CGIBS para arrecadar)
- LC 227/2026, art. 32 (Diretoria de Arrecadação e Cobrança)
- EC 132/2023, art. 156-A §5º, II (CF/1988 — creditamento condicionado ao recolhimento)

---

## 1. Fundamento constitucional — EC 132/2023, art. 156-A §5º, II

**Art. 156-A, §5º, II da CF/1988** *(inserido pela EC 132/2023)*

> "Lei complementar disporá sobre [...] o regime de compensação, podendo estabelecer hipóteses em que o aproveitamento do crédito ficará condicionado à **verificação do efetivo recolhimento** do imposto incidente sobre a operação com bens materiais ou imateriais, inclusive direitos, ou com serviços, desde que:
>
> a) o adquirente possa efetuar o **recolhimento do imposto incidente** nas suas aquisições de bens ou serviços; ou
>
> b) o recolhimento do imposto ocorra na **liquidação financeira** da operação."

O split payment implementa precisamente a alínea "b": o recolhimento ocorre na liquidação financeira, eliminando a necessidade de o adquirente verificar individualmente se cada fornecedor recolheu o tributo.

---

## 2. Conceito e funcionamento — LC 214/2025, arts. 31 a 35

**Art. 31, *caput* da LC 214/2025**

> "Nas operações de fornecimento de bens e serviços liquidadas por meio de **arranjos de pagamento** — incluindo pagamentos por cartão de crédito, cartão de débito, PIX, transferência eletrônica, boleto bancário e demais instrumentos de pagamento —, os **participantes do arranjo** deverão reter e recolher ao CGIBS (IBS) e à Receita Federal do Brasil — RFB (CBS) o montante dos tributos devidos, mediante **débito automático no valor a ser creditado ao fornecedor** no momento da liquidação financeira da operação."

### 2.1 Mecânica operacional

O split payment funciona em quatro etapas sequenciais:

| Etapa | Evento | Participante |
|---|---|---|
| **1. Pagamento** | Adquirente realiza o pagamento pelo bem ou serviço | Adquirente |
| **2. Cálculo** | Sistema calcula o IBS e a CBS devidos com base na alíquota e na base de cálculo informados no documento fiscal eletrônico | Arranjo de pagamento |
| **3. Retenção** | O valor do IBS e da CBS é automaticamente segregado do valor a ser creditado ao fornecedor | Arranjo de pagamento |
| **4. Recolhimento** | IBS é repassado diretamente ao CGIBS; CBS é repassada diretamente à RFB | Arranjo de pagamento |

### 2.2 Prazo de recolhimento

**Art. 31, §2º da LC 214/2025**

> "O recolhimento ao CGIBS e à RFB deverá ser efetuado em até **3 (três) dias úteis** após a liquidação financeira da operação, salvo prazo diferenciado estabelecido em regulamento para categorias específicas de arranjos de pagamento."

### 2.3 Informações necessárias para o cálculo

Para que o arranjo de pagamento realize corretamente a retenção e o recolhimento, o documento fiscal eletrônico deve conter, previamente à liquidação:
- O valor do IBS (alíquota estadual + alíquota municipal × base de cálculo);
- O valor da CBS (alíquota federal × base de cálculo);
- A identificação do local da operação (Estado e Município de destino);
- O CNPJ/CPF do fornecedor e do adquirente.

---

## 3. Participantes do arranjo de pagamento — responsabilidade

**Art. 32 da LC 214/2025**

> "São responsáveis pela retenção e pelo recolhimento do IBS e da CBS via split payment os seguintes participantes dos arranjos de pagamento, conforme sua posição na cadeia de liquidação:
>
> I — os **instituidores** do arranjo de pagamento (bandeiras de cartão, gestores de PIX, operadores de boleto);
>
> II — os **participantes diretos** (bancos, fintechs, instituições de pagamento que se relacionam diretamente com o fornecedor);
>
> III — os **participantes indiretos** que processem a liquidação em nome dos diretos."

### 3.1 Responsabilidade solidária

**Art. 32, §1º da LC 214/2025**

> "Caso o participante do arranjo que deveria efetuar a retenção e o recolhimento não o faça, a obrigação retorna ao **fornecedor contribuinte**, que permanece solidariamente responsável pelo valor do IBS e da CBS devidos, independentemente de sua atuação na liquidação."

### 3.2 Acompanhamento pelo fornecedor

**LC 227/2026, art. 32, IV** — A Diretoria de Arrecadação e Cobrança do CGIBS deve:

> "IV — estabelecer, em conjunto com a RFB, **mecanismo para acompanhamento, pelo fornecedor, do recolhimento** pelo adquirente."

O fornecedor terá acesso a painel de acompanhamento no sistema eletrônico do CGIBS para verificar se as retenções das suas operações foram efetivadas.

---

## 4. Hipóteses em que o split payment NÃO se aplica

**Art. 33 da LC 214/2025**

O split payment não se aplica a operações:

| Hipótese | Motivo |
|---|---|
| Pagamentos **em espécie** (dinheiro físico) | Não há arranjo de pagamento intermediário |
| Operações sujeitas a **regimes aduaneiros especiais** | Possuem tratamento próprio |
| **Compras governamentais** (art. 473 da LC 214/2025) | Fato gerador ocorre no pagamento; regime especial do art. 149-C da CF |
| Valor tributado **inferior ao limite mínimo** do regulamento | Micro-operações cujo custo de retenção supera o valor do tributo |
| Operações com **substituição tributária** em que o substituto recolhe antecipadamente | Tributo já foi recolhido em etapa anterior |
| **Diferimento** aprovado pelo CGIBS | Recolhimento postergado para etapa subsequente |

---

## 5. Direito ao crédito do adquirente — nascimento — LC 214/2025, art. 49 §1º

**Art. 49, §1º da LC 214/2025**

> "Nas operações sujeitas ao split payment, o direito ao crédito do adquirente nasce no **momento da liquidação financeira** da operação, independentemente do efetivo repasse ao CGIBS ou à RFB."

O adquirente **não precisa verificar** se o arranjo de pagamento efetivamente repassou o valor ao CGIBS para exercer seu direito ao crédito — o crédito nasce com a liquidação. O risco de inadimplemento do participante do arranjo não recai sobre o adquirente.

---

## 6. Restituição em caso de cancelamento ou devolução

**LC 227/2026 (ajustes à LC 214/2025)**

> "Nas hipóteses de cancelamento ou devolução de operações sujeitas ao split payment, a restituição do IBS e da CBS retidos deverá ocorrer em até **3 (três) dias úteis** após o estorno do débito ou o momento em que seria possível a apropriação de crédito pelo adquirente."

---

## 7. Procedimento simplificado — critérios opcionais

**Art. 34 da LC 214/2025**

> "O regulamento poderá estabelecer **procedimentos simplificados e opcionais** de split payment para:
>
> I — microempresas e empresas de pequeno porte optantes pelo Simples Nacional que optarem pelo recolhimento separado do IBS e da CBS;
>
> II — setores com particularidades operacionais que dificultem a aplicação do modelo padrão (ex.: vendas a prazo com múltiplos vencimentos, operações com cartões private label);
>
> III — arranjos de pagamento de menor porte ou com características tecnológicas específicas."

---

## 8. Penalidades pelo descumprimento — LC 214/2025, art. 471-D

**Art. 471-D da LC 214/2025**

> "O descumprimento das obrigações relativas ao split payment sujeitará os participantes dos arranjos de pagamento às seguintes **penalidades administrativas**:
>
> I — pela **não retenção** do IBS ou da CBS devidos: multa de **100% (cem por cento)** do valor do tributo não retido;
>
> II — pela **retenção sem o correspondente recolhimento** ao CGIBS ou à RFB: multa de **75% (setenta e cinco por cento)** do valor retido e não recolhido, além de juros de mora;
>
> III — pelo **recolhimento em prazo superior ao regulamentar**: multa de **0,33% (trinta e três centésimos por cento) por dia de atraso**, limitada a **20% (vinte por cento)** do valor do tributo."

### 8.1 Sujeito passivo das penalidades

As penalidades incidem sobre os **participantes dos arranjos de pagamento** responsáveis pela retenção — não sobre o fornecedor contribuinte, salvo quando este for solidariamente responsável por falha do arranjo.

### 8.2 Impacto para o contribuinte fornecedor

Se o arranjo não reter, o fornecedor permanece responsável pelo pagamento do tributo, podendo acionar o participante do arranjo para ressarcimento do valor eventualmente cobrado. A solidariedade do fornecedor é de natureza subsidiária — o Fisco deve primeiro exigir do participante do arranjo.

---

## 9. Supervisão pelo CGIBS e pela RFB

**LC 227/2026, art. 32**

A Diretoria de Arrecadação e Cobrança do CGIBS é responsável por:
- Monitorar o fluxo de retenções e recolhimentos via split payment em tempo real;
- Identificar participantes de arranjos inadimplentes;
- Coordenar com a RFB o acompanhamento do split payment da CBS;
- Estabelecer mecanismo de acompanhamento pelo fornecedor.

---

## 10. Quadro-resumo do split payment

| Aspecto | Regra |
|---|---|
| **Quem retém e recolhe** | Participantes dos arranjos de pagamento |
| **Prazo de recolhimento** | Até 3 dias úteis após a liquidação |
| **Destinatário do IBS** | CGIBS |
| **Destinatário da CBS** | RFB |
| **Crédito do adquirente** | Nasce na liquidação financeira (independe de repasse efetivo) |
| **Responsabilidade solidária** | Fornecedor, se o arranjo não reter |
| **Não se aplica a** | Pagamentos em espécie; compras governamentais; diferimento; substituição tributária; pequenas operações |
| **Cancelamento/devolução** | Restituição em até 3 dias úteis do estorno |
| **Penalidade — não retenção** | 100% do tributo |
| **Penalidade — retenção sem recolhimento** | 75% do retido + juros |
| **Penalidade — atraso no recolhimento** | 0,33%/dia, limitado a 20% |
| **Limite de financiamento CGIBS** | Até 0,2% da arrecadação do IBS (art. 47, I da LC 227) |

---

*Consulte também: [ad-distribuicao-entes.md](ad-distribuicao-entes.md) · [ad-conformidade-tributaria.md](ad-conformidade-tributaria.md) · [../ibs/ibs-operacionalizacao.md](../ibs/ibs-operacionalizacao.md) · [../processo-administrativo/pat-multas-penalidades.md](../processo-administrativo/pat-multas-penalidades.md)*

*Atualizado com base na LC 227/2026 (publicada em 13/01/2026).*
