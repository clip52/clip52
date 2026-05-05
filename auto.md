# Como abrir empresa para SaaS B2B em Uberlândia (MG) em 2026 — Guia decisão-pronto para o caso "Automatiza"

## TL;DR
- **Abra uma SLU (Sociedade Limitada Unipessoal) com CNAE principal 6202‑3/00** (programas de computador customizáveis), opte pelo **Simples Nacional** e mantenha pró‑labore mensal ≥ 28% do faturamento bruto dos últimos 12 meses para tributar pelo **Anexo III via Fator R** (alíquota inicial de 6%); a economia frente ao Anexo V (15,5%) é de até 9,5 pontos percentuais (~R$ 34 mil/ano em R$ 360 k de receita).
- **Custo total estimado de abertura em Uberlândia em 2026: R$ 800 a R$ 1.500** (DARE da JUCEMG R$ 268,51 com contrato‑padrão ME — preço mantido desde 2018 + honorários de contador + e‑CNPJ A1). **Mensal recorrente:** R$ 300‑800 de honorários contábeis + DAS Simples (~6%) + INSS 11% sobre pró‑labore (teto de contribuição R$ 932,31, 11% sobre R$ 8.475,55, conforme Portaria Interministerial MPS/MF nº 13/2026) + IRPF zero até R$ 5.000/mês (Lei 15.270/2025).
- **Atenção crítica:** o ISS para serviços de TI em Uberlândia é **3%** (Lei Complementar Municipal 336/2003, Anexo, subitens 1.01–1.08); o programa "Inova Uberlândia" (LC 629/2017) **não oferece mais redução de ISS** (revogou a LC 588/2014) e exige imóvel próprio em polo tecnológico — para um dev solo é inócuo. STF (ADI 5.659/2021) pacificou que SaaS é serviço sujeito a ISS, e a Reforma Tributária preserva o Simples em 2026 em fase de testes (regulamentos do IBS via Resolução CGIBS nº 6/2026 e da CBS via Decreto nº 12.995/2026, ambos publicados em 30/04/2026).

---

## Key Findings

### 1. CNAE recomendado para SaaS B2B
- **Principal: 6202‑3/00 — Desenvolvimento e licenciamento de programas de computador customizáveis.** Sujeito ao **Fator R** (Anexo III se Folha 12m/RBT12 ≥ 28%, ou Anexo V se < 28%). É a escolha mais flexível para SaaS que pode ter customizações por cliente. O 6203‑1/00 (não‑customizáveis) é teoricamente mais "puro" para SaaS padronizado, mas tem o **mesmo tratamento** de Fator R e mesma classificação V/III — semanticamente, 6202‑3/00 cobre melhor o caso "SaaS B2B com possibilidade de customização".
- **Secundários recomendados:**
  - **6201‑5/01** — Desenvolvimento de programas de computador sob encomenda (para projetos pontuais)
  - **6311‑9/00** — Tratamento de dados, provedores de serviços de aplicação e hospedagem na internet (Anexo III direto, **sem Fator R** — útil para receita explicitamente de hosting/API)
  - **6209‑1/00** — Suporte técnico, manutenção e outros serviços em TI (Anexo III direto)
  - **6204‑0/00** — Consultoria em TI (sujeito ao Fator R)
- **Regra prática:** segregar receita por nota fiscal sempre que parte da operação for hospedagem/suporte para tributar diretamente no Anexo III sem depender do Fator R.

### 2. SLU vs LTDA — para o seu caso, **SLU vence**

| Critério | SLU | LTDA (2 sócios) |
|---|---|---|
| Sócios mínimos | 1 | 2 (1 pode ter 1% só para abrir) |
| Capital social mínimo | R$ 1 | R$ 1 |
| Proteção patrimonial | Igual à LTDA | Igual |
| Contrato social | Padrão automático no Módulo Integrador | Mais cláusulas (ingresso/saída, voto, distribuição) |
| Conversão futura | Vira LTDA com simples alteração | — |
| DARE JUCEMG (ME, contrato‑padrão) | **R$ 268,51** | **R$ 268,51** |
| Risco "sócio laranja" | Nenhum | Pode gerar litígio futuro |

