# Entrega Parcial 02 — conteúdo do deck

> **Proposta de Valor & Business Model** · entrega em **05/10/2026** (portal da FIAP, conferido em
> 30/09/2026 — é a terceira data; antes 21/09 e 01/10). Requisitos em [`../entregas-fiap.md`](../entregas-fiap.md) §2 — inclusive o
> cruzamento entre o PDF oficial e o que o orientador pediu em voz na aula de 11/09 (§2.9).
>
> Este documento é a **fonte**; o `.pptx` é derivado. Corrija aqui e regere com a skill
> `gerar-deck` — editar só o `.pptx` faz os dois divergirem.
>
> ⚠️ **As páginas marcadas "(preliminar)" são a primeira versão de 19/09 e aguardam revisão do
> responsável do bloco** — páginas 2 a 4 com Felipe, 5 a 7 com Paulo, 8 e 9 com Diogo. As
> páginas 10 a 14 estão fechadas. A marca sai do título quando o dono revisar.
>
> Aberto em 19/09/2026. **Nenhuma entrevista foi realizada até esta data**; tudo que depende do
> campo está marcado como hipótese (ver a convenção abaixo); a página 13 diz o que cai junto com
> cada uma e a 14 é o plano de validação.

---

## A regra que governa este deck

O enunciado pede uma **lógica integrada de criação de valor** e fecha o checklist com a pergunta que
decide a nota: *"está claro o que já possui evidência e o que ainda é hipótese?"*. A aula de 11/09
disse o mesmo de outro jeito: canvas preenchido só com suposição é o erro nº 1.

Siglas que aparecem daqui em diante: **VPC** é o *Value Proposition Canvas* (canvas de proposta de
valor — tarefas, dores e ganhos do cliente de um lado; produtos, aliviadores de dor e criadores de
ganho do outro) e **BMC** é o *Business Model Canvas* (os nove blocos do modelo de negócio).

Por isso cada célula de canvas, cada traço de persona e cada bloco do BMC carrega uma marca:

| Marca | Significa                                                                        | De onde vem                                                                           |
| ----- | -------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------- |
| 🟢    | **evidência** — sustentado por fonte da Entrega 1                        | PRF 2024, CNT 2025, Oliveira & Carlotto 2020, relatos públicos, TRT-3, Portarias MTE |
| 🟡    | **hipótese** — o time acredita, ninguém confirmou                       | a validar por entrevista ou formulário (páginas 13 e 14)                            |
| ⚪    | **decisão de desenho** — escolha do time, não afirmação sobre o mundo | `arquitetura.md`, `modelo-de-negocio.md`                                          |

Três limites que valem para todas as páginas:

- **O produto aparece pelo *quê*, nunca pelo *como*.** Score de risco 24–72 h, PGR automático,
  check-in, rota e paradas — sim. Modelo, arquitetura, features, pipeline — não. O `ip-guardian`
  revisa antes de sair; esta é a primeira entrega que mostra a solução.
- **Sem número de resultado sem fonte.** "20–30% menos acidentes" e "payback < 12 meses" estão em
  `modelo-de-negocio.md` como premissa e **não entram aqui**. A aula mandou não precificar; o PDF
  manda a proposta nascer das evidências da Aula 01 — e são essas que sustentam o valor.
- **Nenhum entrevistado, empresa, praça ou integrante identificável.** Quando as entrevistas
  acontecerem, entram como "gestor de SST de transportadora de carga", nada mais.

### Sobre as personas

São **personas sintéticas**: compostas a partir das fontes públicas da Entrega 1 e do que o time
sabe do setor. Não descrevem nenhuma pessoa entrevistada. O deck diz isso na própria página, porque
o checklist pergunta se a persona "representa aprendizados reais" — e a resposta honesta hoje é
"reais, mas secundários".

---

# Slide 1 — Capa

> Entrega Parcial 02 · Proposta de Valor & Business Model

Gestão Preditiva de Riscos<br>Psicossociais no Transporte Rodoviário

Gabriel Santos · Diogo Veiga · Felipe Ciarini · Paulo Henrique

Orientador: Ricardo Francisco Esposto

FIAP · Startup One · Outubro de 2026

---

