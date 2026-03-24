# WSJT-X per contest MDXC

Questo fork di WSJT-X Improved e' specifico per i contest MDXC. Supporta un nuovo tipo di messaggio, pensato per poter scambiare provincia e numero MDXC (opzionale) durante il Contest Italia (https://www.mdxc.org/contestitalia/).

## Istruzioni

- Scarica ed installa questa versione di WSJT-X
- Nelle impostazioni, abilita "MDXC Contest Settings" e seleziona provincia e numero MDXC (0 se non socio)
- Inizia a chiamare CQ con "CQ MDXC <call> <locatore>"

## Come segnalare un baco

- Attivare nel menu "Save", "Save all" per collezionare i file WAV utili per verificare problemi di errata decodifica
- Fornire la versione in uso (si trova nella barra del titolo, es. "MDXC mod v.58d12345")
- Fornire screenshot e video del comportamento errato
- Fornire i file WAV (se rilevanti)
- Fornire ALL.TXT e wsjtx_log.adi (se rilevanti)
- Aprire una issue in https://github.com/enricolorenzoni59/wsjtx-mdxc/issues

## Sequenza QSO

- CQ MDXC I1AAA JN11
- I1AAA I2BBB PI 123
- I2BBB I1AAA R RM 123
- I1AAA I2BBB RR73

## Domande frequenti

- Come si scarica il binario?
  - Cliccando sul file, poi cliccando "View raw"