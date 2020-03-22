# Beskrivelse

## Tabeller

### Landsoversikt

![Landsoversikt](landsoversikt.png)

Viser en fullstendig oversikt over partienes samlede mandatgevinst (både distriktsmandater og utjevningsmandater), fordelt på de enkelte valgdistrikter (fylker).

### Fylker

![Fylker](fylker.png)

Viser en oversikt over fylkenes antall stemmer og mandatgevinst (både distriktsmandater og utjevningsmandater).

### Utjevningsmandater - oversikt

![Utjevningsmandater](utjevningsmandater_tabell.png)

Viser en oversikt over hvilke utjevningsmandater (fylke) hvert parti har fått.

### Restkvotienter

![Restkvotienter](restkvotienter.png)

Viser partienes restkvotienter i alle valgkretser (fylker)

***Hva er restkvotient?***  
I en valgkrets, etter at mandatene er delt ut, så er restkvotientene det samme som partiene sine gjenstående stemmeantall. Det vil si stemmene som er igjen etter at Saint Legues metode er utført.

***Restkvotienter representert i Lavinia***  
For å utjevne de store forskjellene mellom fylkene så er partienes restkvotienter justert ved å dividere restkvotientene på det gjennomsnittlige antall stemmer som står bak hvert mandat i vedkommende fylke.

### Fordeling

![Fordeling](fordeling.png)

Viser fordelingen av fylkenes mandater på hvert parti.

### Enkeltfylke  

![Enkeltfylke](enkeltfylke.png)

Viser en fullstendig oversikt, for valgt fylke, over partienes andel stemmer, mandatgevinst, margin (i antall stemmer) og sistekvotient.

## Menyer

### Valgt år

![Valgt år](valgt_aar.png)

Her kan du se på Stortingsvalg fra 1945 og fram til 2017.

Ved å se på ulike valgår kan du se utviklingen av den norske valgordningen for stortingsvalg fram til i dag.

### Valgt metode

![Valgt Metode](valgt_metode.png)

Her kan du velge å fordele mandatene med enten Sainte-Laguës eller d'Hondts metode.

Dette er beregningsmetoder som blir brukt når distriktsmandatene skal fordeles på partiene i distriktene og deretter når utjevningsmandatene skal fordeles på partiene på landsbasis (kun for partier over sperregrensen). Både Sainte-Laguës og d'Holts metode er proporsjonale valgordninger hvor kandidater velges i forhold til antall stemmer de eller deres valgliste får. d'Holts metode er mindre proporsjonal enn Sainte-Laguës metode.

Matematisk ser Sainte-Laguës metode slik ut:
$$\frac{V}{2s+1}$$
 $V$ uttrykker her partienes andel av stemmene og $S$ uttrykker deres andel av mandatene

Sainte-Laguës oddetallsmetode er opprinnelig slik at man først deler stemmetallet på 1,0 - dvs. at partiene konkurrerer om førstemandatet med de stemmer de fikk ved selve valget. En annen måte å uttrykke dette på er at første divisor er lik 1. Når et parti har erobret sitt første mandat, divideres stemmetallet på 3, ved mandat nummer 3 divideres stemmetallet på 5, osv. i oddetallsrekken. Ved økende antall mandater stiger derfor "kostnadene" i form av stemmer for partiene. I forhold til d'Hondts metode gir dette betydelig dårligere uttelling for de store partiene. Den norske valgordningen ble endret fra d'Hondts til St. Laguës metode i 1952. Som en kompensasjon for de store partiene forhøyet man første divisor fra 1,0 til 1,4 som er den nåværende ordning. Det er altså en modifisert St. Laguës metode som er i bruk i Norge i dag.

Matematisk ser d'Hondts slik ut:
$$\frac{V}{s+1}$$
 $V$ uttrykker her partienes andel av stemmene og $S$ uttrykker deres andel av mandatene

d'Hondts metode er basert på delingstallene 1, 2, 3, 4, 5, 6, 7, 8 osv. Denne metoden gir svært god mandatgevinst for de største partiene. Overrepresentasjonen for de store partiene blir så stor at dette i mange tilfeller oppfattes som et demokratisk problem.