# Slide 2 — 01 · Base da Aula 01 (preliminar)

**O recorte que segue.** Fadiga e sofrimento psíquico de motoristas profissionais, em transportadoras
de carga com frota própria e motoristas CLT, em contexto de jornada longa, remuneração por produção
e descanso cobrado por punição. Fora: aplicativo e autônomo sem vínculo — sem empregador não há PGR.

| Hipótese da E1                          | O que ficou                        | Consequência para esta entrega                                                        |
| ---------------------------------------- | ---------------------------------- | -------------------------------------------------------------------------------------- |
| H1 · sinais aparecem dias antes         | 🟢 sustentada, indiretamente       | é o que torna a **predição** o benefício central                              |
| H2 · gestor trata como dor prioritária | 🟡**não testada**           | a hipótese mais cara do BMC — decide se o cliente paga por predição ou só por PGR |
| H3 · motorista resiste à coleta        | 🟢 ajustada: a causa é econômica | o produto tem de devolver algo ao motorista no mesmo ato                               |
| H4 · tecnologia atual age tarde         | 🟢 sustentada                      | o diferencial é*antes*, não *melhor*                                             |

```fonte
Entrega Parcial 01, seção 06 — PRF Dados Abertos 2024 · CNT 2025 · Oliveira & Carlotto 2020 · TRT-3 (22/07/2026)
```

<!-- coluna -->

> **Declaração do problema (5W2H)**
>
> Nosso **serviço de gestão preditiva de risco psicossocial** permitirá que **gestores de SST de
> transportadoras** saibam **quais motoristas estão entrando em risco de fadiga nas próximas 24–72 h
> e ajam antes da viagem**, o que afetará **motoristas profissionais** ao **substituir a punição
> posterior por uma pausa anterior** — e afetará a **transportadora** ao **transformar essa gestão no
> PGR psicossocial que a NR-1 exige desde 26/05/2026**.
>
> Mediremos a eficácia por: **(a)** proporção de motoristas com score alto abordados **antes** de
> iniciar a jornada; **(b)** PGR psicossocial emitido e aceito em auditoria sem ressalva; **(c)**
> sinistros e afastamentos por fadiga frente à linha de base da própria frota. 🟡 *As três métricas
> são propostas; (c) é lenta e só faz sentido com histórico.*

**O que mudou desde a E1:** a resistência do motorista deixou de ser problema de privacidade e virou
problema de renda. Isso reordena a proposta de valor: o motorista precisa **ganhar** com a pausa,
não só ser poupado por ela.

---

# Slide 3 — 02 · Persona do gestor de SST (preliminar)

*Persona sintética — composta de fontes públicas, não de entrevista.*

**Quem:** responsável por SST/RH de uma transportadora de carga com 200–2.000 motoristas CLT e frota
própria. Responde pelo PGR, pelo PCMSO, pelas autuações e pelo passivo trabalhista. Reporta à
diretoria e negocia com a seguradora.

| Dimensão                    | O que a persona vive                                                                                      | Marca |
| ---------------------------- | --------------------------------------------------------------------------------------------------------- | ----- |
| **Contexto**           | Frota dispersa; dado operacional abundante (telemetria, jornada), dado de saúde quase nenhum             | 🟢    |
| **Objetivo**           | Passar pela fiscalização sem autuação; reduzir sinistro, afastamento e reclamatória                  | 🟢    |
| **Comportamento hoje** | Cobra o descanso por advertência, suspensão e justa causa — depois do descumprimento                   | 🟢    |
| **Dor**                | Desde 26/05/2026 precisa **provar** que gerencia risco psicossocial — e não tem método para medir | 🟢    |
| **Necessidade**        | Um documento defensável para o auditor e um sinal acionável antes do sinistro                           | 🟡    |
| **Motivação**        | Evitar multa e MPT; não ser o nome no processo; ser visto como quem cuida da frota                       | 🟡    |

```fonte
Portarias MTE nº 1.419/2024 e nº 765/2025 · TRT da 3ª Região, 4ª Turma, decisão de 22/07/2026 · E1 slide 2
```

<!-- coluna -->

