# Hub Sbranding su GitHub Pages

Nella cartella ci sono due file che devono stare sempre insieme:

- **index.html** è l'hub (le cinque tab, il calendario, la dashboard)
- **data.json** contiene tutti i contenuti: strategia, rubriche, post, idee e la fotografia degli insight Instagram al 30 ottobre 2026

## Metterlo online (una volta sola, 10 minuti)

1. Su github.com crea un nuovo repository, per esempio `hub-sbranding`. Deve essere **Public** (con l'account gratuito GitHub Pages funziona solo sui repository pubblici).
2. Nel repository clicca "Add file", poi "Upload files" e trascina `index.html` e `data.json`. Conferma con "Commit changes".
3. Vai su Settings, poi Pages. In "Branch" scegli `main` e la cartella `/ (root)`, poi Save.
4. Dopo un paio di minuti l'hub è su `https://TUOUSERNAME.github.io/hub-sbranding/`. Questo è il link da mandare.

## Dare al collaboratore il permesso di salvare

1. Nel repository vai su Settings, Collaborators, Add people e invita il suo account GitHub.
2. Lui (e anche tu) crea un token: avatar in alto a destra, Settings, Developer settings, Personal access tokens, Fine-grained tokens, Generate new token. In "Repository access" scegli solo `hub-sbranding`, in "Permissions" imposta **Contents** su **Read and write**. Copia il token.
3. Nell'hub clicca "Collega GitHub" e incolla il token. Resta salvato solo in quel browser.

Da quel momento "Salva" scrive direttamente su `data.json` e chiunque apra il link vede le modifiche. Ogni salvataggio resta nella cronologia del repository, quindi puoi sempre tornare a una versione precedente.

Se due persone salvano a pochi secondi di distanza, la seconda riceve un avviso e il browser scarica una copia delle sue modifiche, così non si perde niente.

## Cosa cambia rispetto alla versione su Claude

- I bottoni "Ottimizza con Claude" e le proposte automatiche non ci sono: funzionano solo dentro Claude.
- I dati Instagram sono una fotografia. Per aggiornarli chiedimelo in chat e ti preparo un nuovo `data.json`.
- Le modifiche fatte qui e quelle fatte nell'artifact su Claude non si parlano: conviene scegliere una delle due come versione di lavoro.

## Password e privacy

Chi apre il link vede prima una pagina che chiede la password: **Sbranding2026**. Mandala sempre separata dal link (per esempio il link via mail e la password su WhatsApp).

La password non è un semplice cancello: `data.json` è cifrato con quella password, quindi anche chi apre il file direttamente nel repository pubblico vede solo testo illeggibile. Ogni salvataggio dall'hub resta cifrato.

Una volta inserita, la password resta valida finché la scheda del browser è aperta.

Per cambiare password serve rigenerare `data.json`: chiedimelo in chat. Se la cambi, chi ha ancora quella vecchia non entra più.
