# Costruzioni Molinari

Landing page italiana statica. Aprire `index.html` nel browser oppure caricarlo
su un qualsiasi hosting statico. Nessuna installazione, build o server richiesto.

## Prima della pubblicazione

1. In `index.html`, impostare `const contactEmail = '';` con l'indirizzo reale
   dell'impresa. Il modulo resta disabilitato finche' il valore e' vuoto.
2. Completare il footer con i dati societari richiesti e l'area servita.
3. Sostituire gli esempi con progetti reali e fotografie autorizzate, se disponibili.
   Non rimuovere l'avvertenza sulle immagini illustrative senza averle sostituite.

## Contatti

Il modulo valida i campi e prepara un collegamento `mailto:` con oggetto e
messaggio. Il visitatore deve avere un'applicazione di posta configurata e
confermare personalmente l'invio. Non c'e' un servizio di invio, nessuna richiesta
viene salvata dal sito e non viene mostrata una falsa conferma di consegna.
Un invio automatico richiederebbe un servizio esterno o un backend.

## Risorse esterne

Tailwind CSS via CDN, Google Fonts (Manrope e Barlow Condensed), Lucide via CDN
e immagini Unsplash richiedono internet. Il sito non e' quindi una versione
offline. Prima di pubblicare, valutare le informative applicabili alle risorse
esterne. Non sono presenti analytics o cookie applicativi.

Il CDN browser di Tailwind e' scelto per rispettare il vincolo zero build;
richiede JavaScript ed e' meno ottimizzato di un foglio CSS precompilato.