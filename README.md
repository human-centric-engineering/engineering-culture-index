# Engineering Culture Index
The Engineering Culture Index is a service available from [Human Centric Engineering](https://www.humancentricengineering.com/) which is a consultancy practice specialising in the human aspects of software engineering. The service comprises the survey-based questionnaire in this repository supported with workshops, coaching and consultancy to help software engineering departments create optimal ecosystems where engineers can thrive. See [Engineering Culture Index](https://www.humancentricengineering.com/engineering-culture-index) for a service description.

## Intro
Culture, by its emergent nature, defies accurate measurement. It is an intuitive ‘tacit knowing’ derived from our subjective experiences. Culture results from our collective underlying assumptions and worldviews and our experience of the interactions which ensue from acting on our beliefs and values. The Engineering Culture Index is a working hypothesis on engineering culture which is version controlled and will be modified over time to reflect emerging insights and changes in the craft of software engineering.

## The Questions
Below are links to the survey questions. The questions are Likert Scale statements to which individual engineers will be asked to signify their level of agreement on the familiar scale of Strongly Disagree to Strongly Agree. The questions relate to a software engineer's subjective assessment of the engineering culture as they experience it.

### Mastery
Care and quality in engineering and continual growth as teams and individuals.

* <a href="/questions/craftsmanship.md">Craftsmanship</a>
* <a href="/questions/creativity.md">Creativity</a>
* <a href="/questions/learning.md">Learning</a>
* <a href="/questions/professionalism.md">Professionalism</a>

### Autonomy
Self-directed teams and individuals collaborating effectively.

* <a href="/questions/trust.md">Trust</a>
* <a href="/questions/agency.md">Agency</a>
* <a href="/questions/infrastructure.md">Infrastructure</a>
* <a href="/questions/information.md">Information</a>

### Purpose
Deep fulfilment and being part of something bigger than ourselves.

* <a href="/questions/clarity.md">Clarity</a>
* <a href="/questions/leadership.md">Leadership</a>
* <a href="/questions/engagement.md">Engagement</a>
* <a href="/questions/meaning.md">Meaning</a>

#### Summary
The 3 categories above are each comprised of 24 Likert Scale statements, 72 questions in total. Each section will also have a comments input box to collect any additional information an engineer wishes to share. There will also be a concluding section to collect feedback on how engineers feel about the survey.

We will seek a response to these final 2 questions as well as provide a comments box to collect feedback about the survey.
* The survey questions have been clear and unambiguous.
* The survey questions relate well to the most important aspects of engineering culture.

## Rationale for the Questions and the Structure
The Engineering Culture Index survey is based on 12 categories of questions to understand the subjective experience of engineers. The categories are grouped into three columns representing the dimensions of intrinsic human motivation identified by Self-Determination Theory<sup>[1](#self-determination-theory)</sup>, namely Mastery, Autonomy and Purpose so that the survey is directly related to aspects of human motivation and thriving. A framework of the constituents of motivation has been used because motivation determines where we'll put our attention and effort. It reflects the contagious energy that drives inspired accomplishment. In all, there are 72 statements which use a Likert scale to capture a positive or negative response from the engineer. Assumptions woven into the survey are derived from the evidence-based research of Ron Westrum<sup>[2](#ron-westrum)</sup> and the predictive influence of organisational culture on software delivery performance and organisational performance as discussed in the book Accelerate<sup>[3](#accelerate)</sup>. Also woven into the survey are the findings from Google's Project Aristotle<sup>[4](#aristotle)</sup> which highlighted the constituents of team success at Google. The have been numerous other<sup>[5](#accelerate)</sup> influences and personal experiences which have been incorporated into this work.

Each category has 4 subsets containing 6 questions, 2 questions are about how the engineer experiences their organisation, 2 are about their experience of working in teams, and 2 questions are about them as individuals and the impact they have on their engineering culture. The reason for this structure is that by simply taking the questionnaire engineers will learn about the key aspects of motivation and self-determination which can be consciously influenced to improve their developer experience. The format of the questions also shows engineers that they can have direct influence over their engineering culture, rather than seeing culture solely as something which is thrust upon us by the organisation. Analysis of the respondent's answers will reveal leverage points where changes can be made to optimise engineering culture over time.  The Team related questions could be split off from this survey and be used to assess the dynamics of a particular team, or the individual statements could be given to an individual engineer to help them understand their own impact on the prevailing culture.

## Contributions
Comments and contributions are welcome. See <a href="CONTRIBUTING.md">Contributing for details</a>.

## License & Copyright

The materials herein are all &copy; [John Durrant](https://www.linkedin.com/in/johndurrant/).

This work is licensed under a <a rel="/license" href="/LICENSE">GNU General Public License v3.0</a>.

The survey questions may be used for commercial or non-commercial purposes without permission of the author however it is requested that the author, John Durrant of Human-Centric Engineering, is credited.

## Footnotes
<a name="self-determination-theory">1</a>: Self-Determination Theory was popularised by Daniel Pink in his book, Drive, based on earlier research into intrinsic motivation by Edward L. Deci and Richard Ryan. See [Wikipedia Self-Determination Theory](https://en.wikipedia.org/wiki/Self-determination_theory)

<a name="ron-westrum">2</a>: Ron Westrum is an American Sociologist whose paper [A Typology of Organisational Cultures](https://qualitysafety.bmj.com/content/13/suppl_2/ii22) has been highly influential in the DevOps movement to assert the role that culture plays in software delivery performance. This research has been picked up by the DevOps Research and Assessment (DORA) teams to support their underlying assumptions. See more at [DevOps culture: Westrum organizational culture](https://cloud.google.com/architecture/devops/devops-culture-westrum-organizational-culture). Also see Westrum's paper [The study of information flow: a personal journey](https://www.researchgate.net/publication/261186680_The_study_of_information_flow_A_personal_journey).

<a name="accelerate">3</a>: Accelerate: The Science of Lean Software and DevOps: Building and Scaling High Performing Technology Organizations is a book by Gene Kim, Jez Humble, and Nicole Forsgren which uses rigorous statistical analysis to support the theoretical justifications for successful technology practices such as the use of DORA metrics. See [THE ROLE OF CONTINUOUS DELIVERY IN IT AND ORGANIZATIONAL PERFORMANCE](https://deliverypdf.ssrn.com/delivery.php?ID=042078025114070002072097115101078072040084020051087045067030119027078068068102115100114096097007061062034023124105029092009095021052023087058005028014084000121075030066014005021124005122025120105097005125075006118127109075078103122025000108088115087001&EXT=pdf&INDEX=TRUE) as well as the yearly [State Of Devops](https://cloud.google.com/devops/state-of-devops) reports which have been published since 2014.

<a name="aristotle">4</a>: Project Aristotle found that Psychological Safety, Dependability, Structure & Clarity, Meaning, and Impact were the most important predictors of team success. See [Project Aristotle](https://rework.withgoogle.com/print/guides/5721312655835136/)

<a name="other">5</a>: Other influences for this survey include (but are not limited to) [Gallup’s State of the Global Workplace report on employee engagement](https://www.gallup.com/workplace/349484/state-of-the-global-workplace.aspx), various Systems Thinking resources, notably Donella Meadows' book "Thinking in Systems", Peter Senge's thinking on Learning Organisations, specifically his book "The Fifth Discipline", David Marquet's thinking on Leadership, notably his book "Turn the Ship Around", Mihaly Czicksentmihy's work on the Flow state, "The Five Dysfunctions of a Team" by Patrick Lencioni, "The Culture Code" by Daniel Coyle, "Principles" by Ray Dalio, the work and musings of organisational and culture specialists such as Dr Richard Claydon of the [EQ Lab](https://www.eqlab.co/), and [Geoff Marlow](https://www.geoffmarlow.com/).
