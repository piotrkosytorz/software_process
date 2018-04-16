# Software Process: Assignment 1

- See your annotations for the papers/sources you have to read (check blackboard assignments) for:
    1. Methods (first assignments),
    1. Power,
    1. Planning, also explore the list of perspectives on planning.

- Make an overview that shows the differences and similarities of the methods: Scrum, RUP, XP, Waterfall and show what DevOps changes to this .
- Which best practices are missing in the methods?

# Papers/sources

## Methods

### Waterfall
    
- Royce, W. W. (1970). Managing the development of large software systems. Electronics, 26(August), 1–9. https://doi.org/10.1016/0378-4754(91)90107-E

Waterfall is a very general project management methodology with a sequential structure of actions. According to Royce, the methodology can be described as a sequence of the following phases:

1. System requrements
1. Software requrements
1. Analysis
1. Program design
1. Coding
1. Testing 
1. Operations

Royce draws attention to two very important aspects of waterfall methodology in its starting phases: documentation and project knowledge. As he says, *During the early phase of software development the documentation is the specification and is the design.* Documentation is thus the backbone of project management. The second thing Royse mentions is priject knowledge: there should be at least one person that has a deep understanding of the whole system. This knowledge must be the exhaustively put into documentation. Each proejct phase must deliver appropriate documetnation.

Waterfall as methodology sets up a clear structure in project management. Each proceeding phase is a logical result of the previous one. 

Waterfall seems like a good solution to projects which requirements can be fully detemined from the beginning. Unfortunatelly, there is very little (or actually none) space for requirements change during the project. Rouce gives examples of systems that take 12 months to develop. Due to the fact that in waterfall, proceeding from one phase another requires an extended amount of work and documentation, every change in requirements would reset the whole process. 

Waterfall could be a good fit for single-domain highly specialized products.

### Scrum
    