**Conclusão:** SLU é mais simples, barata e segura para o desenvolvedor solo. Pode ser convertida em LTDA depois sem custos relevantes se entrar sócio efetivo.

### 3. Regime tributário: Simples Nacional Anexo III via Fator R

**Comparação para faturamento R$ 30.000/mês (R$ 360 mil/ano — 1ª faixa):**

| Regime | Alíquota efetiva | DAS/mês estimado |
|---|---|---|
| **Simples Anexo III (Fator R ≥ 28%)** | **~6%** | **R$ 1.800** |
| Simples Anexo V (Fator R < 28%) | ~15,5% | R$ 4.650 |
| Lucro Presumido (serviços) | PIS 0,65 + COFINS 3 + IRPJ 4,8 + CSLL 2,88 + ISS 3 ≈ **14,33%** + INSS patronal 20% sobre pró‑labore | R$ 4.300+ |

**Diferença Anexo III vs V: ~R$ 2.850/mês (R$ 34.200/ano).**

**Mecânica do Fator R para sócio solo sem CLT:**
- Fator R = Folha de salários dos últimos 12 meses (incluindo **pró‑labore + INSS patronal + FGTS** efetivamente pagos pelo regime de caixa) ÷ RBT12.
- Resolução CGSN nº 140/2018, art. 26, e LC 123/2006, art. 18, §24: **pró‑labore conta** na folha do Fator R (Solução de Consulta Cosit confirma; alguns blogs erroneamente afirmam que pró‑labore "não conta" — confundem com a folha CLT pura).
- **Cálculo prático para R$ 30.000/mês:** pró‑labore mínimo = 28% × 30.000 = **R$ 8.400/mês** bruto. Use **R$ 8.500/mês** como referência conservadora para criar margem.
- Migração entre Anexo III e V é automática mês a mês no PGDAS‑D (sem requerimento).
- **Regra especial:** se há folha > 0 e RBT12 = 0 (mês inicial), o Fator R é fixado em 28% (Resolução CGSN 140/2018, art. 26, §6º) — ou seja, comece já no Anexo III no mês 1.

**INSS pró‑labore 2026** (sócio = contribuinte individual): 11% retido na fonte, sobre o bruto, com piso de 1 salário mínimo (R$ 1.621,00 a partir de 01/01/2026, conforme Decreto nº 12.797/2025) e **teto de contribuição R$ 932,31** (11% × R$ 8.475,55, conforme Portaria Interministerial MPS/MF nº 13/2026). No Simples, **não há INSS patronal** sobre pró‑labore (já está incluído no DAS) — uma economia de 20% relevante frente a Lucro Presumido.

**IRPF sobre pró‑labore em 2026 (Lei nº 15.270/2025):** **isento até R$ 5.000/mês**; entre R$ 5.000 e ~R$ 7.350 há redutor; acima, tabela progressiva. Para um pró‑labore de R$ 8.400 há tributação parcial — confirme o cálculo exato com o contador.

### 4. ISS em Uberlândia para SaaS — 3%, não 5% nem 2%

A **Lei Complementar Municipal nº 336/2003** (Anexo, Lista de Serviços) fixa **3%** para todos os subitens 1.01 a 1.08 (todos os serviços de TI):

| Subitem LC 116/2003 | Descrição | Alíquota Uberlândia |
|---|---|---|
| 1.03 | Processamento, armazenamento, hospedagem de dados | **3%** |
| 1.04 | Elaboração de programas de computador | **3%** |
| **1.05** | **Licenciamento ou cessão de direito de uso de programas (chave para SaaS)** | **3%** |
| 1.07 | Suporte técnico em informática | **3%** |

No Simples Nacional, esse ISS de 3% **já está embutido** na alíquota efetiva do DAS Anexo III (não há recolhimento separado, exceto retenção na fonte por tomador específico previsto na lei municipal).

