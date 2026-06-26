# Vecchio Amaro del Capo - Report SEO schematico per presentazione e LLM

## Come usare questo documento

Questo documento è una versione operativa e schematica del report SEO completo. È pensato per due usi: alimentare una presentazione più agile e fornire all'LLM una base ordinata per approfondire i temi quando l'utente fa domande.

Regola di lettura per l'LLM: rispondi prima con la sintesi, poi approfondisci solo se richiesto. Usa i dettagli sotto ogni sezione come materiale di supporto, non come testo da riversare integralmente nella risposta.

---

## 1. Executive summary

### Tesi centrale

Vecchio Amaro del Capo ha asset di marca molto forti, ma il sito attuale li usa dentro un ecosistema contenutistico troppo stretto. Il nuovo sito dovrebbe trasformare il brand da semplice brand site con pagine prodotto e cocktail a piattaforma editoriale e commerciale leggera, internazionale e ben strutturata.

### Asset forti del brand

| Asset | Valore SEO/brand | Come usarlo meglio |
|---|---|---|
| Calabria | Identità territoriale distintiva | Hub su territorio, botanicals, tradizione e cultura del consumo |
| 29 ingredienti | Differenziazione di prodotto | Pagine ingredienti, storytelling botanico, contenuti educational |
| Ricetta segreta | Mistero e heritage | Brand story, FAQ, contenuti premium e narrative di autenticità |
| Consumo a -20 °C | Ritualità proprietaria | Hub "come si beve", video, FAQ, cocktail e occasioni |
| Mixology | Apertura a nuovi usi | Recipe hub, bartender content, ricette per stagione/occasione |
| Riserva e Red Hot Edition | Segmentazione portfolio | Template prodotto ricchi, gifting, premium, occasioni specifiche |

### Problema principale

Il limite principale non è solo tecnico: è la scarsa ampiezza del sistema contenuti. Il sito racconta bene alcuni messaggi iconici, ma non costruisce abbastanza cluster SEO su categoria, occasioni, rituali, mercati esteri, cocktail, acquisto e trade.

### Opportunità principale

Costruire un sito organizzato per hub-and-spoke:

| Hub principale | Funzione |
|---|---|
| Brand e Calabria | Rendere memorabile l'origine e la differenza |
| Categoria amaro / herbal liqueur | Educare chi non conosce la categoria |
| Come si beve / rituale -20 °C | Trasformare il serve in asset proprietario |
| Cocktail e occasioni | Intercettare query informational e lifestyle |
| Where to buy | Collegare domanda organica e percorsi commerciali |
| Bartender / trade | Costruire autorevolezza professionale e link earning |

### Cinque priorità strategiche

1. Uniformare l'architettura tra Italia, Germania, Spagna e inglese.
2. Passare da pagine isolate a cluster editoriali.
3. Localizzare davvero i contenuti, non solo tradurli.
4. Rendere coerenti i percorsi commerciali "where to buy" in ogni mercato.
5. Progettare contenuti leggibili da Google e sistemi generativi, con entità chiare, dati strutturati e gerarchie semantiche.

---

## 2. Diagnosi del sito attuale

### 2.1 Stato tecnico e crawling

| Tema | Diagnosi | Impatto | Azione consigliata |
|---|---|---|---|
| Age gate | Le home locali reindirizzano verso pagine di autorizzazione con parametro `return_to=home` | Può complicare crawling, canonicalizzazione e UX SEO | Verificare con crawl completo, log file e Search Console |
| Indicizzazione | Google sembra comunque indicizzare snippet di pagine locali e interne | Il contenuto è raggiungibile, ma il percorso non è pulito | Separare controllo età lato UX da accessibilità crawler |
| Canonical/hreflang | Non certificabili dal solo rendering pubblico | Rischio di segnali internazionali incompleti | Audit sorgente su canonical, hreflang, sitemap, robots |
| Structured data | Non verificato in modo completo | Opportunità persa su Product, Recipe e Breadcrumb | Implementare e validare markup nel nuovo sito |
| Performance | Da misurare con dati reali | Possibile impatto su UX e ranking | Usare PageSpeed, CrUX, Search Console, non checker generici |

Dettaglio utile per LLM: l'age gate non va trattato come prova certa di blocco SEO, ma come rischio da verificare. Il report segnala che Google trova comunque contenuti, quindi la raccomandazione corretta è audit tecnico, non conclusione definitiva.

### 2.2 Architettura internazionale

| Mercato | Navigazione osservata | Problema |
|---|---|---|
| Italia | Cocktails, Segreti del Capo, Riserva, Red Hot Edition, Ready to Serve, Store | Più completa ma non replicata negli altri mercati |
| Inglese | Cocktails, Capo's secrets, Riserva, Red Hot Edition | Manca percorso commerciale chiaro |
| Germania | Cocktails, "Geheimnisse del Capo", Riserva, Wo kaufen | Label ibrida e struttura diversa |
| Spagna | Cócteles, Secretos del Capo, Riserva, Red Hot Edition | Manca percorso buy forte; localizzazione da rifinire |

Impatto: i mercati non condividono lo stesso perimetro informativo, lo stesso portfolio navigabile e le stesse call to action commerciali. Questo riduce efficienza SEO, scalabilità dei template e chiarezza internazionale del brand.

### 2.3 Contenuto e copertura semantica

| Area | Stato attuale | Gap |
|---|---|---|
| Brand story | Presente e forte | Poco trasformata in hub tematici |
| Prodotto | Messaggi distintivi chiari | Template da arricchire con FAQ, pairing, serve, correlati |
| Cocktail | Ricette presenti | Mancano cluster per occasione, stagione, stile, difficoltà |
| Education | Debole | Mancano guide tipo "what is amaro", "how to drink amaro" |
| Localizzazione | Presente ma irregolare | Alcune stringhe non native o ibride |
| Commerciale | Non uniforme | Store IT, locator DE, percorsi EN/ES meno chiari |

Dettaglio utile per LLM: il sito non è vuoto; il problema è che i contenuti esistenti sono poco orchestrati. La risposta corretta non è "creare contenuti da zero", ma "organizzare, arricchire e scalare gli asset già presenti".

---

## 3. Gap principali

### Tabella prioritaria

| Priorità | Gap | Perché conta | Effort | Impatto |
|---|---|---|---|---|
| 1 | Architettura internazionale incoerente | Riduce trasferibilità SEO e chiarezza per mercati | Medio | Alto |
| 2 | Mancanza di hub educational | Limita ranking su query non-brand e category search | Medio | Alto |
| 3 | Cocktail non organizzati in cluster | Spreca contenuti già disponibili | Medio | Alto |
| 4 | Localizzazione non nativa | Riduce fiducia, CTR e rilevanza locale | Medio | Medio-alto |
| 5 | Where-to-buy non uniforme | Perde domanda commerciale per paese | Medio | Alto |
| 6 | Calabria e -20 °C sottoutilizzati | Asset proprietari non scalati editorialmente | Medio | Molto alto |
| 7 | Assenza area bartender/trade | Manca autorevolezza professionale e community | Medio-alto | Medio-alto |
| 8 | Structured data da rafforzare | Perde segnali comprensibili da search/AI | Medio | Medio-alto |

### Sintesi dei gap per presentazione

Il sito ha identità, prodotto e rituale; gli manca il sistema editoriale che trasforma questi asset in domanda organica. Il nuovo sito deve lavorare su architettura, hub, localizzazione e percorsi commerciali coerenti.

---

## 4. Competitor analysis schematica

### 4.1 Jägermeister

| Dimensione | Cosa fa bene | Lezione per Vecchio |
|---|---|---|
| Cultura di marca | Non si limita a prodotto e drinks; costruisce exploration e lifestyle | Ogni asset del brand deve generare contenuti e percorsi |
| Community bartender | Hubertus Circle con community, exchange, education, experience | Creare almeno una sezione bartender/trade leggera |
| E-commerce/shop | Percorsi commerciali più avanzati | Rafforzare where-to-buy e retailer paths |
| Autorevolezza | Usa contenuti e community come motore di relazione | Non copiare estetica, copiare infrastruttura editoriale |

Risposta breve se chiesto "perché Jägermeister è avanti": perché presidia prodotto, cultura, community bartender e percorsi commerciali, mentre Vecchio resta più vicino a un brand site tradizionale.

### 4.2 Amaro Montenegro

| Dimensione | Cosa fa bene | Lezione per Vecchio |
|---|---|---|
| Internazionalizzazione | Più lingue e struttura più ampia | Rendere coerente il perimetro internazionale |
| Mixology | Ricette attribuite a mixologist e community "The Vero Bartender" | Passare da archivio ricette a strategia cocktail |
| Posizionamento | Digestif e cocktail classici reinterpretati | Elevare il prodotto da ingrediente a ingrediente autorevole |

Risposta breve: Montenegro mostra come un amaro possa restare credibile come digestivo e allo stesso tempo diventare rilevante nella mixology internazionale.

### 4.3 Ramazzotti, focus Germania

