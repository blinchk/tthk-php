# Ülesanne 11

## Andmete salvestamine faili

**Loo PHP skript, mis järgib järgmisi samme:**
1. Avage fail "andmefail.txt" kirjutamiseks `fopen` abil.
2. Looge assotsiatiivne massiiv, mis sisaldab järgmist teavet:
* Nimi: John Doe
* Email: johndoe@tthk.ee
* Vanus: 30
* Hobi: Jalgrattasõit
3. Salvestage see massiiv faili, kasutades `fwrite`, nii et andmed on selles failis loetavad.
4. Sulgege fail `fclose` abil.

## Andmete lugemine failist

**Loo PHP skript, mis järgib järgmisi samme:**
1. Avage fail "andmefail.txt" lugemiseks `fopen` abil.
2. Kasutage `fread`, et lugeda faili sisu muutujasse.
3. Parandage tekst, et asendada reavahetused `<br>`-märgenditega, kasutades `nl2br`.
4. Väljastage loetud ja töödeldud tekst ekraanile.
5. Sulgege fail `fclose` abil.

## Andmete muutmine failis

**Loo PHP skript, mis järgib järgmisi samme:**
1. Avage fail "andmefail.txt" lugemiseks ja kirjutamiseks "r+" režiimis `fopen` abil.
2. Kasutage `fgets`, et lugeda esimene rida failist.
3. Lisage uus rida, kus on järgmised andmed:
* Telefon: 555-1234
* Aadress: 123 Main Street
4. Salvestage muudetud sisu tagasi faili, kasutades `fwrite`.
5. Sulgege fail `fclose` abil.

## Faili suuruse kontroll ja kustutamine

**Loo PHP skript, mis järgib järgmisi samme:**
1. Kontrollige, kas faili "andmefail.txt" suurus on suurem kui 200 baiti, kasutades `filesize`.
2. Kui fail on suurem kui 200 baiti, siis kustutage fail `unlink` abil ja väljastage teade faili kustutamisest.
3. Kui fail ei ole suurem kui 200 baiti, siis väljastage teade, et fail ei vasta kustutamise kriteeriumile.
