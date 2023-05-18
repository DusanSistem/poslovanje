# poslovanje

Koliko je Petar Petrovic koji prodaje bmw zelene boje prodao po kojoj ceni kog dana? Upit je sledeci :

SELECT prodaja.kolicina,prodaja.cena,prodaja.datum FROM `prodaja` INNER JOIN prodavac ON prodavac.id=prodaja.prodavac_id 
WHERE prodavac.ime = 'Petar' AND prodavac.prezime = 'Petrovic' AND prodavac.automobil='bmw' AND prodavac.boja = 'zelena';