| Dimensione | Cosa fa bene | Lezione per Vecchio |
|---|---|---|
| Governance paese | Struttura locale chiara e selettore paese più maturo | La Germania richiede gestione locale vera |
| Ricette e occasioni | Ampia copertura di serve, prodotti, stagioni, momenti d'uso | Creare recipe hub DE molto più articolato |
| Esperienza fisica | Casa Ramazzotti trasforma storia e tasting in contenuto | Calabria e luoghi del brand possono diventare contenuto visitabile |

Risposta breve: in Germania Ramazzotti è il benchmark più duro perché non vende solo prodotto, ma un universo di usi e occasioni.

### 4.4 Averna

| Dimensione | Stato | Lezione per Vecchio |
|---|---|---|
| Presenza digitale | Sito ufficiale osservato in manutenzione nel report | Possibile spazio competitivo da occupare |
| Identità territoriale | Forte associazione con Sicilia | Vecchio deve trasformare Calabria in vantaggio editoriale |
| Categoria | Brand storico e semanticamente rilevante | Batterlo su freschezza digitale e struttura SEO |

Risposta breve: Averna resta forte come marca di categoria, ma lascia spazio digitale se Vecchio costruisce meglio Calabria, rituale e contenuti.

### 4.5 Benchmark aspirazionali

| Brand | Cosa insegna | Applicazione per Vecchio |
|---|---|---|
| Hendrick's | Immaginario editoriale, rubriche, stagionalità | Creare serie narrative su rituale, botanicals e cocktail |
| Aperol | Ritualità semplice e scalabile, 3-2-1, eventi, pairing | Trasformare il -20 °C in un sistema di contenuti |
| Martini | Education di categoria, esperienze, Casa Martini | Creare guide su amaro, aperitivo, digestif e visite/esperienze |

---

## 5. Strategia per mercati

### 5.1 Italia

| Tema | Raccomandazione |
|---|---|
| Posizionamento | L'amaro italiano di Calabria dal rituale ghiacciato inconfondibile |
| Priorità SEO | Passare da brand noto a categoria autorevole |
| Pagine chiave | Cos'è un amaro, amaro calabrese, perché si beve a -20 °C, cocktail con amaro, abbinamenti, dove comprare, regalo premium |
| Competitor | Montenegro, Averna, Ramazzotti |
| Vantaggio di Vecchio | Ritualità a -20 °C più distintiva rispetto ai competitor |

Dettaglio utile: in Italia il pubblico capisce già la categoria amaro, quindi il contenuto può spingere su rituale, territorio, pairing, premium e mixology.

### 5.2 Germania

| Tema | Raccomandazione |
|---|---|
| Posizionamento | Italian herbal bitter liqueur with a unique iced serve ritual |
| Lessico chiave | Kräuterlikör, Digestif, Aperitif, Rezepte, pur auf Eis, Spritz, wo kaufen |
| Pagine chiave | Category page DE, how to drink DE, recipe hub DE, seasonal DE, ingredients/Calabria DE, where to buy DE |
| Competitor | Ramazzotti per ricette/occasioni, Jägermeister per community/culture/trade |
| Rischio | Tradurre dall'italiano senza adattare al lessico locale |

Dettaglio utile: la Germania è il mercato più esigente perché i competitor hanno già una grammatica digitale matura. Serve localizzazione vera, non traduzione.

### 5.3 Spagna

| Tema | Raccomandazione |
|---|---|
| Posizionamento | Amaro italiano legato a aperitivo, cócteles, spritz e convivialità |
| Lessico chiave | amaro italiano, licor amargo italiano, licor de hierbas italiano, cócteles con amaro, spritz italiano, dónde comprar |
| Pagine chiave | Qué es el amaro italiano, cómo tomarlo, cócteles con amaro, spritz con amaro, aperitivo italiano, dónde comprar |
| Competitor/benchmark | Aperol per rituale spritz e aperitivo |
| Rischio | Lingua poco naturale o stringhe lasciate in inglese |

Dettaglio utile: in Spagna la leva migliore è rendere il prodotto culturalmente comprensibile, fresco e conviviale.

### 5.4 Inglese / internazionale

| Tema | Raccomandazione |
|---|---|
| Posizionamento | Italian amaro from Calabria / Italian herbal liqueur |
| Problema attuale | "Italian liquor" è troppo generico |
| Pagine chiave | What is amaro, Italian herbal liqueur guide, how to drink amaro, amaro cocktails, digestif after dinner, amaro vs vermouth, where to buy |
| Intent dominante | Education di categoria |
| Rischio | Dare per scontato che l'utente sappia cos'è un amaro |

Dettaglio utile: nel mercato internazionale bisogna prima spiegare la categoria, poi vendere il brand.

---

## 6. Keyword map sintetica

### Italia

| Cluster | Query esempio | Intent | Pagina consigliata | Priorità |
|---|---|---|---|---|
| Brand | vecchio amaro del capo, amaro del capo | Navigazionale | Home + product hub | Alta |
| Categoria | amaro italiano, amaro calabrese, digestivo alle erbe | Informazionale/commerciale | Hub "Cos'è l'amaro" | Alta |
| Rituale | amaro ghiacciato, come servire amaro del capo, amaro a -20 | Informazionale | Hub rituale ghiacciato | Alta |
| Cocktail | cocktail con amaro, negroni con amaro, spritz con amaro | Informazionale | Cocktail hub | Alta |
| Territorio | Calabria liquori, botaniche di Calabria | Informazionale | Hub Calabria/ingredienti | Medio-alta |
| Commerciale | dove comprare amaro del capo | Transazionale | Dove comprare | Alta |

### Germania

| Cluster | Query esempio | Intent | Pagina consigliata | Priorità |
|---|---|---|---|---|
| Categoria | italienischer kräuterlikör, amaro italien | Informazionale/commerciale | Category landing DE | Alta |
| Rituale | amaro eisgekühlt, digestif auf eis | Informazionale | Serving ritual DE | Alta |
| Cocktail | cocktails mit amaro, spritz mit amaro | Informazionale | Recipe hub DE | Alta |
| Commerciale | wo kaufen vecchio amaro del capo | Transazionale | Where to buy DE | Alta |
| Educational | was ist amaro, unterschied amaro und kräuterlikör | Informazionale | FAQ/guide DE | Medio-alta |
| Stagionali | winter aperitif, sommer aperitif | Informazionale | Seasonal clusters | Media |

### Spagna

| Cluster | Query esempio | Intent | Pagina consigliata | Priorità |
|---|---|---|---|---|
| Categoria | amaro italiano, licor amargo italiano | Informazionale/commerciale | Category landing ES | Alta |
| Cocktail | cócteles con amaro, spritz italiano | Informazionale | Recipe hub ES | Alta |
| Rituale | cómo tomar amaro, amaro con hielo | Informazionale | Serving guide ES | Medio-alta |
| Commerciale | dónde comprar amaro del capo | Transazionale | Where to buy ES | Alta |
| Territorio | Calabria Italia licor, hierbas de Calabria | Informazionale | Story/ingredients ES | Media |

### Inglese

| Cluster | Query esempio | Intent | Pagina consigliata | Priorità |
|---|---|---|---|---|
| Categoria | italian amaro, italian herbal liqueur, what is amaro | Informazionale | Educational hub EN | Alta |
| Brand | vecchio amaro del capo, capo amaro | Navigazionale | Brand hub EN | Alta |
| Cocktail | amaro cocktails, amaro spritz | Informazionale | Recipe hub EN | Alta |
| Serving | how to drink amaro, serve amaro cold | Informazionale | Serving ritual EN | Alta |
| Commerciale | where to buy vecchio amaro del capo | Transazionale | Where to buy EN | Alta |
| Education | amaro vs vermouth, digestif vs aperitif | Informazionale | Guides/FAQ EN | Medio-alta |

---

## 7. Blueprint del nuovo sito

### 7.1 Principio architetturale

Il nuovo sito dovrebbe usare una logica hub-and-spoke: pochi hub principali molto solidi, collegati a pagine figlie per prodotti, cocktail, guide, occasioni, mercati e acquisto.

### 7.2 Hub consigliati

| Hub | Obiettivo | Pagine figlie |
|---|---|---|
| Brand | Rafforzare identità e differenza | Storia, Calabria, ingredienti, ricetta segreta, premi |
| Products | Spiegare portfolio e usi | Del Capo, Riserva, Red Hot, Ready to Serve |
| How to drink | Possedere il rituale | -20 °C, servizio, bicchiere, after dinner, aperitivo |
| Cocktails | Intercettare ricerca e occasioni | Spritz, sour, negroni twist, summer, winter, party |
| Journal / Guides | Educare categoria e mercati esteri | What is amaro, amaro vs vermouth, digestif vs aperitif |
| Calabria & botanicals | Trasformare origine in contenuto | Botaniche, territorio, cultura, tradizione |
| Where to buy | Convertire domanda commerciale | Italy, Germany, Spain, Global, retailers, venues |
| Bartenders / trade | Costruire autorevolezza B2B | Signature serves, resources, community, featured bars |

### 7.3 Template necessari