**Stortingsvalg**  
Et eksempel på hvordan valgoppgjøret foregår ved stortingsvalg kan klargjøre hva som ligger i Sainte Laguës metode. La oss tenke oss at det i Akershus fylke skal velges 5 representanter til Stortinget. I alt stiller 5 partier (A, B, C, D, og E) til valg.

Steg 1.
Partienes stemmetall fremgår av oversikten under. Første steg er å dividere hvert partis stemmetall med det første delingstallet (første divisor) som er 1,4. (For å forenkle fremstillingen, ser vi bort fra desimalene i dette eksempelet).

Akershus fylke, 5 representanter, 5 lister.

   Parti A: 50 000 / 1,4 = __35714__  
   Parti B: 40 000 / 1,4 = 28571  
   Parti C: 30 000 / 1,4 = 21428  
   Parti D: 20 000 / 1,4 = 14285  
   Parti E: 10 000 / 1,4 =  7142  
  
Ved å sammenligne kvotientene (etter divisjonen), finner vi at parti A har den største kvotienten, og derfor vinner mandat nummer 1.

Steg 2.
Fordi parti A har vunnet ett mandat, divideres dette parties opprinnelige stemmetall med neste tall i oddetallsrekken som er 3.

   Parti A: 50 000 / 3   = 16666  
   Parti B: 40 000 / 1,4 = __28571__  
   Parti C: 30 000 / 1,4 = 21428  
   Parti D: 20 000 / 1,4 = 14285  
   Parti E: 10 000 / 1,4 =  7142  

Etter divisjonen er det parti B som har den største kvotienten, og dermed vinner det andre mandatet. Derfor må parti Bs stemmetall også divideres med 3 i neste steg.

Steg 3.

   Parti A: 50 000 / 3   = 16666  
   Parti B: 40 000 / 3   = 13333  
   Parti C: 30 000 / 1,4 = __21428__  
   Parti D: 20 000 / 1,4 = 14285  
   Parti E: 10 000 / 1,4 =  7142  

Det tredje mandatet tilfaller parti C, som har den største kvotienten i denne runden. Parti Cs stemmetall divideres derfor også med 3 i neste steg.

Steg 4

   Parti A: 50 000 / 3   = __16666__  
   Parti B: 40 000 / 3   = 13333  
   Parti C: 30 000 / 3   = 10000  
   Parti D: 20 000 / 1,4 = 14285  
   Parti E: 10 000 / 1,4 =  7142  

Sammenligner vi restkvotientene, finner vi at parti A igjen er størst, og dermed vinner sitt andre mandat som er mandat nummer 4 i dette fylket. Parti As stemmetall divideres i neste runde derfor med 5.

Steg 5.

   Parti A: 50 000 / 5   = 10000  
   Parti B: 40 000 / 3   = 13333  
   Parti C: 30 000 / 3   = 10000  
   Parti D: 20 000 / 1,4 = __14285__  
   Parti E: 10 000 / 1,4 =  7142  

Nå er det bare ett mandat igjen til fordeling i fylket, og det tilfaller parti D som har den største kvotienten.

### Første delingstall

![Første delingstall](forste_delingstall.png)

Her kan du forandre det første delingstallet i Sainte-Laguës metode. Dette er det tallet som hvert partis stemmetall deles på før tildelingen av mandater begynner. Dagens valgordning har 1,4 som første delingstall.

Hensikten er at dette skal gi et visst «styringstillegg» til de store partiene og hindre politisk fragmentering. Ved å gjøre det første delingstallet større blir det vanskeligere å få det første mandatet. Dermed blir det også vanskeligere for de partiene som kan bare få ett mandat å få det ene mandatet.

Eksempel: Gå til landsoversikt-tabellen og se hvor mange mandater de enkelte partiene får hvis du varierer det første delingstallet fra 1,0 til 2,0. Merk at ved valget i 2017 ville Miljøpartiet De Grønne fått ett mandat ekstra hvis delingstallet hadde vært 1,2. Senterpartiet ville da mistet ett mandat. Med et delingstall på 1,0 ville MDG fått to mandater ekstra, men da på bekostning av Kristelig Folkeparti og Høyre.

Vær oppmerksom på at når man skal fordele stortingsmandatene på de enkelte fylkene benyttes ikke første divisor 1.4, men i stedet 1.0 (den rene Sainte Laguës metode). Se fylkesfordeling av mandatene.

