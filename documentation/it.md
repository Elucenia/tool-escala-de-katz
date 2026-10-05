<!-- ELUCENIA technical documentation · escala-de-katz · it · no clinical/professional/rights approval -->

# Indice di Katz (attività di base della vita quotidiana)

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/escala-de-katz)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Bagno (indipendente: si lava autonomamente o necessita aiuto solo per una parte del corpo)

`banho`

- `0` — Dipendente
- `1` — Indipendente

### Vestirsi (indipendente: prende gli indumenti e si veste senza aiuto, salvo allacciare le scarpe)

`vestir`

- `0` — Dipendente
- `1` — Indipendente

### Uso del bagno (indipendente: va in bagno, si pulisce e sistema gli indumenti senza aiuto)

`higiene`

- `0` — Dipendente
- `1` — Indipendente

### Trasferimento (indipendente: si corica e si alza dal letto e dalla sedia senza aiuto)

`transf`

- `0` — Dipendente
- `1` — Indipendente

### Continenza (indipendente: completo controllo di urina e feci)

`contin`

- `0` — Dipendente
- `1` — Indipendente

### Alimentazione (indipendente: porta il cibo dal piatto alla bocca senza aiuto)

`alim`

- `0` — Dipendente
- `1` — Indipendente

## Edizione del metodo

Katz ADL binario: 6 attività, totale 0–6; modulo HIGN 2019, lievemente adattato da Katz et al. 1970; escluse le categorie A–G del 1963

## Formula documentata

1 punto per attività autonoma (senza supervisione, guida o aiuto altrui): bagno, vestirsi, servizi, trasferimento, continenza, alimentazione. Totale 0–6.

## Limiti e popolazione

Registrare la versione dell’indice e le definizioni di indipendenza in ogni attività. L’adattamento brasiliano del 2008 è stato studiato per equivalenza culturale e affidabilità; ciò non certifica questa implementazione binaria né le sue nuove traduzioni. Il totale locale 0–6 non è la classificazione storica A–G. La somma binaria di 6 attività è stata verificata rispetto al modulo HIGN del 2019, dichiarato lievemente adattato da Katz et al. 1970. Questa fonte non è la classificazione A–G del 1963 e non certifica l’adattamento brasiliano del 2008 né le attuali traduzioni redatte dagli autori. Le eccezioni all’indipendenza e lo scopo di valutare le attività di base nelle persone anziane devono seguire il modulo corrispondente.

## Riferimenti

- [Katz S et al. Studies of illness in the aged. The index of ADL: a standardized measure of biological and psychosocial function. JAMA, 1963.](https://doi.org/10.1001/jama.1963.03060120024016)

- [Lino VTS et al. Adaptação transcultural da Escala de Independência em Atividades da Vida Diária (Escala de Katz). Cad Saude Publica, 2008.](https://doi.org/10.1590/S0102-311X2008000100010)

- [McCabe D. Katz Index of Independence in Activities of Daily Living. HIGN/NYU, Issue 2, revised 2019; slightly adapted from Katz et al. 1970.](https://hign.org/sites/default/files/2020-06/Try_This_General_Assessment_2.pdf)

## Riprodurre i test tecnici

Esegua node test.cjs nella cartella principale di questo repository per ripetere i casi sintetici registrati. Gli input, i risultati attesi e le tolleranze originali sono conservati. I test tecnici non costituiscono validazione clinica.

```sh
node test.cjs
```

tool.json contiene le fonti, l’edizione e l’ambito della revisione. examples.json conserva gli input e i risultati attesi dei casi sintetici; results.json registra i risultati ottenuti.

[Scheda e riferimenti](../tool.json) · [Codice JavaScript](../calculator.js) · [Casi di riferimento](../examples.json) · [results.json](../results.json)

## Revisione e condizioni d’uso

Non è stata effettuata una revisione clinica indipendente.

Questa interfaccia è una traduzione realizzata dagli autori, non un’edizione ufficiale o certificata. Non sono state eseguite la revisione clinica indipendente, la revisione linguistica professionale né la verifica delle autorizzazioni relative ai diritti sugli strumenti.

Risultato della formula o classificazione. Interpretazione, condotta e applicabilità dipendono dalla valutazione professionale e dalla fonte selezionata.

## Licenza e attribuzione

Apache-2.0 si applica solo al codice di ELUCENIA. I diritti su strumenti, pubblicazioni, traduzioni e dati restano ai rispettivi titolari. Conservi LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