| Template | Deve includere |
|---|---|
| Product | Descrizione, rituale di servizio, ingredienti chiave, FAQ, pairing, cocktail correlati, structured data Product |
| Recipe | Ingredienti, step, tempo, difficoltà, occasione, glassware, garnish, related recipes, structured data Recipe |
| Guide | Definizione, contesto, esempi, FAQ, link a prodotti/cocktail, entità chiare |
| Where to buy | Paese, retailer/locator, disponibilità, FAQ acquisto, link a prodotti |
| Market landing | Linguaggio locale, category education, prodotti disponibili, cocktail locali, buying path |

### 7.4 Sitemap consigliata

#### Corporate e brand

- `/it-it/`, `/de-de/`, `/es-es/`, `/en/`
- `/brand/`
- `/brand/storia/`
- `/brand/calabria/`
- `/brand/ingredienti/`
- `/brand/come-si-serve/`
- `/brand/perche-a-20/`
- `/brand/premi-e-riconoscimenti/`
- `/brand/contatti/`

#### Prodotti

- `/products/vecchio-amaro-del-capo/`
- `/products/riserva-del-centenario/`
- `/products/red-hot-edition/`
- `/products/ready-to-serve/`
- `/products/ready-to-serve/capo-tonic/`
- `/products/ready-to-serve/capo-arrabbiato/`

#### Cocktail

- `/cocktails/`
- `/cocktails/by-occasion/aperitivo/`
- `/cocktails/by-occasion/after-dinner/`
- `/cocktails/by-occasion/party/`
- `/cocktails/by-style/spritz/`
- `/cocktails/by-style/sour/`
- `/cocktails/by-style/negroni-twist/`
- `/cocktails/by-season/summer/`
- `/cocktails/by-season/winter/`
- `/cocktails/negroni-del-capo/`
- `/cocktails/capo-arrabbiato-spritz/`
- `/cocktails/capo-sour/`

#### Editoriali

- `/journal/`
- `/journal/what-is-amaro/`
- `/journal/italian-herbal-liqueur-guide/`
- `/journal/amaro-vs-vermouth/`
- `/journal/digestif-vs-aperitif/`
- `/journal/how-to-drink-amaro/`
- `/journal/food-pairing-with-amaro/`
- `/journal/calabrian-botanicals/`
- `/journal/gift-guide-premium-amaro/`

#### Commerciali

- `/where-to-buy/`
- `/where-to-buy/italy/`
- `/where-to-buy/germany/`
- `/where-to-buy/spain/`
- `/where-to-buy/global/`
- `/retailers/`
- `/venues/`
- `/events/`

#### Stagionali e campagne

- `/summer-aperitivo/`
- `/winter-digestif/`
- `/holiday-gifting/`
- `/festival-season/`
- `/world-amaro-day/`

#### Bartender e trade

- `/bartenders/`
- `/bartenders/signature-serves/`
- `/bartenders/resources/`
- `/bartenders/community/`
- `/venues/featured-bars/`

---

## 8. Roadmap annuale

| Fase | Attività principali | Output | KPI |
|---|---|---|---|
| Q1 | Audit tecnico, architettura IA, mappatura URL, piano hreflang, template product/recipe/guide, localizzazione DE/ES/EN | Specifiche SEO e template pronti | Errori tecnici, baseline CWV, copertura indicizzazione |
| Q2 | Lancio nuovo sito/struttura, core hub, redirect, markup Product/Recipe/Breadcrumb, immagini | Nuovo perimetro indexable | Ranking brand/non-brand, CTR, pagine indicizzate, rich results |
| Q3 | Espansione cocktail, occasioni, Calabria, pairing, where-to-buy, digital PR estiva | Crescita copertura semantica | Click non-brand, share of voice, referral/link mentions |
| Q4 | Stagionalità inverno, gifting, digestif culture, hot serves DE, refresh top pages, AI visibility | Consolidamento | Conversion assisted, branded demand, featured snippets, citazioni AI proxy |

### Ritmo mensile consigliato

Ogni mese pubblicare o aggiornare:

- 1 contenuto educational.
- 2 o 3 cocktail pages o refresh ricette.
- 1 contenuto stagionale.
- Internal linking e metadati delle pagine principali.
- 1 piccola attivazione PR, bartender, venue o evento.

---

## 9. Quick wins

| # | Azione | Perché è urgente |
|---|---|---|
| 1 | Uniformare la navigazione principale fra IT, DE, ES, EN | Riduce incoerenza internazionale |
| 2 | Correggere stringhe non native o miste | Migliora fiducia e CTR locale |
| 3 | Creare hub "What is Amaro" | Intercetta query educational |
| 4 | Creare hub "How to drink" | Possiede il rituale -20 °C |
| 5 | Rendere stabile "Where to buy" in tutti i mercati | Recupera domanda commerciale |
| 6 | Arricchire template ricetta | Trasforma ricette isolate in cluster |
| 7 | Creare hub Calabria e botanicals | Scala l'asset territoriale |
| 8 | Implementare Product/Recipe/Breadcrumb structured data | Migliora comprensione da search e AI |
| 9 | Preparare hreflang con x-default | Migliora governance internazionale |
| 10 | Misurare CWV e indicizzazione con strumenti ufficiali | Evita decisioni basate su dati deboli |

---

## 10. Dati verificati, ipotesi e dati mancanti

### Verificati pubblicamente nel report

- Struttura per cartelle lingua.
- Redirect verso pagine age gate.
- Composizione diversa dei menu per mercato.
- Presenza di store IT e dealer locator DE.
- Presenza di pagine prodotto e cocktail.
- Segnali di localizzazione incompleta.
- Strutture editoriali visibili dei competitor e benchmark.

### Ipotesi ragionate

- Peso effettivo dell'age gate su crawling e canonicalizzazione.
- Qualità reale di canonical, hreflang e markup nel sorgente completo.
- Severità delle criticità Core Web Vitals.
- Entità e structured data effettivamente leggibili dai sistemi generativi.

### Dati proprietari necessari

- Search Console per query e paesi.
- GA4 per comportamento, conversioni e engagement.
- Crawl completo del sito.
- Log file server.
- Tool keyword/ranking come Semrush, Sistrix o Similarweb.
- Dati sell-out/distribuzione per priorità commerciali per paese.

---

## 11. Risposte pronte per LLM

### Se l'utente chiede "qual è il problema principale?"

Il problema principale è che il sito ha asset di marca forti ma li organizza in un ecosistema contenutistico troppo stretto. Mancano hub educational, cluster cocktail, localizzazione nativa e percorsi commerciali coerenti per mercato.

### Se l'utente chiede "cosa manca rispetto a Jägermeister?"

Mancano soprattutto community, cultura di marca strutturata, contenuti trade/bartender e percorsi commerciali più maturi. Jägermeister trasforma ogni asset in un sistema di contenuti e relazioni, mentre Vecchio oggi lavora più per pagine isolate.

### Se l'utente chiede "cosa fare subito?"

Le prime azioni sono uniformare la navigazione internazionale, correggere la localizzazione, creare hub "What is Amaro" e "How to drink", rendere coerente il where-to-buy e arricchire i template ricetta/prodotto con markup.

### Se l'utente chiede "perché la Germania è importante?"

La Germania è il mercato più competitivo perché Ramazzotti e Jägermeister presidiano già ricette, occasioni, community e linguaggio locale. Vecchio deve localizzare davvero su termini come Kräuterlikör, Digestif, Rezepte, Spritz e wo kaufen.

### Se l'utente chiede "come rendere il sito più adatto all'AI?"

Serve contenuto strutturato per entità, cluster chiari, FAQ, dati strutturati Product/Recipe/Breadcrumb, naming coerente e pagine educational che spieghino categoria, rituale, ingredienti e usi.

### Se l'utente chiede "quali sono le dieci pagine fondamentali?"

Le pagine fondamentali sono: Cos'è Vecchio Amaro del Capo, Cos'è un amaro italiano, Perché si beve a -20 °C, Calabria e botanicals, Come bere l'amaro, Cocktails with Amaro del Capo, Where to buy, aperitivo/after dinner, food pairing e FAQ amaro vs vermouth/digestif vs aperitif.

---

## 12. Sintesi finale per slide

Vecchio Amaro del Capo non deve limitarsi a rifare il sito: deve costruire un ecosistema editoriale internazionale. Il vantaggio competitivo esiste già nei suoi asset, soprattutto Calabria, 29 ingredienti e rituale a -20 °C; ora va trasformato in architettura, contenuti, localizzazione, percorsi commerciali e markup.
# Analisi SEO strategica e operativa per Vecchio Amaro del Capo

## Sintesi strategica

L’attuale sito di Vecchio Amaro del Capo comunica bene alcuni asset di marca molto forti — Calabria, ricetta segreta con 29 ingredienti, consumo ghiacciato a -20 °C, mixology, Riserva e Red Hot Edition — ma li distribuisce in un ecosistema informativo ancora troppo stretto per sostenere una crescita SEO internazionale ambiziosa. Le pagine pubblicamente rilevabili ruotano soprattutto attorno a homepage locali, brand story, alcune product page e ricette cocktail; mancano invece veri hub editoriali, pagine educational di categoria, percorsi per intent commerciali più maturi e una strategia internazionale coerente tra Italia, Germania, Spagna e inglese. citeturn2search0turn0search8turn22search9turn22search10turn15search10

