# Interazioni: alert, prompt, confirm

## Alert

L'alert è una finestra di dialogo che mostra un messaggio e un pulsante "OK". È utile per informare l'utente di qualcosa di importante.

```javascript
// Visualizzare un messaggio di avviso
alert("Questo è un messaggio di avviso!");
```

## Prompt

Il prompt è una finestra di dialogo che chiede all'utente di inserire un valore. È utile per ottenere input dall'utente.

```javascript
// Chiedere all'utente di inserire il proprio nome
var nome = prompt("Inserisci il tuo nome:");
console.log("Ciao, " + nome + "!");
```

## Confirm

Il confirm è una finestra di dialogo che chiede all'utente di confermare o annullare un'azione. È utile per ottenere la conferma dell'utente prima di eseguire un'azione.

```javascript

// Chiedere all'utente di confermare un'azione
var conferma = confirm("Sei sicuro di voler procedere?");
if (conferma) {
  console.log("Azione confermata!");
} else {
  console.log("Azione annullata!");
}
```

### Conclusioni

Le interazioni con l'utente sono importanti per creare siti web interattivi e coinvolgenti. Le finestre di dialogo come alert, prompt e confirm sono utili per comunicare con l'utente e ottenere input da esso. Tuttavia, è importante utilizzare queste interazioni con parsimonia e considerare l'usabilità e l'accessibilità per garantire un'esperienza utente positiva.

#### By [Maurizio Tolomeo](https://github.com/moris88)

[HOMEPAGE](https://moris88.github.io/formazione-javascript/) | [LEZIONE SUCCESSIVA](https://moris88.github.io/formazione-javascript/lezioni/lezione7)
