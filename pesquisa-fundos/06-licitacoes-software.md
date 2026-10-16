# 06 — Licitações públicas de software e apps (Lei 14.133/2021 e Lei 13.303/2016)

*Pesquisa de mercado, 16/10/2026. Cliente: dev com PJ de menos de 1 ano, mais um sócio/amigo com PJ mais antiga, sem histórico em licitações. Hipótese: usar IA para preparar propostas e, se ganhar, contratar gente para entregar.*

> Aviso de método: o PNCP, o Planalto e alguns portais privados não abriram neste ambiente (DNS/proxy bloqueado). Por isso os textos de lei e os números vieram de fontes secundárias: editais, pareceres, TCU, Zênite, Effecti, CNM. O que não conferi na fonte primária está marcado como **(não confirmado)**.

---

## Resumo

1. É um mercado grande e recorrente. Todo órgão público (5.568 municípios, mais câmaras, autarquias, universidades, estatais e consórcios) compra software o tempo todo, e tudo é publicado no PNCP. Para pequenos órgãos, o ticket típico vai de R$ 20 mil a R$ 120 mil por app ou sistema sob encomenda.
2. A porta de entrada realista para empresa nova é a **dispensa eletrônica por valor** (até **R$ 65.492,11** em serviços em 2026) e o **pregão exclusivo para ME/EPP** (itens até R$ 80 mil). Nesses casos muitas vezes não se exige atestado, ou exige-se um atestado simples.
3. O grande obstáculo é o **atestado de capacidade técnica em nome da própria PJ**. O TCU não deixa uma PJ usar o atestado de outra, nem com sócios em comum. A PJ do amigo só ajuda se for **ela** a licitante.
4. Quase sempre o critério é **menor preço**, com disputa de lances. IA e desenvolvimento acelerado dão uma vantagem real de custo. Os riscos são o mergulho de preço (abaixo de cerca de 50% do estimado vira indício de inexequibilidade), os **atrasos de pagamento** (29% das prefeituras atrasavam fornecedores em dez/2025) e as sanções por inexecução.
5. **Nota de chances: 6/10.** É viável como canal complementar, começando por dispensas pequenas para formar atestados. Não serve como fonte principal de receita nos primeiros 12 a 18 meses.

---

## Como funciona

**Base legal**
- **Lei 14.133/2021** (administração direta, autarquias, fundações, câmaras, consórcios públicos).
- **Lei 13.303/2016** para estatais: cada uma tem regulamento próprio de licitações, e o pregão também é usado.
- **LC 123/2006** para o tratamento favorecido de ME/EPP.

**Modalidades e caminhos relevantes para software**

| Caminho | Quando | O que significa para nós |
|---|---|---|
| **Dispensa por valor** (art. 75, II) | Serviços até **R$ 65.492,11** em 2026 (Decreto 12.807/2025, em vigor desde 01/01/2026; antes era R$ 62.021,48). Obras e serviços de engenharia até R$ 130.984,20 | Feita por "dispensa eletrônica": cotação aberta de 3 dias úteis ou mais no Compras.gov.br ou em portal privado, com lances. Exigências de habilitação mais leves. **É a melhor porta de entrada.** |
| **Pregão eletrônico** | Serviço comum, que inclui fábrica de software, desenvolvimento sob demanda e locação de sistema | Menor preço ou maior desconto. Lances abertos ou aberto-fechado. A habilitação só é analisada para o 1º colocado. |
| **Concorrência** (técnica e preço) | Serviços intelectuais, ou quando o órgão quer pontuar a técnica | É rara em municípios pequenos. Aparece mais em órgãos federais e estatais. |
| **Registro de preços (SRP/ARP)** | "Fábrica de software" por UST ou PF, com demanda incerta | A ata garante o preço, não o volume. Pode ser aderida por outros órgãos (carona). |
| **Inexigibilidade** | Produto exclusivo ou serviço técnico especializado de notória especialização | Não se aplica a nós no início. |

**Valores atualizados para 2026 (Decreto 12.807/2025)**, segundo ConLicitação e Effecti (não confirmado no Diário Oficial):
- Dispensa de compras e serviços: R$ 65.492,11
- Dispensa de obras e engenharia: R$ 130.984,20
- Serviços técnicos especializados ou P&D: R$ 392.952,63
- Grande vulto: acima de R$ 261.968.421,04