Il limite principale rispetto ai competitor non è solo “tecnico”, ma di **ampiezza del sistema contenuti**. Jägermeister presidia non solo prodotti e drink, ma anche exploration, cultura di marca e community bartender con Hubertus Circle; Montenegro ha una struttura multilingua più estesa e un’area cocktail con ricette attribuite a mixologist; Ramazzotti in Germania presidia in modo molto più capillare ricette, famiglie prodotto, newsletter, history e persino un’esperienza fisica di brand; Aperol e Martini mostrano come un brand beverage possa unire recipe content, ritualità, eventi, shop/visit, guide educational e lifestyle. citeturn17view2turn18view0turn18view1turn19view0turn19view1turn19view2turn21view0turn21view1turn20view3turn20view4

Per il nuovo sito, l’opportunità più rilevante è trasformare Vecchio Amaro del Capo da “brand site con pagine prodotto e cocktail” a **piattaforma editoriale e commerciale leggera**, capace di coprire quattro grandi aree: brand heritage, categoria amaro/herbal liqueur, occasioni di consumo, e rituali/cocktail. Questo è particolarmente importante nei mercati esteri, dove il brand non può dare per scontata la comprensione della categoria “amaro” come accade in Italia. Google raccomanda per i siti multilingua e multiregionali un uso chiaro di versioni localizzate e `hreflang`, mentre per product, recipe e breadcrumb pages la documentazione Search Central evidenzia vantaggi espliciti di dati strutturati corretti. citeturn24search9turn24search0turn24search1turn24search4turn24search7turn24search25

Le differenze strategiche fra mercati sono nette. In Italia il sito può ambire a presidiare le query su amaro italiano, digestivo, ghiacciato, Calabria, food pairing e rituale post-cena. In Germania il lessico di categoria è più vicino a **Kräuterlikör**, **Digestif**, **Aperitif**, **Rezepte**, e il benchmark Ramazzotti/Jägermeister è molto più avanzato sul fronte ricette, community e articolazione del portafoglio. In Spagna il potenziale è soprattutto nell’area aperitivo/spritz/cócteles e nella traduzione culturale del prodotto. In inglese la sfida è educativa: spiegare “what is amaro”, “Italian herbal liqueur”, serving ritual e cocktail use in modo molto più esplicito rispetto a quanto oggi si vede sul sito. citeturn2search18turn7search5turn10search6turn21view1turn20view4turn14search8

Le priorità che dovrebbero guidare il progetto sono cinque. Prima: risolvere l’incoerenza di architettura fra lingue e mercati. Seconda: costruire un modello di contenuti per cluster, non per singole pagine isolate. Terza: localizzare davvero, non solo tradurre. Quarta: integrare percorsi “where to buy / dove comprare / where to find it” coerenti per ogni mercato. Quinta: progettare il sito in modo che sia leggibile da motori di ricerca e sistemi generativi, con contenuti ben strutturati, nomenclatura chiara, entità esplicite e dati strutturati. citeturn1view2turn1view3turn1view4turn1view5turn24search0turn24search25

Le attività annuali che hanno più probabilità di generare crescita reale non saranno micro-fix tecnici isolati, ma un programma continuativo di: consolidamento internazionale, lancio di hub editoriali, messa a terra di template recipe/product più ricchi, contenuti stagionali, contenuti bartender e occasion-based, ottimizzazione immagini e markup, e digital PR coerente con Calabria, aperitivo, mixology e lifestyle italiano. I competitor più forti stanno già lavorando su questi fronti con maggiore continuità e profondità. citeturn17view2turn18view1turn19view1turn21view0turn20view3

## Audit SEO del sito attuale

### Stato tecnico e segnali di crawling

La struttura pubblicamente raggiungibile usa sottocartelle lingua (`/it/`, `/en/`, `/de/`, `/es/`), ma l’accesso diretto alle home locali viene reindirizzato verso pagine di autorizzazione/age gate (`/autorizzazione/`, `/authorization/`, `/genehmigung/`, `/autorizacion/`) con parametro `return_to=home`. Allo stesso tempo, le SERP mostrano che Google indicizza e snippetta contenuti delle pagine locali e di molte pagine interne. Questo suggerisce che l’age gate convive con contenuti comunque crawlati o pre-renderizzati, ma introduce una complessità inutile sul percorso di ingresso e sulla coerenza fra URL di destinazione per utenti e motori. È un punto da verificare in profondità con crawl completo, log file e Search Console, perché può incidere su crawling, canonicalizzazione e UX SEO. citeturn1view2turn1view3turn1view4turn1view5turn22search2turn22search4

Dal solo rendering pubblico non è possibile certificare in modo affidabile l’implementazione corrente di `canonical`, `hreflang`, sitemap XML, robots.txt e structured data nel sorgente completo. Per questo audit ho potuto verificare con certezza la struttura URL, i redirect verso l’age gate, la presenza di footer/accessibilità e la semantica delle pagine accessibili via snippet e pagine aperte; per il resto servirebbe un crawl sorgente o accesso a Search Console. Google chiarisce che `hreflang` è lo strumento corretto per comunicare versioni localizzate, mentre i report Core Web Vitals e PageSpeed sono gli strumenti appropriati per misurare performance reali. citeturn24search0turn24search8turn24search2turn24search5turn24search17

Una nota metodologica importante: esiste una vecchia analisi di terze parti del 2021 che menzionava robots.txt, sitemap.xml e punteggi PageSpeed mediocri, ma la considero **a bassa affidabilità** per decisioni 2026, sia per età del dato sia per i limiti noti di questi checker. La cito solo come segnale debole da re-testare, non come base decisionale. citeturn22search0

### Architettura informativa e coerenza internazionale

Il problema più evidente dell’architettura attuale è la **non uniformità fra mercati**. La navigazione italiana espone Cocktails, Segreti del Capo, Riserva, Red Hot Edition, Ready to Serve e Store; quella inglese espone Cocktails, Capo’s secrets, Riserva e Red Hot Edition; quella tedesca espone Cocktails, “Geheimnisse del Capo”, Riserva e Wo kaufen; quella spagnola espone Cócteles, Secretos del Capo, Riserva e Red Hot Edition. In altre parole: i mercati non condividono lo stesso perimetro informativo, lo stesso portafoglio navigabile né le stesse call to action commerciali. citeturn1view2turn1view3turn1view4turn1view5

Questa asimmetria genera un danno doppio. Da un lato riduce la trasferibilità SEO fra template e cluster di contenuto; dall’altro indebolisce la chiarezza di marca a livello internazionale. In Italia esiste un collegamento di store esterno verso Caffo Store; in Germania esiste un dealer locator interno “Wo kaufen”; in inglese e spagnolo non emerge con la stessa chiarezza un percorso d’acquisto comparabile dalla navigazione principale. Per un brand beverage distribuito in più mercati, questa divergenza architetturale è una perdita di efficienza sia organica sia commerciale. citeturn1view2turn2search2turn15search3

C’è anche un secondo indizio di debolezza IA: il sito ha sì un’area cocktail, ma non mostra pubblicamente veri hub tematici per intent diversi, come “what is amaro”, “how to drink amaro”, “amaro cocktails by occasion”, “amaro vs vermouth”, “digestivo calabrese”, “pairing”, “gift”, “where to buy”, “bartender resources” o “events”. I competitor e benchmark più maturi hanno proprio questo livello intermedio: non solo pagine, ma **sistemi di pagine**. citeturn22search10turn17view2turn18view1turn19view1turn21view1turn20view4

### Qualità del contenuto e copertura semantica

Il contenuto di marca oggi ruota attorno a pochi messaggi molto forti: amaro italiano, ricetta segreta, 29 ingredienti dalla Calabria, consumo ghiacciato a -20 °C, mixology e alcune varianti come Riserva e Red Hot Edition. Sono asset eccellenti; il problema è che non vengono ancora espansi in una copertura semantica all’altezza del potenziale del brand. Il sito presiede bene il racconto “iconico”, ma ancora poco il racconto “educational” e “occasion-based”. citeturn2search0turn0search8turn22search9turn22search6turn22search7

Le ricette cocktail hanno una struttura utile — ingredienti, step, glassware/servizio implicito — ma sembrano spesso isolate, senza un’intelaiatura editoriale più ampia che le metta in relazione per stile, occasione, stagione, livello di difficoltà o flusso di navigazione. Esempi come *Capo Vaticano*, *Negroni del Capo*, *Last Minute Sidecar*, *Momò* o *Capo Arrabbiato Spritz* mostrano che il contenuto base esiste; ciò che manca è il layer superiore di cluster, filtri, raccolte, guide e internal linking semantico. citeturn2search8turn2search16turn2search17turn15search0turn15search11

