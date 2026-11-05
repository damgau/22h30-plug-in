# 22h30-plug-in

Versions publiées du panneau Premiere « 22H30 ».

Ce dépôt ne contient que les paquets construits : `version.json` (la dernière version) et `versions/`
(un zip par version). Le bouton « Mettre à jour » du panneau lit `version.json` et télécharge le zip.

Ne rien modifier à la main : tout est écrit par le script de construction du panneau.

Première installation : télécharger le dernier zip de `versions/`, le décompresser, puis lancer
`installer_mac.command` (macOS) ou `installer_windows.cmd` (Windows).
