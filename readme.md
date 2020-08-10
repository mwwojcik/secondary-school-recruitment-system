## Table of contents

## Domain description
![](img/pupils.png)


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
In this step the consistency check is performed. Participants analyze events from the end to the beginning and reflect on what must happen before the event
 will happen.

##### Stage 4 - identyfing actors
Workshop participants successively analyze the events and identify their sources. The event source can be an actor or other system. 

##### Stage 5 - identyfing hot spots
In this step, hot spots are identified, i.e. places that are undefined and require special attention

#### Phase 2 - Process Modelling
The goal is to implement future that solve a specific problem. The modeling space is **timeline** . At this stage, workshop participants identify autonomous 
fragments of the process which are the basis for isolating separate Bounded Context. At this stage, workshop participants identify autonomy fragments of the process, 
which are the basis for the identification of separate Limited Contexts, and look for the possibility of process optimization.  

Diagrams are detailed, new, more precise elements are introduced. Finally, aggregates are distinguished.

#### The picture that explains everything
This nice picture comes from [Introducing EventStorming-Alberto Brandolini](https://leanpub.com/introducing_eventstorming).

![Introducing EventStorming-Alberto Brandolini](img/process-modeling-events.png) 


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