Sul piano della localizzazione, il sito mostra segnali di traduzione non pienamente rifinita. Nella versione tedesca compare una voce di menu ibrida, “Geheimnisse del Capo”, che mescola tedesco e italiano; nella versione spagnola compare la stringa “Too bad…” lasciata in inglese; diversi snippet in spagnolo e inglese suonano meno naturali di quanto sarebbe opportuno per pagine pensate per SEO locale. Questo non è un dettaglio cosmetico: nei mercati internazionali, una lingua poco nativa peggiora CTR, fiducia, leggibilità e capacità di presidiare query locali reali. citeturn1view4turn1view5turn23search2turn1view3

### Problemi tecnici, problemi di IA, problemi di contenuto e opportunità

| Area | Valutazione | Impatto |
|---|---|---|
| Problemi tecnici | Age gate in ingresso, verifiche incomplete su `canonical`/`hreflang`/markup, performance da re-testare con dati reali | Medio-alto |
| Problemi di architettura informativa | Navigazioni disallineate per paese, assenza di hub per intent, assenza di modello country-commerce coerente | Alto |
| Problemi di contenuto | Copertura semantica stretta, poco educational, poche pagine “categoria/occasione”, localizzazione da rifinire | Alto |
| Opportunità editoriali | Cocktail hub, guide su amaro/digestivo/aperitivo, pairing, stagionalità, bartender content, Calabria content | Molto alto |
| Opportunità internazionali | Presidio di “Italian amaro”, “Italian herbal liqueur”, “Kräuterlikör”, “amargo italiano”, where to buy | Molto alto |
| Opportunità brand/UX | Rendere il sito più rituale, aspirazionale, visitabile, condivisibile, con percorsi per eventi e esperienze | Molto alto |

Questa sintesi è un’inferenza strategica costruita sui segnali pubblicamente osservabili del sito e sui benchmark concorrenti; per validarla completamente servirebbero crawl sorgente, GSC, GA4 e dati di ranking/keyword proprietari. citeturn1view2turn1view3turn1view4turn1view5turn24search8

## Competitor analysis

### Jägermeister

Jägermeister è il competitor più evoluto nel trasformare un liqueur brand in una piattaforma editoriale e comunitaria. La sua struttura non si limita a *Products*, *Our Story* e *Drinks*; include anche *Shop* ed *Exploration*. Dentro *Exploration* vive Hubertus Circle, una vera infrastruttura di community bartender, con pillars espliciti di community, exchange, education ed experience, scholarship annuale, workshops ed eventi internazionali. Questo non è solo branding: è un motore di contenuti, link earning, relazioni col trade e autorevolezza semantica. citeturn17view2turn17view3

Dal punto di vista SEO, Jägermeister presidia bene tre strati che a Vecchio oggi mancano: il layer heritage/culture, il layer bartender/community e il layer e-commerce/shop. Inoltre il sito global mostra policy e shipping verso vari paesi europei, segnale di un ecosistema più avanzato anche sui percorsi transazionali. Ciò che Vecchio dovrebbe “copiare” non è l’estetica dark del brand, ma la logica per cui ogni asset di brand genera un cluster di contenuti e un use case di ricerca. citeturn17view2turn5search4

### Amaro Montenegro

Montenegro lavora meglio di Vecchio su due piani: **consistenza internazionale** e **cocktail credibility**. La home ufficiale mostra lingue multiple ben oltre il perimetro di Vecchio — IT, EN, ES, FR, DE, ZH — e una struttura di contenuti più ampia, con sezioni quali history, secret formula, flavour, mixology, responsibility e contacts. L’area cocktail non è un semplice archivio di ricette: include ricette attribuite a mixologist, call to action verso la community “The Vero Bartender” e una narrativa che posiziona il prodotto sia after meal sia in reinterpretazioni di cocktail classici. citeturn18view0turn18view1

Per Vecchio, Montenegro è un benchmark diretto molto utile perché dimostra come un amaro possa rimanere fedele alla categoria digestif ma aprirsi in modo credibile alla mixology internazionale. La lezione qui è chiara: non basta avere cocktail pages; serve una **cocktail strategy editoriale**, capace di elevare il prodotto da “ingrediente” a “ingrediente con autorevolezza”. citeturn18view1

### Ramazzotti con focus Germania

Per la Germania, Ramazzotti è il benchmark più importante. Il sito tedesco ha una struttura locale chiara — prodotti, ricette, heritage & storia, contatti, newsletter — e un selettore paese che distingue DE/Germany da IT/Italy, ES/Chile, ES/Argentina, EN/USA e EN/Global. Questo è un segnale di governance internazionale molto più matura e più facilmente scalabile in ottica `hreflang`/multi-market. citeturn19view0turn24search0turn24search9

Soprattutto, Ramazzotti presidia in Germania una larghezza di ricette che Vecchio oggi non ha: amaro, limoncello, rosato, fresco, espresso, prodotti 0.0%, serve stagionali caldi e freddi, dessert topping e variazioni per momenti di consumo diversi. Il sito non si limita a “cocktail”, ma presidia un **universo di usi**. In più c’è Casa Ramazzotti, che trasforma ingredienti, produzione, storia e tasting in contenuto esperienziale. Questo è esattamente il tipo di materiale che, se ben editorializzato, genera SEO, PR, contenuto social e brand love insieme. citeturn19view0turn19view1turn19view2turn10search6

Per Vecchio in Germania, la minaccia non è solo “Ramazzotti ranka meglio”: è che Ramazzotti ha già la grammatica digitale di un marchio beverage moderno. Vecchio ha un posizionamento distintivo forte — Calabria, iced serve, 29 botanicals — ma deve trasformarlo in un sistema di contenuti e percorsi locali comparabile. citeturn19view0turn19view1turn2search18turn7search5

### Averna

Averna, in questo preciso momento, presenta una situazione particolare: il sito ufficiale appare in manutenzione, il che limita molto la sua capacità di essere benchmark UX/SEO attuale e, al tempo stesso, riduce la sua forza digitale immediata. Tuttavia, il brand continua a esprimere una forte identità di tradizione siciliana e storytelling emozionale su asset corporate/di gruppo, e resta semanticamente rilevante nella categoria amaro. citeturn12view0turn3search7

Per Vecchio, questo significa due cose. Primo: Averna è un competitor storico di categoria, ma oggi lascia probabilmente uno spazio digitale che Vecchio potrebbe provare a colonizzare. Secondo: proprio perché Averna è legato a una geografia-fonte molto chiara, la lezione non è ignorarlo ma batterlo su un terreno affine — trasformare Calabria in un vantaggio editoriale e non solo visivo. citeturn12view0turn3search7

### Cosa copiare, evitare o reinterpretare

Da Jägermeister va presa la logica **community + education + culture**. Da Montenegro la logica **mixology autorevole e internazionale**. Da Ramazzotti Germania la logica **copertura occasionale e country governance**. Da Averna va colta l’importanza della geografia identitaria, con l’opportunità di superarlo digitalmente in questa fase. Vecchio dovrebbe invece evitare due errori: l’iper-frammentazione di prodotto senza gerarchia editoriale, e la traduzione letterale senza vera localizzazione. citeturn17view2turn18view1turn19view1turn12view0

## Benchmark aspirazionale

### Hendrick’s, Aperol e Martini come modelli di sito

Hendrick’s è un benchmark aspirazionale soprattutto per il modo in cui organizza il brand attorno a un immaginario editoriale: cocktails “for any occasion”, gamma di gin, rubriche tematiche come *Cabinet of Curiosities* e contenuti stagionali come le spritz collections. Il principio copiabile per Vecchio è che ogni estensione di gamma o rituale può diventare una serie narrativa continuativa, non un semplice lancio prodotto. citeturn14search1turn14search4turn14search16

Aperol è il benchmark più interessante per il binomio **ritualità + distribuzione editoriale del rituale**. Il sito non si limita a dire “questo è il prodotto”: mette in scena recipe, 3-2-1 rule, FAQs, party planner, pairing, blog, news & events, Terrazza Aperol, shop, promo e localizzazione nazionale. In Germania, per esempio, il sito include storia, prodotti, recipe, news & events, blog, Terrazza e shop; nella pagina ricetta globale c’è anche un planning tool per calcolare quanti ingredienti servono in base agli ospiti. Questo è SEO utile perché converte query semplici in esperienze navigabili. citeturn21view0turn21view1turn21view2

Martini è invece il benchmark migliore per **education + esperienzialità + categoria**. Oltre ai prodotti e ai drinks, offre guide come *A Guide to Vermouth* e *A Guide to Aperitivo*, più un’intera infrastruttura di visita e masterclass con Casa Martini, inclusi tour, cocktail experience, vermouth class, food pairing, team building ed eventi corporate/private, il tutto in più lingue. Questo dimostra come un sito beverage possa essere un ecosistema di contenuti, turismo di marca e conversione relazionale. citeturn20view3turn20view4turn14search8

### Cosa può imparare Vecchio Amaro del Capo

