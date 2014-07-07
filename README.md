AnnOtaria-Standards
===================


NON CI SONO TUTTE LE TIPOLOGIE: ne stiamo discutendo, a breve cercheremo di ultimarle.

I prefix non sono presenti in tutti i file. non volevo fare copia incolla.

Linea generale per le annotazioni:

1. sono di tipo "Annotation": [] a oa:Annotation
2. hanno l'attributo type: [] rdf:type "denotesPerson"
3. hanno una label esterna sarà la traduzione italiana del tipo, nel modo piu semplice possibile: "Persona"
4. parametro annotatedAT : "2014-07-07T13:07"
5. ha un body di tipo rdf:Statement
   1. ha un subject relativo all'url del documento: + "#" +"id_container" +"start"+"end"
   2. ha un predicate relativo al tipo di annotazione sopra citato
   3. ha un object : uri dell'input, e se nn disponibile, valore dell'input
   4. ha una label: valore dell'input
6. ha un target che puo essere una risorsa specifica (frammento) oppure un documento 


* denotesDisease e hasSubject sono le uniche con un vincolo al prefisso delle proprie risorse 
  Non ci sono modi per distinguerle, ed in ogni caso le specifiche suggeriscono di prendere le informazioni relative da 2     siti dedicati, non lasciando la libertà di usare risorse a piacere.


tutti gli esempi relativi ad ogni tipo di annotazione, vengono continuamente aggiornati. 
Verranno bloccati gli aggiornamenti il 13/07/2014

Vi prego di seguire questi standards: non è una competizione, dobbiamo solo fare bene e rimanere in linea tra di noi



per qualsiasi richiesta di variazione contattatemi oppure fate una pull request.