> **Mapa da empatia — gestor**
>
> **Vê:** o Diário de Bordo e o relatório de telemetria; o sinistro depois que aconteceu; a
> checklist do ERP que "atende a NR-1".
> **Ouve:** da diretoria, "resolve isso sem parar a operação"; do jurídico, "a partir de maio a
> fiscalização pode autuar"; do motorista, silêncio.
> **Pensa e sente:** que vai descobrir o problema pela multa ou pelo acidente — nunca antes.
> **Fala e faz:** compra checklist, contrata consultoria de SST, disciplina quem não cumpre pausa.
> **Dores:** sem método, sem tempo, sem dado de saúde — e agora com obrigação.
> **Ganhos:** PGR pronto, risco visível por frota, uma decisão possível antes da viagem.

🟡 **A hipótese que esta persona esconde.** O gestor pode tratar a NR-1 como papelada a terceirizar
pelo menor preço (H2). Se for assim, a dor é de conformidade, não de saúde — e a proposta de valor
muda de "antecipe o risco" para "tenha o PGR". A entrevista com gestor decide.

---

# Slide 4 — 02 · Persona do motorista (preliminar)

*Persona sintética — composta de fontes públicas, não de entrevista.*

| Dimensão                   | O que a persona vive                                                                                                                            | Marca    |
| --------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- | -------- |
| **Contexto**          | Longe de casa, dorme no trabalho; descansar depende de haver onde parar                                                                         | 🟢       |
| **Objetivo**          | Entregar no prazo e ganhar a produção — e chegar inteiro. Renda, família, voltar para casa                                                  | 🟢       |
| **Comportamento**     | Estende a jornada porque parar custa dinheiro; não fala de cansaço com a empresa                                                              | 🟢 · 🟡 |
| **Dor e necessidade** | Desgaste contínuo, não episódio; descanso cobrado sem condição de descansar. Queria saber **onde e quando** parar sem perder a viagem | 🟢 · 🟡 |

```kpi
10h42 | jornada diária média
*17,8% | acima de 12 h por dia
39,6% | dormem até 6 h
```

```fonte
CNT, Perfil e Preferências dos Caminhoneiros 2025 (n=800) · Agência Brasil, 20/09/2025 · Pé na Estrada, 28/05/2026
```

<!-- coluna -->

> **Mapa da empatia — motorista**
>
> **Vê:** o prazo, a estrada sem ponto de parada, o colega demitido por não cumprir pausa.
> **Ouve:** "tem que cumprir a lei", da empresa; "quando você volta?", da família.
> **Pensa e sente:** que ninguém oferece condição para descansar — só cobra; que falar de cansaço
> é arriscar o emprego.
> **Fala e faz:** segue viagem, dorme pouco, resolve sozinho.
> **Dores e ganhos:** parar custa e reclamar custa; queria uma pausa que não custasse a produção,
> e alguém que visse o risco antes dele.

```citacao
Setenta por cento do pessoal é comissionado. Se você não trabalhar, você não produz, você não ganha.
— Emerson André, motorista, à Agência Brasil (2025)
```

*Nota de apresentação: o que só a entrevista responde é se, recebendo a rota com paradas, o motorista aceita o check-in de 30 s — a hipótese H6, que sustenta a camada consentida. Está na página 13.*

---

# Slide 5 — 03 · Proposta de valor (preliminar)

**Benefício central:** saber **antes** — não depois.

Para o **gestor de SST**, em resposta à dor de ter de provar que gerencia risco psicossocial sem ter
método nem dado: um score de risco de fadiga por motorista, 24–72 h à frente, construído sobre o
dado operacional que a transportadora **já coleta**, e o PGR psicossocial gerado a partir dele —
auditável, no formato que a NR-1 pede.

Para o **motorista**, em resposta à dor de que parar custa e reclamar custa: a rota da viagem com os
pontos de parada **antes** do trecho em que o risco sobe, e a garantia de que o gestor vê a frota,
não a saúde de cada um.

| A Entrega 1 mostrou                                            | Logo, o valor é                         |
| -------------------------------------------------------------- | ---------------------------------------- |
| Dormir ao volante mata 2× mais que álcool por sinistro 🟢    | antecipar, porque o desfecho é letal    |
| O único instrumento de gestão do descanso é punir depois 🟢 | dar ao gestor uma ação **antes**  |
| Quem decide a pausa é quem perde dinheiro com ela 🟢          | fazer a pausa valer para o motorista     |
| A obrigação de gerir risco psicossocial está em vigor 🟢    | entregar o documento que prova a gestão |

