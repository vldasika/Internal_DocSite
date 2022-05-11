Feasibility

Identify the product/project investors, business sponsor, and key stakeholders.
Establish economic model with costs and benefits spanning average and best/worst cases.
Write a clear mission and vision statement.
Requirements

Document requirements for Minimum Viable Product (MVP).
Architecture

Visualize the solution architecture - High Level Design Document.
Design

Consistency — use consistent naming conventions, code styles, etc.

Database

Is ACID necessary? Then perhaps SQL/RDBMS. Or does scalability suggest NoSQL?
Visualize logical entities and their relationships using diagrams.
Use primary keys and foreign keys for referential integrity.
Use default and check constraints for column data integrity.
Use indexes for large tables (1M+) and partitions for larger data sets (1B+).
Use NoSQL, document oriented databases for very large data sets (1T+).
Avoid cursors, triggers, and dynamic SQL. Use them sparingly and consciously.
Secure access through groups and roles.
Plan for growth and disaster recovery. Stress test for performance and reliability.
Artifact Control

Manage source code, binary references, and documentation using Version Control System.
Prefer GIT; all other VCS systems are inferior.
Secure access to artifacts through groups and roles.
Plan for several people working on system over time, perhaps at same time.
Source code is not owned by 1 person; it is owned by the team.
Quality Control

Code defensively. Check parameters. Use assertions. No broken windows.
Are there tests for Correctness? Integration? Performance? Security? UX?
Define automated unit tests such as MSTest, NUnit, jUnit, or RUnit.
Assign manual beta testing driven by checklists to independent group of power users.
Review designs before coding.
Review code before production deployment.
Devops

Where will the solution run? desktops? Mobile? On Prem? Cloud?
How will you deliver system updates and changes over time?
Maintain separate environments for Development, Test, and Production.
How do you log system activity especially errors and end-user usage?
Automate builds and deployments from Development through Production using VSTS, Chef, Octopus, PowerShell, bash, etc.
Support

How will users contact you regarding features and defects?
Track past, present, and future work in an online backlog.
Use JIRA, VSTS, or a similar system. Avoid spreadsheets and email.
Customers

Delight users. Under promise and over deliver.
Prioritize system feedback from power users who influence others and are passionate.
Key users should be part of project and product teams and available — onsite, daily.
Peopleware

Align team member interests with work assignments.
Create workspaces that support thoughtful, focused, un-interrupted work. Avoid open offices.
Establish accountability and responsibility for decisions by making people put skin in the game.
Take time to celebrate achieving milestones and performing post-mortems.
Metaphors

Cone of uncertainty — explore risk areas and learn to reduce uncertainty over lifecycle.
Triangle of constraints — cost, scope, and quality. Pick 2 out of 3; it’s tough to have it all.
Tracer bullets — use prototypes and feature spikes to find the moving target in the dark.
Microstones — track progress on smaller units work to keep team focused within milestones.
Proverbs

Work with users to think like a user.
Don’t gather requirements like scattered seeds; dig for them like buried treasure.
You will fail, if there is no plan, no one following plan, and no change to plans when things change.
Abstractions live longer than details.
Test early, often, and automatically.
Provide options; don’t give lame excuses.
The word of someone else’s mouth sells better than opening yours.
Good architectures with conceptual integrity should manage complexity and change.
Do not assume something to be true; try to prove it.
Sign your work; take pride in quality and craftsmanship.
If you found it painful more than twice, then automate it.
The cost of “quick and dirty” often lasts longer and gets dirtier than the quick win’s benefit.
The best and the perfect are the enemy of the good.
You don’t make money by developing software, but by delivering and selling software.
Leverage 80/20 rule — finish 80% of requirements before design and 80% of design before coding.