Vecchio dovrebbe ispirarsi a questi brand su quattro elementi precisi. Primo: ritualizzare il consumo. Aperol ha il 3-2-1; Vecchio ha il -20 °C, ma oggi non lo trasforma ancora in un sistema di contenuti altrettanto esteso. Secondo: trasformare l’origine territoriale in contenuto visitabile, come Martini e Ramazzotti fanno con Casa Martini e Casa Ramazzotti. Terzo: creare contenuti social-friendly con resa SEO — recipe systems, pairing, party tools, seasonal rounds, bartender stories. Quarto: costruire un “world of brand” che vada oltre homepage, prodotto e ricetta singola. citeturn21view1turn20view3turn19view2turn14search1

Per Vecchio, il terreno più fertile è probabilmente una sintesi: l’**iconic ritual** di Aperol, l’**education di categoria** di Martini, e la **serialità editoriale** di Hendrick’s. Calabria, botanicals, freddo, digestivo, mixology e ready-to-serve sono asset sufficienti per costruire un immaginario molto ricco, purché vengano strutturati in cluster e non lasciati come pagine isolate. citeturn0search8turn22search6turn21view1turn20view4turn14search4

## Keyword map e search intent per mercato

### Metodo e limiti

La keyword map seguente è **strategica e qualitativa**, non basata su volumi proprietari. È stata costruita combinando la terminologia del sito attuale, il linguaggio usato dai competitor e benchmark ufficiali, e i pattern lessicali che emergono dalle versioni locali e dalle SERP pubbliche osservabili. Per validare priorità e cluster con precisione servirebbero Search Console, GA4 e tool come Semrush, Sistrix o Similarweb. citeturn2search0turn2search18turn15search10turn18view0turn19view0turn21view1turn20view4

### Italia

In Italia il brand può legittimamente giocare sia sulla **marca** sia sulla **categoria**, perché il mercato conosce l’amaro come digestivo e come oggetto culturale. Il lessico chiave già presente sul sito — amaro italiano, ricetta calabrese, ghiacciato, cocktail, ready to serve — va espanso verso pairing, occasioni, territorio e guida alla categoria. citeturn2search0turn0search8turn2search12

| Cluster | Query esempio | Intent | Pagina/sezione consigliata | Priorità | Competitor già forti |
|---|---|---|---|---|---|
| Brand | vecchio amaro del capo, amaro del capo | Navigazionale | Home + product hub | Alta | Brand stesso |
| Categoria | amaro italiano, amaro calabrese, digestivo alle erbe | Informazionale/commerciale | Hub “Cos’è l’amaro del Capo” | Alta | Montenegro, Averna, Ramazzotti |
| Rituale | amaro ghiacciato, come servire amaro del capo, amaro a -20 | Informazionale | Hub “Il rituale ghiacciato” | Alta | Nessuno con claim identico |
| Cocktail | cocktail con amaro, negroni con amaro, spritz con amaro | Informazionale | Hub cocktail + recipe index | Alta | Montenegro, Ramazzotti |
| Territorio | Calabria liquori, botaniche di Calabria, ingredienti calabresi | Informazionale | Hub Calabria/ingredienti | Media-alta | Debole presidio competitor |
| Occasioni | digestivo dopo cena, aperitivo con amaro, amaro per regalo | Commerciale | Occasion hubs + gifting | Media | Ramazzotti più ampio |
| Commerciale | dove comprare amaro del capo, store amaro del capo | Transazionale | Dove comprare / store locator / ecommerce bridge | Alta | Vari retailer, brand distribuiti |

### Germania

In Germania la priorità è la vera localizzazione di categoria. Le evidenze pubbliche mostrano un lessico più vicino a “Kräuterlikör”, “Digestif”, “Aperitif”, “Rezepte”, “pur auf Eis”, “Spritz” e “wo kaufen”. Ramazzotti presidia già moltissimo l’area ricette e occasioni; Jägermeister presidia culture/community/bar. Vecchio deve entrare in Germania non come semplice traduzione dell’italiano, ma come **Italian herbal bitter liqueur with a unique iced serve ritual**. citeturn7search5turn10search6turn19view1turn17view2turn23search1

| Cluster | Query esempio | Intent | Pagina/sezione consigliata | Priorità | Competitor già forti |
|---|---|---|---|---|---|
| Categoria | italienischer kräuterlikör, amaro italien, bitterlikör italien | Informazionale/commerciale | Category landing DE | Alta | Ramazzotti, Jägermeister retail presence |
| Rituale | amaro eisgekühlt, digestif auf eis, amaro mit zitrone | Informazionale | Serving ritual DE | Alta | Ramazzotti |
| Cocktail | cocktails mit amaro, spritz mit amaro, kräuterlikör cocktails | Informazionale | Recipe hub DE | Alta | Ramazzotti, Jägermeister |
| Brand | vecchio amaro del capo, capo likör | Navigazionale/commerciale | Brand hub DE | Alta | Brand stesso |
| Commerciale | wo kaufen vecchio amaro del capo, amaro del capo deutschland | Transazionale | Dealer locator DE + retailer pages | Alta | Ramazzotti meglio attrezzato |
| Educational | was ist amaro, unterschied amaro und kräuterlikör | Informazionale | FAQ/guide DE | Media-alta | Opportunità aperta |
| Stagionali | winter aperitif, heiße amaro drinks, sommer aperitif | Informazionale | Seasonal recipe clusters | Media | Ramazzotti molto forte |

### Spagna

In Spagna l’opportunità più promettente è connettere il brand al mondo **aperitivo/cócteles/spritz** più che tentare una replica del contesto italiano del digestivo. Il sito locale già parla di *cócteles* e *amargo italiano*, ma la resa linguistica appare da rifinire; proprio per questo c’è spazio per un lavoro di localizzazione più naturale e orientato alla convivialità. citeturn2search15turn15search10turn23search2

| Cluster | Query esempio | Intent | Pagina/sezione consigliata | Priorità | Competitor già forti |
|---|---|---|---|---|---|
| Categoria | amaro italiano, licor amargo italiano, licor de hierbas italiano | Informazionale/commerciale | Category landing ES | Alta | Retail e contenuti editoriali sparsi |
| Cocktail | cócteles con amaro, spritz italiano, negroni con amaro | Informazionale | Recipe hub ES | Alta | Aperol sul rituale spritz |
| Rituale | digestivo italiano, cómo tomar amaro, amaro con hielo | Informazionale | Serving guide ES | Media-alta | Opportunità aperta |
| Brand | vecchio amaro del capo españa | Navigazionale/commerciale | Brand hub ES | Alta | Brand stesso |
| Territorio | Calabria italia licor, hierbas de Calabria, tradición calabresa | Informazionale | Story/ingredients ES | Media | Più spazio libero |
| Commerciale | dónde comprar amaro del capo, precio amaro del capo | Transazionale | Where to buy ES | Alta | Retailer marketplace |

### Inglese e internazionale

Nel mercato inglese/internazionale la priorità non è solo vendere il brand, ma **spiegare la categoria**. Oggi il sito inglese tende a una dicitura molto generica come “Italian liquor” e lascia sottoutilizzata la definizione “Italian amaro / Italian herbal liqueur”, che invece sarebbe più precisa e SEO-friendly per utenti che non conoscono già il marchio. In parallelo, benchmark come Martini mostrano quanto funzionino guide esplicative su categoria, occasioni e uso in cocktail. citeturn22search2turn22search9turn22search10turn20view4

| Cluster | Query esempio | Intent | Pagina/sezione consigliata | Priorità | Competitor già forti |
|---|---|---|---|---|---|
| Categoria | italian amaro, italian herbal liqueur, what is amaro | Informazionale | Educational hub EN | Alta | Broad category publishers, Montenegro |
| Brand | vecchio amaro del capo, capo amaro | Navigazionale | Brand hub EN | Alta | Brand stesso |
| Cocktail | amaro cocktails, amaro spritz, negroni with amaro | Informazionale | Recipe hub EN | Alta | Montenegro, Martini adjacent |
| Serving | how to drink amaro, serve amaro cold, digestif after dinner | Informazionale | Serving ritual EN | Alta | Opportunity open |
| Commerciale | where to buy vecchio amaro del capo, amaro del capo online | Transazionale | Where to buy EN | Alta | Retailers/search aggregators |
| Education | amaro vs vermouth, digestif vs aperitif, best italian digestifs | Informazionale | Guides/FAQ EN | Media-alta | Martini, aperitivo publishers |
| Gifting | italian liqueur gift, premium amaro gift | Commerciale | Gifting/Riserva EN | Media | Premium spirits retailers |

## Gap analysis e blueprint del nuovo sito

### Gap analysis

Il gap fra sito attuale e competitor è meno evidente sul “prodotto iconico” e molto più evidente su tutti gli strati intorno al prodotto: category education, recipes by occasion, country governance, trade/bartender content, visitability, eventability, e percorsi commerciali coerenti. Vecchio ha una storia distintiva e un rituale fortissimo; gli manca ancora il **sistema** che converta questi asset in domanda organica e in autorevolezza internazionale. citeturn0search8turn22search9turn17view2turn18view1turn19view1turn21view1turn20view3