**Programa "Inova Uberlândia" (LC 629/2017, alterada pela LC 682/2019):** revogou a antiga LC 588/2014 ("Uberlândia Inovadora"), que oferecia ISS reduzido a 2%. **Hoje os benefícios são apenas isenção de IPTU e ITBI** sobre imóvel próprio em polo/micropolo aprovado (Polo Tecnológico Sul, no bairro Gávea; e micropolos definidos por decreto). Gestão pela **Secretaria Municipal de Desenvolvimento Econômico e Inovação (SEDEI)**, não mais pela AMDES. **Para um dev solo SLU sem imóvel em polo, o programa é inacessível na prática** — e mesmo elegível, o benefício atual não inclui ISS.

### 5. Tributação de SaaS em 2026 — STF + Reforma Tributária

- **STF ADI 5.659 e ADI 1.945 (julgadas em 2021):** software (incluindo SaaS, download, cloud, padronizado ou customizado) é **serviço sujeito a ISS, não ICMS** (subitem 1.05 da LC 116/2003). Modulação ex nunc desde 03/03/2021. Tema 590 do STF.
- **Reforma Tributária (EC 132/2023 + LC 214/2025):**
  - **2026 é ano de testes:** CBS 0,9% + IBS 0,1% destacados em NF (caráter informativo), compensáveis com PIS/COFINS para regime regular. Os **regulamentos do IBS (Resolução CGIBS nº 6/2026) e da CBS (Decreto nº 12.995/2026)** foram publicados em **30/04/2026**, inaugurando a fase prática de adaptação.
  - **Empresas do Simples Nacional NÃO têm alteração em 2026** — só passam a destacar IBS/CBS no documento fiscal a partir de **2027**.
  - **Setembro/2026 = decisão estratégica:** o contribuinte do Simples decide se permanece no regime ou migra para o **"Simples Híbrido"** (recolhe IBS/CBS por fora do DAS, gerando crédito integral para clientes B2B do regime regular — alíquota cheia ~26,5%).
  - Para SaaS B2B vendendo a grandes empresas, **avaliar Simples Híbrido em set/2026** é crucial: clientes B2B só aproveitam crédito limitado se você ficar 100% no DAS.

### 6. Exportação de serviços (clientes fora do Brasil)
- **PIS/COFINS:** **não incidem** (Solução de Consulta Cosit nº 78/2019), desde que (1) tomador seja domiciliado no exterior, (2) pagamento represente ingresso de divisas, (3) **resultado do serviço se verifique fora do Brasil**.
- **ISS:** **não incide** (LC 116/2003, art. 2º, I) sobre exportação ao exterior, desde que o resultado também se verifique no exterior.
- **IRPJ e CSLL:** incidem normalmente (no Simples, embutidos no DAS).
- **Operacional:** segregar a receita de exportação no PGDAS‑D no campo **"Receitas no mercado externo"**; sem isso, o sistema cobra como interna.

### 7. Marca "Automatiza" no INPI
- **Classes Nice relevantes:**
  - **Classe 9** — programas de computador gravados/baixáveis (software como produto)
  - **Classe 42** — desenvolvimento, manutenção e atualização de software, SaaS, consultoria em TI
- **Custo INPI vigente em 2026 (Portaria GM/MDIC nº 110/2025):** **R$ 440 por classe** com desconto (ME/EPP/MEI/PF, especificação pré‑aprovada) ou **R$ 880** sem desconto. **Inclui depósito + análise + 1º decênio + certificado** (emitido automaticamente desde 20/09/2025).
- **Estratégia para "Automatiza":** registrar simultaneamente em **classe 9 + classe 42** (~**R$ 880** com desconto ME) — proteger só uma deixa brecha competitiva.
- **Antes:** verificar disponibilidade na busca pública do INPI (busca por radical "automatiza"). Se houver conflito, considerar marca composta ("Automatiza Tech", "Automatiza App").

