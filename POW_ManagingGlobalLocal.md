# Managing Global Local (case)
### Interview with Declan, Project Programme Manager - Dublin.

|Case | Comments|
|:--- |:---------------------------- |
| "Bringing this project up to the starting line is a story in itself however I can say we **had a <br/>great start**. A **really compelling prototype**, demonstrated all the key functionality; web access, <br/>cloud data, simple workflow, **fine grained ownership with security**, reporting, **detailed <br/>versioning**, multilingual. We **demonstrated the capacity to delivery a key internal service to the <br/>global company**. You don't really need to know too much about the detail." | The first statement in the case is very positive and I had little to say about it until I had read the whole case; *"You don't really need to know too much about the detail."*. I wonder now if getting to the pitch stage was accomplished using a fast, iterative approach, and if organisational policies forced an old fashioned project development style that choked progress and tried to do too much in long phhases. |
| "**The initial prototype was a joint production between Santa Monica (US) and Dublin**, we <br/>pitched the project at our quarterly Knowledge Exchange event. In the company we call this <br/>kind of bidding process **'outsourcing inside'**. We **ended up with bids from three other groups**, <br/>from our offices in **Cairo (Egypt), Pune (India) and Langfang (China)**. Some of them signed up <br/>as 50% 'own time', the others were full-time. Cairo provided full-time developers, Langfang <br/>and Pune gave us full-time testers (figure 1)." <br/> <br/> ![fig. 1](Case9_fig1.jpg "Figure 1. Global-Local initial project team") | Judging from the positive reaction from other groups the project prototype was good, and not just in the designers opinion, people wanted to be a part of it's creation. |
| "**We applied formal project planning from the start**. The project is **outsourced to multiple sites** <br/>so **a number of different cultures are involved**. From our video calls I can say that the **physical <br/>environments at all sites appear to be open plan cubicle formats**, or 'tube-farms'. It is a tribute <br/>to the whole team that **a passion for quality and for doing the job well has remained <br/>throughout and that is common across all geographies.**" | No red flags here, this looks like a distributed setup that is ready and willing to do great work.  |
| "The **working cultures have little differences from office to office** but I can say **that's a <br/>strength**. The vendor development team in Cairo appear to **think little of working 24 hours a <br/>day, 7 days a week** if they feel it necessary. Some of the flexibility shown in Cairo **has its cost. <br/>After a 'spike' of effort they need to recover before reverting to normal working hours**, <br/>inevitably your life outside (or lack of sleep) catches up with you. **Those of us in Dublin and <br/>the US, we need our sleep and breaks just a little more** but we're nearly always on hand to <br/>check mail, and, **if necessary, work at weekends too**. The test teams in India and China are <br/>very structured, very productive, and seem to always work the same hours, sometimes little <br/>later on busy weekdays, very rarely at weekends. In contrast, **the part-time nature of the <br/>involvement of some of the players contributes to a certain lack of accountability**, after all this <br/>isn't their 100% day job. You might load a work-task in Project at 50% but they **aren't really <br/>able to allocate 50% all the time.**" | Talking about the Cairo development team Declan says *"Those of us in Dublin and the US, we need our sleep and breaks just a little more"*. I have difficulty believing that anyone would prefer to work 24/7 to the point that recovery time is needed before returning to normal work. I am concerned that the project timelines mean that this kind of effort is required, and why in Cairo? I believe the organisation has some ethical responsibility to ensure that the vendor is not exploiting staff. |
| "With the number of locations involved in conference calls we've found that **verbal <br/>communications can be a big problem**. The **mixture of accents** in each office is compounded <br/>by **differing audio quality** across the sites. **Audio and video quality degradation is just <br/>unavoidable**. We're a global technology leader and **only use best-in-class systems and still it's <br/>difficult to have perfectly clear group discussions**. I think it has been **a factor in generating <br/>some miscommunication.**"  | The issue here is recognised, cultural differences and technology limitations accepted, but we are missing an approach to mitigate their effects. I suggest that Sensedemanding (Vlaar et al., 2008) is purposefully introduced as a necessary way for client and supplier understanding to be matched. |
| "But the situation we're dealing with now... The **formal project management** approach requires <br/>an initial design process, **very structured, heavy on documentation and long-winded**. Crucially <br/>we agreed on **multiple customers with different requirements**, so **every possible feature <br/>requirement was included in the plan from the start**. You could say, with three customers the <br/>**project might lack a certain direction**. The customers (and I suspect architects) were <br/>**essentially free to add their own personal dreams into the requirements and specifications**. <br/>The **requirements are also 'moving targets'** because the goals of the different customer <br/>groups have shifted over time." | The project would be easier and possibly more successful, if features were prioritised, for instance using Moscow method to reduce the development to more manageable pieces. |
| "We followed formal project planning practice, a **one year schedule** with **three major <br/>milestones**: alpha, beta, general release. Each feature had a feature spec written, subjected <br/>to a review and sign-off meeting. Feature **spec review and sign-off ends up being quite <br/>lengthy** and it has to happen for each feature. After the feature specification is nailed down <br/>the developers create a detailed design spec. This hammers out the finer details of the <br/>features. The **test teams use the design spec to write a test spec** and start generating 'white <br/>box' tests. The developers take the design specs and implement them. " |   |
| "It was pretty obvious that the **formal approach takes time, but it can also lead to over <br/>engineered feature specifications.** This **causes problems elsewhere because of integration**, <br/>features have to work with each other, and the **interdependencies are complicated in <br/>unexpected ways.** The **alpha milestone was the point where first draft features were <br/>integrated. Debugging these interactions and interdependencies takes more time and <br/>generates further instabilities.**"  | They should introduce earlier integration testing, small changes, test, feedback, change, (push left).  |
| "It quickly became clear that while the features had been **highly designed, perhaps even 'over <br/>engineered', their integration with each other was troublesome.** While it had been considered <br/>during design it was obvious that each feature's **designer should have studied the interfaces <br/>with the others far more closely.** Another factor was that the customers had, in some cases, <br/>quite **different requirements; the outputs of features customised for one customer regularly <br/>caused problems as inputs for features customised for another.** **Debugging the interactions** <br/>between the features has **pushed the schedule out by months.**" | Frustratingly clear that the project aims are too complex for this approach, short-term small iterations will simplify and allow early detection of failures. |
| "We've been on a **'death march' to reach the beta milestone. Management** are beginning to <br/>**question the project's funding.** We have a management meeting next week, the **project is <br/>close to being canned**, but a lot of blood, sweat and tears has been invested. I think **everyone <br/>wants to give it a chance.**"  |   |
| "Starting with a concept, prototyping, and making the funding pitch is the base of a good <br/>technology recipe. How to succeed with distributed development teams? That's the secret <br/>sauce." | Assumption is that distributed teams is the main issue;  <br/>but the major issue I see, and mentioned during the interview,  <br/> is related to the wide scope and changing nature of customer, and possibly architect, specifications.  <br/>I would suggest breaking this project into smaller parts,  <br/>introduce newer Agile practices with sprints, iterative changes and releases within much smaller timelines. |


