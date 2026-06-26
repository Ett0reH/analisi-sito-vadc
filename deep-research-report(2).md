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
