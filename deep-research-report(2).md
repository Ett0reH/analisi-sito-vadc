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