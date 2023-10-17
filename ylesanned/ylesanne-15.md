# Ülesanne 15
Igal tabelil kindlasti peab olema ID ja Primary Key.

* Loo tabel `albums` veergudega `title`, `artist`, `year`, `price`
* Andmebaasi ühendus hoia eraldifailis config.php (config.inc vms)
* Väljasta kogu ‘albumid’ sisu ridade kaupa (10 rida)
* Väljasta tabelist ainult artist ja album read, kusjuures sorteeri kasvavalt artisti järgi (10 rida)
* Väljasta tabelist ainult artist ja album read, mille aasta on 2010 ja uuemad
* Väljasta kui palju erinevaid albumeid on andmebaasis, mis on nende keskmine hind ja koguväärtus (summa)
* Väljasta kõige vanema albumi nimed
* Väljasta albumid, mille hind on kogu keskmisest suurem
* Loo otsingukast, mis lubab valida, kas otsing toimub artistide või albumite veerust.
* Tekita lehele vorm, mille kaudu saab andmeid juurde lisada
* Välista kasutaja poolelt “rämpsu” postitamist ja kood ei tohi väljastada veateateid
* Täienda väljundi iga rida kahe lingiga: kustuta ja muuda
* Klikkides kustuta, kustutatakse vastav kirje andmebaasist
* Klikkides muuda, võimaldab antud kirjet muuta
* Loo tabel `clients` veergudega `first_name`, `last_name`, `phone` ja tabel `invoice` veergudega `albums.id`, `clients.id`, mis on seotud omavahel kasutades Foreign Key
* Sinu ülesandeks on tekitada vastav klientide tabel, väljadega eesnimi, perenimi ja telefoninumber ning siduda see arvete tabeliga
* Väljundina täienda olemasoelvat näidet nii, et ma näeksin ostu sooritanud kliendi nime