### Sperregrense

![Sperregrense](sperregrense.png)

Her kan du variere sperregrensen. Dagens ordning har en sperregrense på 4 prosent.

For å være med i konkurransen om utjevningsmandater må partiene komme over sperregrensen i oppslutning i landet sett under ett (prosent av stemmene på landsbasis). Sperregrensen gjelder kun for konkurransen om utjevningsmandater, det er ingen formelle sperregrenser ved fordeling av distriktsmandatene.

Sperregrensen gjør at fordelingen av utjevningsmandater kan få store utslag. Den kan hindre små partier i å få stor innflytelse, siden små partier får færre mandater enn stemmeantallet deres skulle tilsi uten sperregrensen. De som kommer akkurat over sperregrensen derimot, kan få mange flere mandater enn de ellers ville ha fått.

Eksempel: Partier som kommer over sperregrensen kan bli representert uten at de har vunnet noen distriktsmandater. Hvis f.eks. sperregrensen hadde vært 3 prosent i 1989, ville Venstre blitt representert med 5 utjevningsmandater.

### Sperregrense for distriktsmandat

![Sperregrense for distriktsmandat](sperregrense_distriktsmandat.png)

Her kan du se hvilke utslag en sperregrense for fordeling av distriktsmandatene ville fått, også kjent som sperregrensen på laveste nivå.

Denne sperregrensen skal gjelde i det enkelte valgdistrikt, dvs. ved beregningen av distriktsmandater. I den gjeldende valgordning er det ingen slik formell sperregrense på distriktsnivå.

### Utjevningsmandater

![Utjevningsmandater](utjevningsmandater.png)

Her kan du justere antall utjevningsmandater.

Mens distriktsmandatene fordeles etter partienes stemmetall i det enkelte fylke, er det deres samlede stemmetall for landet som helhet som er utslagsgivende for fordelingen av utjevningsmandatene. Hensikten med utjevningsmandater er å utjevne skjevheter som er oppstått etter fordelingen i fylkene. Utjevningsmandatene går til de partiene som har kommet dårligere ut av distriktsfordelingen enn deres stemmeandel skulle tilsi.

Vær oppmerksom på at partier/lister som har under 4,0 prosent av stemmene på landsbasis ikke er med i konkurransen om utjevningsmandatene. Men dette kan endres ved å sette sperregrensen lavere enn 4,0. Med den nye valgordningen fra 2005 er det mer komplisert å øke antallet utjevningsmandater utover 19, fordi det bare skal være ett utjevningsmandat i hvert fylke.

Når man foretar endringer i antallet utjevningsmandater og distriktsmandater fra valgene etter 2001, vil Lavinia foreta en fordeling på fylkene som følger de nye reglene for fylkesfordeling (se arealfaktoren).

Med dagens ordning så har Stortinget 169 representanter hvor 19 av disse er utjevningsmandater.

