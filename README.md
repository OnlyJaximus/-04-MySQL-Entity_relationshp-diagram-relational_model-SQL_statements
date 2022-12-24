# -04-MySQL-Entity_relationshp-diagram-relational_model-SQL_statements

************************************* Entity_Relationship ********************************************** </br>
ENTITETI identifikacija: autoservis, radionica, usluga, radnik, vozilo, klijent </br>
ATRIBUTI: </br>
         autoservis (id, lokacija, telefon)  </br>
         radionica  (broj radionice, vrsta usluge) </br>
         usluga (naziv) </br>
         radnik (IS_A) </br>
         vozilo (id, tip vozila, marka vozila, registarski broj, marka) </br></br>
         
         Marka atribut se sastoji iz dva atributa (naziv model i naziv prozivodjaca)  </br>
         Marka NIJE entitet. Marka JE kompozitni atribut! To je  atribut koji se sastoji iz druga dva atributa. </br>
         
         klijent IS_A () </br>
         
         Veza izemdju vozila i majstora je entitet POPRAVLJA koji ima neke svoje atribute. Popravlja ce biti ascoijatvini entitet.
         Veza je (1,n) na (0, n) tj. vise na vise. </br>
