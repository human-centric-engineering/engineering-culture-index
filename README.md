# Engineering Culture Index
The Engineering Culture Index is a service available from [Human Centric Engineering](https://www.humancentricengineering.com/) which is a consultancy practice specialising in the human aspects of software engineering. The service comprises the survey-based questionnaire in this repository supported with workshops, coaching and consultancy to help software engineering departments create optimal ecosystems where engineers can thrive. See [Engineering Culture Index](https://www.humancentricengineering.com/engineering-culture-index) for a service description.

## Intro
Culture, by its emergent nature, defies accurate measurement. It is an intuitive ‘tacit knowing’ derived from our subjective experiences. Culture results from our collective underlying assumptions and worldviews and our experience of the interactions which ensue from acting on our beliefs and values. The Engineering Culture Index is a working hypothesis on engineering culture which is version-controlled and will be modified over time to reflect emerging insights and changes in the craft of software engineering.

| Mastery |  Autonomy | Purpose |
| ------- | ------- | ------- |
| **Care and quality in engineering and continual growth as teams and individuals** | **Self-directed teams and individuals collaborating effectively** | **Deep fulfilment and being part of something bigger than ourselves** |
| **Craft** Pride in Work, Care for Quality, Technical Excellence | **Trust** Dependability, Psychological Safety,  Strong Relationships, Honesty, Vulnerability | **Clarity** Clarity of the primary purpose of the organisation and teams. Clear Direction. Clear Career Paths, Clear Roles and Responsibilities |
| **Creativity** Experimentation, Prototyping, Innovation, Hypothesis-Driven Culture, Implementing Novelty | **Agency** Influence, Autonomy, Empowerment, Ownership, Accountability, Self-Organising Teams, Sustainable Pace | **Leadership** Decision Making, Taking Actions, Organisational Cohesion, Collaboration, Small ‘L’ Leadership, Shared Responsibility |
| **Learning** Knowledge Sharing, Dedicated Learning Time, Communities of Practice,  Continuous Improvement Mentoring, Coaching, Growth Mindset, Feedback | **Resources** Tools, Environments, Automation, Structures, Processes, Operational Excellence | **Direction** Momentum, North Star, Goals, Aspiration, Vision, Potential, Destination, Journey, Orientation, Narrative |
| **Professionalism** Technical Practices, Principles, Standards, Competencies, Attitudes, and Behaviours | **Context** Communication, Visibility, Documentation, Information Flows, Sensemaking, Exposing Reality | **Meaning** Inclusion, Belonging, Connection, Contribution, Aligned Values, Meaningful Results, Individual Transformation, Stability, Feeling Valued, Mattering, Significance, Hope, Engagement, Energy, Motivation, Flow, Challenge, Inspiration, Wellbeing, Vitality |



## The Questions
Below are links to the survey questions. The questions are Likert Scale statements to which individual engineers will be asked to signify their level of agreement on the familiar scale of Strongly Disagree to Strongly Agree. The questions relate to a software engineer's subjective assessment of the engineering culture as they experience it.

### Mastery
Care and quality in engineering and continual growth as teams and individuals.

* <a href="/questions/craft.md">Craft</a>
* <a href="/questions/creativity.md">Creativity</a>
* <a href="/questions/learning.md">Learning</a>
* <a href="/questions/professionalism.md">Professionalism</a>

### Autonomy
Self-directed teams and individuals collaborating effectively.

* <a href="/questions/trust.md">Trust</a>
* <a href="/questions/agency.md">Agency</a>
* <a href="/questions/resources.md">Resources</a>
* <a href="/questions/context.md">Context</a>

### Purpose
Deep fulfilment and being part of something bigger than ourselves.

* <a href="/questions/clarity.md">Clarity</a>
* <a href="/questions/leadership.md">Leadership</a>
* <a href="/questions/direction.md">Direction</a>
* <a href="/questions/meaning.md">Meaning</a>

#### Summary
The 3 categories above are each comprised of 24 Likert Scale statements, 72 questions in total. Each section will also have a comments input box to collect any additional information an engineer wishes to share. There will also be a concluding section to collect feedback on how engineers feel about the survey.

We will seek a response to these final 2 questions as well as provide a comments box to collect feedback about the survey.
* The survey questions have been clear and unambiguous.
* The survey questions relate well to the most important aspects of engineering culture.

## Rationale for the Questions and the Structure
The Engineering Culture Index survey is based on 12 categories of questions to understand the subjective experience of engineers. The categories are grouped into three columns representing the dimensions of intrinsic human motivation identified by Self-Determination Theory<sup>[1](#self-determination-theory)</sup>, namely Mastery, Autonomy and Purpose so that the survey is directly related to aspects of human motivation and thriving. A framework of the constituents of motivation has been used because motivation determines where we'll put our attention and effort. It reflects the contagious energy that drives inspired accomplishment. In all, there are 72 statements which use a Likert scale to capture a positive or negative response from the engineer. Assumptions woven into the survey are derived from the evidence-based research of Ron Westrum<sup>[2](#ron-westrum)</sup> and the predictive influence of organisational culture on software delivery performance and organisational performance as discussed in the book Accelerate<sup>[3](#accelerate)</sup>. Also woven into the survey are the findings from Google's Project Aristotle<sup>[4](#aristotle)</sup> which highlighted the constituents of team success at Google. The have been numerous other<sup>[5](#accelerate)</sup> influences and personal experiences which have been incorporated into this work.

Each category has 4 subsets containing 6 questions, 2 questions are about how the engineer experiences their organisation, 2 are about their experience of working in teams, and 2 questions are about them as individuals and the impact they have on their engineering culture. The reason for this structure is that by simply taking the questionnaire engineers will learn about the key aspects of motivation and self-determination which can be consciously influenced to improve their developer experience. The format of the questions also shows engineers that they can have direct influence over their engineering culture, rather than seeing culture solely as something which is thrust upon us by the organisation. Analysis of the respondent's answers will reveal leverage points where changes can be made to optimise engineering culture over time.  The Team-related questions could be split off from this survey and be used to assess the dynamics of a particular team, or the individual statements could be given to an individual engineer to help them understand their own impact on the prevailing culture.

## A Cautionary Approach to Implementation
A LinkedIn post by John Cutler<sup>[6](#johncutler)</sup> provides a cautionary counterbalance to engagement surveys in general. His valuable words from his LinkedIn Post on 15th Oct 2023 are provided in full below:

> If you're relying on engagement surveys (or people "speaking up") to understand what is happening in your company you're likely missing A GREAT DEAL—especially if things are getting worse Why?
> 
> 1. Feedback Saturation
> 2. Emotional Exhaustion
> 3. Acclimatization
> 4. Cognitive Dissonance
> 5. Shifted Expectations
> 6. Localized Tolerance
> 7. Locus of Control
> 8. Fear of Repercussions
> 9. Hedonic Treadmill
> 
> ⚠ Feedback Saturation: If a situation continues to deteriorate, team members might feel that they've already given feedback on the issue multiple times. Over time, they provide less feedback because they believe their previous feedback hasn't led to change.
> 
> ⚠ Emotional Exhaustion: As team members get more and more exhausted, they tend to become less vocal and less expressive about their concerns because they're emotionally drained.
> 
> ⚠ Acclimatization: As team members adapt to worsening conditions, they might come to accept the conditions as the "new normal" and provide less critical feedback.
> 
> ⚠ Cognitive Dissonance: If employees have invested a lot in the company (time, energy, emotions), they might experience cognitive dissonance, where they downplay or ignore negative aspects to maintain a consistent positive image of the place they've devoted so much time to.
> 
> ⚠ Shifted Expectations: Over time, faced with unmet needs in the workplace, team members recalibrate their expectations. They begin to expect less from their job in terms of satisfaction, growth, or engagement, and prioritize getting those needs met elsewhere.
> 
> ⚠ Localized Tolerance: In large organizations, many issues manifest as minor inconveniences at the local level. Teams develop workarounds or short-term solutions to navigate these inconveniences. Because these issues don't seem critical, they don't feel the urgency to provide feedback.
> 
> ⚠ Focus on What You Can Control: One common coping strategy, especially in large companies, is to narrow one's focus to what is directly within your control. This narrowed focus can lead to a decrease in feedback about broader organizational challenges. The mindset becomes: "If I can't change it, I won't worry about it."
> 
> ⚠ Fear of Repercussions for Others: Even in systems that promise anonymity, employees may hold back on feedback out of concern for the consequences it might have on others, especially their managers or immediate supervisors. There's a worry that if they highlight certain problems, it might reflect poorly on their team or leader.
> 
> ⚠ Hedonic Treadmill: As individuals experience changes in their work environment, they tend to quickly adapt to new conditions, whether positive or negative. Over time, what was once a significant improvement or decline in conditions can become the new baseline for their experience.
> 
> This is why you have to connect with people directly, listen deeply, observe, and seek diverse perspectives. Surveys and "waiting for people to speak up" will not cut it.


## Contributions
Comments and contributions are welcome. See <a href="CONTRIBUTING.md">Contributing</a> for details.

## License & Copyright

The materials herein are all &copy; [John Durrant](https://www.linkedin.com/in/johndurrant/).

This work is licensed under a <a rel="/license" href="/LICENSE">GNU General Public License v3.0</a>.

The survey questions may be used for commercial or non-commercial purposes without permission of the author however it is requested that the author, John Durrant of Human-Centric Engineering, is credited.

## Footnotes
<a name="self-determination-theory">1</a>: Self-Determination Theory was popularised by Daniel Pink in his book, Drive, based on earlier research into intrinsic motivation by Edward L. Deci and Richard Ryan. See [Wikipedia Self-Determination Theory](https://en.wikipedia.org/wiki/Self-determination_theory)

<a name="ron-westrum">2</a>: Ron Westrum is an American Sociologist whose paper [A Typology of Organisational Cultures](https://qualitysafety.bmj.com/content/13/suppl_2/ii22) has been highly influential in the DevOps movement to assert the role that culture plays in software delivery performance. This research has been picked up by the DevOps Research and Assessment (DORA) teams to support their underlying assumptions. See more at [DevOps culture: Westrum organizational culture](https://cloud.google.com/architecture/devops/devops-culture-westrum-organizational-culture). Also see Westrum's paper [The study of information flow: a personal journey](https://www.researchgate.net/publication/261186680_The_study_of_information_flow_A_personal_journey).

<a name="accelerate">3</a>: Accelerate: The Science of Lean Software and DevOps: Building and Scaling High Performing Technology Organizations is a book by Gene Kim, Jez Humble, and Nicole Forsgren which uses rigorous statistical analysis to support the theoretical justifications for successful technology practices such as the use of DORA metrics. See [THE ROLE OF CONTINUOUS DELIVERY IN IT AND ORGANIZATIONAL PERFORMANCE](https://deliverypdf.ssrn.com/delivery.php?ID=042078025114070002072097115101078072040084020051087045067030119027078068068102115100114096097007061062034023124105029092009095021052023087058005028014084000121075030066014005021124005122025120105097005125075006118127109075078103122025000108088115087001&EXT=pdf&INDEX=TRUE) as well as the yearly [State Of Devops](https://cloud.google.com/devops/state-of-devops) reports which have been published since 2014.

<a name="aristotle">4</a>: Project Aristotle found that Psychological Safety, Dependability, Structure & Clarity, Meaning, and Impact were the most important predictors of team success. See [Project Aristotle](https://rework.withgoogle.com/print/guides/5721312655835136/)

<a name="other">5</a>: Other influences for this survey include (but are not limited to) [Gallup’s State of the Global Workplace report on employee engagement](https://www.gallup.com/workplace/349484/state-of-the-global-workplace.aspx), various Systems Thinking resources, notably Donella Meadows' book "Thinking in Systems", Peter Senge's thinking on Learning Organisations, specifically his book "The Fifth Discipline", David Marquet's thinking on Leadership, notably his book "Turn the Ship Around", Mihaly Czicksentmihy's work on the Flow state, "The Five Dysfunctions of a Team" by Patrick Lencioni, "Team Topologies" by Manuel Pais and Matthew Skelton, "The Culture Code" by Daniel Coyle, "Principles" by Ray Dalio, the work and musings of organisational and culture specialists such as Dr Richard Claydon of the [EQ Lab](https://www.eqlab.co/), and [Geoff Marlow](https://www.geoffmarlow.com/).

<a name="johncutler">6</a>: John Cutler's [LinkedIn post on engagement surveys](https://www.linkedin.com/posts/johnpcutler_if-youre-relying-on-engagement-surveys-activity-7119182332590256128-1B2t).