**ME/EPP (LC 123, arts. 42 a 49)**
- **Licitação exclusiva para ME/EPP** em itens de até **R$ 80.000**. Esse valor não foi atualizado pelo decreto.
- **Cota reservada de até 25%** em bens divisíveis acima de R$ 80 mil. Vale para bens, não para serviços de software.
- **Empate ficto:** a ME/EPP com lance até **5% acima** do melhor lance (no pregão) pode cobrir a oferta.
- **Regularidade fiscal tardia:** a ME/EPP pode regularizar certidões em 5 dias úteis depois de declarada vencedora.
- Pelo art. 4º da Lei 14.133, esses benefícios **não valem** para itens acima do limite de receita de EPP (R$ 4,8 milhões) nem para a empresa que já tenha contratos com a Administração acima desse limite no ano.

**Portais**
- **PNCP** (pncp.gov.br): agregador obrigatório. Tem API de busca, útil para automação.
- **Compras.gov.br**: federal e muitos municípios.
- **BLL, BNC, Licitar Digital, Portal de Compras Públicas, Licitações-e (BB), BBMNet** e portais municipais próprios.
- O cadastro é feito em cada plataforma. O **SICAF** é necessário no Compras.gov.br, e alguns portais privados cobram taxa do fornecedor (valores **não confirmados**).

**Ferramentas de monitoramento**
- Effecti, ConLicitação (que já tem o "ConLicita IA", com assistente jurídico e geração de petições), Siga Pregão, Alerta Licitação, LicitaJá, BuscarLicitação.
- Alerta Licitação: R$ 44,90/mês, ou cerca de R$ 31/mês no plano anual.
- Effecti, ConLicitação e Siga Pregão: preços sob consulta, estimados entre R$ 150 e R$ 600/mês (**não confirmado**).
- Alternativa barata: um robô próprio sobre a API do PNCP com triagem por LLM. Um TCC do IFBA de 2026 (Licita.AI) faz exatamente isso.

---

## Volume e recorrência

- **Não encontrei estatística consolidada** de "licitações de software por ano" (**não confirmado**). O PNCP permite medir isso por API, mas não consegui acessar daqui.
- Estimativa (**não confirmada**): existem cerca de 5.568 prefeituras e cerca de 5.500 câmaras, e quase todas contratam ao menos um destes itens por ano: site/portal da transparência, sistema legislativo, ouvidoria/e-SIC, app de serviços, diário escolar digital, controle de ponto, sistemas de saúde. Isso dá **dezenas de milhares de processos de TI por ano** no PNCP, somando dispensas e pregões.
- **Atenção:** a maior parte é **locação de software pronto (SaaS)**, e não desenvolvimento sob encomenda. A fatia de "desenvolver um app do zero" é bem menor.
- **Recorrência:**
  - Locação de sistema e sustentação são contratos de 12 meses, prorrogáveis por até 10 anos em serviços contínuos.
  - Desenvolvimento sob encomenda é pontual, mas costuma gerar um contrato de manutenção depois.
  - A fábrica de software por UST ou PF fica concentrada em órgãos maiores: estados, capitais, tribunais, estatais.
- **Concentração:** no software de gestão pública municipal (ERP, folha, tributos), players estabelecidos como Betha, IPM, Fiorilli e Elotech dominam. Os editais exigem dezenas de módulos e integração com o Tribunal de Contas estadual. O TCE/SC abriu consulta pública em 2025 para padronizar esse tipo de contratação. **Não é um nicho para nós.**

**Valores típicos observados em pequenos órgãos (2026)**

| Órgão | Objeto | Modalidade | Valor |
|---|---|---|---|
| Câmara de Américo Brasiliense/SP | Aplicação web full stack de integração com as APIs do AUDESP (TCE-SP) | Dispensa 033/2026 | R$ 51.222,50 (vencedora: 8BITS Tecnologia) |
| Câmara de Itinga do Maranhão/MA | Sistema de votação eletrônica + app mobile | Dispensa 006/2026 | R$ 63.600,00 |
| Câmara de Centenário do Sul/PR | Site, e-mail e sistema legislativo | Dispensa eletrônica 001/2026 | R$ 28.266,58 (estimado) |
| Prefeitura de São Paulo/SP | App web/mobile de táxi para uso municipal | Contrato jun/2026 | R$ 98.238,00 (não confirmado se esse é o valor do item) |
| Prefeitura de Itaúba/MT | Sistema de controle de ponto eletrônico | Pregão 2026 | Estimado R$ 810.533,50, homologado R$ 732.782,00 (deságio de cerca de 10%) |
| Quatiguá/PR | Sistema integrado de gestão pública | Pregão 21/2026 | cerca de R$ 2,35 milhões (estimado) |

