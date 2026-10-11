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

## Resources and Requirements

**What SharP runs on**

- **Client:** A web platform built with Vanilla web technologies and Three.js that works in any modern browser without installation.
- **Backend Infrastructure:** Psi and the community features are currently hosted entirely without commercial paid hosting—running live on a university computer maintained by the team, connected to the internet via secure tunneling.
- **AI Architecture & Compute:** Model-agnostic design. Our architectural plan to host and run fine-tuned physics models locally 24/7 is currently on hold due to a lack of dedicated GPU compute and funds to afford commercial hosting. In the interim, Psi relies on API key pools with smart local physics fallbacks.
- **Knowledge Base:** A curated vector index of standard university physics textbooks and SharP teaching materials.

**What would help us most**

- **Financial support and GPU compute:** Dedicated compute resources or hosting grants so we can transition from a university PC to permanent, dependable infrastructure and run local models 24/7 as traffic scales.
- **Mentorship:** Guidance on evaluating an AI tutor responsibly, validating physics reasoning, and growing an open-source contributor community.
- **Educational partnerships:** Introductions to universities, physics departments, and lecturers who want to adopt SharP for their classrooms and labs to help further improve the experience and introduce more interactive community-based learning features, all by using AI in a responsible way.

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

*See the provided SharP_Showcase Github repository for Screenshots.*
