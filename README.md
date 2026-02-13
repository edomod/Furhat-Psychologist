# Assistente Psicologico Virtuale

## Progetto di laurea
Questo repository contiene il mio progetto di laurea, realizzato con la prof.ssa Rita Francese e il mio collega di studi Mattia Guariglia. Il progetto esplora l'uso di un robot sociale per supportare conversazioni psicologiche simulate, con un focus su empatia, qualita della comunicazione e valutazione dell'esperienza utente.

## Descrizione
Sistema di interazione basato su intelligenza artificiale che simula un colloquio psicologico utilizzando il modello linguistico GPT-3 di OpenAI. L'assistente virtuale, Maurizio, e progettato per condurre conversazioni empatiche e supportive in italiano, con comportamenti multimodali del robot (espressioni facciali e gesticolazione) per rendere l'interazione piu naturale.

## Caratteristiche
- Interazione naturale in lingua italiana
- Conversazioni personalizzate e adattive
- Registrazione automatica dei colloqui
- Supporto per espressioni facciali e gesticolazione

## Requisiti tecnici
- Chiave API OpenAI (https://openai.com/api/)
- Connessione internet stabile
- Sistema operativo compatibile con SDK Furhat

## Limitazioni
- Massimo 2 utenti simultanei
- Necessaria una distanza ottimale di 0.5-1.5 metri dal robot
- Ambiente con rumore di fondo limitato

## Note sulla privacy
Tutte le conversazioni vengono registrate in formato JSON per scopi di ricerca e miglioramento del servizio. I dati vengono trattati nel rispetto della normativa sulla privacy vigente.

## Il mio contributo
Mi sono occupato maggiormente della parte di analisi e test: ho fatto provare il robot a 20 persone di differenti fasce di eta (18-80 anni), raccogliendo pareri attraverso moduli Google e conducendo studi sui dati raccolti, tra cui la likeability del sistema, uno score di valutazione, l'andamento delle interazioni e il cambiamento di opinione pre e post test.

## Contesto e motivazione
La salute mentale e una emergenza globale. Oltre 970 milioni di persone convivono con disturbi mentali e, in Italia, circa il 28% della popolazione riporta problemi psicologici. Questi numeri evidenziano limiti strutturali nei sistemi sanitari: carenza di personale specializzato, tempi di attesa lunghi e difficolta nel monitoraggio continuo dei pazienti. Da qui nasce la domanda di ricerca: e possibile usare un robot sociale come strumento di supporto per la salute mentale?

## Obiettivi della ricerca
- Sviluppare un sistema di dialogo capace di conversare in modo naturale con i pazienti.
- Valutare l'accettabilita di un robot in un contesto psicologico.
- Raccogliere dati strutturati utili per il lavoro dei clinici.

## Metodologia
Il sistema e stato implementato su Furhat, un robot sociale con volto proiettato, integrato con il modello linguistico GPT-3 tramite un prompt che definisce una personalita empatica e non giudicante. Il prompt guida l'AI a esplorare interessi ed esperienze dell'utente, evitare argomenti sensibili, adattarsi dinamicamente alle risposte e approfondire i temi rilevanti. Le conversazioni sono fluide, in italiano, non ripetitive e registrate automaticamente per analisi successive.

## Valutazione sperimentale
Il sistema e stato testato con 19 partecipanti (18-70 anni) con diversi livelli di familiarita tecnologica. Ogni partecipante ha compilato questionari pre e post interazione con Furhat, usando scale validate per misurare usabilita, percezione del robot e soddisfazione.

## Risultati principali
- Miglioramento significativo dell'atteggiamento pre-post interazione: da 3.58 a 4.11 (p = 0.015).
- Scala Goodspeed: percezione di intelligenza 4.29/5 e simpatia 4.21/5.
- System Usability Scale: 54.6, con presenza di central tendency bias (scelte neutre frequenti).
- Net Promoter Score: +36.84 (47% promotori, 10% detrattori).

## Conclusioni e sviluppi futuri
I risultati indicano che una singola interazione con un robot sociale puo migliorare in modo significativo l'atteggiamento verso questa tecnologia, rendendola promettente per il supporto alla salute mentale. Gli sviluppi futuri includono test con robot piu umanoidi (Pepper, NAO) e integrazione di analisi automatica delle conversazioni per supportare il lavoro clinico.