---

## Exemplos recentes

| Órgão | Objeto | Situação | Valor |
|---|---|---|---|
| **EMATER-DF**, PE/SRP 90003/2026 | Fábrica de software (sistemas, apps, portais) por 60 meses, sob Ordens de Serviço | Sessão em 16/07/2026 | Não visto |
| **Prefeitura de Rio Branco/AC**, PE/SRP 90220/2026 | Sustentação e desenvolvimento de software (valor fixo mensal mais horas técnicas) | Sessão em 06/07/2026 | Não visto |
| **Convales/MG** (consórcio) | Desenvolvimento de aplicativo | Propostas até 09/10/2026 no portal BNC | Valor mascarado no agregador (não confirmado) |
| **Itacambira/MG** | Diário escolar digital, web e/ou app | Pregão 2026 | Não visto |
| **Superintendência Nacional de Previdência Complementar**, PE 33/2025 | Desenvolvimento e sustentação sob demanda | 2025 | cerca de R$ 2,1 milhões |
| **Ministério da Fazenda / BASA**, PE 7/2026 | Evolução de produtos de software, SRP de 5 anos | 2026 | R$ 821 milhões (fora do nosso alcance; só ilustra a escala) |

**Referências de preço unitário (fábrica de software)**
- **UST:** a CAST Informática registrou R$ 99,95/UST na ata do MP-GO de 2022/23 (300 mil UST).
- **Ponto de função:** os modelos de proposta do BNB (2018) usavam referências de R$ 2.592 a R$ 6.800/PF. Não está claro se eram estimativas ou preços vencedores.
- Não achei médias municipais de 2025/26 (**não confirmado**).

Todos os editais abertos acima já passaram da data. É preciso buscar editais **abertos hoje** direto no PNCP, filtrando por "aplicativo", "desenvolvimento de sistema" e "fábrica de software", com status "recebendo proposta".

---

## Pré-requisitos (habilitação)

**Documentos padrão (arts. 62 a 70 da Lei 14.133)**
1. **Jurídica:** contrato social e CNPJ. O **CNAE** precisa ser compatível, por exemplo 6201-5/01 (desenvolvimento sob encomenda), 6202-3/00, 6203-1/00, 6204-0/00 ou 6209-1/00. Um CNAE incompatível é motivo comum de inabilitação.
2. **Fiscal, social e trabalhista:**
   - CND federal/INSS, FGTS (CRF), CNDT, estadual e municipal.
   - Declarações de cumprimento do art. 7º, XXXIII da Constituição (menor), de reserva de cargos e de enquadramento ME/EPP.
3. **Econômico-financeira (art. 69):**
   - Balanço patrimonial, DRE e índices (LG, SG, LC maiores que 1). Às vezes também capital ou patrimônio líquido mínimo de até 10% do valor estimado.
   - **Empresa constituída há menos de 2 anos** apresenta só o último exercício (art. 69, §6º).
   - **Empresa criada no próprio exercício da licitação** pode apresentar **balanço de abertura** (art. 65, §1º).
   - **Atenção:** se a PJ do cliente foi aberta em 2025, ela **não** pode usar balanço de abertura em 2026. Precisa do balanço de 2025 (o esclarecimento do MPRS PE 94/2026 confirma esse entendimento).
   - Há controvérsia sobre o registro do balanço na Junta. A Zênite defende que ele é necessário. É bom ter um contador que faça o balanço "padrão licitação".
