# head

> Stampa a schermo le prime linee di un file.
> Maggiori informazioni: <https://www.gnu.org/software/coreutils/manual/html_node/head-invocation.html>.

- Stampa a schermo le prime linee di un file:

`head -n {{numero_di_linee}} {{file}}`

- Stampa a schermo i primi byte di un file:

`head -c {{numero_di_byte}} {{file}}`

- Stampa a schermo tutto il file meno le ultime linee:

`head -n -{{numero_di_linee}} {{file}}`

- Stampa a schermo tutto il file meno gli ultimi byte:

`head -c -{{numero_di_byte}} {{file}}`
