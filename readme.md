Bluemix oppgave MøllerGruppen


Denne oppgaven tar utgangspunkt i en Watson tjeneste som kan benyttes for å gjøre en personlighets analyse av tekst. Mer om tjenesten her: http://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/personality-insights.html

Tanken er følgende. Bruk noe tekst input om en av deres kunder (feks twitter feeds) send de til watson for analyse. Etabler en referanse database med møllers biler knyttet mot personlige egenskaper (Big 5). Sammenstill analysen fra watson med databasen og finn hvilken møller bli som passer.

Dere står helt fritt till hvordan dere ønsker å løse denne oppgaven - om dere vil kode i java, js eller stiften den sammen i feks Node-Red.

Jeg har to eksempler her - en hvor vi bygger dette opp som en prototype i Node-Red og siden bygger en node.js app med et enkelt gui.


Opprett en konto på Bluemix - hvis du ikke allerede har  http://blumix.net - sign-up.
Opprett en ny app basert på en Node-Red Starter Boilerplate.
Følg steg i «getting started» - last ned CF tool og starter code ( den trendier vi senere da vi skal endre litt på oppsettet av node-red.
Legg en Watson Personal insights service oil happen din ved å gå på connections fanen - connect new. Bekreft re-stage av app.
Når Node-red har startet gå til url du valgte som app navn.
La os lage en enkel flow for å teste ut tjenesten.
Velg en watson peronality insights node fra paletten på venstre side.
Legg til en inject node + en debug node og koble dem sammen slik
Endre debug noden til å ligge msg.insights
<img src=images/mimg1.png>