4. **Qualificação técnica (art. 67):** é **o grande obstáculo**.
   - **Técnico-operacional:** atestados em nome da **própria PJ licitante**, emitidos por pessoa jurídica pública ou privada, de serviço similar.
     - O atestado só pode ser exigido para parcelas de maior relevância (pelo menos 4% do valor).
     - A quantidade mínima exigida é de **até 50%** dessas parcelas.
     - São vedadas limitações de tempo e de local.
     - Em geral **pode-se somar vários atestados**.
   - **Técnico-profissional:** um profissional do quadro (sócio, empregado ou contratado) com experiência comprovada. Em TI às vezes pedem certificações (Scrum, PMP, ITIL, cloud) ou diplomas. Isso é mais comum em fábrica de software de órgão grande.
   - **Atestado de potencial subcontratado** (art. 67, §9º): o edital *pode* aceitar atestados de um subcontratado para aspectos técnicos específicos, limitados a **25% do objeto**. Há debate se isso é faculdade ou dever do órgão; o TCU, no Acórdão 1.923/2025, já leu como dever em itens especializados.
5. **SICAF** (Compras.gov.br) e cadastros em cada portal. Exigem certificado digital e-CNPJ A1 ou A3.

**Restrições importantes (TCU)**
- **Não se pode usar atestado de outra PJ**, nem com os mesmos sócios. O TCU já considerou irregular habilitar com atestado em nome de outra pessoa jurídica (Acórdão 673/2020 e Plenário). A exceção é reorganização societária real, como cisão ou incorporação com transferência de acervo.
- **Autoatestação é vedada.** Um atestado emitido por empresa de parente ou de sócio é zona cinzenta: há editais que proíbem atestados de empresas do mesmo grupo.

**Como empresas novas contornam**

| Estratégia | Viabilidade | Comentário |
|---|---|---|
| **Licitar com a PJ do sócio/amigo** (a mais antiga) | **Alta, se ela tiver CNAE de TI, balanço limpo e atestados** | É o caminho mais rápido. O cliente entra como profissional técnico ou subcontratado. É preciso um acordo formal de divisão de resultado. |
| **Atestados de clientes privados** | Alta | Todo projeto já entregue pela PJ do cliente pode virar atestado: papel timbrado, descrição do escopo, período, valor e contato, de preferência com contrato e notas fiscais como lastro. **Fazer isso já.** |
| **Dispensas pequenas para formar atestado** | Alta | Atestado de órgão público pesa mais. Dispensas de R$ 10 a 60 mil (sites, pequenos sistemas, integrações com o TCE) exigem pouco. |
| **Consórcio** (art. 15) | Média | Permite somar atestados e índices dos consorciados. Há acréscimo de 10% a 30% nas exigências econômicas, que não se aplica a consórcio composto só de ME/EPP. O edital pode vedar consórcio. |
| **Subcontratação** (art. 122) | Média | Depende de o edital permitir. A responsabilidade continua com o contratado. |
| **Impugnar exigências excessivas** | Média | Exigência de atestado sem justificativa técnica, acima de 50%, com limite de tempo ou com certificação desnecessária é impugnável até 3 dias úteis antes da sessão. A IA ajuda muito a redigir. |

---

## Critérios de julgamento

- **Menor preço ou maior desconto** é a regra em mais de 90% dos pregões de software (estimativa, **não confirmada**). **Técnica e preço** aparece em concorrências de órgãos maiores e estatais.
- **Dinâmica de lances:**
  - **Modo aberto:** lances sucessivos, com prorrogação automática de 2 minutos a cada lance nos minutos finais.
  - **Modo aberto-fechado:** os melhores fazem um lance final sigiloso.
  - Depois vem a **negociação** pelo pregoeiro, o **empate ficto** de ME/EPP, a análise da proposta (planilha de custos) e a habilitação só do 1º colocado.
  - Há **prova de conceito (PoC)** frequente em sistemas: o vencedor demonstra que atende os requisitos em prazo curto. Isso é uma vantagem para quem já tem um produto base.
- **Deságio típico:**
  - De 10% a 40% sobre o estimado (**não confirmado** como média). No exemplo de Itaúba foi cerca de 10%.
  - Em dispensas eletrônicas com muitos concorrentes, o deságio costuma ser alto.
- **Inexequibilidade:**
  - Para bens e serviços comuns, a IN SEGES 73/2022 (federal) trata proposta **abaixo de 50% do valor orçado** como **indício**: o agente faz diligência e o licitante pode provar a viabilidade (TCU, Acórdão 803/2024).
  - Para obras e engenharia o limite legal é 75% (art. 59, §4º).
  - Municípios podem ter regra própria.
- **Mergulho de preço:** quem ganha "no osso" muitas vezes não entrega, e isso leva a sanção. Com IA o custo real de desenvolvimento cai, então é possível ofertar 30% a 45% abaixo do estimado **de forma exequível**, desde que haja planilha de custos coerente.

