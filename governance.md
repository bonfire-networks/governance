# Bonfire governance & value distribution [draft]

[TOC]

## Objectives
* Create heterogeneous and fair spaces for humans to work together. 
* Welcome new participants to contribute and get involved according to their skills and preferences.
* Reward everyone according to shared and transparent value formulas. 
* Create one or more mutualistic circles to take care of participants according to their needs, and protect participants from burnouts. 

One pattern frequently observed in several enthusiastic open source projects, is to prefer to expand the community at all cost, without a reasoned plan about how to handle team / community relationships and (social, political, economic) needs. 
Let's avoid that for bonfire: let's not end up having a rigid/fixed/hierarchical team that treats anyone else as an external contributor, so to take any economic advantages for themselves - but at the same time let's not end up navigating without any clear and transparent structure and pretend to treat anyone as a contributor with same rights.

Patterns to avoid: [BDFL](https://en.wikipedia.org/wiki/Benevolent_dictator_for_life) | [TYRANNY of STRUCTURELESSNESS](https://www.jofreeman.com/joreen/tyranny.htm)

*Here then is a draft proposal of something we could try:*


## Decision-making

- Decisions are made within a circle by [consent](https://patterns.sociocracy30.org/principle-consent.html) of all members (based on [sociocracy](https://sociocracy30.org))
- There is consent to a proposal when no member of the circle has an objection (meaning something is "good enough to try"). This is different from consensus. 
- [Objecting](https://patterns.sociocracy30.org/objection.html) requires that a circle member has reason to assume that circle cannot achieve its aim adequately if the circle approves the proposal. In other words, any circle member can flag an issue in a proposal and make sure the circle interates on the proposal until consent can be found. 
- Decisions are made by discussion an issue or proposal in [rounds](https://patterns.sociocracy30.org/rounds.html, talking one-by-one until everyone has spoken once in that round. The intention is to hear all voices and contribute to more mutual listening and understanding.
- A circle will decide by consent what topics they put on their agenda, what tasks to work on, and how much time they spend on each.
- A circle can decide (with all members consenting) to try a different decision-making process.


## Circles
Small groups are the basis of everything. These [circles](https://patterns.sociocracy30.org/circle.html) (based on [sociocracy](https://sociocracy30.org)) have a defined aim (a description of what the circle is doing) and full responsability over a domain. 

- Circles can be [linked](https://patterns.sociocracy30.org/linking.html) or [double linked](https://patterns.sociocracy30.org/double-linking.html) by having a member represent them in another circle. 
- Circles use consent to assign [roles](https://patterns.sociocracy30.org/role.html) like facilitator, record keeper, representative (for linking with another circles), or other self-defined operational roles. 
- One person can simultaneously be in multiple circles.
- Members of a circle can object to a new member being added. 
- Each circle has a dedicated chat room, from which it can conduct discussions and decide what other tools to use. 

### Ad-hoc circles
Circles can be created as needed for a project, milestone, app, extension, different categories of maintainance activities (eg. a Documentation circle), etc. 

### Contributors circle
* Takes on spare open tasks
* Paid per merged PRs on open tasks 
* Can benefit from crowdfunding/grant funds for specified tasks
* Can eventually become team members if desired.

### Team Members circle
* Decisions that affect Bonfire team members are made in here (examples include the assignment of funds to a new circle).
* Can be paid per merged PR on open funded tasks. 
* Can benefit from crowdfunding/grant funds to build new extensions or features.
* Can be paid for recurring caring activities. 
* Eligible for a basic income that is flexible according to available funds.

### Project Maintainers circles
* Each of these circles is responsible for the building and maintainance of one or more specified core projects (such as extension or libraries).
* Paid for recurring caring activities (such as reviewing PRs and fighting code rot). 
* Eligible for a basic income that is flexible according to available funds.

### Ecosystem Maintainers circle
* Does both caring and building work on a regular basis.
* Responsible for building and maintainance of the overall ecosystem (such as finding sources of sustainability or cooperation with other ecosystems).
* Eligible for a basic income that is flexible according to available funds.

### Ecosystem Circle
* Decisions that affect the Bonfire ecosystem as a whole are made here (examples include changing what federation protocols we support, or major changes to the technology stack). 
* Made up of representatives [linked](https://patterns.sociocracy30.org/linking.html) from all other circles


## Rewarded activities
All the activities that are worth to get rewarded for the success of bonfire ecosystem at large. Monetary rewards come from shared funds (currently on Open Collective) that might be pre-assigned to a specific project or milestone, or that might be available to be assigned later. These funds may come from donations, grants, or other revenue. 

### Maintenance & caring 
Any recurring activity that empowers the community. Usually (but not always) such activities are hard to be represented as a single atomic task, and the outcomes may or may not be tangible. [Most of the time these activities are invisible or not properly valued.](https://syllabus.pirate.care/#care-a-political-notion)

Such activities include:
 - Participate to meetings
 - create, curate, and reply to issues on github
 - reviewing/merging peoples' PRs
 - engage with bonfire audience via social networks, chats and forums
 - Discover and apply to grants
 - Organize meetings w/ communities or projects
 - Moderate matrix channels
 - Share feedbacks & lead or participate in UX interviews
 - Keep an eye for broken tests and avoid code rot
 - Routing updates of dependencies
 - Updating changelogs
 - Do admin stuff
 - Etc
 
### Building 
Any activities that can be represented as a one-time atomic issue (a task):
- Backend 
- Frontend
- User Experience / User Interface
- Documentation
- Art
- Copy (blog posts, forum threads)
- Localisation / translation
- Other tasks needed to build Bonfire, its extension, or tools and libraries it depends on

## Formulas
The team assigns a fixed budget to a milestone. Each milestone is specified as a list of tasks. Because tasks can be added, split, merged, or removed throughout the duration of a project, rather than assigning a per-task budget, calculations are made once the milestone is complete – the budget is split between the contributors of the milestone's tasks based on their weight. 

### Milestone
A milestone refers to a specific and detailed set of tasks and caring activities, that lends to one or more measurable outcomes, with a defined deadline.

### Tasks
A task needs to be part of a specified and funded milestone to be eligible for reward. 

Each task has an assigned **weight** that spans from 1 to 10. 
Team members define together each task's weight, according to the following parameters: 
- Urgency (1 to 10)
- Difficulty (1 to 10)
- Duration (1 to 10)
- Impact (1 to 10)

The sum of the 4 ratings, divided by the number of parameters and rounded up, gives the task **weight**.

eg. Backend for admin to handle flags: 
- Urgency: 6
- Difficulty: 3
- Duration: 2
- Impact: 2

Total: 13/4 -> 3.25 -> 4

eg. Functionality to delete my account and data
- Urgency: 2
- Difficulty: 7
- Duration: 4
- Impact: 5

Total: 18/4 -> 4.5 -> 5

### Maintenance & caring
One option would be to link the basic income to these activities, so that people in circles responsible for maintenance & caring received a fixed (as in not based on hours or tasks) but flexible (as in based on what the treasury allows at any given time) income. 

Here are relevant links that could shape our discussions for a contribution model for caring activities:
- https://disco.coop/governance-model/
- https://syllabus.pirate.care/#care-a-political-notion