### 8. Nome empresarial e nome fantasia
- **Razão social** (registrada na JUCEMG): deve conter **"Ltda" ou "Limitada"**. Em SLU, a razão social ainda usa "Ltda" (a SLU é uma espécie de LTDA unipessoal); na prática, a JUCEMG aceita denominações como "Automatiza Tecnologia Ltda" ou "[Seu nome] Automatiza Ltda".
- **Nome fantasia:** livre — "Automatiza".
- **Verificação prévia de nome:** Consulta de Viabilidade no Portal Redesim MG (redesim.mg.gov.br) faz busca de nomes idênticos/semelhantes na JUCEMG automaticamente.
- **Domínio automatiza.app.br:** já registrado pelo usuário; manter sincronizado com a marca INPI.

---

## Details

### Passo a passo de abertura em Uberlândia (2026)

| # | Etapa | Órgão | Prazo | Custo |
|---|---|---|---|---|
| 1 | Consulta de Viabilidade (nome + endereço) | Redesim MG (redesim.mg.gov.br) | 1–2 dias úteis | Grátis |
| 2 | DBE/CNPJ no Coletor Nacional | Receita Federal | Automático após viabilidade | Grátis |
| 3 | DARE JUCEMG (contrato padrão ME) | JUCEMG | — | **R$ 268,51** (R$ 429,61 se contrato personalizado) |
| 4 | Registro do contrato social na JUCEMG (assinatura digital) | JUCEMG | 1–5 dias úteis | (incluso no DARE) |
| 5 | Inscrição Municipal e Alvará | Prefeitura de Uberlândia (Empresa Fácil) | Automática para baixo risco | Taxa eventual; TI geralmente dispensada |
| 6 | Opção pelo Simples Nacional | Portal do Simples (gov.br/simples) | Em até 30 dias após inscrição municipal/estadual deferida (60 dias após CNPJ) | Grátis |
| 7 | Certificado Digital e‑CNPJ A1 | AC autorizada (Serasa, Soluti, Certisign, Valid) | Mesmo dia | R$ 180–350/ano |
| 8 | Credenciamento NFS‑e | Prefeitura (nfse.uberlandia.mg.gov.br) | Mesmo dia | Grátis |
| 9 | Conta PJ (banco/fintech) | Cora, Inter, Bradesco, Itaú, Asaas | 1–3 dias | Geralmente grátis |

**Tudo é 100% online** desde 2024 com o programa **Redesim + Livre** da JUCEMG — 915 atividades dispensadas de alvará, registro automático em até 24h em muitos casos.

### Onde ir em Uberlândia

- **Sala Mineira do Empreendedor** (parceria PMU + Sebrae + JUCEMG): **Centro Administrativo Municipal Virgílio Galassi, Av. Anselmo Alves dos Santos, 600, Bairro Santa Mônica, CEP 38408‑150, piso 3, bloco 1**. Atendimento de **segunda a sexta, 12h às 17h**; **JUCEMG presencial às quartas‑feiras** (Uberlândia foi a 1ª cidade do interior de MG com este serviço, desde 2025). Telefone PMU: **(34) 3239‑2800**.
- **Sebrae Minas em Uberlândia:** Av. Floriano Peixoto, 1, Centro — Tel. (34) 3237‑2270; também atende via 0800 570 0800 e WhatsApp 24h.
- **JUCEMG (online):** jucemg.mg.gov.br | (31) 3219‑7900 (10h–16h) | portal de serviços: portalservicos.jucemg.mg.gov.br.
- **Receita Federal Uberlândia:** atendimento por agendamento via gov.br.
- **Prefeitura — Secretaria de Finanças (ISS, NFS‑e):** uberlandia.mg.gov.br/empreendedor.
- **Contadores em Uberlândia:** opções locais com foco em TI (ex.: Saber Contábil) ou contabilidades online (Contabilizei, Contabilidade.com, Contaja, Agilize) — faixa de honorários R$ 300–800/mês para Simples Nacional.

### Custos consolidados — primeiro ano (R$)

