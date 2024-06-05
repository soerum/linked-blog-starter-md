 **Hva er statistikk?
 - **Statistikk** er vitenskapen for planlegging av undersøkelser, innsamling og presentasjon av tallmateriale, og analyse og beslutninger ut fra innsamlede data.
	 - Statistikk beskriver populasjon og deres iboende variabilitet, mens sannsynlighet handler om å kvantifisere usikkerhet. 
	 - Vi kan dele statistikk inn i to deler:
		 - **Deskriptiv statistikk** fokuserer på å beskrivelse og oppsummering av datasett. Dette inkluderer å lage grafer, tabeller og målinger av sentral tendens og spredning.
		 - **Inferensiell statistikk** handler om å generalisere og gjøre slutninger om en populasjon basert på en dataprøve. Dette inkluderer hypotesetesting, konfidensintervaller, regresjonsanalyse og variansanalyse. 
 - **Sannsynlighet** brukes for å uttrykke hvor trolig en hendelse er og som et uttrykk for hvor ofte en hendelse opptrer.

**Populasjon og utvalg**
- Populasjon i statistikk er den komplette samlingen av elementer (personer, objekter, målinger og lignende) som har visse felles karakteristikker. Det er altså alle mulige elementer.
- Utvalg er en delmengde av en populasjon som brukes for å representere hele populasjonen, da det sjeldent er mulig å måle samtlige elementer i populasjonen.
- Vi bruker stor N om antall observasjoner i hele populasjonen, og n om antall observasjoner i et utvalg.
	- Utvalg er viktig fordi det er mer praktisk gjennomførbart og reduserer kostnader. Analysene blir mer effektive.
	![[Pasted image 20240605093519.png|500]]
-  Vi har flere typer utvalg:
	- **Enkelt tilfeldig utvalg** er når hvert medlem av populasjonen har samme sannsynlighet for å bli valgt.
	- **Stratifisert utvalg** er når populasjonen deles inn i strata, og det foretas et tilfeldig utvalg i hvert stratum.
	- **Klyngeutvalg** er deling av populasjonen inn i klynger(?)
	- **Systematisk utvalg** er utvalg av elementer fra en liste med jevne mellomrom
- **Bias (statistisk skjevhet)** referer til enhver form for skjevhet eller systematisk forvrengning i data eller resultater av en analyse.
- **Utvalgsfeil** refererer til feil som oppstår når et utvalg ikke nøyaktig representerer populasjonen det er trukket fra. Utvalgsfeil kan skje av flere grunner, som begrenset utvalgsstørrelse eller utilstrekkelig randomisert utvalgsmetode

**Variabeltyper**
- Enheten i utvalg og populasjon kan beskrives av visse **variabler**. De mulige variabelverdiene kalles kjennetegn. De to hovedtypene av variabler er:
	- Kvalitative variabler:
		- **Kvalitative nominale variabler** er variabler som representerer kategorier uten en naturlig eller hierarkisk orden, som for eksempel kjønn, nasjonalitet og farge. 
		- **Kvalitative ordinale variabler** er variabler som indikerer kategorier med en rangering eller nivå, som for eksempel utdanningsnivå og resultat i sportsarrangementer. 
	- Kvantitative variabler:
		- **Kvantitative diskrete variabler** er de variablene som representerer de tellbare dataene i spesifikke verdier, som for eksempel antall barn i en familie og antall biler solgt i løpet av en måned. 
		- **Kvantitative kontinuerlige variabler** er de kontinuerlig variablene som kan anta hvilken som helst verdi innenfor et intervall, for eksempel vekt, høyde og tid på et løp. 
- Vi har også flere typer måleskalaer:
	- **Nominell måleskala** brukes til å klassifisere data uten en naturlig orden, som for eksempel blodtype og forskjellig type boliger.
	- **Ordinær måleskala** brukes til å uttrykke en orden eller grad mellom kategoriene, som for eksempel en stjernevurdering av restauranter, kundetilfredshetsnivåer også videre.
	- **Intervallskalaen** har betydelige forskjeller mellom verdiene, men ingen absolutt null. Dette kan være grader i celsius og poeng i en test(?). 
	- **Forhold** inkluderer en absolutt null og tillater proporsjonale sammenligninger, som for eksempel årsinntekt og alder. 

**Sentralmål**
- Vi bruker sentralmål for å beskrive en typisk, representativ verdi fra et datasett. Det er tre vanlige verdier her:
	- **Modus** er verdien eller verdiene som forekommer oftest i et datasett.
	- **Median** er den sentrale verdien i et **ordnet datasett**. Mindre følsom for ekstreme verdier sammelignet med gjennomsnittet. 
		![[Pasted image 20240605095606.png]]
	- **Gjennomsnitt** er summen av alle verdiene delt på antall verdier. Mer følsom for ekstreme verdier. Median er dermed ofte mer nyttig dersom det er outliers eller ekstremverdier. 
		![[Pasted image 20240605095850.png]]

**Spredningsmål**
- **Spredningsmålet** beskriver hvor mye verdiene i et datasett avviker fra hverandre og fra deres gjennomsnitt. Det er essensielt for å forstå datafordelingen.
- **Utvalgsvarians** er gjennomsnittet av kvadratene av avvikene for hver verdi fra datasettsgjennomsnittet. Måler hvor mye dataene avviker fra gjennomsnittet i utvalget. 
	![[Pasted image 20240605100409.png]]
- **Utvalgsstandardavvik**, eller **standardavviket**, er kvadratroten av variansen og måler spredningen av data i forhold til gjennomsnittet. 
	![[Pasted image 20240605100616.png]]
- **Variasjonsbredde** er forskjellen mellom den høyeste og laveste verdien i datasettet. Svært påvirket av ekstreme verdier.
	![[Pasted image 20240605100717.png]]
- **Variasjonskoeffisient** er forholdet mellom standardavviket og gjennomsnittet, og viser den relative variabiliteten. Nyttig for å sammenligne spredningen mellom datasett med forskjellige gjennomsnitt. 
	![[Pasted image 20240605100825.png]]
- **Kvartilbredden (IQR)** eller **kvartildifferansen** måler variabiliteten innenfor datasettets mindre kvartiler. For eksempel forskjellen mellom tredje og første kvartil:
	![[Pasted image 20240605101035.png]]
	