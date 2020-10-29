# Business Process Modeling  

A visual way to represent how an organisation performs work and services  

1. Capture processes  
2. Provide visual representation - who does what, and in what order  
3. Identify what's needed  

**Business models** represent *current* state, define *future* state, and identify *gaps*  

**Actor**  
A person, department, system, or external entity to the organisation  

**Benefits**  
1. Ensure understanding of how an org runs, performs, and relates to the outside world.  
2. Identify areas not well understood.  
3. Clarifies responsibilities across the whole process.  
4. Identify and break down complex business processes.  
5. Helps with training documentation.  
6. Captures interrelationships between people, processes, activities, and systems.  

### Most commonly used tools:  

##### Context Diagram  
The context diagram provides the high level framework and interaction of an org. The context diagram depicts the org as a circle. The external entities that connect to the area or system being analysed, represented by boxes. And lastly, the relationship of interactions between the org and the external entities are shown as the arrows. Our focus here are the interrelationships and activities that are either initiated or needed by the org.  

##### Functional Flow Diagram  
The functional flow diagram is a simple model showing the functional areas or stakeholders internally to our org and how they interact in a logical overall flow of work. The functional flow diagram always starts with a stakeholder, usually the customer or another entity external to the org, initiating a transaction. Stakeholders and internal functional areas are captured in the ovals. Then, the appropriate relationships and workflows are drawn between these stakeholder groups.  

##### Cross Functional Flow Diagram  
A way to capture and sequentially display the activities that are performed. Cross-functional flow diagrams also referred to as **activity diagrams**, and **swimlane diagrams**. The stakeholders also referred to as actors in the process. These diagrams organise activity sequences that displays the process in the context of the actors responsible for performing the work. This added structure makes it very easy to read and quickly identifies the individual actors work as well as cross-functional interactions needed. These diagrams are very effective in visually sharing a process is performed from start to finish, and what each and every stakeholder or actor needs to perform to enable completion of the activity.

##### Process Flow Charting  
These traditional process flow models show the sequential flow of activities, decision points, and other interactions. Process Flow models are used as a way to capture the step by step procedures and activities performed by an individual actor. These processes describe who and what has to be involved in fully responding to an event, or how people in the enterprise collaborate to achieve a goal. These process workflow models are the low level detail not represented in the cross functional swimlane models.

## UML and BPMN  
Internationally recognised modeling standards  

**UML** - Unified Modeling Language  
**BPMN** - Business Process Modeling Notation  

### Context Diagram  

- provides a visual view  
- high level  
- serves as a checklist  
- at a glance tool  

<img src="https://online.visual-paradigm.com/servlet/editor-content/knowledge/system-context-diagram/what-is-system-context-diagram/sites/7/2019/08/system-context-diagram-example-hotel-reservation-system.png"><img>

 --> boxes show external entities  
 --> arrows show interactions coming into and from the organisation  
 
 - understand relationships  
 - understand functions  
 - explain scope  
 
Context - how a business area interacts with the world  
Actor - a person, department, or system directly involved in what is being analysed  
External entity - a person, department, or system not being analysed  
 
Research - ask colleagues, run workshops, search intranet  
Start with a single page - keep it high level and simple  
 - start with main entity (in a circle)  
 - add external stakeholders (in boxes)  
 - connect relationships with arrows  

### Functional Flow Diagram  

- shows each functional area or stakeholder internal to the organisation  
- shows how they interact in the logical overall flow of the work
- effective in showing new users and executives the conceptual detail of how, internally, information, data and activities pass between the different functional areas  
- useful in targeting specific audiences when analysing detail  
- ensures all areas are touched upon before documenting the cross-functional flow diagram  

--> should focus on a single interaction between the external entity and the organisation  
--> provide a quick overview  
--> identifies improvement opportunities  

<img src="https://static-cdn.imageservice.cloud/4125645/understanding-the-purpose-of-the-functional-flow-diagram.jpg"><img>