<!-- coluna -->

> **Proposta única de valor — em uma frase**
>
> **O QAP Care antecipa em 24–72 h o risco de fadiga de cada motorista a partir do que a
> transportadora já coleta, e transforma essa gestão no PGR psicossocial que a NR-1 exige — sem
> que o gestor veja o dado de saúde de ninguém.**

*Nota de apresentação: a frase responde na ordem — o que oferecemos (predição + PGR), para quem (o gestor de SST de transportadora de carga), que problema (descobrir a fadiga pelo sinistro ou pela multa) e em que se diferencia (age antes, sem exigir que o motorista se exponha).*

⚪ **A decisão que a frase carrega:** o gestor recebe risco agregado e ação sugerida, nunca o dado
clínico individual — é o que faz o consentimento ser livre. 🟡 **O que ela ainda não provou:** que
o gestor paga pela predição, e não só pelo PGR (H2).

---

# Slide 6 — 03 · Canvas de proposta de valor: gestor (preliminar)

**Perfil do cliente** — preenchido antes do mapa de valor, na ordem da aula.

| Tarefas (jobs)                                    | Dores                                                           | Ganhos                                                 |
| ------------------------------------------------- | --------------------------------------------------------------- | ------------------------------------------------------ |
| Manter o PGR com risco psicossocial auditável 🟢 | Ter de provar gestão sem método nem dado de saúde 🟢         | PGR pronto para a fiscalização 🟡                    |
| Reduzir sinistro, afastamento e reclamatória 🟢  | Descobrir a fadiga pelo sinistro 🟢                             | Ver o risco da frota antes da viagem 🟡                |
| Gerir motoristas dispersos e escalas 🟢           | Só ter instrumentos punitivos (advertência → justa causa) 🟢 | Uma decisão possível: trocar escala, adiar saída 🟡 |
| Reportar à diretoria e à seguradora 🟡          | Câmera de fadiga alerta no momento crítico, tarde demais 🟡   | Argumento para a seguradora e a diretoria 🟡           |

<!-- coluna -->

**Mapa de valor** — o que o QAP Care põe contra cada linha.

| Produtos & serviços                              | Aliviadores de dor                                              | Criadores de ganho                        |
| ------------------------------------------------- | --------------------------------------------------------------- | ----------------------------------------- |
| Score de risco 24–72 h por motorista ⚪          | Sinal antes da viagem, não no volante ⚪                       | Mapa de risco da frota por dia e rota ⚪  |
| PGR psicossocial gerado da gestão real ⚪        | Método clínico validado por trás do score ⚪                 | Trilha de evidência para o auditor ⚪    |
| Base sobre dado operacional já coletado ⚪       | Funciona mesmo com adesão parcial do motorista ⚪              | Relatório para diretoria e seguradora 🟡 |
| Camada consentida: check-in e rota com paradas ⚪ | O gestor não vê dado de saúde individual — menos passivo ⚪ | —                                        |

> **Fit declarado, não medido.** As dores da coluna da esquerda têm evidência; os ganhos são o que
> **achamos** que o gestor valoriza. A pergunta da aula — "tenho evidência de que essas dores e
> essas soluções são relevantes para o cliente?" — só se responde com o gestor na frente.

---

# Slide 7 — 03 · Canvas de proposta de valor: motorista (preliminar)

**Perfil do usuário.** Não é quem paga — mas sem ele a camada que melhora a predição não existe, e a
E1 mostrou que a resistência dele tem causa econômica.

| Tarefas (jobs)                                     | Dores                                              | Ganhos                                     |
| -------------------------------------------------- | -------------------------------------------------- | ------------------------------------------ |
| Cumprir a viagem no prazo e ganhar a produção 🟢 | Parar custa dinheiro 🟢                            | Pausa que não custe a viagem 🟡           |
| Encontrar onde descansar 🟢                        | Não há ponto de parada quando o sono vem 🟢      | Saber antes onde e quando parar 🟡         |
| Cumprir a pausa legal sem ser punido 🟢            | Descanso cobrado por advertência e justa causa 🟢 | Não ser o próximo caso de justa causa 🟡 |
| Manter a família e voltar para casa 🟢            | Falar de cansaço com a empresa é risco 🟡        | Ser ouvido sem que o chefe leia 🟡         |

