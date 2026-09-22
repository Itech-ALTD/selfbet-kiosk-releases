# selfBeft Kiosk — pacchetti di distribuzione

Questo repository contiene **soltanto i pacchetti di installazione e
aggiornamento** del kiosk selfBeft. Il codice sorgente non è qui.

## Perché è pubblico

I terminali installati scaricano gli aggiornamenti da qui, da soli, senza
supervisione. Tenere il repository pubblico evita di dover mettere una
credenziale di accesso su ogni macchina: un terminale sta in un luogo pubblico,
e qualunque segreto conservato lì va considerato leggibile.

Pubblicare resta possibile solo a chi ha accesso in scrittura a questo
repository.

## Cosa trovate nelle release

| File | A cosa serve |
|---|---|
| `selfBeft-win-Setup.exe` | Prima installazione |
| `selfBeft-*-full.nupkg` | Pacchetto completo |
| `selfBeft-*-delta.nupkg` | Solo le differenze dalla versione precedente |
| `RELEASES`, `releases.win.json` | Indice letto dai terminali |

## Assistenza

Per problemi di installazione o funzionamento, rivolgetevi al vostro referente
tecnico abituale.
