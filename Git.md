Git este un sistem distribuit de control al versiunilor dezvoltat de Linus Torvalds în 2005, care rulează local pe computer și nu necesită conexiune la internet:
-Ramuri:O ramură este un indicator mobil către un commit care permite dezvoltarea izolată a unor caracteristici noi fără a afecta codul principal. Când munca pe o ramură este gata, modificările sunt îmbinate (_merge_) înapoi în ramura principală (_master_).
-commit-ul:Reprezintă salvarea propriu-zisă a modificărilor. Fiecare commit conține un ID unic (hash), numele autorului, data la care a fost creat și un mesaj descriptiv al modificărilor.
-urmarirea fisierelor:Înregistrează modificările aduse fișierelor de-a lungul timpului, oferind posibilitatea de a compara fișierele sau de a reveni la o versiune anterioară.
-starile fisierelor:Un fișier trece prin stările _untracked_ (neurmărit/proaspăt creat), _modified_ (modificat), _staged_ (pregătit pentru salvare) și _committed_ (salvat în depozitul Git).