| Area | Problema o opportunità | Evidenza | Competitor di riferimento | Impatto SEO | Impatto brand | Effort | Priorità |
|---|---|---|---|---|---|---|---|
| International SEO | Navigazioni e portafogli disallineati per lingua/paese | IT vs EN vs DE vs ES molto diversi citeturn1view2turn1view3turn1view4turn1view5 | Ramazzotti, Montenegro | Alto | Alto | Medio | Alta |
| Localizzazione | Traduzioni/label non pienamente native | “Geheimnisse del Capo”, “Too bad…” in ES citeturn1view4turn1view5 | Aperol, Martini | Medio-alto | Alto | Medio | Alta |
| Categoria | Mancano guide forti su amaro/herbal liqueur/digestif | Sito focalizzato su brand e ricette singole citeturn22search9turn22search10 | Martini, Montenegro | Alto | Alto | Medio | Alta |
| Cocktail | Esistono ricette ma manca hub per occasioni/stagioni/livello | Ricette isolate a snippet/URL dedicati citeturn2search8turn2search16turn15search11 | Ramazzotti, Aperol | Alto | Medio-alto | Medio | Alta |
| Commerciale | Percorsi buy differenziati e incompleti | Store IT, locator DE, assenza chiara EN/ES citeturn1view2turn15search3 | Jägermeister, Ramazzotti | Alto | Medio | Medio | Alta |
| Territorio | Calabria presente ma non scalata a ecosistema editoriale | 29 ingredienti e Calabria, ma pochi hub visibili citeturn0search8turn22search9 | Ramazzotti Casa, Martini Casa | Medio-alto | Molto alto | Medio-alto | Alta |
| Bartender/trade | Nessuna community o area B2B/bar visibile | Nessun equivalente di Hubertus Circle/Vero Bartender citeturn17view2turn18view1 | Jägermeister, Montenegro | Medio | Alto | Medio-alto | Media-alta |
| Stagionalità | Poco presidio di cluster estate/inverno/feste | Ramazzotti ha molte ricette stagionali citeturn19view1 | Ramazzotti, Aperol | Medio-alto | Medio | Medio | Media-alta |
| AI/LLM visibility | Contenuto poco entity-rich e poco guide-based | Necessità di strutturare meglio entità e markup citeturn24search25turn24search1turn24search4 | Martini, Aperol | Medio | Medio | Medio | Media |

### Insight per la costruzione del nuovo sito

Il nuovo sito dovrebbe nascere con una logica di **hub-and-spoke**. La homepage locale deve introdurre il brand e i percorsi principali; subito sotto devono esistere hub permanenti per Prodotto, Cocktails, How to drink, Calabria & ingredients, Occasions, Where to buy, Journal/Magazine, e — almeno in una versione leggera — Bartender & venues. Questo evita che il sito sia dipendente da poche hero pages e permette di crescere per cluster. citeturn24search9turn24search0turn24search7

La proposta migliore per la gestione country/language è: `it-it`, `de-de`, `es-es`, e `en` come versione globale con `x-default`. Se il budget o il CMS non consentono un passaggio immediato a language-country code, una struttura `/it/`, `/de/`, `/es/`, `/en/` può funzionare, ma le pagine commerciali e distributive dovrebbero comunque poter differenziare i mercati. Google raccomanda di usare versioni localizzate chiaramente distinguibili e `hreflang` per aiutare il motore a servire la variante più adatta. citeturn24search0turn24search9

Dal punto di vista dei template, servono almeno quattro template forti. Il **Product template** deve includere descrizione completa, serving ritual, ingredienti/botanicals chiave, FAQ, pairing, award/social proof dove consentito, e link a cocktail correlati. Il **Recipe template** deve includere ingredienti, passaggi, tempo, livello di difficoltà, occasioni, glassware, garnish, related recipes e markup recipe. Il **Guide template** deve servire query educational. Il **Where to buy template** deve collegare distribuzione, store locator, retailer e mercati. Google indica in modo esplicito che markup Product, Recipe e Breadcrumb possono migliorare comprensione e arricchimento nei risultati di ricerca. citeturn24search1turn24search4turn24search7turn24search25

### Sitemap consigliata

Di seguito una sitemap concreta, pensata per il nuovo sito.

#### Pagine corporate e brand
- `/it-it/`, `/de-de/`, `/es-es/`, `/en/`
- `/brand/`
- `/brand/storia/`
- `/brand/calabria/`
- `/brand/ingredienti/`
- `/brand/come-si-serve/`
- `/brand/perche-a-20/`
- `/brand/premi-e-riconoscimenti/`
- `/brand/contatti/`
- `/brand/accessibilita/`

#### Pagine prodotto
- `/products/vecchio-amaro-del-capo/`
- `/products/riserva-del-centenario/`
- `/products/red-hot-edition/`
- `/products/ready-to-serve/`
- `/products/ready-to-serve/capo-tonic/`
- `/products/ready-to-serve/capo-arrabbiato/`

#### Pagine cocktail
- `/cocktails/`
- `/cocktails/by-occasion/aperitivo/`
- `/cocktails/by-occasion/after-dinner/`
- `/cocktails/by-occasion/party/`
- `/cocktails/by-style/spritz/`
- `/cocktails/by-style/sour/`
- `/cocktails/by-style/negroni-twist/`
- `/cocktails/by-season/summer/`
- `/cocktails/by-season/winter/`
- `/cocktails/negroni-del-capo/`
- `/cocktails/capo-arrabbiato-spritz/`
- `/cocktails/capo-sour/`

#### Pagine editoriali
- `/journal/`
- `/journal/what-is-amaro/`
- `/journal/italian-herbal-liqueur-guide/`
- `/journal/amaro-vs-vermouth/`
- `/journal/digestif-vs-aperitif/`
- `/journal/how-to-drink-amaro/`
- `/journal/food-pairing-with-amaro/`
- `/journal/calabrian-botanicals/`
- `/journal/gift-guide-premium-amaro/`

#### Pagine commerciali
- `/where-to-buy/`
- `/where-to-buy/italy/`
- `/where-to-buy/germany/`
- `/where-to-buy/spain/`
- `/where-to-buy/global/`
- `/retailers/`
- `/venues/`
- `/events/`

#### Pagine stagionali e campagne
- `/summer-aperitivo/`
- `/winter-digestif/`
- `/holiday-gifting/`
- `/festival-season/`
- `/world-amaro-day/` oppure editorial equivalente

#### Pagine bartender e trade
- `/bartenders/`
- `/bartenders/signature-serves/`
- `/bartenders/resources/`
- `/bartenders/community/`
- `/venues/featured-bars/`

## Piano annuale e raccomandazioni per paese

### Roadmap SEO e content per dodici mesi

La roadmap migliore è trimestrale, con una cadenza editoriale mensile costante all’interno di ogni trimestre.

| Fase | Attività principali | Output atteso | Effort | Impatto | KPI |
|---|---|---|---|---|---|
| Q1 | Audit tecnico completo, design IA, mappatura URL, piano `hreflang`, nuovi template product/recipe/guide, revisione localizzazione DE/ES/EN | Specifiche SEO per nuovo sito + primi template pronti | Alto | Molto alto | Pagine valide, errors, CWV baseline, copertura indicizzazione |
| Q2 | Lancio nuovo sito o nuova struttura, publication dei core hub, migrazioni/redirect, Product/Recipe/Breadcrumb markup, ottimizzazione immagini | Nuovo perimetro indexable e cluster core online | Alto | Molto alto | Ranking brand/non-brand, CTR, pagine indicizzate, rich results |
| Q3 | Espansione editoriale su cocktail, occasioni, Calabria, pairing; landing “where to buy” per mercati; digital PR estiva | Crescita copertura semantica e discovery top-funnel | Medio-alto | Alto | Click non-brand, share of voice cluster, referral/link mentions |
| Q4 | Stagionalità autunno-inverno, gifting, digestif culture, hot serves per DE, refresh contenuti top pages, analisi AI visibility | Consolidamento e aumento efficienza | Medio | Alto | CVR assisted, branded demand, featured snippets, AI citations proxy |

All’interno di questa roadmap, le attività mensili dovrebbero seguire un ritmo fisso. Ogni mese: un contenuto educational, due/tre cocktail pages o refresh, un contenuto stagionale, aggiornamento immagini/metadati/internal linking, e una piccola attivazione PR o co-marketing con bartender, venue o eventi. Questo approccio è più sostenibile e cumulativo della pubblicazione a blocchi casuali. citeturn17view2turn18view1turn19view1turn21view1turn20view3

### Raccomandazioni per Italia

In Italia la priorità SEO è portare Vecchio da brand noto a **categoria autorevole**. Le pagine da creare subito sono: “cos’è un amaro”, “perché si beve ghiacciato”, “amaro calabrese”, “cocktail con amaro”, “abbinamenti”, “dove comprare”, “regalo premium” e “ready to serve”. Il posizionamento consigliato è: *l’amaro italiano di Calabria dal rituale ghiacciato inconfondibile, capace di vivere sia come digestivo sia in mixology*. Rispetto a Montenegro, Averna e Ramazzotti, Vecchio ha il vantaggio differenziante più nitido sul rito di servizio; deve sfruttarlo molto di più. citeturn2search0turn0search8turn22search6turn12view0turn18view1turn19view0