---

## O que os vencedores fazem de diferente

1. **Monitoramento diário e volume com filtro.** Fazem triagem de dezenas de editais por semana, mas só disputam os que têm aderência. A taxa de vitória melhora mais com seleção do que com volume.
2. **Documentação impecável e "pasta pronta".** Mantêm as certidões sempre válidas, com renovação automatizada. Têm balanço padrão licitação, declarações-modelo e um atestado para cada tipo de objeto. **A inabilitação por documento é a principal causa de perda** de quem é novato (**não confirmado** estatisticamente, mas é recorrente nas fontes).
3. **Produto base reaproveitável.** Quem vende "app de ouvidoria", "sistema legislativo" ou "portal da transparência" para 50 câmaras tem custo marginal quase zero e passa na PoC. **O modelo vencedor no varejo municipal é produto replicável com customização, não desenvolvimento do zero.**
4. **Atestados acumulados** e equipe com certificações quando o edital pede.
5. **Atenção no chat do pregão.** Respondem ao pregoeiro dentro do prazo. A falta de resposta leva a desclassificação e até sanção.
6. **Impugnações e recursos.** Usam esses instrumentos para abrir editais restritivos e derrubar concorrentes mal documentados.
7. **Relacionamento:** visitas, apresentações e participação na fase de ETP e pesquisa de preços (enviar cotação quando o órgão pede). Isso é legítimo até certo ponto.
   - O lado ruim: **"cartas marcadas"** com termo de referência copiado do produto de um fornecedor, exigências sob medida, prazos curtíssimos e portais pouco conhecidos.
   - Sinais de alerta: requisitos que só um produto atende, PoC em 48h, atestados com quantidades exatas ou incomuns.
   - Os Tribunais de Contas e o TCU (robô ALICE) fiscalizam, mas a prática persiste. **Não confirmado** em escala, mas é amplamente relatado.

---

## Seriedade e riscos

| Risco | Detalhe | Mitigação |
|---|---|---|
| **Atraso de pagamento** | Pesquisa da CNM de dez/2025: **28,8% dos prefeitos** (1.202 de 4.172) relataram atraso a fornecedores. No CE eram 52% dos municípios, no MS 36%. Muitos deixaram restos a pagar sem cobertura para 2026. Diadema/SP aprovou parcelamento de dívidas, chamado de "calote" pela oposição. | Consultar o RREO/RGF (Siconfi) e o histórico do órgão antes de disputar. Preferir câmaras (duodécimo garantido), autarquias, órgãos federais e estatais. Pela Lei 14.133 (art. 137), o contratado pode suspender a execução se o atraso passar de 2 meses (**não confirmado** no texto oficial). |
| **Sanções** (art. 156) | Advertência, multa, **impedimento de licitar** com o ente por até **3 anos**, **inidoneidade** de 3 a 6 anos em todo o país. Também se aplicam a quem não assina o contrato, não mantém a proposta ou apresenta documento falso. | Não disputar o que não consegue entregar. Ler o termo de referência e os SLAs com cuidado. |
| **Inexecução e atraso de entrega** | Multas por SLA e glosas em fábrica de software medida por UST ou PF, com discussões frequentes sobre contagem. | Escopo e critérios de aceite claros. Registrar tudo. |
| **Aditivos** | Acréscimos ou supressões de até 25% (art. 125), que o contratado é obrigado a aceitar. Reequilíbrio só com prova. Reajuste anual pelo índice do edital. | Precificar o risco desde o início. |
| **Tribunal de Contas** | Auditorias e representações podem suspender o certame ou o contrato. Preço muito acima do mercado leva a sobrepreço e responsabilização solidária. | Preço justificável e documentação de execução. |
| **Garantia contratual** | Até 5% do valor, ou 10% em casos especiais, mais garantia de proposta de até 1% em alguns editais. Em Convales/MG a garantia era de 1%. | Seguro-garantia é barato para tickets pequenos (**não confirmado** quanto a preço). |
| **Responsabilidade trabalhista e subcontratação** | Contratar "PJs" para entregar é comum. Em serviço com dedicação exclusiva de mão de obra, o órgão exige comprovação de encargos. | Preferir objetos por entrega ou produto, não postos de trabalho. |

