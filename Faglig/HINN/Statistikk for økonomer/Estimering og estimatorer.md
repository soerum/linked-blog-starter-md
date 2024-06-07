- Til nå har fordelingen alltid vært kjent, og formålet med diskusjonen har vært å regne ut sannsynligheten for noen spesielle begivenheter, for eksempel P (X≤x). Nå antar vi at fordelingen bare delvis er kjent, og vi skal forsøke å trekke konklusjoner omkring de ukjente størrelsene ut fra observerte data.
- Vi har to typer estimering:
	- **Punktestimering**, hvor vi anslår verdien av en parameter med en enkelt verdi.
	- **Konfidensintervall**, hvor vi presenterer et intervall som vi mener at parameterverdien med stor sikkerhet ligger i. 
- Eksempler på ukjente tall man ønsker å anslå verdien til, kan være forventning og varians. Slike størrelser, som sier noe om vesentlige egenskaper for en sannsynlighetsfordeling, kalles gjerne **parametere**. Når vi regner ut en anslått verdi for en parameter, sier vi at vi estimerer størrelsen på parameteren.
	- Dersom parameterne µ=E[X] og σ^2=Var[X] er ukjente tall, ønsker vi å anslå verdien på dem ut fra de observasjonene som er gjort.
- En **estimator** er en stokastisk variabel knyttet til en forsøksserie, og som har den egenskapen at den observerte verdien kan brukes til å anslå en ukjent parameter.
	- Kravene til en god estimator er at den skal være forventningsrett og at den skal være konkret, altså ha minst mulig varians. 
- **Målemodellen:**
	- Litt usikker på denne. Undersøk. 
- **Konfidensintervallet:**
	- Vi vil nå finne en metode til å angi intervall som inneholder en ukjent parameter med høy grad av sikkerhet. Et slik intervall skal vi kalle et **konfidensintervall**, og slik estimering kalles **intervallestimering**.
	![[Pasted image 20240607172656.png|500]]
		![[Pasted image 20240607172552.png]]
		(1-α) 100% konfidensintervall betyr at hadde vi gjentatt forsøket manger ganger ville den sanne parameterverdien ligget i konfidensintervallet (1-α) 100% av gangene.
- **t-Student-fordeling**:
	![[Pasted image 20240607172631.png|500]]
	