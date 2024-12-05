### SQL UPIT
SELECT s.id, s.artikl, s.kolicina
FROM stavke s
JOIN racuni r ON s.racun = r.id
WHERE r.id = ?;