---

## Chances para nós (nota 0-10)

**Nota: 6/10.**

**A favor**
- Desenvolvimento acelerado por IA reduz muito o custo de entrega de apps e sistemas pequenos. Dá para ofertar preço agressivo **e exequível**.
- Dispensas eletrônicas até R$ 65 mil e pregões exclusivos para ME/EPP até R$ 80 mil, geralmente com habilitação leve, são abundantes e abertos a novatos.
- A IA reduz drasticamente o custo de triagem de editais, checagem de habilitação, montagem de propostas, planilhas e impugnações. É o gargalo operacional de quem licita.
- O sócio com PJ mais antiga pode resolver o balanço e talvez parte dos atestados.

**Contra**
- Não há atestados em nome da PJ nova, e muitos pregões de maior valor exigem. Atestado de outra PJ não serve.
- Há concorrência de centenas de micro software houses e de players com produto pronto. Preço é commodity.
- Há risco de calote ou atraso de prefeituras e um ciclo de caixa longo.
- O desenvolvimento "do zero" é uma fatia menor do mercado. O dinheiro recorrente está em locação de SaaS e manutenção.
- A curva de aprendizado operacional (portais, certificado digital, chat do pregoeiro, prazos) é de 2 a 4 meses (**não confirmado**).

**Leitura:** a chance de ganhar **algo** em 6 meses, como dispensas de R$ 10 a 60 mil, é boa: entre 50% e 70% se disputar 30 ou mais processos bem filtrados (estimativa, **não confirmada**). A chance de virar um negócio de R$ 1 milhão ou mais por ano só com licitações em 12 meses é baixa.

---

## Encaixe no modelo de negócio

**Modelo "empresa especializada em licitar e entregar software"**

**Unit economics ilustrativo** (estimativas, **não confirmadas**): app ou sistema para câmara ou prefeitura pequena, por dispensa.

| Item | Valor |
|---|---|
| Ticket médio | R$ 45.000 |
| Custo de entrega com IA (dev contratado, cerca de 120 a 200h a R$ 80-120/h, mais infra e QA) | R$ 12.000 a 22.000 |
| Impostos (Simples Anexo III, cerca de 6% a 11% no início) | R$ 3.000 a 5.000 |
| Custo comercial por vitória (ferramenta, certificado, horas de proposta, mais as derrotas) | R$ 2.000 a 5.000 |
| **Margem de contribuição** | **cerca de 35% a 60%** |
| Upsell: manutenção ou hospedagem mensal de 12 meses (R$ 1.000 a 3.000/mês) | Aumenta muito o LTV |

**Taxa de vitória típica**
- Não há dado público confiável (**não confirmado**).
- Relatos de mercado sugerem de 5% a 15% para iniciantes em pregão aberto e de 15% a 30% em nichos com produto pronto e bom filtro.
- Planejar com 10%: são cerca de 10 disputas bem preparadas por vitória.
- Com IA, o custo de cada disputa cai para poucas horas.

**Ciclo de caixa**
- Do edital à sessão: 8 a 15 dias úteis em pregão, 3 dias úteis ou mais em dispensa.
- Da sessão à assinatura: 2 a 6 semanas.
- Entrega: 1 a 4 meses.
- Pagamento: em até 30 dias após o aceite pela regra; na prática prefeituras levam de 30 a 120 dias ou mais.
- **Total de 3 a 8 meses entre o início e o recebimento.** O negócio exige capital de giro para pagar os devs antes de receber.

**Estratégia que melhor encaixa**
1. **Produtizar.** Escolher 2 ou 3 produtos verticais para nichos pequenos e numerosos: app de ouvidoria/serviços municipais, sistema de votação/legislativo para câmaras, integração AUDESP/TCE, diário escolar, agendamento de saúde. Vender o mesmo produto customizado para muitos órgãos, cobrando implantação mais mensalidade.
2. Usar licitações como **um dos canais**, ao lado de editais de inovação (CPSI / Marco Legal das Startups), fundos e clientes privados, e não como único canal.

---

## Próximos passos práticos

1. **Semana 1: base documental**
   - Conferir o CNAE das duas PJs (6201-5/01 e outros de TI). Emitir o e-CNPJ A1.
   - Cadastrar no SICAF/Compras.gov.br, no PNCP (como fornecedor, se aplicável), na BLL, no BNC e no Portal de Compras Públicas.
   - Pedir ao contador o balanço 2025 "padrão licitação" com índices. Se a PJ for de 2026, o balanço de abertura.
