# weather

Učitavamo csv file sa githuba. 
Csv file sadržava podatke za vrijeme u New Yorku 2016. godine. 
File sadržava minimalnu/maksimalnu/prosječnu temperaturu, oborine, snijeg za svaki dan. 
Temperatura je na početku izražena u Fahrenheitima. Radi lakšeg razumijevanja temperature, preračunali smo ih u Celzijuse.
Oborine su mjerene u inčima, oborina može poprimati i vrijednost T što znači da se nalaze u tragovima. Slično tako i za snijeg.
Provodimo analizu vremena na razne načine, gledamo grafove za prosječnu temperaturu, količinu padalina.
Prikazali smo i video gdje se nalaze mećave u New Yorku. 
Kako bi uopće prikazali gdje je New York, koristimo folium. Postoje i mnogi drugi načini za prikaz karti, ali neki zahtjevaju API key. 
Uzeli smo geografski smještaj New Yorka i Zagreba. Uz pomoć geopy-a računamo distancu između Zagreba i New Yorka i uzimamo ručno podatke sa stranice 
https://meteo.hr/klima.php?section=klima_podaci&param=k1&Grad=zagreb_maksimir i uspoređujemo vrijeme između Zagreba i New Yorka.