```citacao
Tem que ter uma boa estrada, tem que ter lugar de descanso. Querem cobrar descanso dentro da lei, mas não te oferecem essa situação.
— Del Caminhoneiro, 27 anos de profissão, à Agência Brasil (2025)
```

<!-- coluna -->

**Mapa de valor** — o que o motorista recebe no mesmo ato em que contribui.

| Produtos & serviços                                            | Aliviadores de dor                                       | Criadores de ganho                        |
| --------------------------------------------------------------- | -------------------------------------------------------- | ----------------------------------------- |
| Rota da viagem com pontos de parada antes do trecho de risco ⚪ | A pausa entra no planejamento, não na multa ⚪          | Chegar inteiro sem perder a produção 🟡 |
| Check-in emocional de 30 s, opcional ⚪                         | Recusar não desliga nada — o consentimento é livre ⚪ | Ver o próprio padrão de cansaço 🟡     |
| Abordagem antes da viagem quando o risco sobe ⚪                | O gestor vê a frota, não o indivíduo ⚪               | Alguém percebe antes dele 🟡             |

> **A troca que o produto propõe ao motorista:** informação útil para a viagem em troca de um sinal
> de 30 s — e nenhuma consequência disciplinar ligada ao dado. 🟡 Se ele não aceitar a troca, o
> produto continua funcionando sobre a camada operacional; o que se perde é precisão, não o
> produto. Esta é a hipótese H6 das páginas 13 e 14.

```fonte
Entrega 1, slides 8–9 · especificação interna de funcionalidade, não implementada
```

---

# Slide 8 — 04 · Jornada do usuário

⚠️ **Cenário sintético, não evidência de campo.** Construído sobre o roteiro de entrevista do time
para testar o instrumento. Tudo aqui é hipótese a validar.

| Momento | Motorista | Gestor e operação | Fricção atual | Oportunidade |
|---|---|---|---|---|
| **1 · Entrada** | Recebe treinamento e regras 🟡 | Registra treinamento e controles 🟡 | Não fica claro que informação é vista, por quem e com que efeito 🟡 | Segurança como apoio, não punição automática ⚪ |
| **2 · Escala** | Aceita rota e prazo; mais viagens, mais renda 🟡 | Combina veículo, carga, rota e janela 🟡 | Fecha no papel sem contar cansaço acumulado nem custo de parar 🟡 | Decidir antes da saída: horário, rota, pausa ou troca ⚪ |
| **3 · Estrada** | Percebe o sono e decide entre parar ou seguir para não perder o frete 🟡 | Acompanha rota e telemetria, sem agir 🟡 | O sinal fica com o motorista; nenhum contato preventivo aqui 🟡 | Planejar a parada antes do alerta crítico ⚪ |
| **4 · Alerta** | Recebe contato da central quando a câmera aponta 🟡 | Busca parada e tenta preservar a entrega 🟡 | O contato existe, mas chega tarde e improvisado 🟡 | Converter risco em ação: pausa, troca ou reprogramação ⚪ |
| **5 · Depois** | Explica o atraso e teme perder rotas 🟡 | Registra, investiga e alimenta o PGR 🟡 | A aprendizagem vem depois, e soa como cobrança 🟡 | Cada ocorrência revisa escala e controle ⚪ |

> **Onde a jornada dói mais.** O vazio não é depois do alerta de câmera — ali já existe contato da
> central. Está **entre o primeiro sinal que o motorista percebe e uma decisão operacional com tempo
> de agir**. É esse intervalo que o produto quer preencher, sem expor dado pessoal e sem reduzir
> segurança a um alerta tardio.

*Nota de apresentação: a simulação sugere que a fadiga não é só comportamento individual — prazo, remuneração por frete, escala, segurança da parada e capacidade de replanejar entram todos. Tudo isso precisa de validação em campo, e está no plano da página 14.*