| Item | Mín | Esperado | Observação |
|---|---|---|---|
| DARE JUCEMG (contrato padrão ME) | 268,51 | 268,51 | 429,61 se contrato personalizado |
| Honorários abertura (contador) | 0 | 800 | Contabilidades online dão grátis com plano mensal |
| Certificado digital e‑CNPJ A1 | 180 | 280 | Anual |
| Taxa de alvará Uberlândia | 0 | 130 | TI geralmente dispensada |
| Registro de marca INPI (classes 9 + 42, ME) | 880 | 880 | Pré-aprovada com desconto |
| **Subtotal abertura** | **~1.328** | **~2.358** | — |
| Honorários contador (12 meses) | 3.600 | 9.600 | R$ 300–800/mês |
| DAS Simples (média 6% × R$ 360 k) | 21.600 | 21.600 | Anexo III via Fator R |
| INSS pró-labore (11% × R$ 8.400 × 12) | 11.088 | 11.088 | Para manter Fator R |
| **Total ano 1** | **~37.616** | **~44.646** | All‑in ~10–12% sobre R$ 360 k |

### Endereço da empresa
- **Residencial:** permitido em Uberlândia para atividade de TI (sem atendimento ao público, sem impacto urbano), sujeito a aprovação na Consulta de Viabilidade (zoneamento). É a opção mais econômica.
- **Coworking com endereço fiscal:** opções em Uberlândia (CoworkUDI, Distrito Tech, espaços privados) — preços médios **R$ 250–600/mês**.
- **Escritório virtual:** **R$ 100–300/mês**.
- **UDI Lab:** coworking público gratuito da Prefeitura no Parque do Sabiá (12 estações, ar‑condicionado, internet) — **mas sem endereço fiscal**.

### Documentos necessários
- RG, CPF e comprovante de residência atualizado (até 90 dias) do sócio
- Comprovante de endereço da empresa (IPTU ou contrato de locação)
- Certidão de casamento (se casado, dependendo do regime de bens)
- Capital social: recomenda-se **R$ 5.000 a R$ 10.000** (passa credibilidade sem comprometer caixa)
- Contrato social padrão (gerado automaticamente no Módulo Integrador da JUCEMG para SLU)
- Procuração para o contador (eletrônica via gov.br)
- Certificado digital e‑CNPJ A1 (após CNPJ emitido)

---

## Recommendations

### Ações imediatas (próximas 2 semanas)
1. **Contratar contador especializado em TI** com plano R$ 300–500/mês (online ou local em Uberlândia).
2. **Decidir SLU** com:
   - **CNAE principal: 6202‑3/00**
   - **Secundários: 6201‑5/01, 6209‑1/00, 6311‑9/00, 6204‑0/00**
3. **Definir capital social R$ 5.000–10.000** e endereço (residencial é OK para SaaS após Viabilidade).
4. **Verificar disponibilidade da marca "Automatiza" no INPI** (busca pública gratuita) e protocolar registro em **classes 9 + 42** (~R$ 880 com desconto ME).
5. **Iniciar processo via Redesim MG**: viabilidade → DBE → DARE → registro → CNPJ → inscrição municipal → opção pelo Simples (em até 30 dias após inscrição municipal deferida).
6. **Contratar e‑CNPJ A1** assim que sair o CNPJ e credenciar para emitir NFS‑e em nfse.uberlandia.mg.gov.br.

### Otimização tributária (Fator R)
- **Pró‑labore mensal:** comece em **R$ 4.000–8.500** mesmo no início (28% do faturamento projetado), para construir histórico do Fator R e manter‑se no Anexo III.
- **Mês 1:** com folha > 0 e receita = 0, o Fator R é fixado em 28% (Resolução CGSN 140/2018, art. 26 §6º) — você já entra no Anexo III.
- **Monitoramento mensal:** o contador deve calcular o Fator R no fechamento, antes de gerar o DAS no PGDAS‑D.
- **Em 2026,** aproveitar a **isenção de IRPF até R$ 5.000/mês** de pró‑labore (Lei 15.270/2025) — pró‑labore acima disso ainda paga IRPF na faixa 27,5%, mas mantém o Fator R.

