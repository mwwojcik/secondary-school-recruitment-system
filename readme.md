## Spis treści

## Intro

![](img/pupils.png)

Jest to projekt systemu wspomagającego rekrutację uczniów do szkół ponadpodstawowych. Proces jest całkowicie wymyślony i ma niewiele wspólnego
 z rzeczywistością, umożliwia jednak realizację celu jakim jest doskonalenie praktycznych umiejętności w zakresie
  eksploracji dziedziny przy użyciu technik zaczerpniętych z Domain Driven Design.
  
Nasz  miniprojekt samorozwojowy realizowaliśmy w kilkuosobowym zespole:

* Ruslan Pidhainyi - todo link
* Tomek Przybylski - todo link
* Mariusz Olbryś - todo link
* Gabriel Kurzac - todo link
* Mariusz Wójcik - todo link


Spotykaliśmy się na cotygodniowych, dwugodzinnych sesjach online na których realizowaliśmy kolejne etapy eksploracji dziedziny przy użyciu techniki
 Event Stormingu . 
 
 Naszym przewodnikiem była pozycja absolutnie zasadnicza:
 [Introducing EventStorming-Alberto Brandolini](https://leanpub.com/introducing_eventstorming). 
 Podczas sesji staraliśmy się czerpać z niej całymi garściami...
 
 Wykorzystaliśmy narzędzia umożliwiające nam pracę zdalną: 
 
 * Google Meeting
 * [miro.com](http://www.miro.com)

   
## ETAP I - Eskploracja domeny - Big Picture

Rozpoznawanie dziedziny rozpoczyna się od wypracowania sobie jej ogólnego, aktualnego obrazu. Służy temu pierwsza faza eksloracji zwana **Big Picture**.  
Jej celem jest zobrazowanie aktualnego przebiegu procesu biznesowego oraz identyfikacja ryzyk, niedogodności i problemów które w nim występują.   

Składa się na nią kilka faz:

* Chaotyczna eksploracja
* Oś czasu
* Identyfiacja aktorów i systemów emitujących zdarzenia
* Opowieść (od początku do końca)
* Retrospektywa (analiza od końca do początku)
* Identyfikacja ryzyk


### Notacja

![Introducing EventStorming-Alberto Brandolini](img/event-storming-symbols.png) 

*źródło: [Introducing EventStorming-Alberto Brandolini](https://leanpub.com/introducing_eventstorming)*

Na etapie Big Picture najważniejsza jest pomarańczowa karteczka symbolizująca Zdarzenie - coś ważnego co zaszło  w procesie.

### Chaotyczna eksploracja
Na tym etapie każdy z uczestników warsztatu umieszczał zdarzenia które wydawały mu się zasadne. Był to proces bardzo chaotyczny, zdarzenia się dublowały, 
powstawały bez konsultacji z innymi uczestnikami. 
 

<a href="https://raw.githubusercontent.com/mwwojcik/secondary-school-recruitment-system/master/img/ES-training-big-picture-chaotic.jpg" target="_blank
">Pokaż</a>

![](img/ES-training-big-picture-chaotic.jpg)

### Oś czasu

Na tym etapie następuje porządkowanie zdarzeń - nadanie im chronologii. Czasami jest to bardzo trudne, wtedy dopuszczone są techniki wspomagające, jedną z nich
jest użycie *Pivotal Events*. Są to zdarzenia, które wydają się kluczowe. Inne zdarzenia są porządkowane względem nich, po zadaniu pytania czy to zdarzenie
 stało się wcześniej , czy później względem najbliszego PE.
 
 Wynik :

<a href="https://raw.githubusercontent.com/mwwojcik/secondary-school-recruitment-system/master/img/ES-training-bigpicture-timeline.jpg" target="_blank
">Pokaż</a>

![](img/ES-training-bigpicture-timeline.jpg)

### Identyfiacja aktorów i systemów emitujących zdarzenia

Na tym etapie następuje próba identyfikacji osób i systemów biorących udział w procesie. 

<a href="https://raw.githubusercontent.com/mwwojcik/secondary-school-recruitment-system/master/img/ES-training-bigpicture-actors.jpg" target="_blank
">Pokaż</a>

//todo opis (cel i obrazek)
![](img/ES-training-bigpicture-actors.jpg)


### Opowieść (od początku do końca)

### Retrospektywa (analiza od końca do początku)

### Identyfikacja ryzyk 


<!--
## Domain exploration
### EventStorming - general assumptions

#### Phase 1 - Big Picture
It has the character of a workshop aimed at discovery **hot spots** . 
Hot spot can mean:
* lack of expert knowledge (regarding this part of the process)
* uncertainty
* risk

The modeling space is **timeline** .

##### Stage 1 - finding unordered events
Workshop participants search for events that are important in their process.   At the beginning, no chronology is allowed. 
 
##### Stage 2 - ordering on the timeline
At this stage, the events are arranged in chronological order. 

##### Stage 3 - reversing the narrative
In this step the consistency check is performed. Participants analyze events from the end to the beginning and reflect on what must happen before .

##### Stage 4 - identyfing actors
Workshop participants successively analyze the events and identify their sources. The event source can be an actor or other system. 

##### Stage 5 - identyfing hot spots
In this step, hot spots are identified, i.e. places that are undefined and require special attention

#### Phase 2 - Process Modelling
The goal is to implement future that solve a specific problem. The modeling space is **timeline** . At this stage, workshop participants identify autonomous 
fragments of the process which are the basis for isolating separate Bounded Context. At this stage, workshop participants identify autonomy fragments of the process, 
which are the basis for the identification of separate Limited Contexts, and look for the possibility of process optimization.  

Diagrams are detailed, new, more precise elements are introduced. Finally, aggregates are distinguished.
-->

<!--
### Secondary School Recruitment System - domain exploration - Big Picture 

#### Events

<a href="https://raw.githubusercontent.com/mwwojcik/secondary-school-recruitment-system/master/img/recruiment-big-picture-events.png" target="_blank">Show
 picture
</a>

![](img/recruiment-big-picture-events.png)

#### Events arranged in chronological order

<a href="https://raw.githubusercontent.com/mwwojcik/secondary-school-recruitment-system/master/img/recruiment-big-picture-events-timeline.png" target="_blank">Show
 picture
</a>

![](img/recruiment-big-picture-events-timeline.png)
-->