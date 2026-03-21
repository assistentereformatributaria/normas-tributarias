# Base Pública — Reforma Tributária do Consumo

> Documentação estruturada das normas que instituem o novo sistema de tributação sobre o consumo no Brasil, organizada por tema e com referenciamento cruzado aos dispositivos legais.

---

## Normas-fonte

| Norma | Ementa resumida | Vigência |
|---|---|---|
| [EC 132/2023](normas-fonte.md#ec-1322023) | Altera o Sistema Tributário Nacional — base constitucional da reforma | Promulgada em 20/12/2023 |
| [LC 214/2025](normas-fonte.md#lc-2142025) | Institui o IBS, a CBS e o IS; cria o Comitê Gestor do IBS | Publicada em 16/01/2025 |
| [LC 227/2026](normas-fonte.md#lc-2272026) | Institui o CGIBS; dispõe sobre o PAT do IBS; normas gerais do ITCMD; altera diversas leis | Publicada em 13/01/2026 |

---

## Estrutura do repositório

```
reforma-tributaria/
│
├── README.md                          ← este arquivo
├── normas-fonte.md                    ← quadro das três normas-fonte
├── principios-gerais.md               ← princípios do STN e da neutralidade
├── glossario.md                       ← definições legais unificadas
│
├── ibs/                               ← Imposto sobre Bens e Serviços
│   ├── ibs-visao-geral.md
│   ├── ibs-incidencia.md
│   ├── ibs-nao-incidencia.md
│   ├── ibs-fornecimento-misto.md
│   ├── ibs-imunidades.md
│   ├── ibs-fato-gerador.md
│   ├── ibs-local-operacao.md
│   ├── ibs-base-calculo.md
│   ├── ibs-aliquotas.md
│   ├── ibs-sujeito-passivo.md
│   ├── ibs-nao-cumulatividade.md
│   ├── ibs-creditamento.md
│   ├── ibs-operacionalizacao.md
│   ├── ibs-importacoes.md
│   └── ibs-exportacoes.md
│
├── cbs/                               ← Contribuição Social sobre Bens e Serviços
│   ├── cbs-visao-geral.md
│   ├── cbs-aliquotas.md
│   ├── cbs-base-calculo.md
│   ├── cbs-regras-comuns-ibs.md
│   └── cbs-consulta-harmonizacao.md
│
├── comite-gestor/                     ← Comitê Gestor do IBS (CGIBS)
│   ├── cg-visao-geral.md
│   ├── cg-competencias.md
│   ├── cg-fiscalizacao-cobranca.md
│   ├── cg-estrutura-orgaos.md
│   ├── cg-conselho-superior.md
│   ├── cg-deliberacoes.md
│   ├── cg-presidencia.md
│   ├── cg-diretoria-executiva.md
│   ├── cg-corregedoria.md
│   ├── cg-auditoria-interna.md
│   ├── cg-financiamento.md
│   ├── cg-integracao-rfb.md
│   ├── cg-regulamento-unico.md
│   └── cg-escola-nacional.md
│
├── processo-administrativo/           ← PAT do IBS
│   ├── pat-visao-geral.md
│   ├── pat-lancamento-oficio.md
│   ├── pat-1a-instancia.md
│   ├── pat-2a-instancia.md
│   ├── pat-3a-instancia.md
│   ├── pat-rito-sumario.md
│   ├── pat-consulta-tributaria.md
│   ├── pat-solucao-conflitos.md
│   └── pat-multas-penalidades.md
│
├── arrecadacao-distribuicao/          ← Arrecadação e distribuição do IBS
│   ├── ad-split-payment.md
│   ├── ad-distribuicao-entes.md
│   ├── ad-receita-media-referencia.md
│   ├── ad-retencoes-compensacoes.md
│   ├── ad-fundo-combate-pobreza.md
│   └── ad-conformidade-tributaria.md
│
├── imposto-seletivo/                  ← Imposto Seletivo (IS)
│   ├── is-visao-geral.md
│   ├── is-fato-gerador.md
│   ├── is-nao-incidencia.md
│   ├── is-base-calculo.md
│   ├── is-integracao-outros-tributos.md
│   ├── is-biocombustiveis.md
│   ├── is-compensacao-ipi.md
│   └── is-alteracoes-lc227.md
│
├── regimes-diferenciados/             ← Regimes diferenciados de tributação
│   ├── rd-disposicoes-gerais.md
│   ├── rd-reducao-30-porcento.md
│   ├── rd-reducao-60-porcento.md
│   ├── rd-reducao-zero.md
│   ├── rd-transporte-coletivo.md
│   ├── rd-reabilitacao-urbana.md
│   ├── rd-produtor-rural.md
│   └── rd-simples-nacional.md
│
├── regimes-especificos/               ← Regimes específicos setoriais
│   ├── re-combustiveis.md
│   ├── re-servicos-financeiros.md
│   ├── re-planos-saude.md
│   ├── re-concursos-prognosticos.md
│   ├── re-bens-imoveis.md
│   ├── re-cooperativas.md
│   ├── re-turismo-hotelaria.md
│   ├── re-saf-futebol.md
│   ├── re-diplomatico.md
│   └── re-prouni.md
│
├── regimes-aduaneiros/                ← Regimes aduaneiros e bens de capital
│   ├── regimes-aduaneiros-especiais.md
│   ├── zpex.md
│   ├── bens-de-capital.md
│   └── bagagem-remessas.md
│
├── cashback/                          ← Devolução e cesta básica
│   ├── cashback-visao-geral.md
│   ├── cashback-energia-gas.md
│   ├── cashback-cbs-federal.md
│   └── cesta-basica-nacional.md
│
├── itcmd/                             ← ITCMD: normas gerais nacionais
│   ├── itcmd-visao-geral.md
│   ├── itcmd-fato-gerador.md
│   ├── itcmd-base-calculo.md
│   ├── itcmd-aliquotas.md
│   ├── itcmd-imunidades.md
│   ├── itcmd-transmissoes-internacionais.md
│   ├── itcmd-trusts.md
│   ├── itcmd-holdings.md
│   ├── itcmd-competencia-territorial.md
│   └── itcmd-fiscalizacao-arrecadacao.md
│
├── transicao/                         ← Transição tributária 2026–2033
│   ├── transicao-visao-geral.md
│   ├── transicao-2026-fase-teste.md
│   ├── transicao-2027-2028.md
│   ├── transicao-2029-2032.md
│   ├── transicao-2033.md
│   ├── transicao-aliquotas-referencia.md
│   ├── transicao-distribuicao-ibs-2029-2077.md
│   ├── transicao-receita-media-referencia.md
│   ├── transicao-creditos-icms.md
│   ├── transicao-creditos-pis-cofins.md
│   ├── transicao-beneficios-fiscais-icms.md
│   ├── transicao-bens-de-capital.md
│   ├── transicao-compras-governamentais.md
│   └── transicao-avaliacao-quinquenal.md
│
├── fndr/                              ← Fundo Nacional de Desenvolvimento Regional
│   ├── fndr-visao-geral.md
│   ├── fndr-coeficientes.md
│   ├── fndr-sustentabilidade.md
│   ├── fundo-amazonas.md
│   └── fundo-amazonia-ocidental.md
│
├── zona-franca/                       ← Zona Franca de Manaus e ALC
│   ├── zfm-diferencial-competitivo.md
│   ├── zfm-instrumentos.md
│   ├── alc-areas-livre-comercio.md
│   └── devolucao-turista-estrangeiro.md
│
├── compras-governamentais/            ← Compras governamentais
│   ├── adm-publica-tributacao.md
│   └── adm-publica-transicao.md
│
├── alteracoes-legislativas/           ← Alterações promovidas pela LC 227/2026
│   ├── al-ctn.md
│   ├── al-lei-kandir.md
│   ├── al-simples-nacional.md
│   ├── al-fundeb.md
│   ├── al-lc63-municipios.md
│   ├── al-lc141-saude.md
│   ├── al-lc192-combustiveis.md
│   ├── al-crimes-responsabilidade.md
│   ├── al-afrmm.md
│   └── al-lc214-ajustes.md
│
└── outros/                            ← Outros dispositivos constitucionais alterados
    ├── ibs-cbs-harmonizacao.md
    ├── ipva-reformulado.md
    ├── itbi-atualizacao.md
    ├── iluminacao-publica.md
    ├── distribuicao-ibs-municipios.md
    ├── administracoes-tributarias.md
    └── receitas-is-estados.md
```

---

## Mapa normativo — temas por norma-fonte

### EC 132/2023 — Emenda Constitucional

Estabelece a **base constitucional** da reforma. Seus dispositivos principais:

| Dispositivo | Tema |
|---|---|
| Art. 145 §§3º-4º | Princípios do Sistema Tributário Nacional |
| Art. 149-A | Contribuição de iluminação pública |
| Art. 149-B | Harmonização obrigatória IBS–CBS |
| Art. 149-C | Tributação das contratações públicas |
| Art. 153, VIII e §6º | Imposto Seletivo |
| Art. 155 §1º VI-VII | ITCMD — progressividade e imunidades |
| Art. 155 §6º II-III | IPVA — veículos aquáticos, aéreos e critérios ambientais |
| Art. 156-A e §§ | IBS — regras gerais constitucionais |
| Art. 156-B e §§ | Comitê Gestor do IBS |
| Art. 158 §2º | Distribuição do IBS aos Municípios |
| Art. 159-A | Fundo Nacional de Desenvolvimento Regional |
| Art. 195 V e §§15-19 | CBS — base constitucional |
| Art. 225 §1º VIII | Regime favorecido para biocombustíveis |
| Arts. 124–136 ADCT | Transição tributária |
| Art. 92-B ADCT | Zona Franca de Manaus |
| Art. 159-A | FNDR |

### LC 214/2025 — Lei Complementar

Institui o IBS, a CBS e o IS em nível infraconstitucional (~544 artigos):

| Livro/Título | Tema |
|---|---|
| Livro I, Título I | Normas gerais do IBS e da CBS (arts. 1–83) |
| Livro I, Título II | Regimes aduaneiros e bens de capital (arts. 84–111) |
| Livro I, Título III | Cashback e cesta básica (arts. 112–124) |
| Livro I, Título IV | Regimes diferenciados (arts. 125–171) |
| Livro I, Título V | Regimes específicos (arts. 172–300) |
| Livro II | Administração tributária do IBS e CBS (arts. 301–408) |
| Livro III | Imposto Seletivo (arts. 409–480) |
| Livro IV | Disposições transitórias e finais (arts. 481–544) |

### LC 227/2026 — Lei Complementar

Regulamenta institucionalmente o CGIBS e temas complementares (~181 artigos + alterações):

| Livro/Título | Tema |
|---|---|
| Livro I, Título I | Comitê Gestor do IBS — estrutura, competências e organização (arts. 1–99) |
| Livro I, Título II | Processo Administrativo Tributário do IBS (arts. 100–136) |
| Livro I, Título III | Arrecadação e distribuição do IBS (arts. 137–145) |
| Livro II | Normas gerais do ITCMD (arts. 146–165) |
| Livro III | Alterações legislativas em ~12 normas (arts. 166–181) |

---

## Convenções de referenciamento

Os arquivos desta base adotam as seguintes convenções para referências normativas:

- **EC 132** → `EC 132/2023, art. X [§Y] [inciso Z]`
- **LC 214** → `LC 214/2025, art. X [§Y] [inciso Z]`
- **LC 227** → `LC 227/2026, art. X [§Y] [inciso Z]`
- **CF** → `CF/1988, art. X` (para artigos da Constituição Federal não alterados pela EC 132)
- **ADCT** → `ADCT, art. X` (disposições transitórias)
- Referências internas entre arquivos desta base: `[texto do link](../pasta/arquivo.md)`

---

## Sobre este repositório

Esta base foi estruturada para fins de **consulta pública, pesquisa e estudo** da Reforma Tributária do Consumo no Brasil, com foco na tríade normativa:

- **EC 132/2023** — promulgada em 20 de dezembro de 2023
- **LC 214/2025** — publicada em 16 de janeiro de 2025
- **LC 227/2026** — publicada em 13 de janeiro de 2026

Os textos normativos reproduzidos são de domínio público, nos termos do art. 8º, I, da Lei nº 9.610/1998.

> **Aviso:** este repositório tem caráter informativo e de referência. Para fins jurídicos, consulte sempre os textos oficiais publicados no Diário Oficial da União e disponíveis em [www.planalto.gov.br](https://www.planalto.gov.br).

---

*Atualizado com base na LC 227/2026 (publicada em 13/01/2026).*