# Reading

|Reading | Case Comments|
|:--- |:---------------------------- |
|1. establish and maintain trust through the use of communication technology;| CT in use but it has it's limitations |
|2. ensure that distributed diversity is understood and appreciated; | Recognised | 
|3. manage virtual work-life cycle (meetings); | Not detailed | 
|4. monitor team progress using technology; | Not detailed | 
|5. enhance visibility of virtual members within the team and outside in the organization; | Not detailed | 
|6. enable individual members of the virtual team to benefit from the team. | Not detailed | 

" Considerable attention has
also focused on the communication technologies
needed to facilitate virtual work and enable
knowledge sharing (Malhotra & Majchrzak, 2004,
2005; Cascio, 2000; Zigurs, 2003; & Davis, 2004).
However, the special skills needed to lead teams
that have both geographic dispersion and innova
tive problem-solving challenges have received
limited attention in research."
p. 62, para. 2 ???

" successful virtual teams use the time between meetings to
asynchronously (through use of electronic discus
sion threads and annotation of documents in the
repository) generate and evaluate ideas. By work
ing asynchronously virtual team members can
pick and choose when they can make their con
tributions. This allows team members with diverse
backgrounds to have a different rhythm and pace
of generating their own ideas and digesting others’
ideas. Leaders also use asynchronous discussion
threads to identify areas of disagreements because
the discussion threads give members with different
language capabilities time to share their thoughts
in their non-native languages in ways that they
find difficult in synchronous (fast-paced audio
conference) sessions."
p. 64, para. 2