---

# Slide 9 — 05 · Ecossistema e core

**Cenário sintético, não evidência de campo** — posições e interesses dos atores ainda precisam ser
validados, e o plano está na página 14.

| Ator | Papel | O que busca | Posição provável |
|---|---|---|---|
| **Motorista** | Usa; percebe o cansaço primeiro e decide parar ou seguir | Renda, entrega, segurança e privacidade | A favor se a pausa não custar; contra se for vigilância 🟡 |
| **Gestor de SST** | Recomenda ou compra; cuida de controles e do PGR | Menos risco e passivo; demonstrar gestão contínua | Aliado se houver decisão preventiva simples 🟡 |
| **Operação e central** | Monta escala e atua depois do alerta | Cumprir o prazo com alternativa viável | Aliada se o sinal vier com margem de ação 🟡 |
| **Diretoria e cliente final** | Uma aprova o orçamento; o outro define o prazo e a janela | Custo, reputação e seguro; previsibilidade na entrega | Diretoria neutra até ver redução de risco; o cliente amplia ou alivia a pressão 🟡 |
| **Fornecedores: telemetria, DMS, jornada e consultoria de SST** | Produzem o sinal de rota e tempo de direção; apoiam processo e documentação | Manter o contrato e entregar conformidade | Fonte e parceira — e concorrente na mesma casa 🟡 |
| **MTE, MPT, sindicatos e seguradora** | Regulam, fiscalizam e influenciam adesão | Proteção do trabalhador e menos sinistro | Alta relevância; posição não validada 🟡 |

> **A tensão que organiza o mapa:** o motorista precisa de proteção sem perder renda; a operação
> precisa decidir antes do atraso crítico; o SST precisa demonstrar gestão contínua. **O core é
> orquestrar essa prevenção entre os três** — câmera, dashboard e app viabilizam, não são o produto.

*Nota de apresentação: "startup não é aplicativo", como disse o orientador. Apoio e parceria: telemetria, câmera, controle de jornada, ERP, infraestrutura, consultoria e validação clínica; a central de operação é o canal que executa a decisão. Material de origem: simulação de pesquisa e documentos de trabalho do time, no repositório.*

---

# Slide 10 — 05 · Business Model Canvas

**Geração de valor**

| Bloco | Conteúdo | Marca |
|---|---|---|
| **Segmentos** | Transportadora de carga, 200–2.000 motoristas CLT, frota própria. | 🟢 recorte da E1 |
| **Proposta de valor** | Antecipar em 24–72 h o risco de fadiga com o dado que a empresa já coleta, mais os dados de saúde do motorista, sem expor o dado | ⚪ · 🟡 H2 |
| **Canais** | Direto ao gestor de SST; sindicato patronal; ERP; seguradora | 🟡 nenhum testado |
| **Relacionamento** | Quem paga: implantação, relatório, apoio na auditoria. Quem usa: o app canal | ⚪ · 🟡 |
| **Receita** | Recorrente = motoristas cadastrados e ativos × preço por motorista × meses. | 🟡 preço na E3 |

<!-- coluna -->

**Operação**

| Bloco | Conteúdo | Marca |
|---|---|---|
| **Recursos-chave** | Motor de risco; instrumento clínico validado (escala de sonolência e rastreio breve de humor); equipe de dados e de saúde; base longitudinal por frota | ⚪ · 🟡 a base como moat |
| **Atividades-chave** | Gerar o PGR; manter e validar o motor; vender B2B; intervir antes da viagem | ⚪ |
| **Parcerias-chave** | Telemetria; clínica de saúde do trabalhador; sindicato; ERP; seguradora | 🟡 nenhuma firmada |
| **Custo** | Fixo: equipe e conformidade. Por motorista: infraestrutura. Por venda: comercial B2B | ⚪ |

> **Cobra-se por motorista cadastrado e ativo.** O cliente paga pelo que usa, e quem sai da frota
> sai da conta.

*Nota de apresentação: se perguntarem o preço, nesta etapa não se precifica — a faixa é premissa da Entrega 3. O que se defende aqui é a variável, não o número. E sete dos nove blocos deste canvas dependem de algo nunca testado com cliente: a página 13 diz o que cai junto com cada hipótese.*

