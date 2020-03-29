
# Forklaringer

## Geografisk fordeling av mandater

Stortinget skal ha representanter fra hele Norge. Derfor fordeles alle stortingsmandatene på fylkene.

For å finne antallet mandater hvert fylke skal ha så foretas følgende beregninger:

1. Hvert fylke får tildelt en sum basert på antall innbyggere og fylkets areal.

   $$fylkets\ sum = antall\ innbyggere + (antall\ kvadratkilometer * arealfaktor)$$

2. Deretter brukes den originale Saint Laguës (første delingstall 1,0) metode til å fordele 169 mandater på fylkene.

Den geografiske fordelingen av mandater justeres hvert 8. år (annet hvert stortingsvalg) for å kunne fange opp endringer i bosettingsmønsteret.

Se [Tabell over geografisk fordeling](##Tabell-over-geografisk-fordeling)

## Tabell over geografisk fordeling

I følgene tabell kan du se areal, innbyggere (i 2012) og sum (fordelingstall) i tillegg til antall mandater hvert fylke har fått utdelt etter Saint Laguës metode:

Fylke            | Areal     | Innbyggere | Fordelingstall | Mandater
---              | ---             | ---       | ---           | ---
Østfold          | 4182 $km^{2}$   | 278352    | 285879,60      | 9
Akershus         | 4918 $km^{2}$   | 556254    | 565106,40      | 17
Oslo             | 454 $km^{2}$    | 613285    | 614102,20      | 19
Hedmark          | 27398 $km^{2}$  | 192791    | 242107,40      | 7
Oppland          | 25192 $km^{2}$  | 187147    | 232492,60      | 7
Buskerud         | 14911 $km^{2}$  | 265164    | 292003,80      | 9
Vestfold         | 2224 $km^{2}$   | 236424    | 240427,20      | 7
Telemark         | 15298 $km^{2}$  | 170023    | 197559,40      | 6
Aust−Agder       | 9157 $km^{2}$   | 111495    | 127977,60      | 4
Vest−Agder       | 7277 $km^{2}$   | 174324    | 187422,60      | 6
Rogaland         | 9376 $km^{2}$   | 443115    | 459991,80      | 14
Hordaland        | 15440 $km^{2}$  | 490570    | 518362,00      | 16
Sogn og Fjordane | 18623 $km^{2}$  | 108201    | 141722,40      | 4
Møre og Romsdal  | 15115 $km^{2}$  | 256628    | 283835,00      | 9
Sør−Trøndelag    | 18856 $km^{2}$  | 297950    | 331890,80      | 10
Nord−Trøndelag   | 22415 $km^{2}$  | 133390    | 173737,00      | 5
Nordland         | 38462 $km^{2}$  | 238320    | 307551,60      | 9
Troms            | 25870 $km^{2}$  | 158650    | 205216,00      | 6
Finnmark         | 48617 $km^{2}$  | 73787     | 161297,60      | 5
Totalt           | 323785 $km^{2}$ | 4985870   |  --            |169

## Utregning med arealfaktor

Arealfaktoren er tallet som multipliseres med antall kvadratkilometer i fylket.

Ta følgene regnestykker basert på tallene fra [tabellen ovenfor](##Tabell-over-geografisk-fordeling) med arealfaktor på 1.8. Regnestykkene illustrerer hvordan **fordelingstall** regnes ut.

Aust−Agder har 111495 innbyggere og 9157 kvadratkilometer:
$$111495 + (9157 * 1.8) = 127977.66$$

Finnmark har 48617 innbyggere og 73787 kvadratkilometer:
$$48617 + (73787 * 1.8) = 161297.60$$

Merk at selv om Finnmark har færre innbyggere enn Aust−Agder så ender Finnmark opp med større fordelingstall. Finnmark ender også opp med flere mandater enn Aust-agder etter endt fordeling med Saint Laguës metode (første delingstall 1,0).

Se [Geografisk fordeling av mandater](##Geografisk-fordeling-av-mandater)

## Beregningsmetoder

**Sainte-Laguës** oddetallsmetode er opprinnelig slik at man først deler stemmetallet på 1,0 - dvs. at partiene konkurrerer om førstemandatet med de stemmer de fikk ved selve valget. En annen måte å uttrykke dette på er at første divisor er lik 1. Når et parti har erobret sitt første mandat, divideres stemmetallet på 3, ved mandat nummer 3 divideres stemmetallet på 5, osv. i oddetallsrekken. Ved økende antall mandater stiger derfor "kostnadene" i form av stemmer for partiene. I forhold til d'Hondts metode gir dette betydelig dårligere uttelling for de store partiene. Den norske valgordningen ble endret fra d'Hondts til St. Laguës metode i 1952. Som en kompensasjon for de store partiene forhøyet man første divisor fra 1,0 til 1,4 som er den nåværende ordning. Det er altså en modifisert St. Laguës metode som er i bruk i Norge i dag.

Matematisk ser Sainte-Laguës metode slik ut:
$$\frac{V}{2s+1}$$
 $V$ uttrykker her partienes andel av stemmene og $S$ uttrykker deres andel av mandatene

Se [stortingsvalg med Sainte Laguës metode](##Stortingsvalg-med-Sainte-Lagues-metode)

**d'Hondts** metode er basert på delingstallene 1, 2, 3, 4, 5, 6, 7, 8 osv. Denne metoden gir svært god mandatgevinst for de største partiene. Overrepresentasjonen for de store partiene blir så stor at dette i mange tilfeller oppfattes som et demokratisk problem.

Matematisk ser d'Hondts slik ut:
$$\frac{V}{s+1}$$
 $V$ uttrykker her partienes andel av stemmene og $S$ uttrykker deres andel av mandatene

## Stortingsvalg med Sainte Lagues metode

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

## Margin til sistemandatet

Ved stortingsvalg er vi ofte interessert i vite hvilket parti som fikk sistemandatet og hvor mange stemmer det var om å gjøre for at et annet parti hadde vunnet dette mandatet. Det siste refererer vi til som 'marginen' til sistemandatet. Er marginen liten, betyr det at mandatet er utsatt ved neste valg. Det vil si at andre partier kan ta mandatet fra det partiet som vant det forrige gang.

[Stortingsvalg med Sainte-Laguës metode, steg 5:](##Stortingsvalg-med-Sainte-Lagues-metode)

   Parti A: 50 000 / 5   = 10000  
   Parti B: 40 000 / 3   = __13333__  
   Parti C: 30 000 / 3   = 10000  
   Parti D: 20 000 / 1,4 = __14285__  
   Parti E: 10 000 / 1,4 =  7142  

I eksempelet over  er det parti B som har den nest største kvotienten i siste runde. Differansen til parti D som vant mandatet er (14285 - 13333) = 952. Men for å kunne ta sistemandatet fra parti D, måtte parti B hatt minst 1 stemme mer, samtidig som vi må ta hensyn til at parti B har fått tildelt mandater tidligere. Vi må derfor multiplisere opp differansen (952+1)*3, dvs. at parti B måtte hatt 2858 flere stemmer (altså før første deling) for at partiet skulle vunnet sistemandatet (her er det tatt hensyn til desimalene, derfor blir marginen 2858 og ikke 2859). I enkelte tilfeller er et parti så mye større enn de andre partiene at partiet både kan ha sistemandatet og ligge nærmest til å "vinne" det samme mandatet. Et eksempel på dette finner man i Sogn og Fjordane ved stortingsvalget i 1989 der Arbeiderpartiet vant sistemandatet, samtidig som partiet lå nærmest til å vinne sistemandatet (selv om SV som ikke vant noe mandat, hadde trengt færre stemmer enn Arbeiderpartiet).

## Justert restkvotient

Antall stemmer bak hvert mandat varierer fra fylke til fylke. Restkvotiene til partiene er derfor justert. Det blir gjort ved å dividere restkvotientene på gjennomsnittlige antall stemmer som står bak hvert mandat i vedkommende fylke.

$$justert\ restkvotient\ = \frac{partiet\ sin\ restkvotient}{gjennomsnittlig\ antall\ stemmer\ bak\ hvert\ mandat}$$

Eksempel: I Finnmark stod det i gjennomsnitt 9727,25 stemmer bak hvert mandat i 2017. I Oslo stod det 20394, 5 stemmer bak hvert mandat. Høyres rekvotient på 5600 stemmer utgjør med andre ord 0,58 deler av et mandat i Finnmark, men bare 0,27 deler av et mandat i Oslo. For å utjevne de store forskjellene mellom fylkene justerer man derfor partienes restkvotienter ved å dividere restkvotienter på det gjennomsnittlige antall stemmer som står bak hvert mandat i vedkommende fylke.

I Finnmark blir resultatet slik for de fem partiene som skal ha utjevningsmandat:
  --             |      SV      |       V      |      KrF    |       SP     |      H
  --             | ---          | ---          |---          |---           |---
Restkvotient     | 3437         | 1644         | 808         | 5790/3=1930  | 5600
Divisjon         | $\frac{3437}{9727,25}$ | $\frac{1644}{9727,25}$ | $\frac{808}{9727,25}$ | $\frac{1930}{9727,25}$ | $\frac{5600}{9727,25}$
Justert restkvotient |  0,3533      | 0,1690       | 0,0831      | 0,1984       | 0,5757

[Eksempel på hvordan utjevningsmandatene fordeles på partier og fylker med den nye valgordningen](https://www.sv.uio.no/isv/forskning/prosjekter/valgforskning/valgordning/utjvnex.pdf)

## Restkvotioent

I en valgkrets, etter at mandatene er delt ut, så er restkvotientene det samme som partiene sine gjenstående stemmeantall (etter at Saint Legues metode er utført). Har partiet ikke vunnet noe mandat, er restkvotienten lik stemmetallet ved valget.1 Har partiet vunnet ett distriktsmandat, er restkvotienten lik stemmetallet dividert på 3.

Se eksemplet [Stortingsvalg med Sainte-Laguës metode, steg 5:](##Stortingsvalg-med-Sainte-Laguës-metode)

   Parti A: 50 000 / 5   = __10000__  
   Parti B: 40 000 / 3   = __13333__  
   Parti C: 30 000 / 3   = __10000__  
   Parti D: 20 000 / 1,4 = __14285__  
   Parti E: 10 000 / 1,4 =  __7142__  

## Fordelingen av utjevningsmandater på partier

Etter fordeling av distriktsmandater så foretas fordelingen av utjevningsmandater. Merk at partier under sperregrensen (4 prosent oppslutning på landsbasis) er ikke med i konkurransen om utjevningsmandater.

Først må det beregnes hvilke partier som skal ha utjevningsmandater og hvor mange de skal. Dette gjøres gjennom å beregne et nytt valgoppgjør der man fordeler alle de 169 mandatene, men nå med hele landet som én valgkrets. Denne fordelingen gjøres med Saine Lagües modifiserte metode.

Det antallet mandater partiene får i dette nye oppgjøret sammenlignes så med det antallet distriktsmandater de allerede har fått tildelt. Forskjellen mellom de to oppgjørene utgjør det antallet utjevningsmandater partiet skal ha. Dersom differansen er negativ, altså at partiet allerede er «overrepresentert», må beregningen gjøres på nytt uten dette partiet. Mandatene de har vunnet holdes da utenom.

Neste steg er å avgjøre i hvilke fylker partiene skal få utjevningsmandatene sine.

## Geografisk fordeling av utjevningsmandater

For å fordele utjevningsmandatene på fylkene så må justerte restkvotienter regnes ut for partiene i hvert fylke. Dette regnestykket gjøres for partiene som skal ha utjevningsmandater.

Vi tar for oss stortingsvalget i 2017 som eksempel:
Alle restkvotiene samles i en lang rekke, rangert fra størst til minst. Den største restkvotienten er Høyres 0,5757 i Finnmark. Høyre vinner derfor det første utjevningsmandatet. Så får de fem partiene sine utjevningsmandater alt etter hvor store restkvotientene deres er. I og med at det bare er ett utjevningsmandat i hvert fylke, kan man stryke restkvotientene for de partiene som ikke har vunnet mandatet i dette fylket. Det nittende og siste utjevningsmandatet vinnes av Venstre i Nord-Trøndelag med restkvotienten 0,0897. Legg merke til at flere av de andre partiene har større restkvotient enn Venstre i dette fylket. Men de andre partiene har fått det antall utjevningsmandater de skal ha når jeg er kommeet så langt i prosessen, så deres restkvotienter teller ikke.
