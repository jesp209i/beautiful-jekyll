---
layout: post
title: Udfør brugertest
subtitle: Eksekvering, observationer og evaluering
tags: [uge 21, testing, usability]
---

Her vil jeg komme ind på hvordan en test udføres, hvem der deltager og deres roller samt hvordan man afslutter sådan en omgang.

# Læsevejledning
Dette blogindlæg er en fortsættelse af mit sidste indlæg. Det er nummer 2 i min gennemgang af Steve Krugs bog "Rocket Surgery made easy", som jeg bruger som basis for mit emne om brugertest.

Du kan læse mere om emnet i disse blogindlæg:
- [Gør klar til brugertest](https://enmango.dk/2019-05-22-prepare-test/)
- [Brugertestens efterspil](https://enmango.dk/2019-05-26-after-test/) 

Til at belyse andre testtyper kan du også læse dette indlæg:
- [Typer af tests](https://enmango.dk/2019-05-24-test-types/)

# Test
Til at gennemføre test skal der bruges:
- en facilitator
- et testrum
- overslag over testens tidsforbrug
- viden om hvordan test-deltagere skal håndteres

## Facilitatorens job
Facilitatoren fungerer som en guide og vejleder for deltagerene. Han skal sætte deltagerne igang, få dem til at fortsætte, og sørge for at oplevelsen er behagelig. UDEN at besvare deltagerens spørgsmål om opgaverne/produktet der testes. Det er vigtigt at facilitatoren hele tiden får deltageren til at italesætte sine tanker og observationer undervejs i testen.

> "I like to say that you and the observers want to be able to see the thought ballons forming over the participant's head. You're particularly interested in moments when the ballons contains question marks or exclamation points, indicating that the user is confused, puzzled, or frustrated" <br>
> \-side 64 i Rocket surgery...

## Opsætning af testrum
I et testrum skal du bruge:
- en computer du selv har kontrol over med:
  - internetadgang
  - software til at optage skærmen
  - software til at dele skærmen
- en ekstern skræm, tastatur og en almindelig mus
- USB microfon som optager i god kvalitet
- en speakerphone, som både fungerer som backup for microfonen og til hvis observationsrummet skal have fat i facilitatoren

Inden de rigtige tests sættes igang, testes alt udstyr og om forbindelse til observationsrummet er iorden.

## Test timeline
Testene består følgende "faser":
- Velkomst og intro 4 min
- opvarmningsspørgsmål 2 min
- produkt tour 3 min
- opgaver 35 min (dette er selve testen)
- opfølgende spørgsmål fra observatører 5 min
- afslutning af test 5 min
- klargøring til test 10 min
- [Test-drejebog fra SK's website](http://sensible.com/downloads/test-script-web.pdf)

## Håndtering af test-deltagere
Test-deltagerne skal naturligvis behandles ordentligt. Hvis de bliver usikre eller fortvivlede skal de forsikres om at deres indput til testen er værdifuldt. Opfordr dem til at snakke hvis de er gået i stå, men sørg for at de bliver behandlet etisk forsvarligt.
- ['Ting en terapeut ville sige' fra SK's website](http://sensible.com/downloads/things-a-therapist-would-say.pdf)

# Observatører
Det er en god ide at få folk til at observere når testene bliver udført. Der opfordres til at også andre end udviklerne deltager som observatører (såsom chefer og marketingsfolk).

Observatørernes opgave er at: 
- observere og tage notater
- efter hver testsession, notere de 3 vigtigste problemer de har observeret
- foreslå spørgsmål som facilitatoren kan stille til test-deltagerne
- nyde de snacks der er tilgængelige (Steve Krug går meget op i at der er snacks, for det kan få folk til at møde op)
- deltage i afrapporteringen under frokosten
- [Observatørinstruktioner fra SK's website](http://sensible.com/downloads/instructions-for-observers.pdf)

Observatørerne skal ikke sidde i samme rum hvor testene bliver udført. Man kan godt udføre test hvor de sidder i samme rum, men Steve fraråder det fordi observatørerne ofte (vidende eler uvidende) vil påvirke testen.

I observatørrummer skal der være følgende ting tilgængelige:
- en computer som kan vise det delte skærmbillede fra testrummet
- en stor skærm eller projektor så alle observatører kan se hvad der foregår
- gode højtalere så alle kan høre 
- gode snacks (der var den igen)
- en speakerphone, så man har en måde at komme i kontakt med facilitatoren i testrummet hvis det er nødvendigt

Der bør desuden udpejes en "ordstyrer" til observationsrummet som kan hjælpe facilitatoren med at styre aktiviteterne der. Det skal være en kollega som ikke bliver intimideret af andre kollegaer eller chefer.
- [Ordstyrerinstruktioner fra SK's website](http://sensible.com/downloads/hall-monitor-guide.pdf)

> "Ordstyrer" er mit forsøg på at oversætte titlen "hall monitor", som SK bruger i bogen, til noget der virker mere passende i en dansk kontekt :).

# Evaluering
Der er to formål med evalueringen:
- at producere en liste med de mest alvorlige problemer der blev fundet
- at producere en liste med de problemer som skal udbedres inden næste måneds test

Brug cirka en time sammen med de observatører der kan deltage. Er der nogen som observerede, men som ikke kan være med i afrapporteringen, så skal ordstyreren indsamle deres noter fra testene. På den måde indgår de i evalueringen alligevel.

Det er vigtigt at fokusere på de mest alvorlige problemer først. Steve Krug nævner at det vil fremgå tydeligt af testen hvilke der er mest kritiske. 

Bearbejd listen hvor man skriver forslag til fixes på problemerne. Dette fortsætter man med indtil det vurderes at der ikke kan bruges flere ressourcer på at rette problemer for den næste måned (også selvom der er flere punkter på listen)

Efter afrapporteringsmødet skrives der en email der kort opsummerer dagen aktiviteter:
- hvad der blev testet
- listen af opgaver som test-deltagerne gennemgik
- listen af problemer som der bliver fikset på baggrund af dagens observationer

# Refleksion
Dette indlæg dækker overordnet kapitel 8-9-10. Jeg har undladt flere detaljer, og kan kun opfordre til at man selv finder en kopi af bogen og går igang. Steve Krug har mange gode betragtninger med undervejs, så jeg føler at man får meget god viden med videre.

Min umiddelbare vurdering er at denne type test er nem at lære, men svær at mestre. De fleste af koncepterne som Steve beskriver er jo relativ simple i sig selv, men det hele indgår i en helhed som bliver kompleks. Der er en hvis balance i den måde Steve Krug beskriver hvordan man skal udføre og bearbejde testdata på. Der er en bevisthed om at man ikke kan nå at komme helt til bunds i alle fejl. Selv hvis man kunne finde alle problemstillinger, kan det næbbe betale sig at bruge tid på at rette alt. 

Der lægges vægt på at fokuse på de problemer der er mest kritiske - hvis de ikke bliver løst først, vil de altid eksistere. Det betyder dog ikke at udviklere/andre ikke må rette "de små" problemer, hvis de støder på noget under testen. Eksempelvis stavefejl, som nemt kan rettes.

SK skriver også meget om hvordan man håndterer test-deltager: Dels hvordan man undgår at påvirke dem, og dels hvordan man opfordrer dem til at fortælle så meget som muligt. Kommer man til at påvirke, eller får man ikke spurgt ind på det rigtige tidspunkt, kan det betyde en dårlig, eller endda ødelagt test. Dette er igen med diciplin der på overfladen er simpel, men i virkeligheden er en kompleks størrelse da mennesker er så forskellige.
