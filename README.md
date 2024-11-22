Flask aplikacija koja koristi sql baza na podatoci preku SQlachemy( koristime ova za komunikacija so baza na podatoci)
Imame 3 klasi koi sto objasnuva -
1. Informacii za korisnikott
2. Troshoci na korisnik
3. Korisnici koi imaat troshoci povekje od 1000(kako za primer go napishav brojo)

API ( so pomos na @app.route se izvrsuvat instrukcii edna po edna)
   /total_spent/<user_id> (GET) - vrakja site trosoci na nekoj korisnik i go bara spored negov ID.
   /average_spending_by_age (GET) - presmetuva trosoci spored vozrasta na korisnici(sum stavil vozrast da bide od 18 do 47 najvekje), i gi vrakja na kraj
/write_high_spending_user (POST) - gi zapisuva site korisnici koi imat trosoci nad 1000 vo posebna tabela za trosoci nad 1000.

Za POST I GET
POST se koristi za dodavanje na korisnici vo tabeli
GET za presemtka na trosoci na korisnici