---

# Slide 11 — 06 · Matriz de concorrência

As colunas trazem o que cada empresa publica no próprio material

| Tipo | Quem | O que já faz hoje | O que não faz |
|---|---|---|---|
| **Status quo** | Consultoria ou SESMT; questionário em planilha, o SETCESP distribui um modelo grátis desde 08/2026 | Levanta percepção e produz o documento | Mede uma vez por campanha; não acompanha o dia a dia |
| **Direto** | Câmera de fadiga (Cobli, Ituran) | Detecta bocejo e olho fechado, com alerta na cabine no instante do evento | Nenhuma menção a NR-1 ou risco psicossocial no material de produto |
| **Direto, caso à parte** | Geotab | Já prevê risco por motorista, por comportamento de direção | Prevê colisão, não fadiga; sem horizonte nem instrumento clínico declarados; sem menção a NR-1 |
| **Indireto** | Saúde mental corporativa (Zenklub, Moodar) | Já entregam inventário de risco psicossocial para o PGR: HSE-IT e COPSOQ II | Questionário de campanha, não dado operacional contínuo; sem oferta setorial para transporte no material público; sem método e horizonte de predição publicados |
| **Substituto** | Praxio (software Globus), que declara presença em mais de metade das grandes operadoras de ônibus | Painel de Riscos Psicossociais desde 05/2026: Cruza afastamento por CID e escala para apontar padrão antes do afastamento | Análise por área, não score por motorista; sem horizonte, instrumento clínico ou camada de saúde declarados |

*Nota de apresentação: "o que não faz" significa "não identificamos na fonte pública consultada em 30/09/2026" — não é afirmação sobre capacidade não publicada nem sobre roadmap. Praxio e Globus são a mesma empresa: Globus é o software da Praxio. Nunca citar como dois concorrentes. Fontes e datas no registro do fact-checker, em modelo-de-negocio.md §10.*

---

# Slide 12 — 06 · Diferenciais e canais

A ameaça que imaginávamos como futura já aconteceu: antecipamos que o ERP poderia acoplar um módulo
de NR-1 psicossocial antes de nós, e ele acoplou em maio de 2026.

**O diferencial.** "Antecipar" e "Conformidade" já têm dono. O que ninguém oferece é a combinação:
score por motorista, horizonte de 24–72h, instrumento clínico validado e uma camada de saúde que o
gestor não enxerga.

| Critério | Veredito | Marca |
|---|---|---|
| **Difícil de copiar** | O método clínico e a base longitudinal, sim. Mas a base só existe depois de operar, e a Praxio já tem os clientes | 🟡 |
| **Relevante para o cliente** | A obrigação é real. Se o gestor paga por predição individual em vez do painel por área que já está no ERP dele | 🟡 |
| **Escalável** | Sem hardware novo, sobre dado que a empresa já coleta | 🟡 |

<!-- coluna -->

| Canais | Conteúdo | Marca |
|---|---|---|
| **Direto ao gestor de SST** | Tem a dor e o orçamento; ciclo longo | 🟡 |
| **Sindicato patronal** | Legitima e alcança muitos. E é também substituto: o SETCESP já distribui questionário de risco psicossocial de graça aos associados | 🟡 |
| **ERP de transporte** | Distribuição onde o dado está, e o concorrente mais próximo | 🟡 |
| **Seguradora de frota** | Interesse direto em menos sinistro | 🟡 |

*Nota de apresentação: o diferencial não passa nos três critérios hoje, e a matriz explica por quê — dois deles dependem de operar para existir. Dizer isso é mais defensável do que afirmar vantagem que ainda não temos.*

---

# Slide 13 — O que é evidência e o que é hipótese

| # | Hipótese | Se cair, o que muda no negócio |
|---|---|---|
| **H2** | O gestor paga por **antecipar**, não só pelo documento | Vira gerador de PGR com o score como acessório |
| **H5** | A escala é montada hoje **sem** olhar o histórico de jornada | O ganho marginal encolhe: a venda passa a ser sobre precisão, não sobre existir |
| **H6** | O motorista aceita o check-in em troca da rota | A camada de saúde não se forma; o produto fica de pé no operacional e perde o que o separa da telemetria |
| **H7** | O dado operacional já coletado sustenta a predição | **Fatal.** Sem isso não há produto preditivo, só um gerador de documento |
| **H8, H9** | Sindicato e ERP funcionam como canal; o SESMT vê o score como apoio | Volta para venda direta, com ciclo e custo maiores |