[Hvordan utgjevningsmandatene fordeles på fylker og partier kan du se her.](https://www.aardal.info/wp-content/uploads/2018/11/utjevn2017-2.pdf)

### Distriktsmandater

![Distriktsmandater](distriktsmandater.png)

Her kan du endre antall distriktsmandater.

I dag så består Stortinget av i alt 169 representanter der 150 mandater fordeles distriktsvis. Distriktsmandatene (169) fordeles etter partienes stemmetall i de enkelte valgdistrikter, mens utjevningsmandatene (19) fordeles etter partienes samlede stemmetall på landsbasis.

Merk at før stortingsvalget så må det regnes ut hvor mange distriktsmandater hvert enkelt valgdistrikt (fylke) skal ha. Fordelingen av mandatene på valgdistriktene er nemlig basert på en veid sum av antall innbyggere og fylkets areal. Denne fylkesfordelingen justeres hvert 8. år (annet hvert stortingsvalg) for å kunne fange opp endringer i bosettingsmønsteret.

Etter at stemmene er telt opp under stortingsvalget så brukes Sainte Laguës modifiserte metode til å fordele mandatene på partienes stemmetall i de enkelte valgdistriktene.

Når man foretar endringer i antallet utjevningsmandater og distriktsmandater fra valgene etter 2001, vil Lavinia foreta en fordeling på fylkene som følger de nye reglene for fylkesfordeling (se arealfaktoren).

### Arealfaktor

![Arealfaktor](arealfaktor.png)

Her kan du endre arealfaktor (1.8 med dagens ordning)

Arealfaktor (1,8) er det sifferet som multipliseres med antall kvadratkilometer i fylket med for å få fram den veide summen av innbyggertall og areal. Jo høyere arealfaktor, jo større vekt tillegges fylkets geografiske utstrekning. Hvis arealfaktoren settes til null, vil fordelingen bare ta hensyn til innbyggertallet i fylket og gi en fylkesfordeling av mandatene som er proporsjonal med folketallet.

### Disproporsjonalitetsindeks

![Disproporsjonalitetsindeks](disproporsjonalitetsindeks.png)

Velg enten Loosemore-Hanbys eller Gallaghers

Det finnes mange ulike måter å gi uttrykk for i hvor stor grad en valgordning avviker fra matematisk "rettferdighet", det vil si at partienes andel av mandater er lik deres andel av stemmene. Vi skal kort beskrive to ulike mål eller "indekser".

Loosemore-Hanbys indeks (L-H)
Denne indeksen beregnes ved å summere prosentdifferansene mellom partienes andel av mandatene og deres andel av stemmene. Dernest deler man på 2 (Vanligvis brukes 'D' som forkortelse av denne indeksen. I Lanvinia brukes imidlertid 'L-H' som er mer direkte forståelig).

Matematisk ser formelen slik ut:

$$LH=\frac{1}{2}\sum_{i = 1}^{n}|v_{i}-s_{i}|$$
$V$ uttrykker her partienes andel av stemmene (votes) og $S$ uttrykker deres andel av mandatene (seats)

Denne indeksen gir et enkelt mål på hvor mange prosentpoengs avvik det er for de partiene som er overrepresentert (henholdsvis underrepresentert) i forhold til den aktuelle valgordning. Fordelen med indeksen er at den er enkelt å forstå og tolke. Indeksen uttrykker avviket fra fullstendig proporsjonalitet i prosentpoeng, og jo høyere indeksverdi, jo mindre proporsjonal er valgordningen. Svakheten med Loosemore-Hanbys indeks er imidlertid at den overdriver disproporsjonaliteten i systemer med mange partier. I Lavinia er det Loosemore-Hanbys indeks som vises når programmet starter opp første gang. I resultatvinduet står det da f.eks. "L-H:5,4". Det er imidlertid mulig å endre dette til Gallaghers indeks (se under).

Gallaghers indeks (LSq)
Et tredje mål på disproporsjonalitet er Gallaghers minste kvadraters indeks (ofte benevnt 'LSq'). Denne indeksen er den mest vanlige når man ønsker å måle avvik fra matematisk rettferdighet. Det er også mulig å få Lavinia til å beregne denne indeksen i stedet for Loosemore-Hanbys. Gallaghers indeks beregnes ved å ta kvadratroten av følgende uttrykk: de summerte kvadrerte avvikene mellom hvert partis andel av stemmene og dets andel av mandatene dividert på 2.

Matematisk ser formelen slik ut:

$$LSq=\sqrt{\frac{1}{2}\sum_{i = 1}^{n}(V_{i}-S_{i})^{2}}$$
$V$ uttrykker partienes andel av stemmene (votes), mens $S$ uttrykker deres andel av mandatene (seats)

Denne indeksen lar med andre ord de store avvikene telle mer enn de små. I prinsippet kan Gallaghers indeks variere mellom 0 og 100, men i praksis viser det seg at de fleste indeksverdier ligger mellom 1 og 10. I størrelse ligger Gallaghers indeks mellom Loosemore-Hanbys (høyest) og Raes (lavest). De forskjellige måtene å måle disproporsjonalitet på er imidlertid sterkt korrelert. Dessuten er graden av disproporsjonalitet ikke nødvendigvis den viktigste egenskap ved en valgordning. De politiske utslagene kan være langt viktigere. I faglitteraturen blir det påpekt at man i tillegg til en valgordnings samlede avvik fra fullstendig proporsjonalitet, bør se om ordningen diskriminerer mellom store og små partier, eller om disse behandles likt.
