# Invest in your team's growth

![](images/team-growth.jpg)

- [Invest in your team's growth](#invest-in-your-teams-growth)
	- [Make hiring everyone's responsibility](#make-hiring-everyones-responsibility)
	- [Design a Good onboarding process](#design-a-good-onboarding-process)
	- [Share ownership of Code](#share-ownership-of-code)
	- [Build Collective Wisdom through Post-Mortems](#build-collective-wisdom-through-post-mortems)
	- [Build a great engineering culture](#build-a-great-engineering-culture)

> One of the biggest lessons I learned from Ooyala is that investing in a positive, smooth onboarding experience is extremely valuable. 

Investing in onboarding is just one way to invest in your team’s growth. `The people and the team that you work with have a significant impact on your own effectiveness—and you don’t have to be a manager or a senior engineer to influence your team’s direction`. For some people, developing a team may be less enjoyable than developing software. `But if you want to increase your effectiveness, it’s important to recognize that building a strong team and a positive culture has a considerable amount of leverage.`

> The higher you climb up the engineering ladder, the more your effectiveness will be measured not by your individual contributions but by your impact on the people around you.

Companies like Google, Facebook, and others all have similar criteria for senior engineers, staff engineers, principal engineers, distinguished engineers, and their equivalent positions: the higher the level, the higher the expected impact.

> "You’re a staff engineer if you’re making a whole team better than it would be otherwise. You’re a principal engineer if you’re making the whole company better than it would be otherwise. And you’re distinguished if you’re improving the industry."

> "The secret to your own career success is to “focus primarily on making everyone around you succeed."

## Make hiring everyone's responsibility

Interviewing new engineering candidates can feel bothersome. It interrupts productivity and breaks up our day, and it’s time-consuming to write feedback on candidates and debrief with the team. `If the recruiting pipeline is not set up well, interviews can feel like hit-or-miss sessions with unqualified candidates who bomb our questions`

It’s only when we look at interviews in the aggregate do we realize that hiring is an extremely high-leverage activity. The smaller the company—and the more likely that the person you interview will be an immediate co-worker—the greater the leverage of those interviews.

So how do we design an effective interview process? A good interview process achieves two goals:

- It screens for the type of people we likely to do well on the team

- `It gets candidates excited about the team, the mission and the cultures`. Even if a candidate goes home without an offer, they still leave with a good impression of the team and refer their friends to interview with the company.

As an interviewer, your goal is to optimize for questions with high signal-to-noise ratios - questions that reveal a large amount of useful information (signal) about the candidate per minute spent, with little irrelevant or useless data (noise)

The types of questions that generate the most signal depend on the qualities most correlated with success on your team. Traditionally, many large technology companies like Google, Microsoft, Facebook, and Amazon require engineering candidates to answer algorithm and coding questions on a whiteboard. `These textbook-style questions evaluate a candidate’s computer science knowledge, but they can often fall short in gauging whether an engineer actually gets things done in a work environment.`

An increasing number of companies have shifted toward interviews that include a hands-on programming component. 

- At Quora, for example, we augmented our suite of whiteboard interviews with a practical coding exercise on a laptop. Candidates navigated around, debugged, and extended a large, open-source codebase in their favorite text editors, and they used Google, Stack Overflow, or other online resources as needed. The exercise revealed whether someone could effectively use a terminal, invoke basic UNIX commands, dive into unfamiliar libraries, set up a tight development loop, and write clean code—all of which were valuable signals not well captured by the traditional whiteboard interview.

- At the payments startup Stripe, the team similarly designed its `on-site interviews` to simulate the work that their engineers do on a day-to-day basis. Problems included designing and implementing a small end-to-end system, squashing bugs in a popular open-source codebase, refactoring a poorly organized application, and pair programming on a self-contained project.

`Perhaps trickier than the choice of questions is how to continuously iterate on improving your interview process.`

- Take time with your team to identify which qualities in a potential teammate you care about the most:
	- coding aptitude
	- mastery of programming languages
	-  algorithms, data structures
	-  product skills
	-  debugging
	-  communication skills
	-  culture fit, or something else.

- `Periodically meet to discuss how effective the current recruiting and interview processes are at finding new hires who succeed on the team.` Keep on iterating until you find ways to accurately assess the skills and qualities that your team values

- `Design interview problems with multiple layers of difficulty that you can tailor to the candidate’s ability by adding or removing variables and constraints`. Building a fast search interface can, for instance, be made harder by requiring the search query to be distributed across multiple machines.

- Control the interview pace to maintain a high signal-to-noise ratio. Don’t let interviewees ramble, get stumped, or get sidetracked for too long.

- `Scan for red flags by rapidly firing short-answer questions to probe a wide surface area.`

- Periodically shadow or pair with another team member during interviews. These sessions help calibrate ratings across interviewers and provide opportunities to give each other feedback on improving the interview process

## Design a Good onboarding process

In a small team, there aren’t many places to look or people to consult when you’re trying to figure out what’s most important. As the team grows and the surface area of new things to explore increases, it becomes harder and harder for a recent hire to figure out what to learn first without any guidance.

A quality onboarding process is a powerful leverage point for increasing team effectiveness. First impressions matter.

> So I researched Google’s EngEDU training program and Facebook’s 6-week Bootcamp onboarding program, and I reached out to engineers at different companies to learn what had and hadn’t worked for them. Based on my research, I formally defined the role of `engineering mentorship` at Quora and organized a recurring series of onboarding talks.

One component of Quora's new onboarding program is `pairing each hire with a mentor`. Mentors assign small features or bugs from their task list to do as a starter project. These are great learning opportunities for new hires, since the mentors have context for each project and can provide guidance and answer questions. It also frees mentors to shift their attention from less-interesting tasks to higher-leverage projects that they are better suited to tackle. `Onboarding is a win-win situation`; the new hires receive valuable training, and the mentors get more things done.

> Insufficient training means it’s harder to accurately identify low performers—are they doing poorly because they were bad hires, or do they just need more time to acclimate?

So how do you create a good onboarding process for your team?

- First, identify the goals that your team wants to achieve.
  
- Second, construct a set of mechanisms to accomplish these goals.

For examples, here are four goals:

- `Ramp up new engineers as quickly as possible.` Onboarding does require a short-term productivity hit for those leading it. The sooner new employees get ramped up, however, `the sooner they’ll produce meaningful output—enabling the team to get more done in the long run`

- `Impart the team's culture and values`: Those values might include getting things done, being data-driven, working well as a team, building high-quality products and services...

- `Expose new engineers to the breadth of fundamentals needed to succeed`.

- `Socially integrate new engineers onto the team`. This means creating opportunities for them to meet and develop working relationships with other teammates.

Using these above goals, we developed the four main pillars for Quora's onboarding program:

- `Codelabs`: A codelab is a document explaining why a core abstraction was designed and how it's used, walks through relevant parts of its core internals, and supplies programming exercises to validate understanding. We created codelabs to teach new engineers the fundamentals of how we built Quora

	> I invested extra effort to create the first codelab that others could `use as a model`; I then `scaled the effort` by recruiting teammates to pitch in

- `Onboarding talks`: We organized a series of ten onboarding talks to be delivered during a new hire's first three weeks. These talks, given by senior engineers on the team, introduced the codebase and site architecture, explained and demoed our different development tools, covered engineering expectations and values around topics like unit testing, and introduced `key focus areas`

- `Mentorship`: Because each new hire’s background is different, onboarding programs can’t be one-size-fits-all. Quora paired each new hire with a mentor to provide more personalized training during their first few months. Mentors checked in daily with their mentees during the first week, and then met for weekly 1:1s. Responsibilities included everything from reviewing code, discussing design tradeoffs, and planning work priorities, to introducing new hires to the right people on the team and helping them acclimate to the fast pace of a startup. `Quora also held mentoring workshops and meetings to exchange tips and help mentors improve.`

- `Starter tasks`: New engineers pushed commits to add themselves to the team page on their first day, and we aimed for each of them to complete a starter task—whether it be deploying a bug fix, a small new feature, or a new experiment—by the end of the first week

> “It’s important to realize that building a good onboarding program is an iterative process.”

## Share ownership of Code

There’s a common misconception that being the sole engineer responsible for a project increases your value. After all, if fewer people know what you know, then the scarcity of your knowledge translates into higher demand and value, right? `What I’ve learned, however, is that sharing code ownership benefits not only yourself but your entire team as well`. As you increase in seniority, your responsibilities as an engineer also grow. You become the point-person for more projects, and other engineers consult with you more frequently.

To increase shared ownership, reduce the friction that other team members might encounter while browsing, understanding, and modifying code that you write or tools that you build. Here are some strategies:

- Avoid one-person teams

- Review each other's code and software designs

- Rotate different types of tasks and responsiblities across the team

- Keep code readable and code quality high

- Present tech talks on software decisions and architecture

- Document your software

- Document the complex workflows or non-obvious workarounds necessary for you to get things done.

- Invest time in teaching and mentoring other team members

## Build Collective Wisdom through Post-Mortems

In our haste to get things done, we often move from task to task and project to project without pausing to reflect on how effectively we spent our time or what we could have done better. `Developing the habit of regular prioritization provides one opportunity for retrospection`. `Another valuable opportunity comes from debriefing after incidents and projects and sharing lessons more widely across other teams`

The goal of the post-mortem is not to assign blame, which can be counter-productive to the discussion, but to work together to identify better solutions. If the situation is not preventable, the post-mortem may prompt the team to:

- build new tools to recover easier

- compile a step-by-step document that explains how to deal with similar situations

The post-mortem write-up generally gets shared across teams, since many people in the organization want to know what happened.

Companies like Amazon and Asana use methodologies like Toyota’s “Five Whys” to understand the root cause of operational issues. For examples: 

- Why were they overloaded?” Because a disproportionately high fraction of traffic was hitting a few servers.

- Why wasn't traffic more randomly distributed? Because the requests were all coming from the same customer, and their data is only hosted on those machines.

> “By the time the fifth why is asked, they’ve moved from the symptom to the root cause.”


Ultimately, compiling team lessons is predicated upon honest conversation—and holding an honest conversation about a project can be uncomfortable. 

- It requires acknowledging that months of effort may have resulted in failure, and viewing the failure as an opportunity for growth.

- It requires aligning behind a common goal of improving the product or team, and not focusing on where to assign blame. 

- It requires being open and receptive to feedback, with the goal of building collective wisdom around what went wrong and what could’ve been done better.

But if a difficult hour-long conversation can increase the chances that your next month-long team project succeeds, it’s high-leverage and well worth both the time and the emotional investment.

It’s difficult to instill a culture of collective learning into an entire organization. However, consistent applications of effort can go a long way. `Start with small projects that you’re working on with your immediate team; gradually establish the practice of doing post-mortems after larger projects as well. The more you learn from each experience, the more you’ll take with you into your next project, and the more you’ll succeed`. Optimize for collective learning

## Build a great engineering culture

`Engineering culture consists of the set of values and habits shared by people on the team, and a great culture provides a number of benefits.` Engineers feel empowered to get things done, which makes them happier and more productive. Happy and productive engineers in turn translate to `higher employee retention`. The culture provides a shared context and a framework for making decisions, which helps teams and organizations adapt more quickly to problems they encounter. And because the best engineers look for a strong engineering culture, `it becomes a useful tool for recruiting talent`. Hiring those engineers further strengthens the culture and creates a positive feedback loop.

So what do the best engineers look for in a prospective company?

- 1. Optimize for iteration speed
- 2. Push relentless towards automation
- 3. Build the right software abtractions
- 4. Focus on high code quality by using code reviews
- 5. Build shared ownership of code
- 6. Maintain a respectful work environment
- 7. Invest in automated testing
- 8. Allot experimentation time, either through 20% time or hackathons
- 9. Foster a culture of learning and continuous improvement
- 10. Hire the best

`A great engineering culture isn’t built in a day`; nor is it already in place when a company first starts. `It begins with the values of the initial team members`, and `it’s a continual work-in-progress that every engineer helps to shape`. It evolves over time with the decisions we make, the stories we tell, and the habits we adopt. It helps us make better decisions, adapt more quickly, and attract stronger talent. And when we focus on high-leverage activities, we not only become more effective engineers, we also lay the groundwork for a more effective engineering culture.

