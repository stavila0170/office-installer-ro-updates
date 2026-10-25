# Office Installer RO — actualizari

Catalog public si pachete de actualizare pentru Office Installer RO.

## Descarcare

[Descarca OfficeInstallerRO 1.1.0](https://raw.githubusercontent.com/stavila0170/office-installer-ro-updates/main/packages/OfficeInstallerRO-1.1.0.exe)

Aplicatie Windows 10/11 pentru Microsoft 365 si Office LTSC. Selectie editie,
limbi, arhitectura si aplicatii; cache reutilizabil; progres; dezinstalare
MSI/Click-to-Run cu lista confirmata si avertizare pentru documentele nesalvate.
Licenta Office corespunzatoare este necesara. Aplicatia nu activeaza Office.

## Actualizari

Din Actualizari... poti verifica imediat sau dezactiva verificarea automata.
Implicit verifica la pornire cand au trecut 24h si apoi la 24h cat aplicatia este
deschisa. O editie Office noua apare dupa includerea identificatorului si canalului
corect in catalog; nu trebuie recompilat EXE-ul pentru o simpla editie noua.

Un EXE nou se instaleaza numai dupa confirmare. Se verifica SHA-256, numele si
versiunea assembly-ului. Aplicatia se inchide si redeschide, iar EXE-ul vechi este
pastrat intr-o copie .previous. Actualizarea aplicatiei nu instaleaza Office.
Executabilele nu sunt semnate cu certificat de editor.

Catalogul este [updates.json](updates.json), iar pachetele sunt in packages/.
Sursele de recuperare si backupurile sunt pastrate separat, in destinatii private.
Acest repository nu contine configuratii, jurnale sau date private ale utilizatorului.

Pentru versiuni 1.0.x, prima instalare a 1.1.0 se face manual, deoarece aplicatia
veche nu include updaterul.
