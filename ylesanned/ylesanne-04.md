# Ülesanne 4

Kõik ülesanded on varustatud kommentaaridega ja vormindatud Bootstrapiga. Iga osa ülesannest on tehtud eraldi PHP-lehel ühes kaustas.

* **Jagamine** – sisestatakse 2 täisarvulist muutujat. Jaga üks arv teisega. Väljasta ka hoiatav lause, kui kasutaja üritab jagada nulliga. Lisa kontroll, mis ei käivita koodi tühjade lahtrite puhul (N: if(!empty($_GET[‘name’])){lause}, see käivitab koodi siis, kui lahtrisse on midagi lisatud)
* **Vanus (if…elseif)** – sisestatakse kasutaja vanused. Leia, kumb on vanem või on ühevanused. Kood ei käivtu, kui kumbki lahter on jäänud tühjaks
* **Ristkülik või ruut** – kasutaja sisestab ristküliku külgede väärtused. Sinu kood otsustab, kumb on võimalik: ruut või ristkülik
* **Ristkülik või ruut II** – vastavalt kasutaja sisestatud arvudele kuvatakse vastavalt ruut või ristkülik
* **Juubel** – kasutaja lisab sünniaasta ning kood väljastab, kas tegemist on juubeliaastaga. Lisa kontroll, mis ei käivita koodi tühjade lahtrite puhul.
* **Hinne** – kasutaja sisestab oma KT punktide arvu.
  * kui ta sai rohkem >10p, tuleb kiri SUPER!
  * 5-9p TEHTUD!
  * alla 5p KASIN!
  * kui pole punkte lisanud või lisas kogemata teksti tuleb kiri SISESTA OMA PUNKTID!