- [https://www.scrum.org/resources/what-is-scrum](https://www.scrum.org/resources/what-is-scrum)
- [The scrum guide](https://www.scrumguides.org/docs/scrumguide/v1/scrum-guide-us.pdf)

According to [The Scrum Guide](https://www.scrumguides.org/docs/scrumguide/v1/scrum-guide-us.pdf), *Scrum is a framework for developing and sustaining complex products*.

Scrum consists the following elements:

- Product: *what has to be produced*
    - Backlog: *list of elements that will eventually collectivelly produce the end product*
- Sprint: *a sub-project limited by time with a precisely determined output*
    - Planning
    - Backlog: *list of tasks in current spring (a subset of product backlog)*
    - Review: *analysis of the meaning and fitness of the current sprint in relation to the whole product*
    - Retrospective: *analysis of what heve we done wrong, what can we do better next time*
- Scrum team
    - Product Owner: *The guy who pushes*
    - Development Team *The blue collar workers*
    - Scrum Master: *Judge in the ring: makes sure that there is a healthy relationship between the product owner and the development team.*
- Daily scrum: *a 15-minute time-boxed daily meeting/discussion*
- Increment: *A finished spring that builds up the final product.*

Scrum introduces a lot of flexibility in project management and development. The work is divided into manageable chunks. There is always someone who knows what has to be achieved in the project (Product Owner), and someone who takes care of the team and makes sure that the rules are being played fair (Scrum Master). 

Scrum can be applied to both: big and small projects. It allows project adaptation, thus change in requirements is taken into account.

### Agile
- [http://agilemanifesto.org/](http://agilemanifesto.org/)

Agile manifesto:

- **Individuals and interactions** over processes and tools
- **Working software** over comprehensive documentation
- **Customer collaboration** over contract negotiation
- **Responding to change** over following a plan

Agile puts even more pressure on the value of human and practical aspects of software development, rather than of a formalized path to follow.

### RUP
- [https://en.wikipedia.org/wiki/Rational_Unified_Process](https://en.wikipedia.org/wiki/Rational_Unified_Process)
- [RUP on airbrake](https://airbrake.io/blog/sdlc/rational-unified-process)

Rational Unified Process is another software development framework with another look at the problem of project development. The main focus of the framework is to ensure that everyone in the team knows what to do, therefore it is based on three elements: 

- Roles (who)
- Work products (what)
- Tasks (how)

Shortly: **Who** produces **what**, and **how** does he do that?

On the other hand, RUP tries to apply the best of both: Waterfall and Scrum. It consists of four phases:

- Inception,
- Elaboration,
- Construction,
- Transition,

where all six "engineering disciplines" are present, but with different intensity according to different phases. 

Within all the phases RUP introduces international development.

RUP seems like a good solution for big and highly skilled teams of professionals within big organizations (like IBM itself). 

### Extreme Programming 
- [http://www.extremeprogramming.org/](http://www.extremeprogramming.org/)
- [https://en.wikipedia.org/wiki/Extreme_programming](https://en.wikipedia.org/wiki/Extreme_programming)
- [link on agile alliance](https://www.agilealliance.org/glossary/xp/#q=~(filters~(postType~(~'post~'aa_book~'aa_event_session~'aa_experience_report~'aa_glossary~'aa_research_paper~'aa_video)~tags~(~'xp))~searchTerm~'~sort~false~sortDirection~'asc~page~1))

Extreme Programming is an Agile process, that focuses on:

- delivering software (features) as soon as possible,
- testing/gaining feedback from the customers as soon as possible,
- delivering what you need when you need it, and only when you need it,
- staying flexible to respond to changing requirements and technology,
- enabling the teams to self-organize around the problem to solve it as efficiently as possible.

Extreme programming seems like it can be successfully applied in teams that do not require highly skilled programmers. Start-up projects could benefit from this approach, as there the request for requirements change is high. XP, however, does not seem as a solution for big and highly specialized projects.  

### DevOps
- [https://aws.amazon.com/devops/what-is-devops/](https://aws.amazon.com/devops/what-is-devops/)
- [https://en.wikipedia.org/wiki/DevOps](https://en.wikipedia.org/wiki/DevOps)

According to Wikipedia: *DevOps (a clipped compound of "development" and "operations") is a software engineering culture and practice that aims at unifying software development (Dev) and software operation (Ops). The main characteristic of the DevOps movement is to strongly advocate automation and monitoring at all steps of software construction, from integration, testing, releasing to deployment and infrastructure management. DevOps aims at shorter development cycles, increased deployment frequency, and more dependable releases, in close alignment with business objectives.* 

DevOps changes the way teams of specialists cooperate with each other. This results in process change. 

According to Amazon, the following are the DevOps best practices:

* Continuous Integration
* Continuous Delivery
* Microservices
* Infrastructure as Code
* Monitoring and Logging
* Communication and Collaboration

#### What does DevOps change to Waterfall, Scrum, Agile, RUP, and XP?

DevOps introduces automation of repeatable processes, strong decoupling of projects and greater insight in software performance and software process. Linus Torvalds in his talk about Git at Goole [link](https://www.youtube.com/watch?v=4XpnKHJAok8) said, that the speed of your tools (processes) changes, then the way you use them changes as well. To me this is a great paraphrase of what DevOps does to software development methodologies - it changes the way we apply them. The focus is not so much laid on the interfaces between different phases of different methodologies, but rather on the core problems of software development and software quality itself. 

### Methods trade-off table

| Method/characteristic      | Waterfall | Scrum | Agile | RUP    | Extreme Programming | DevOps |
|----------------------------|-----------|-------|-------|--------|---------------------|--------|
| Project time open/closed   | closed    | open  | n.a.  | closed | open                | open   |
| Self-organization | no        | yes   | yes   | no     | yes                 | yes    |
| Transparency               | no        | yes   | n.a.  | yes    | yes                 | yes    |
| Inspection                 | no        | yes   | n.a.  | yes    | yes                 | yes    |
| Adaptation                 | no        | yes   | yes   | yes    | yes                 | yes    |
| Iteration                  | no        | yes   | yes   | yes    | n.a.                | yes    |
| Suitable for highly specialized projects?  | yes | yes | n.a. | yes | no | yes |

## Power

- **Gagné, Marylène, and Edward L. Deci. "Self‐determination theory and work motivation." Journal of Organizational Behavior 26.4 (2005): 331-362.**
	
	SDT (self determination theory) as a theory of work motivation. The article describes how intrinsic and extrinsic motivation are to be found in work settings and how the second one can influence the first one.
	
- Halevy, Nir, Eileen Y. Chou, and Adam D. Galinsky. "A functional model of hierarchy: Why, how, and when vertical differentiation enhances group performance." Organizational Psychology Review 1.1 (2011): 32-52.
- Simons, Robert. Control in an age of empowerment. Harvard Business Review Press, 2008.
- Martinez, Jon I., and J. Carlos Jarillo. "The evolution of research on coordination mechanisms in multinational corporations." Journal of international business studies 20.3 (1989): 489-514.
- Lunenburg, Fred C. "Compliance theory and organizational effectiveness." International journal of scholarly academic intellectual diversity 14.1 (2012): 1-4.
- [Papers/Mintzberg.md](Papers/Mintzberg.md)

## Planning
- De Geus, Arie P. Planning as learning. March/April: Harvard Business Review, 1988.
- Evbota, Felix, Eric Knauss, and Anna Sandberg. "Scaling up the planning game: Collaboration challenges in large-scale agile product development." International Conference on Agile Software Development. Springer, Cham, 2016.
- Landry, Jeffrey P., and Rachel McDaniel. "Agile Preparation Within a Traditional Project Management Course." Proceedings of the EDSIG Conference. 2015.
- [https://hbr.org/1994/01/the-fall-and-rise-of-strategic-planning](https://hbr.org/1994/01/the-fall-and-rise-of-strategic-planning)
- [https://juliagalef.com/2017/02/19/can-we-intentionally-improve-the-world-planners-vs-hayekians/](https://juliagalef.com/2017/02/19/can-we-intentionally-improve-the-world-planners-vs-hayekians/)
- [https://quoteinvestigator.com/2017/11/18/planning/](https://quoteinvestigator.com/2017/11/18/planning/)
- [https://en.wikipedia.org/wiki/Dynamic_capabilities](https://en.wikipedia.org/wiki/Dynamic_capabilities)
- [https://leanpub.com/leprechauns/read#leanpub-auto-chapter-2-the-cone-of-uncertainty](https://leanpub.com/leprechauns/read#leanpub-auto-chapter-2-the-cone-of-uncertainty)

### Perspectives on planning:
* Planning is about getting the right (and sufficient) resources and conditions (including agreements and contracts) to get the job done.
* Planning is about getting the job done with the resources that are available and within the set constraints.
* Planning is about breaking the work up into smaller chunks and assigning these to different responsible people.
* Planning is about managing dependencies
* Planning is about communication and coordination
* Planning is about setting up an approach that will eventually get the work done. In many cases, you have to **learn** how to do the project. Throughout the project, you will focus on getting all the knowledge you need. New knowledge might make you reconsider what type of resources you need and what they should focus on. It's key to not have all your resources committed making change harder.
* Planning is about focusing on getting the things done that have the highest priority / are most important.
* Planning is about preventing waste: doing as much as possible only those things that you really need to do
* Planning is about thinking in scenarios what could happen and what could go wrong and making sure you can deal with those scenarios.
* Planning is about dealing with your stakeholders, expectation management and communication. Enabling others to coordinate with your project.
* Planning is on different levels of abstractions, on different time scales, with a different order of impact.