### Decisões em 2026 a monitorar
- **Setembro/2026:** decisão **Simples vs Simples Híbrido vs Lucro Presumido** para 2027. Se >50% dos clientes forem grandes empresas B2B no regime regular, o **Simples Híbrido pode ser estratégico** para gerar crédito integral de IBS/CBS (~26,5%) ao cliente.
- **A partir de 2027:** começar a destacar IBS/CBS em NFS‑e mesmo no Simples; alinhar emissor.

### Benchmarks que mudam a recomendação

| Cenário | Mudança recomendada |
|---|---|
| Faturamento ultrapassa R$ 360 k/ano | Continuar Simples até R$ 4,8 mi; pró‑labore precisa subir junto para manter Fator R |
| Cliente B2B grande exige fornecedor com crédito integral de IBS/CBS | Avaliar **Simples Híbrido** (set/2026) ou Lucro Presumido |
| Contratação de funcionário CLT | Folha CLT entra no Fator R; revisar nível de pró‑labore para baixo |
| Receita >50% de exportação | Segregar no PGDAS‑D, isenção PIS/COFINS/ISS — alíquota efetiva cai significativamente |
| Migração para imóvel próprio em polo tecnológico | Avaliar "Inova Uberlândia" (IPTU/ITBI isentos por 10 anos) |

---

## Caveats

- **Risco principal: cair no Anexo V por descuido com o Fator R.** Em meses de baixa receita ou pró‑labore atrasado, o índice pode cair abaixo de 28% e disparar 15,5% no DAS — diferença de até R$ 2.850/mês. Use planilha ou software (Agilize, Conta Azul) para simular antes do dia 20 de cada mês. **Pró‑labore precisa ser efetivamente pago e declarado no eSocial/DCTFWeb** (regime de caixa) para entrar no Fator R, conforme Solução de Consulta da Receita Federal.
- **Pró‑labore não é distribuição de lucros.** Distribuir lucro sem registrar pró‑labore mínimo (≥ 1 salário mínimo se houver atividade) pode ser descaracterizado pela Receita como remuneração disfarçada (Solução de Consulta Cosit nº 120/2016) — autuação por INSS atrasado.
- **Reforma Tributária ainda em ajustes finos.** Os regulamentos do IBS (Resolução CGIBS nº 6/2026) e da CBS (Decreto nº 12.995/2026) foram publicados em 30/04/2026 e podem sofrer aperfeiçoamentos. Para o Simples, 2026 é ano de transição informativa, mas é recomendado já adaptar o emissor de NFS‑e.
- **ISS em Uberlândia: 3%, não 2%.** A redução para 2% existia na LC 588/2014 (revogada). O programa "Inova Uberlândia" atual (LC 629/2017) só dá IPTU/ITBI e exige imóvel próprio em polo tecnológico — inacessível para dev solo.
- **Exportação de serviços exige documentação rigorosa** (contrato em inglês, fatura comercial em USD/EUR, comprovante de câmbio bancário, evidência de que o resultado se dá fora do Brasil) para sustentar a não‑incidência de PIS/COFINS/ISS em fiscalização.
- **Modulação STF (ADI 5.659):** restituições de ICMS pagos antes de 03/03/2021 só são recuperáveis se já havia ação em curso — não se aplica a empresa nova.
- **Honorários contábeis variam.** R$ 300/mês é piso para contabilidade online padronizada; R$ 800–1.500/mês para contador local presencial em Uberlândia com atendimento consultivo. Para um SaaS solo iniciante, online é suficiente; à medida que o produto cresce e há clientes internacionais ou questões de planejamento societário, vale migrar para contador consultivo.
- **Várias contabilidades online (Contabilizei, Contabilidade.com, Contaja) abrem a empresa "grátis"** mediante contrato de plano mensal de 12 meses; o "grátis" se traduz em economia de R$ 800 nos honorários de abertura, mas trava você ao serviço por 12 meses. Negocie cláusula de saída.
