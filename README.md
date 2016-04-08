
# svg2lines
Questo tool permette la conversione di SVG in un formato che esprime ciascun elemento del disegno utilizzando esclusivamente linee.

## Come funziona
- Effettuare il drag and drop nell'area disponibile a questo indirizzo http://cvdlab.github.io/svg2lines.
- Automaticamente il sistema fornirà un'anteprima della conversione ed effettuerà il download di un file strutturato nel seguente modo `
x1,y1,x2,y2`

## Cosa supporta
SVG standard contenenti le seguenti tipologie di elementi
- `<line>`
- `<rect>`
- `<polyline>`
- `<polygon>`
- `<circle>`
- `<g>`
- `<path>`

## Cosa NON supporta
- `transform="..."`

## Supporto
Per segnalare incompatibilità aprire un issue al seguente indirizzo https://github.com/cvdlab/svg2lines/issues allegando il file non supportato.
