# chroot

> Führe einen Befehl oder eine interaktive Shell mit einem speziellen root-Verzeichnis aus.
> Mehr Informationen: <https://www.gnu.org/software/coreutils/manual/html_node/chroot-invocation.html>.

- Führe einen Befehl mit einem neuen root-Verzeichnis aus:

`chroot {{pfad/zu/root_verzeichnis}} {{befehl}}`

- Lege einen Benutzer und eine Gruppe (ID oder Name) fest, der benutzt werden soll:

`chroot --userspec={{benutzer:gruppe}}`