2. **Semana 1-2: atestados**
   - Coletar atestados de **todos** os clientes privados já atendidos pela PJ do cliente e pela PJ do sócio, com contrato e notas fiscais como lastro.
   - Mapear o que a PJ do sócio já tem: atestados, balanço, histórico.
   - Decidir **qual PJ licita** em cada caso e formalizar a parceria por contrato de sócio, consórcio ou subcontratação.
3. **Semana 2: robô de triagem com IA**
   - Script sobre a API do PNCP (consulta pública de contratações), com palavras-chave como "aplicativo", "desenvolvimento de sistema", "fábrica de software", "AUDESP" e "sistema legislativo".
   - O LLM classifica a aderência, extrai os requisitos de habilitação e PoC, aponta riscos e calcula um preço-alvo.
   - Alternativa: assinar uma ferramenta (Alerta Licitação, a partir de cerca de R$ 31/mês, ou Effecti/ConLicitação para testar).
4. **Semanas 2-8: disputar 20 a 30 dispensas eletrônicas e pregões exclusivos para ME/EPP de até R$ 80 mil** em objetos que dá para entregar em menos de 6 semanas.
   - O objetivo principal é ganhar 2 ou 3 contratos e **formar atestados públicos**.
   - Antes de disputar, checar a saúde fiscal do órgão (Siconfi/RGF).
5. **Templates com IA:** pasta de habilitação, declarações, proposta comercial, planilha de custos (para defender exequibilidade), modelos de impugnação e de recurso, e checklist pré-sessão.
6. **Meses 3-6:** com atestados em mãos, subir para pregões de R$ 100 a 500 mil e para atas de registro de preços. Avaliar consórcio para fábricas de software maiores.
7. **Regra de ouro:** não ofertar o que não consegue entregar. Uma sanção de impedimento derruba o modelo de negócio.

---

## Fontes

