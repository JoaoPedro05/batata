# Plugg.To: pricing and billing model (sellers/lojistas)

Research date: 2026-10-07. Method notes: plugg.to/planos/ was read through WebFetch and search-engine renderings on 2026-10-07. Direct curl to plugg.to timed out, hub.plugg.to returned 503, and the Wayback Machine (web.archive.org) could not be reached from this environment (WebFetch blocked; curl SSL error). **No Wayback snapshots were read**, so historical pricing rests only on secondary sources. Reclame Aqui returned 403, so only the search snippet for one complaint is available.

## 1. Does Plugg.To charge a subscription, a % of sales (take rate), a per-order fee, or a combination?

### Takeaway
The documented core model is a **fixed monthly or annual subscription** ("taxa fixa mensal"), with no per-order or per-marketplace charge advertised. However, the current plans page also lists "Menor take rate conforme faturamento" (a lower take rate depending on revenue) as a Pro feature, along with "Cobertura de GMV de até R$ 100 mil". That wording suggests a GMV-linked or variable component, at least above a GMV threshold. The percentage is not published anywhere I could find, and Plugg.To's own copy contradicts itself on this point.

### Cited Findings
- Plans page, Pro plan: "Cobertura de GMV de até R$ 100 mil", "CS dedicado", "Menor take rate conforme faturamento". No percentages are published. — [Planos Plugg.To](https://plugg.to/planos/) (read 2026-10-07)
- The FAQ on the same plans page says that from the Pro plan up there are no commissions or additional fees per integrated marketplace, and that access to 70+ marketplaces costs a single monthly or annual fee. It also says the platform charges "taxa fixa mensal" and that marketplace integration is free. — [Planos Plugg.To](https://plugg.to/planos/) (read 2026-10-07)
- FAQ page: "A partir do plano Pro, não há taxa extra por marketplace". The customer pays a fixed monthly or annual fee and can integrate as many channels as they want. Payment methods are credit card, boleto and Pix, processed by **Vindi**. — [Perguntas Frequentes Plugg.To](https://plugg.to/perguntas-frequentes-plugg-to/) (read 2026-10-07)
- A Plugg.To blog post (7 Feb 2023) contrasts integrators that charge a % of revenue or a fixed amount per sale with Plugg.To's model: "é uma mensalidade cujo valor depende do tipo plano, podendo ser tanto anual quanto mensal" and "não existe nenhum tipo de cobrança adicional por nova funcionalidade ou marketplace integrado". — [Integração com marketplaces: quanto custa (Plugg.To blog, 2023-02-07)](https://plugg.to/como-fazer-a-integracao-dos-seus-marketplaces-quanto-custa-3-beneficios/)
- A search-engine summary of a Plugg.To marketplace page says the company states it charges no commission per order and none per integrated marketplace. When I fetched the page, it did not contain that sentence (it only discusses marketplace commissions in general). Treat this claim as **unverified**. — [plugg.to/venda-em-marketplace](https://plugg.to/venda-em-marketplace/)

### Inferences
- Through at least 2023, the model was a pure flat SaaS subscription (monthly or annual), and the marketing positioned this explicitly against %-of-GMV competitors.
- The current (2025-2026) plans page appears to have added a **GMV dimension**. The Pro plan "covers" up to R$ 100k GMV and has a "lower take rate depending on revenue". The most plausible reading is a hybrid: a subscription that includes a GMV allowance, plus a % (take rate) on GMV above the allowance or on higher tiers, with the % falling as revenue rises. This is an inference from page wording, not a documented fee schedule. The FAQ's "sem comissões" wording may be legacy copy, or may refer only to per-marketplace fees, not to GMV-based fees.
- "No per-order fee" is consistent across Plugg.To's own sources. No source shows a per-order fee.

### Gaps
- Actual take-rate percentage(s), how GMV is measured (all channels or marketplace orders only), and what happens above R$ 100k GMV (overage) are not published.
- Plugg.To's Termos de Uso could not be found or read, so billing, readjustment, minimum term and cancellation clauses are unknown.

## 2. Plan names, prices and limits (current and historical)

### Takeaway
Current official list prices are **Basic from R$ 399,00/month** and **Pro from R$ 799,00/month**. Above those sit **Premium** (high volume) and **Personalizado** tiers that are sold only by quote. Tiers are differentiated by users, support level and GMV coverage, not by SKU or order counts. Historical tables could not be verified because the Wayback Machine was unreachable.

### Cited Findings
- **Basic**: "A partir R$ 399,00". It includes 2 users per panel, integration with 80 marketplaces at no extra cost, centralized order and listing management with automatic sync, and support "somente via chamado". — [Planos Plugg.To](https://plugg.to/planos/) (read 2026-10-07)
- **Pro**: "A partir de R$ 799,00". It has everything in Basic plus "Cobertura de GMV de até R$ 100 mil", a dedicated CS and "Menor take rate conforme faturamento". — [Planos Plugg.To](https://plugg.to/planos/)
- **Premium**: described only as aimed at high-volume sellers, with no price. **Personalizado**: "Fale com um consultor". — [Planos Plugg.To](https://plugg.to/planos/)
- The page lists no limits on orders, SKUs or channels. Channel count is effectively unlimited (80 marketplaces included). The page is inconsistent between "80" and "mais de 70" marketplaces. — [Planos Plugg.To](https://plugg.to/planos/)
- Older plan structure: a Nuvemshop guide (updated 29/07/2026, original text likely older) describes three plans. Basic is "ideal para quem está começando e deseja realizar a gestão de apenas um canal de venda". Pro offers integration with "mais de 70 marketplaces sem custos adicionais". Premium comes with "um gerente de contas exclusivo". On prices the guide says they "ficam disponíveis à medida que você entra em contato com um consultor" and are "montados de acordo com a necessidade de cada lojista". — [Nuvemshop blog: O que é o Plugg.To](https://www.nuvemshop.com.br/blog/pluggto/)
- A search-engine summary of an older version of the plans page said Basic was limited to "01 marketplace" with no platform/ERP integration, and that Pro offered WhatsApp, phone and ticket support. This could not be confirmed by direct fetch. — [Planos Plugg.To (search summary)](https://plugg.to/planos/)
- Olist (Plugg.To's parent company) shows prices of R$ 66 to R$ 663,60/month on its Plugg.To integration page. These are **Olist ERP plans**, not Plugg.To prices, and should not be cited as Plugg.To pricing. — [Olist: Integração Plugg.To](https://olist.com/hub-de-integracao/pluggto/)

### Inferences
- **Historical change**: Basic used to be limited to one marketplace, and "no extra cost per marketplace" applied only from Pro up. Today Basic includes all 80 marketplaces, and the tiers are separated by users, support and GMV/take rate. This is a shift from channel-based tiers to volume (GMV)-based tiers. The dating of this shift is uncertain, but it falls after the 2023 blog post and before Oct 2026.
- Prices were quote-only ("consulte") for a period, and the public "a partir de" prices appear to be relatively recent. This is inferred from the Nuvemshop guide and partner listings that show no prices.

### Gaps
- No Wayback Machine snapshots could be retrieved, so there is no dated historical price table. A follow-up should check web.archive.org/web/*/plugg.to/planos* from an environment with access.
- Annual-plan prices and the annual discount percentage are not published.
- The Premium and Personalizado prices are not published.

## 3. Setup/onboarding fee and add-ons

### Takeaway
There **is a setup (implementation) fee**, though it does not appear on the official plans page. Partner landing pages hosted on Plugg.To's own domain document a **list setup fee of R$ 3.000,00**, discounted 50% to R$ 1.500 on monthly plans and waived on annual plans. A third-party marketplace listing showed R$ 2.100. Implementation is assisted via WhatsApp. No paid add-ons are documented.

### Cited Findings
- SGPWeb partnership page (conteudo.plugg.to). Monthly plan: "50% de desconto no SETUP de R$3.000,00 - POR R$1.500,00", charged once at signup. Annual plan: "SETUP isento + 2 meses grátis no final da contratação!" The page is undated. — [Condição Especial Plugg.To (parceria SGPWeb)](https://conteudo.plugg.to/parceria-sgpweb)
- A search-result snippet for the CiaShop app store listing shows "Mensalidade: Consulte" and a setup of R$ 2.100,00 in 3 installments of R$ 700,00. The page itself could not be fetched (DNS failure), so this is snippet only. — [CiaShop store: PluggTo](https://store.ciashop.com.br/produto/156/pluggto)
- Loja Integrada app store listing: "Faça orçamento e ganhe 50% no SETUP!" — [Loja Integrada: Plugg.to](https://lojaintegrada.com.br/loja-aplicativos/plugg.to/)
- A Reclame Aqui complaint title ("Obsoleta e implentação não existe"), as quoted in a search snippet, says "o plano contratado tem isenção do SetUp, que seria o valor da implementação" (annual package). The page itself returned 403. — [Reclame Aqui: plugg.to](https://www.reclameaqui.com.br/plugg-to/obsoleta-e-implentacao-nao-existe_Nh9M1LLT8nKLyBII/)
- FAQ: "A Plugg.To realiza implementação assistida via WhatsApp". Timing depends on complexity. The FAQ does not mention a setup fee. — [Perguntas Frequentes Plugg.To](https://plugg.to/perguntas-frequentes-plugg-to/)
- Nuvemshop guide: "treinamento coletivo gratuito para todos os planos". — [Nuvemshop blog](https://www.nuvemshop.com.br/blog/pluggto/)

### Inferences
- The standard setup fee appears to be about **R$ 3.000** (partner pages discount from this base). The R$ 2.100 figure is either an older price or a channel-specific price. Waiving setup is the main lever used to push annual contracts.
- Add-ons: extra marketplaces and new features are explicitly not charged extra. Premium support (dedicated CS, account manager) is bundled into higher tiers rather than sold separately. Extra users beyond 2 on Basic probably require an upgrade, but this is not documented.

### Gaps
- No source documents paid add-ons (extra users, ERP connectors, premium support) with prices.
- Whether the setup fee is charged to all new clients today is not confirmed by the official plans page.

## 4. Free trial and partner discounts (incl. Total Express)

### Takeaway
Plugg.To officially **does not offer a free trial** and offers live demos instead. Partner discounts of **up to 20%** on the subscription and 50% (or 100% on annual) off setup are documented for several partners. **No source was found for a 20% discount for Total Express customers.**

### Cited Findings
- "Não oferecemos teste gratuito", with live demos offered instead. — [Perguntas Frequentes Plugg.To](https://plugg.to/perguntas-frequentes-plugg-to/); also on [Planos Plugg.To](https://plugg.to/planos/)
- The Nuvemshop guide shows a "Testar 7 dias grátis" CTA. This is most likely Nuvemshop's own store trial CTA, not a Plugg.To trial, and it conflicts with the Plugg.To FAQ. — [Nuvemshop blog](https://www.nuvemshop.com.br/blog/pluggto/)
- Nuvemshop app listing: "Aproveite a parceria exclusiva com a Nuvemshop e garanta até 20% de DESCONTO!" It shows no prices and directs users to WhatsApp for "planos e preços". — [Nuvemshop app store: Plugg.To](https://www.nuvemshop.com.br/loja-aplicativos-nuvem/pluggto-v2)
- Loja Integrada partnership page: "20% de DESCONTO", with "*Desconto diferente para os planos MENSAL e ANUAL". — [conteudo.plugg.to/parceria-loja-integrada](https://conteudo.plugg.to/parceria-loja-integrada)
- SGPWeb: 50% off setup (monthly plan), or setup waived plus 2 free months (annual plan). — [conteudo.plugg.to/parceria-sgpweb](https://conteudo.plugg.to/parceria-sgpweb)
- A search summary also mentioned a ComEcomm member deal (50% off setup) and an e-flips deal (20%). The ComEcomm page returned 404 on fetch. — [comecomm.com.br/pluggto-desconto](https://www.comecomm.com.br/pluggto-desconto/); [conteudo.plugg.to/ecommerce-e-flips](https://conteudo.plugg.to/ecommerce-e-flips)
- Plugg.To runs a partner program. — [Programa Parcerias Plugg.To](https://plugg.to/programa-parcerias/)
- Total Express appears among Plugg.To's logistics integrations, but no discount is stated. A Total Express episode of E-Commerce Brasil's "Entre Amigos" podcast (on PUDO) did not mention Plugg.To in its description. — [Plugg.To integrações](https://plugg.to/marketplace-de-integracao/); [Entre Amigos: E-Commerce Brasil e Total Express](https://creators.spotify.com/pod/profile/e-commerce-brasil3/episodes/Entre-Amigos---E-Commerce-Brasil-e-Total-Express--Pick-up-and-Drop-off-a-revoluo-dos-processos-logsticos-e2nus79)

### Inferences
- A "20% discount for Total Express customers" would fit Plugg.To's standard partner template, where platform and logistics partners get up to 20% off the subscription and/or 50% off setup. The Total Express claim is therefore plausible but **undocumented** in what I could access. It may exist only in the podcast audio or in an unindexed conteudo.plugg.to/parceria-* landing page.

### Gaps
- The Total Express 20% discount could not be verified. The podcast audio was not transcribed and no landing page was found. A suggested check is conteudo.plugg.to/parceria-totalexpress or similar URLs.
- Exact discount percentages for monthly and annual plans under partner deals are not published.
