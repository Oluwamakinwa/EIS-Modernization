# Welcome!
This repo contains documentation describing the Alaska Department of Health and Social Services (DHSS) modernization project. It is intended to be a place where project participants can keep track of the overall project goals, the decision framework, progress to date and learnings as we work. It is also intended to be a project 'home page' where members can access important and up-to-date project information that exists somewhere else.

## Our Big Goal
We seek to transform practices around technology, product and procurement in the Alaska DHSS _so that_ it can more successfully administer the various benefit programs (Medicaid, Food Stamps (SNAP), Temporary assistance (TANF) etc.) for which it is responsible.

## The Challenge
The challenge is rooted in the need for Alaska to migrate these programs off of their "old legacy" eligibility system, EIS, to something that costs less to operate and is more flexible to change. The EIS system does what it does well, but it is built in a old technology (COBOL on a mainframe) that is difficult to change. It is also expensive to host, and as other agencies in Alaska migrate away from the system, DHSS will be responsible for more and more of this cost. Further, expertise for this type of technology is aging out, so it will be harder and harder to support it going forward. Moving away from this system is the ultimate goal.

To this end, Alaska entered into an agreement with a contractor to migrate all programs to a bespoke system that was supposed to be more automated, flexible and maintainable. The first phase of this migration was problematic, leaving the State with a "new legacy" Medicaid eligibility system, ARIES, that is difficult for users to work with. And, the contractor walked away from the agreement in December of 2016, leaving the State with a partially implemented migration, virtually no ability to iterate on the new system and barely any ability to maintain or fix it. The State is now straddling the old system and new one, forcing a good deal of manual workarounds so that the State can continue to deliver services.

ARIES has arguably caused a _significant decrease in worker productivity_ as evidenced by a backlog of between 16,000 and 24,000 applications for Medicaid and other public assistance programs (the exact number is unknown due to bad data and duplication), and a documented decrease in application processing per worker per day from 12 to 4. Beneficiaries can wait months to receive benefits and workers are frustrated. Clients get frustrated with delays, and this causes them to submit duplicate applications thereby adding to the backlog and pressure.

## Our Hypothesis
We want to move away from a legacy "Big Bang" waterfall acquisitions process to a more modular approach, emphasizing user centered design, agile product development, and DevOps practices. We believe doing this will incrementally improve the current situation in a measurable and sustainable way, and eventually allow the continued migration of programs away from the EIS system and onto something more modern, flexible and maintainable.

We will know we are successful, if we can increase worker productivity and morale, among other things, and if benefits are being provided in a timely manner to those who are eligible. We are currently focused on getting a win here fairly soon so that we can show State workers and the Legislature that we are moving in the right direction.

## Risks
* The depth of the vendor pool available that understands agile delivery and can do modular procurement might be limited, at least in the early phases of the project.
* The LOE required to access data across multiple environments (ARIES database, staging table, MCI, Mainframe) is not well known yet.
* The availability of appropriate platforms within the state technology environment for deploying prototypes is not well understood yet.

## Near-term Milestones
- [x] Identify product owner and team - Done 2/28/17
- [x] Identify where to start - Done 3/2/17 (Search API and UI to support)
- [ ] Validate starting point - In Progress
- [ ] Acquire a vendor - To Do
- [ ] First acquisition - To Do

## Important Resources
* [Alaska organizational chart](http://mur.al/vzV3BEBJ)
* [Project Trello Board](https://trello.com/b/siAFtoWJ/alaska-medicaid-eligibility-information-system-replacement-eis-r-project)
* [2/28/17-3/2/17 Workshop findings](https://app.mural.ly/t/gsa6/m/gsa6/1488927409455/view/3842912505)
* [Diagrams for first prototype](https://app.mural.ly/invitation/mural/gsa6/1489619780239?sender=michaeltorres&key=1026750817)
* [Project Folder](https://drive.google.com/drive/u/0/folders/0B4B0xeCMEaFyYmE0VFhTR3lTSms)
* [Modular transformation: Incrementally shifting toward a modular experience](modular-experience.pdf)
* [Research Synthesis]

## Related projects
* [CMS project]
* [MO MMIS Modernization]
* [Prototype]

## Contributing to this repo
* Read the [CONTRIBUTING](CONTRIBUTING.md) Policy
* Questions or suggestions? Open a [new issue](https://github.com/18F/alaska-dhss-modernization/issues) to ask or suggest.
* Want to send us a change? Create a [new pull request](https://help.github.com/articles/creating-a-pull-request/).