- ConLicitação, Nova Lei de Licitações em 2026 (valores): https://conlicitacao.com.br/nova-lei-de-licitacoes-2026/
- Effecti, Decreto 12.807/2025: https://effecti.com.br/decreto-12807-de-2025/
- Effecti, Decreto 12.343 (atualização anterior): https://effecti.com.br/atualizacao-valores-licitacoes-decreto-12343/
- Zênite, balanço e registro: https://zenite.blog.br/?p=20476 e https://zenite.blog.br/?p=21650
- Effecti, empresa nova e balanço: https://effecti.com.br/?p=12041
- MPRS, esclarecimento PE 94/2026 (balanço de abertura): https://www.mprs.mp.br/media/areas/licitacao/arquivos/2026/94_26_24_26_pe_esclarecimento_01.pdf
- Edital de Rondônia (art. 67, 4% e 50%): https://rondonia.ro.gov.br/wp-content/uploads/2026/03/ADENDOO.pdf
- Schiefler Advocacia, atestado de capacidade técnica: https://schiefler.adv.br/atestado-de-capacidade-tecnica-como-comprovar-qualificacao-e-evitar-a-inabilitacao/7724
- Zênite, TCU e transferência de acervo: https://zenite.blog.br/de-acordo-com-o-tcu-nao-e-possivel-transferir-o-acervo-tecnico-de-pessoa-fisica-para-juridica/
- Contrarrazão de Maricá (Acórdão TCU 1.798/2024, parentesco): https://www.marica.rj.gov.br/wp-content/uploads/2025/05/CONTRARRAZAO_ISAPED.pdf
- Art. 67 §9º (potencial subcontratado): https://modeloinicial.com.br/lei/155143/lei-licitacoes-contratos-administrativos/art-67 , https://ronnycharles.com.br/17080-2/ e https://agenciainfra.com/blog/?p=27862
- TCU, participação de ME/EPP: https://licitacoesecontratos.tcu.gov.br/4-5-2-4-participacao-de-microempresas-e-de-empresas-de-pequeno-porte-2/
- Conjur, LC 123 e limites: https://www.conjur.com.br/?p=357288
- Effecti, exclusividade ME/EPP: https://effecti.com.br/?p=1877
- Inexequibilidade (IN 73/2022): https://www.mpf.mp.br/o-mpf/unidades/pr-ap/transparencia/arquivos/licitacao-2024/parecer_tecnico_exequibilidade_de_proposta.pdf e https://www.trt7.jus.br/files/contas_publicas/licitacoes/pregao_eletronico/2025/PE_90035_2025/RECURSO/DECISAO%20DA%20PRESIDENCIA%20PE90035_2025.pdf
- TCU, sanções: https://licitacoesecontratos.tcu.gov.br/6-1-8-infracoes-e-sancoes-administrativas-contratado/
- CNM e imprensa, atrasos a fornecedores: https://jornalgrandebahia.com.br/2025/12/crise-fiscal-nos-municipios-atraso-a-fornecedores-pressao-de-programas-federais-e-risco-de-rombo-nas-contas-de-um-terco-das-prefeituras/ , https://www.campograndenews.com.br/politica/prefeituras-de-ms-pagam-13o-mas-atraso-a-fornecedores-atinge-1-3-das-cidades , https://mais.opovo.com.br/jornal/economia/2025/12/15/cerca-de-26-das-prefeituras-cearenses-nao-vao-conseguir-fechar-as-contas-em-2025.html , https://www.dgabc.com.br/Noticia/4269412/camara-de-diadema-aprova-regras-para-pagamento-de-fornecedores
- Dispensa da Câmara de Américo Brasiliense 033/2026: https://www.americobrasiliense.sp.leg.br/transparencia/licitacoes-e-contratos/a-partir-de-01-12-2025/encerradas/dispensa-no-033-2026-desenvolvimento-de-aplicacao-web-full-stack-para-integracao-com-as-apis-do-sistema-audesp-2013-fase-iv-destinada-a-prestacao-das-informacoes-de-responsabilidade-da-camara-municipal
- Câmara de Itinga do Maranhão (editais): https://www.importacao.cmitinga.ma.gov.br/editais-licitacoes
- Câmara de Centenário do Sul, dispensa 001/2026: https://www.centenariodosul.pr.leg.br/institucional/noticias/processo-licitatorio-no-001-2026-dispensa-eletronica-de-licitacao-001-2026
- Prefeitura de Itaúba/MT, pregões: https://transparencia.itauba.mt.gov.br/Licitacao-e-contratos/Pregao-eletronico/
- Prefeitura de SP, contratos: https://prefeitura.sp.gov.br/web/governo/w/acesso_a_informacao/contratos/291592
- Agregador Alerta Licitação, editais PNCP (Quatiguá 21/2026, Rio Branco 90220/2026, EMATER-DF 90003/2026, SNPC 33/2025, MF 7/2026): https://alertalicitacao.com.br/!licitacao/PNCP-76966852000108-1-000024-2026 , https://alertalicitacao.com.br/!licitacao/PNCP-16958425000148-1-000275-2026 , https://alertalicitacao.com.br/!licitacao/PNCP-00509612000104-1-000012-2026 , https://alertalicitacao.com.br/!licitacao/PNCP-07290290000102-1-000027-2025 , https://alertalicitacao.com.br/!licitacao/PNCP-00394460000141-1-000698-2026
- LicitaJá (apps, incluindo Convales/MG): https://www.licitaja.com.br/conteudo.php?veja=licitacoes+para+desenvolvimento+aplicativo+pregoes+93173&idLj=uZ0pA
- Preços de UST e PF: https://goias.gov.br/seinfra/wp-content/uploads/sites/6/2025/07/anexo-3.pdf e https://bnb.gov.br/documents/45839/9965526/Anexo%20VII%20-%20Guia%20de%20Contrata%C3%A7%C3%A3o%20em%20Pontos%20de%20Fun%C3%A7%C3%A3o%20-%20RFI%202026-003.pdf
- TCE/SC, consulta sobre contratação de sistemas de gestão: https://www.tcesc.tc.br/tcesc-abre-consulta-publica-para-receber-sugestoes-sobre-modelo-de-contratacao-de-sistemas-de
- IA para licitações: https://conlicitacao.com.br/ia , https://effecti.com.br/ia-para-licitacoes-nas-compras-publicas/ , https://ads.ifba.edu.br/dl2947 (Licita.AI)
- Effecti, taxa de vitória: https://effecti.com.br/?p=1842
- Portais: https://pncp.gov.br/app/editais , https://www.gov.br/compras