"Virtual team leaders feel that it is helpful to have
team members reconnect with the “human” side
of each individual, which helps to remind each
member of their similarities, as well as provide
them “boundary objects” or common metaphors
to work from during the meeting."
p. 65, para. 2

" by orchestrating virtual team meetings
carefully, virtual team leaders are able to reinforce
the team’s mission, increase team commitment
and participation, leverage the team’s collective
expertise, and reinforce the value of virtual team
membership. As one virtual team leader pointed
out, “The challenge was to command member atten
tion and focus in an era of multi-tasking.”"
p. 66, para. 2

" As one of the team leaders
we spoke with said: “Synchronizing the efforts of a
geographically, culturally, and technically diverse vir
tual team does not happen magically. .. .My first
priority is to build the kinds of working relationships
where team members will freely share knowledge,
leverage members’ collective expertise, anticipate each
others’ actions, and feel confident that all team mem
bers are making a full-fledged contribution to the
team’s success.”"
p. 68, para. 3

"in the context of a project manage
ment course, students could be assigned to work
virtually with other students taking similar courses
at universities in various parts of the world. The experience of working cross-culturally and virtu
ally introduces students to both the potential and
the challenges of working in virtual teams. In
structors can use these assignments to coach teams
at the “teachable moments” when they encounter
project management issues."
pp. 68-69, para. 8

### ChatGPT
"Side effects describe the broader, long
term, and often unexpected, consequences of
technology use (Zammuto et al., 2007). For
example, we found that employees go to ChatGPT
instead of to colleagues for advice. This is prob
lematic because within-firm knowledge sharing
and integration is a core ingredient for organiza
tional learning and competitive advantage (Azeem
et al., 2021) and arguably the fundamental pur
pose of organizations (Grant, 1996; Spender,
1996)."
p. 513, para 2

"For basic tasks, they feed ChatGPT with the kind of
instructions and context that would often be given
to a junior colleague. More complex, higher-level
questions were also posed to ChatGPT. For
example, insteadof turning toabusiness partner
for help with a task she is known to be proficient in,
ChatGPTwas seen as a more efficient place to turn." 
p. 515, para. 2

"I feel a bit more stupid. I feel like
very much depending on this technology. Like
right now, if you ask me to write something, I
start to feel scared. I don’t really trust my
behavior. I have to rely on this technology."
p. 515 para. 4

**Good examples of use in general but glaringly misses the dangers of entering IP information into Gen AI where it can be stored and accessed outside the control of the organisation.**
**Update:** *"On the other hand, fully unrestricted use of
ChatGPT can be risky due to, for example, hallu
cinations, legal issues such as unknowingly using
copyrighted text, **leaking sensitive data**, or over
reliance"* p. 520, para. 1
**Still a very small entry for such an important risk.**

"In this stage, it is no longer clear (even to
the user) what aspects of their work are human
and which are AI generated. As a side effect, it
becomes difficult to control the quality of knowl
edge that circulates within the organization and is
delivered to clients."
p. 518, para. 1

" First, incentivize interaction that is
related to work, such as collaborative working
practices to encourage opportunities for workers
to learn from one another. We do not advocate for
interaction for the sake of interaction (i.e., forced
fun). Interaction should be carefully tied into how
managers expect work to be done. Second, ensure
that interaction is live. Asynchronous working al
lows moments to ask ChatGPT, but real-time in
teractions are spontaneous and require quick
independent thinking and on-the-spot decision
making. It is important to ensure that such live
interactions are occurring regularly and are appropriately facilitatedwith resources such as
working spaces."
p. 519, para. 5

" A concrete
example for securing the talent bench is designing
mentoring programs where the importance of
tagging along to, for example, meetings and pre
sentations is highlighted. In addition, to ensure
succession, managers are advised to be cautious
about downsizing their entry-level workforce in
spite of the appearance of lowerworkload forthem
due to the efficiency gains from ChatGPT’s affor
dances, focusing instead on forecasting in demand
skill sets that need to be brought in and developed."
p. 520, para. 5



## Links