### Raccomandazioni per Germania

In Germania serve prima di tutto localizzare bene il lessico. Le query e le pagine dovrebbero parlare fluentemente di *Kräuterlikör*, *Digestif*, *Aperitif*, *Rezepte*, *pur auf Eis*, *Spritz*, *wo kaufen*. I competitor principali sono Ramazzotti e Jägermeister, ma con ruoli diversi: Ramazzotti domina l’uso/serves e Jägermeister domina community/culture/trade. La barriera più grande per Vecchio non è di awareness pura, ma di linguaggio e ampiezza dell’offerta editoriale locale. Le pagine consigliate sono: category page DE, how to drink DE, recipe hub DE, seasonal DE, ingredients/Calabria DE, where to buy DE. citeturn7search5turn19view0turn19view1turn17view2turn23search1

### Raccomandazioni per Spagna

In Spagna il potenziale maggiore è il mondo **aperitivo/cócteles/spritz**. La localizzazione deve essere meno letterale e più vicina all’uso reale del mercato: il brand dovrebbe valorizzare convivialità, freschezza, momento aperitivo e twist italiani. Le pagine da creare prima sono: *qué es el amaro italiano*, *cómo tomarlo*, *cócteles con amaro*, *spritz con amaro*, *aperitivo italiano*, *dónde comprar*. Qui l’obiettivo è rendere il prodotto culturalmente comprensibile e desiderabile, non solo “tradotto”. citeturn2search15turn15search10turn23search2turn21view1

### Raccomandazioni per inglese e internazionale

Per l’inglese/internazionale il posizionamento dovrebbe essere esplicitamente: **Italian amaro from Calabria** e **Italian herbal liqueur**. Oggi la formula “Italian liquor” è troppo generica. Le priorità sono educational pages di categoria, serving ritual pages, cocktail pages, FAQ comparative e pagine commerciali / where to buy. Le pagine chiave sono: *what is amaro*, *what is Italian herbal liqueur*, *how to drink amaro*, *amaro cocktails*, *digestif after dinner*, *amaro vs vermouth*, *where to buy*. citeturn22search2turn22search9turn22search10turn20view4

### Quick wins da fare subito

1. Uniformare la navigazione principale fra IT, DE, ES, EN. citeturn1view2turn1view3turn1view4turn1view5  
2. Correggere tutte le stringhe di localizzazione non native o miste. citeturn1view4turn1view5turn23search2  
3. Creare una pagina “What is Amaro / Cos’è l’amaro / Was ist Amaro / Qué es el amaro”. citeturn20view4turn14search8  
4. Creare un hub “Come si beve / How to drink / Wie trinkt man / Cómo se toma”. citeturn2search0turn10search6  
5. Rendere stabile e visibile il percorso “Where to buy” in tutti i mercati. citeturn1view2turn15search3  
6. Arricchire i template ricetta con cluster by occasion, season, difficulty e markup recipe. citeturn24search4turn22search10  
7. Trasformare Calabria e botanicals in un hub editoriale vero. citeturn0search8turn22search9  
8. Introdurre Product, Recipe e Breadcrumb structured data lato nuovo sito. citeturn24search1turn24search4turn24search7  
9. Preparare una governance `hreflang` chiara, con `x-default` per l’inglese globale. citeturn24search0turn24search9  
10. Misurare subito CWV e indicizzazione con Search Console/PageSpeed, non con checker generici. citeturn24search8turn24search2turn24search17

### Priorità strategiche per il brief al team che costruirà il nuovo sito

Il brief al team web non dovrebbe partire da “rifacciamo il look”, ma da queste priorità: una singola architettura internazionale coerente; template SEO-first ma brand-led; localizzazione nativa; hub editoriali permanenti; percorsi commerciali per mercato; markup; performance; governance editoriale continuativa. In altre parole, il nuovo sito deve nascere come **prodotto editoriale internazionale**, non come brochure site. citeturn24search9turn24search0turn24search25

### Dati verificati, ipotesi e ciò che richiede dati proprietari

Sono **verificati pubblicamente**: la struttura per cartelle lingua, i redirect verso le pagine di age gate, la composizione dei menu per mercato, la presenza di store IT e dealer locator DE, molte pagine prodotto e cocktail, i segnali di localizzazione incompleta, e le strutture editoriali visibili dei competitor e benchmark. citeturn1view2turn1view3turn1view4turn1view5turn15search3turn17view2turn18view1turn19view1turn21view1turn20view3

Sono invece **ipotesi ragionate**: il peso SEO preciso dell’age gate sull’indicizzazione/canonicalizzazione, la qualità reale del markup head-side, il livello attuale di `hreflang`, e la severità delle criticità Core Web Vitals. Per queste aree servono crawl completi, accesso al sorgente, Search Console, GA4 e test PageSpeed/CrUX. citeturn24search8turn24search2turn24search17

Servono **dati proprietari** per: verificare le query già performanti per paese, quantificare il gap di ranking con competitor, misurare CTR e conversione per template, stimare la domanda reale per cluster, e prioritizzare le keyword con base numerica. Gli strumenti chiave sarebbero Search Console, Analytics, Semrush, Sistrix, Similarweb e, idealmente, dati di sell-out/distribuzione per costruire i market pages commerciali. citeturn24search8

### Lista sintetica finale

#### Dieci insight principali

1. Il sito attuale ha asset di brand forti ma una copertura SEO troppo stretta. citeturn0search8turn22search9  
2. L’age gate introduce complessità di crawling e di esperienza in ingresso. citeturn1view2turn22search4  
3. L’architettura è incoerente fra IT, EN, DE ed ES. citeturn1view2turn1view3turn1view4turn1view5  
4. Germania è il mercato più esigente dal punto di vista competitivo digitale. citeturn19view0turn19view1turn17view2  
5. La localizzazione attuale va rifinita in modo sostanziale. citeturn1view4turn1view5turn23search2  
6. Calabria e il rituale del -20 °C sono asset SEO/editoriali enormi e poco sfruttati. citeturn0search8turn2search0  
7. Le ricette esistono, ma non sono ancora un vero cluster editoriale. citeturn2search8turn2search16turn15search11  
8. Jägermeister, Montenegro e Ramazzotti dimostrano che il contenuto beverage vince quando unisce prodotto, cultura, community e occasioni di consumo. citeturn17view2turn18view1turn19view1  
9. Aperol e Martini mostrano come ritualità ed education possano diventare SEO scalabile. citeturn21view1turn20view4  
10. Il nuovo sito deve essere progettato per cluster, non per pagine isolate. citeturn24search25turn24search7  

#### Dieci pagine che il nuovo sito dovrebbe assolutamente avere

1. Cos’è Vecchio Amaro del Capo  
2. Cos’è un amaro italiano  
3. Perché si beve a -20 °C  
4. Calabria, territorio e botanicals  
5. Come bere l’amaro del Capo  
6. Cocktails with Amaro del Capo  
7. Where to buy / Dove comprare / Wo kaufen / Dónde comprar  
8. Amaro del Capo per aperitivo e after dinner  
9. Food pairing con amaro  
10. FAQ: amaro vs vermouth / digestif vs aperitif  

Questa lista deriva direttamente dai gap osservati sul sito attuale e dagli spazi presidiati dai benchmark. citeturn22search9turn22search10turn19view1turn21view1turn20view4

#### Dieci attività SEO e content da fare nei primi novanta giorni

1. Crawl tecnico e mappatura redirect/url.  
2. Definizione architettura internazionale e `hreflang`.  
3. Revisione completa localizzazione DE/ES/EN.  
4. Disegno template product/recipe/guide.  
5. Lancio hub “What is Amaro”.  
6. Lancio hub “How to drink it”.  
7. Creazione pagine where-to-buy per i quattro mercati.  
8. Revisione internal linking di tutte le recipes.  
9. Implementazione markup Product/Recipe/Breadcrumb.  
10. Setup KPI dashboard GSC/GA4/CWV.  

Queste attività sono le più urgenti perché sbloccano sia fondazioni tecniche sia capacità editoriale futura. citeturn24search0turn24search1turn24search4turn24search7turn24search8

#### Dieci attività da pianificare nel resto dell’anno

1. Cluster cocktail stagionali estate/inverno.  
2. Cluster aperitivo/after dinner per paese.  
3. Serie editoriali su botanicals e Calabria.  
4. Food pairing hub.  
5. Gifting e premium/Riserva hub.  
6. Bartender signatures o showcase community.  
7. Venue/event pages e partnership content.  
8. Ottimizzazione immagini e media library.  
9. Digital PR con focus su aperitivo, Calabria e mixology.  
10. Refresh trimestrale delle top pages con dati di GSC.  

Queste attività servono a far crescere il sito in modo cumulativo, rendendo più probabile sia l’aumento delle query non-brand sia la visibilità nei motori e nei sistemi generativi che privilegiano contenuti ben strutturati, contestualizzati e aggiornati. La parte finale è in parte inferenziale, ma coerente con le raccomandazioni di Google su contenuti strutturati, versioni localizzate e segnali di qualità della pagina. citeturn24search25turn24search0turn24search17
