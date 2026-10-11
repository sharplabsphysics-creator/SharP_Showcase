# SharP: Project Plan

**Category:** AI in Education · **Document 4 of 5:** Objectives, Users, Timeline, Resources and Risks

## Objectives

- **Put a guide beside every learner.** No one using SharP should meet the question "why did that happen?" alone.
- **Turn watching into experimenting.** Replace passive viewing with a conversation that ends in something to try.
- **Make trust visible.** Answers are grounded in real textbooks, and nothing the tutor proposes runs unchecked.
- **Give the community a home and a voice.** Let the people who learn physics decide what is built for them, and let those who can build be credited for it.
- **Keep it free.** Access to a serious physics education should not depend on what a learner or their institution can afford.

## Expected Outcomes

- Learners who can ask about the exact experiment in front of them and test the answer in the same moment.
- A simulation library that grows where real demand is, because learners propose and vote on it.
- Contributors whose work reaches learners everywhere, under their own names.
- A shared way of writing simulations, so that each new one is tutor-ready from the day it is added.
- A published measurement of how well Psi's answers hold up against the textbooks they draw on. This study is planned, and we claim no accuracy figure before it is done.

## Target Users

- **University physics students** meeting quantum, statistical and solid-state physics for the first time: the subjects where intuition fails and a guide matters most.
- **Teachers and lecturers** who want a live demonstration in the classroom, and a place to send students who are stuck after class.
- **Independent learners and enthusiasts** anywhere in the world, with curiosity but no classroom.
- **Simulation builders**, from students to researchers, who have something worth sharing and nowhere to publish it.
- **Institutions without advanced laboratories.** Most quantum behaviour cannot be shown in any teaching lab; on SharP it can be seen, changed and questioned in a browser.

## Key Deliverables

**Working in the prototype today**

- Interactive simulations across quantum mechanics, statistical physics, solid-state physics and electron transport.
- Psi inside the simulation, aware of the open experiment and its settings.
- Answers grounded in a curated textbook knowledge base.
- One-click experiments, each checked against the simulation's limits before it is offered.
- A Theory view beside each simulation.
- The Idea Lab, the weekly community poll with confirmed votes, the public build board and the record of past polls.

**Planned next**

- Experiments confirmed by the simulation's own physics before Psi offers them.
- Psi returning after each experiment to explain the result.
- Simulations contributed by the community, reviewed and published under their authors' names.
- A published evaluation of Psi on realistic student questions.
- Wider coverage of physics, in the order the community votes for.

## Implementation Plan and Timeline

| Phase | Period | Work |
|---|---|---|
| Foundation | From March 2026 | The platform, the simulation engine and the first simulations |
| Growth | Through mid 2026 | A larger library, a shared design language, the Idea Lab |
| Intelligence | Autumn 2026 | Psi, the textbook knowledge base and one-click experiments |
| Community | Autumn 2026 | Weekly poll, confirmed voting and the public build board |
| Championship preparation | 12 to 24 October 2026 | Physics-confirmed experiments, Psi's explanation after each experiment, evaluation of Psi, a dependable live demonstration |
| Opening to contributors | After the championship | Simulation submissions and review, author credit, new areas of physics |

The prototype described in these documents already exists and is deployed. The time between submission and the final is for deepening and measuring it, not for building it from nothing.

## Resources and Requirements

**Team**

- **Muhammad Haris**, frontend development and integration: the SharP interface, and bringing the simulations, pages and Psi together.
- **Muhammad Abdullah**, simulation development and user experience: the physics behind the simulations and how the platform looks and feels.
- **Hasan Ali**, backend development, security and quality: Psi's server side, and keeping the platform safe and reliable.

We are physics students building an AI system for the subject we study. We are our own first users, and we built SharP because we needed it.

**What SharP runs on**

- A web platform that works in any modern browser.
- A server that hosts Psi and the community features.
- Access to a language model. Psi is designed so that the model behind it can be replaced without changing the platform.
- A curated knowledge base of physics teaching material.

**What would help us most**

- Mentorship on evaluating an AI tutor responsibly and on growing a contributor community.
- Dependable hosting and model capacity, so Psi stays free as use grows.
- Introductions to universities and physics educators who would use SharP with their students.

## Potential Challenges and Risks

| Risk | How we address it |
|---|---|
| **An AI tutor can be wrong.** | Answers are grounded in passages retrieved from university textbooks, not left to the model's memory. We make no accuracy claim until our evaluation is complete. |
| **An AI acting on a simulation could misbehave.** | Psi never touches the simulation directly. It can only propose; every proposal is checked, and nothing happens until the learner clicks. |
| **Model cost and usage limits** could interrupt a free service. | A small, fixed number of model requests per question, none for a simple confirmation, several keys in rotation, and a design that is not tied to a single model provider. |
| **Contributed simulations may vary in quality.** | A written authoring convention, review before publication, and credit that puts the author's name on the work. |
| **Use of textbook material.** | Textbooks are used for retrieval only and are never redistributed. Freely licensed and self-written material will form the core as the knowledge base grows. |
| **A community takes time to form.** | The Idea Lab and weekly poll give visitors a reason to return and a stake in what is built, before any contributor programme begins. |

## Responsible AI by Design

Three rules govern Psi. The tutor proposes, the browser acts, the learner decides. Answers are grounded in real sources. And we claim only what we can demonstrate.

*Continued in Document 5: Screenshots.*
