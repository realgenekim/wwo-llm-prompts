

You are the world's best business analyst, operations researcher, and software architect.

Gene Kim (co-author of "Phoenix Project," "DevOps Handbook, etc.) and Steve Spear (author of "High Velocity Edge" and "Decoding the DNA of the Toyota Production System") wrote a new book together: "Wiring the Winning Organization."

They describe three mechanisms of Slowification, Simplification, and Amplification that explains performance.

- **Slowification**: problem-solving is pulled back from fast-paced operations to more deliberate planning and practice.  By doing so,
  problem-solving is more deliberate, less prone to error, safer, and can be practiced.

- **Simplification**: problem-solving is broken down into smaller, functional, and stateless services and modules.
  By having a more modular system architecture, problems become easier to manage and troubleshoot.
  Breaking down complex problems into simpler components is a key aspect of Simplification.  There are three techniques of Simplification:

    - Incrementalization: partitions problems into smaller increments (e.g., Agile, incremental development)
    - Modularization: partitions problems into smaller modules, which can be worked on independently (e.g., microservices, service oriented architectures, domain driven design)
    - Linearization: partitions proboems within sequential workflows. This makes the problem easier to solve by reducing the number of interacting factors that have to be considered simultaneously.
      This reduces the number of people whose creative collaboration has to be coordinated. In other words, linearization does for sequential processes what Modularization does for parallel processes.   (e.g., Kanban, Lean, Six Sigma, Theory of Constraints, Toyota Production Process, assembly lines, deployment automation, continuous integration, test, and deployment)

- **Amplification**: Describe how the scenario makes it obvious there are issues and draw attention to them early.
  By doing so, the problem can be addressed before it becomes a major issue.

In a bulleted list, for each of the four characteristics of Sequentialize, Standardize, Stabilize, Self-Synchronize, please give three examples found in the case study of each characteristic.

<more-info-on-linearization>

Linearization


The last technique of simplification is linearization, which partitions problem-solving within sequential workflows. This makes the problem easier to solve by reducing the number of interacting factors that have to be considered simultaneously. It also reduces the number of people whose creative collaboration has to be coordinated. In other words, linearization does for sequential processes what modularization does for parallel processes.
Linearization has four elements:

� Sequentialization: All system outputs are generated along the single, dedicated, non-looping pathway of connected activities.* This is how system outputs take form (e.g., products, services, or information), from the start through the finish of their generation to their delivery.�
� Standardization: This is comprised of (1) the explicit and prespecified definition of what a subsystem is meant to deliver in terms of the output it is meant to generate, (2) the sequence of steps to be performed to generate that output (the pathway), (3) the nature of the exchanges or handoffs over the connections linking one step to the next, and (4) the methods by which work is done at each individual activity.�
� Stabilization:� Triggers are built into outputs, pathways, connections, and activities so when a surprise inevitably arises (because of delays, defects, difficulties, etc.), the surprise (i.e., problem) is seen and resources (especially people�s time and attention) are swarmed onto the problem. This is to contain the problem, so its duration is curtailed and its ability to escape and have systemic effects is diminished.�
� Self-synchronization: The production system can automatically selfpace without elaborate scheduling systems.

Sequentialization creates clarity about what activities are upstream and downstream of each other. Standardization makes clear what is exchanged one step to the next and makes signaling possible when intermediate inputs are needed and outputs are done. Stabilization ensures that surprises, one step to the next, are minimized. So, changes at one step are communicated directly to supporting and supported steps.* In short, a workflow is fully linearized when the four elements of sequentialization, standardization, stabilization, and self-synchronization (the �4 S�s�) have been employed.
Linearization solves a common problem in the design of Layer 3 (social circuitry), such as the examples in Chapter 2 of Steve�s daughter and Gene�s father becoming �stuck� in a hospital system, the valve in the oil refinery, or the checkbox in the mobile phone service provider. What could be sequential work is instead assigned and scheduled across different functions or departments.
In the production of automobiles, work is divided into styling, design, and production (and subdepartments like body, trim, interiors, power train, etc.), even though a single car has elements of all of those.
In healthcare, work is divided into medical specialties, such as cardiology, pulmonology, infectious diseases, and psychiatry, and the work of doctors is separated from nurses and technicians, even though patients may have multiple maladies and need the attention from all those specialists to occur in an integrated fashion.
Ideally, regardless of context or industry, there should be coordinated collaboration among those whose work depends on or is depended on by other specialists. However, too often, coordination is done only �at the top of the silo,� as shown in Figure 7.4. This makes collaborative problemsolving less effective due to the loss of frequency, speed, and detail with which collaboration can occur.

* This is an attribute of �pull systems,� just in time, etc., which is the antithesis of using schedules and expediting. Likewise, the concept of value streams from Lean captures many of these concepts.



Despite this, you�ll likely find much of linearization to be familiar. This is because linearization draws upon and incorporates many of the key concepts from the study of management going back hundreds of years. In this section, we will present some of the most prominent examples of linearization.
Some readers might recognize linearization as the thesis behind high performance in Dr. Wickham Skinner�s �The Focused Factory.�18 There, he explained the difference in performance between the many manufacturing plants that had the common experience of adding significant production volume and product variety but only a few having superior performance across many metrics: quality, productivity, etc.
Skinner explained that the superior plants had leaders who had chosen to create �factories within factories.� There were separate production lines




Chapter 7: Simplification: A Theory Overview	145

dedicated to some subset of the facility�s overall production. Coherence was achieved because individual functions committed resources to each line�s pathway of connected activities.*
Once coherence was achieved, each line was decoupled from the other lines. This enabled sequentialization, dedicating resources to specific activity steps, so alignment or arrangement of resources didn�t have to be repeatedly reconfigured. Decoupling and sequentialization made it easier to create alignment around objectives, create more opportunities to build competency around relevant tasks, and so forth. That made standardization around specialization easier too.
In contrast, leaders of the poorer-performing plants had chosen a more job-shop approach. Subgroups of people and capital equipment were not committed to producing a subset of the production mix. Therefore, �jobs� bounced between different departments (creating a scheduling problem) or left one set of processes queued for the first available machine at the next process.
As a result, moving work required either complicated and sophisticated scheduling systems or queues to hold intermediate products as they waited for machines and machinists to become available. Machine operators were often surprised by what work was coming next and by where it was going. In short, without sequentialization of workflows, creating standards was difficult. There was more need to invent on the fly or improvise.
The impact of nonlinear systems affects the performance of people within the system and the performance of the system as a whole. For instance, Don Reinertsen has written about how scheduling and queues in both manufacturing and software development led to �increased cycle time, delayed feedback, constantly shifting priorities, and status reporting�[which] hurt economic performance.�19 This happens, at least in part, because nonlinearized flows need considerably more Layer 3 coordination. In contrast, according to Reinertsen, �[Linearized] factories do far less status reporting than traditional factories.�A traditional factory with a


* This is an example of functions providing resources to the lines rather than the lines sending work to the functions. In software, there is a similar philosophy: send work to the teams instead of sending teams to the work.




146	Wiring the Winning Organization

16-week lead time may use 60 move transactions�.A [linearized] factory making the same product might do two transactions, one to start the work order and the other to close it out.�20

</more-info-on-linearization>


<hp-case-study>
The case study of HP’s LaserJet Firmware division, led by Gary Gruver, showcases the transformative impact of continuous integration in a large-scale software development environment. The division, with a 400-person team spread across the US, Brazil, and India, faced sluggish progress, managing only two firmware releases per year, with a mere 5% of their time dedicated to new features. The rest was consumed by technical debt maintenance, including multiple code branches and manual testing...

...Gruver's goal was to boost innovation time tenfold via continuous integration, trunk-based development, automated testing, a hardware simulator, and a unified architecture for all printer firmware. Previously, unique firmware builds for each model complicated development...

...After four years, a single codebase was developed on trunk for all 24 HP LaserJet product lines. Despite initial skepticism, engineers adapted to the trunk-based approach, which mandated robust automated testing. Initially, manual testing took six weeks...

...To enable automated firmware testing, heavy investments were made in printer simulators, culminating in a farm of two thousand simulators. The CI system executed a suite of automated tests on trunk builds. Development halted when the deployment pipeline broke, ensuring immediate fixes...

...The automated testing regime included unit tests, and automated testing at various intervals, with full regression testing completed daily. This led to:

- A transition from one to up to fifteen daily builds
- The use of compile flags for feature toggling
- An increase from twenty to over a hundred daily commits
- Developers editing up to one hundred thousand lines of code daily
- A reduction in regression test times from six weeks to one day

...The results were remarkable: innovation time rose from 5% to 40% of developers' time, development costs dropped by 40%, development programs increased by 140%, and costs per program fell by 78%...

...Gruver's experience underlines continuous integration as a key practice for efficient work flow in software development, despite its controversial nature... The rest of the chapter delves into the implementation of continuous integration and addressing its criticisms.
</hp-case-study>
