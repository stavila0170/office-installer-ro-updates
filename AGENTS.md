# Canal public Office Installer RO

Publica numai catalogul JSON validat, pachetele EXE si documentatie publica.
Nu publica surse de recuperare, backupuri, credentiale, configuratii, cai locale,
jurnale sau date personale. Pastreaza istoricul; fara force-push.

La o editie Office noua verifica ProductId/Channel in documentatia Microsoft si
creste catalogRevision. La un EXE nou schimba version/downloadUrl/sha256 si publica
manifestul si pachetul in acelasi commit. SHA-256 trebuie sa corespunda fisierului
exact. Executabilele se publica doar dupa build, teste si verificarea resurselor.