- keep it uncluttered  
- start with external entitiy whose relationship you are looking to analyse  
- context diagram within a context diagram  
- choose a interaction to focus on and list the involved stakeholders  
- run high-level process workshops  

- circle for functional areas  
- arrows for relationships  
- label arrows to identify what is exchanged  

### Cross Functional Flow Diagram (swimlane)  

- capture and order activities performed by various stakeholders  
- tell the story from start to end - illustrates a flow of events (how they cross over between the different functional areas)  

<img src-"https://d3n817fwly711g.cloudfront.net/blog/wp-content/uploads/2015/11/Cross-functional-flowchart.png"><img>

- an 'as-is' CFFD identifies and breaks down exisiting complaex business processes - identifying unecessary routing of work  
- identifies inefficiencies  
- if the number of steps looks overwhelming they can be broken down into subprocesses  
- swimlanes clearly show where one task ends and the next begins  
- each actor is assigned a swimlane  
- shows who is involved in the end to end process  

**Flowchart symbols** 
- circle = terminator (start and end points)  
- rectangle = process box  
- parallel lines = subprocess box (plus symbol)  
- diamond = decision symbol (where a decision has to be made before moving on - outcome will split the flow of events)  
- arrows = connectors (direction and order the activities take place)  

- start with a trigger even in a circle  
- from the trigger map out each activity using process boxes and connecting them with arrows in the direction the flow needs to go  
- 'what functions need to occur from start to finish to achieve the fasted result' - the happy path (main path)  
- clearly label each activity with a verb noun phrase (take payment)  
- Alternate flows/exception flows - challenges and unforseen problems ocur and prevent a function from being completed  
- Alternate flow is where a transaction continues via an alternate path, rejoining the original path to complete the transaction after the alternate process is complete  
- Exception flows are when a process comes to a complete stop. A completely different process or trigger is required to complete the activity - create another swim lane diagram to capture the handling of this exception  
- have the diagram validated by the actors - walk them through  

### Process Maps (Flowchart Diagram)  

- documents the flow of activities performed by a single actor at the lowest level of detail  
- used for 'as-is' and future 'to-be'  
- breaks down complex precesses and analyse inefficiencies  
- KRAC (Keep - Remove - Add - Change)  
- single source of truth - what needs to be done  
- support the creation of test scripts  
- ensure consistent outcome  

- overlay as-is with tp-be to see GAPS and set requirements to close them  

- impact assessment - identify what has changed and analyse the impacts to existing functional areas  
- create instructional guides, training manuals - identify the amount of training required  
- isolate each activity - can be taught, assessed, refined, and updated  

<img src="https://m.foolcdn.com/media/the-blueprint/images/Process_Mapping-01-Approvals.width-800.png"><img>

**Features**  
- no interaction with other functional areas (no swimlanes -dealing with a single actor)  
- flows in any direction (start in top left corner)  
- uses standard symbols (process box, decision diamond, arrow/connector)  
- start point (trigger) and end point  

- should trace back to cross-functional flow diagrams  
- never have more than one step in each box  

### Which diagram to use when  

**Contaxt Diagram**  
- how your organisation fits in the big picture and relates with the outside world  
- captures the relationships, input, and outputs that help your organisation understand what is needed by these external entity relationships to deliver products and services to customers  

**Functional Flow Diagram**  
- shows a number of functional areas internal to your organisation, and how they interact with the customer, being an external entity and each other  

**Cross-Functional Flow Diagram**  
- how the flow of work moves across the functional areas of your organisation  
- contains the complete end-to-end process of a single transaction or interaction from the initial customer trigger through to the delivery of a service or product  

**Process Map**  
- take the subprocesses that are in our cross-functional flow diagram and expand them into the finest level of detail in what you now know as flowchart process maps  

Understand your objective  
- what is the area of focus  
- what already exists  
- who is the end user  
- how will the information be used  