> **A H2 é a que mais pesa**, pois decide se vendemos saúde ou conformidade, duas propostas, dois
> preços, dois concorrentes. A H7 é a única fatal, as outras mudam o produto, essa decide se ele
> existe. E é a única que não depende de terceiros: sai de dado sintético e do motorista

*Nota de apresentação: o enunciado pede para tratar o modelo como hipótese, e é isso que esta página entrega. Se perguntarem pela H2: todo o canvas da página 10 muda de lugar conforme a resposta — proposta de valor, receita e concorrente ao mesmo tempo.*

---

# Slide 14 — Plano de validação

| Hipótese | Como se resolve | Depende de | Quando |
|---|---|---|---|
| **H2, H5** | 5 entrevistas com gestor de SST de transportadora de carga | Agenda de terceiros | Entrega 3 |
| **H6** | 3 entrevistas com motorista + protótipo da tela de rota | Agenda; depois, protótipo | E3 / E4 |
| **H8, H9** | Conversa exploratória com sindicato patronal, com um ERP e com médico do trabalho | Agenda | Entrega 3 |
| **Concorrência** | Conferência em fonte pública primária | só de nós | Feito nesta entrega |

O que já é evidência veio da Entrega 1: a letalidade do sono ao volante, o limiar das 12h com razão
de chances 3,33, e o descanso cobrado por punição. O que não é: tudo sobre como o gestor decide e
pelo que paga. E o que foi validado sem depender de ninguém nesta etapa: a matriz de concorrência.

*Nota de apresentação — dizer em voz alta, porque saiu do slide e continua valendo: não houve validação de campo nesta etapa. Os roteiros estão prontos desde agosto e o método está escolhido; as conversas não aconteceram porque dependem da agenda de terceiros, o único insumo do projeto que não controlamos. Declarar isso vale mais do que apresentar suposição com cara de achado.*

*Nota de apresentação — o método, se a banca perguntar: Teste da Mãe, em `pesquisa-campo.md`. Pergunta-se pela última viagem e pelo último caso real, nunca pelo que a pessoa acha que faria; não se apresenta o produto; registra-se sem nome, empresa ou praça. Dois roteiros prontos, um por persona. E o viés que teremos de declarar: o acesso à amostra virá de contato profissional do time no setor de transporte, o que encurta o caminho e enviesa a amostra.*

*Nota de apresentação — a H7 saiu da tabela por espaço, mas é a que resolve sozinha: baseline sobre coorte sintética, com métrica registrada, e depois o piloto. Entrega 4, e não depende de terceiros.*

## Checklist antes de entregar

- [ ] O público prioritário está definido e sustentado pela E1 (gestor de SST; motorista como usuário)?
- [ ] As personas dizem na própria página que são sintéticas — ou já foram confrontadas com entrevista?
- [ ] A proposta de valor responde a uma dor com evidência, e a UVP cabe em uma frase?
- [ ] O VPC marca célula por célula o que é evidência e o que é hipótese?
- [ ] A jornada mostra o vazio entre o sinal e a ação — e nada do *como* técnico?
- [ ] O BMC tem receita como variável, sem preço, e "moat de dados" como hipótese?
- [ ] A matriz de concorrência tem status quo e substituto, e o diferencial passou pelos três critérios?
- [ ] Os concorrentes nomeados passaram pelo `fact-checker`, e o que ele achou está refletido na página 11?
- [ ] A página 13 diz, hipótese por hipótese, **o que muda no negócio se ela cair**?
- [ ] A página 14 declara que **não houve validação de campo** nesta etapa, e quando cada hipótese se resolve?
- [ ] Nenhum entrevistado, empresa, praça ou integrante é identificável?
- [ ] O material passou pelo `ip-guardian` — e a linha do inventário (§2.6) tem veredito antes do envio?
- [ ] Nenhum número de resultado (redução de acidentes, payback) sem fonte?
