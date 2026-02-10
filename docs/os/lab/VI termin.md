**Signali i redovi poruka**

<br>

🚨 **DEFINICIJA**
---

Signali su mehanizam koji se koristi kako bi se proces **obavestio o pojavi** nekog asinhronog dogadjaja. <br>
**Obicno operativni sistemi salju signal** procesima u slucaju greske (neocekivani dogadjaji). <br>
Svaki proces **moze da salje signal drugom procesu ukoliko ima dozvolu da to uradi.** <br>
Svaki signal ima **pridruzenu funkciju za obradu.** <br>
Kada procesu **stigne signal** (signalizira pocetak necega) proces koji se izvrsava **prekida svoj tok izvrsavanja i poziva funkciju** za obradu tog zadataka. <br>
Mozemo podesiti da neki **odredjeni signal bude ignorisan.**
