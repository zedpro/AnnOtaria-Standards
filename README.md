AnnOtaria-Standards
===================

Questi file di esempio, sono stati creati totalmente a nostra discrezione. Qualsiasi richiesta di aggiornamento e/o chiarimento è ben voluta. Gia abbiamo notato che ci sono gruppi che leggono i nostri standard proposti ma poi non li seguono. Complimenti a queste persone che fanno di testa propria, farete molta strada. Ricordo che il fuseki è in comune.
(sfogo personale, sorry).


I prefix non sono presenti in tutti i file.
RIPORTO SOLTANTO I 2 PREFIX PIU IMPORTANTI.

@prefix aop:   <http://vitali.web.cs.unibo.it/AnnOtaria/person/> . prefisso per le persone di annotaria.
@prefix ao:    <http://vitali.web.cs.unibo.it/AnnOtaria/> . prefisso generale di annotaria

NON SONO RISORSE FISICHE: stiamo parlando di semantic web. 

i prefissi conosciuti possono essere reperiti da questo sito: 
http://prefix.cc/




Linea generale per le annotazioni:

1. sono di tipo "Annotation": [] a oa:Annotation
2. hanno l'attributo type: [] ao:type "denotesPerson" NEW: è stato aggiunto di proposito, usare la label per il tipo è   totalmente sbagliato (almeno personalmente), ed in ogni caso la proposta viene direttamente dal primo gruppo che è riuscito a consegnare. Notare che negli esempi delle specifiche, il campo "type" esiste solo nei json ma nel formato turtle non c'è un campo standard per differenziare i tipi di annotazioni.
3. hanno una label esterna sarà la traduzione italiana del tipo, nel modo piu semplice possibile: "Persona"
4. parametro annotatedAt : "2014-07-15T23:53:51+02:00" <<-- news (added timezone, ma se lasciate come negli esempi .ttl non    ci sono problemi di compatibilità)
5. ha un body di tipo rdf:Statement
   1. ha un subject ao:NOMDE-DOCUMENTO_ver1 : + "#" +"id_container" +"start"+"end"
   2. ha un predicate relativo al tipo di annotazione sopra citato
   3. ha un object : stringa o istanza(Persone, Luoghi, Malattie etc)
   4. ha una label: valore dell'input (nome della persona, nome del luogo etc..)
6. ha un target che puo essere una risorsa specifica (frammento) oppure un documento 




tutti gli esempi relativi ad ogni tipo di annotazione, vengono continuamente aggiornati. 

Vi prego di seguire questi standards: non è una competizione, dobbiamo solo fare bene e rimanere in linea tra di noi

per qualsiasi richiesta di variazione contattatemi oppure fate una pull request.



