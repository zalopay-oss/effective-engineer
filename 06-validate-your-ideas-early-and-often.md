# Validate Your Ideas Early and Often 

![](images/lean_startup.png)

- [Validate Your Ideas Early and Often](#validate-your-ideas-early-and-often)
	- [Find low-effort ways to validate your work](#find-low-effort-ways-to-validate-your-work)
	- [Continuously validate product changes with A/B Testing](#continuously-validate-product-changes-with-ab-testing)
	- [Beware the One-Person Team](#beware-the-one-person-team)
	- [Build feedback loops for your decisions](#build-feedback-loops-for-your-decisions)

> Optimizing for feedback as soon as posible - in other words, understanding what customers actually want and then iterating on that feedback

## Find low-effort ways to validate your work

> When building an MVP, you want to focus on high-leverage activities that can validate hypotheses about your users as much as possible, using as little effort as possible, to maximize the chances that the product will succeed.

Sometimes, building an MVP requires being creative. When Drew Houston first started building Dropbox, an easy-to-use file-sharing tool, there were already countless other file-sharing applications on the market. Houston believed that users would prefer the seamless user experience his product could provide—but how could he validate this belief? His solution was to make a short 4-minute video as his MVP. Houston demoed a limited version of his product, showing files synchronizing seamlessly across a Mac, a Windows PC, and the web...

We might not all be working on startup products, but the principles of validating our work with small effort holds true for many engineering projects.

One way to validate your ideas would be spend 10% of your effort building a small, informative prototype. Depending on your project goals, you can use your prototype for anything from measuring performance on a representative workload, to comparing the code footprint of the module you rewrote against the original module, to assesing the ease of adding new features.

The strategy of *faking the full implementation of an idea to validate whether it will work* is extremely powerful. At one point, Asana, a company that builds collaboration and task management software, was considering whether to implement a new Google Signup button on its home page. Its goal was to increase signups. `Rather than building the entire signup flow, they validated the idea by adding a fake signup button: when visitors clicked the button, a pop-up message appeared, reading, “Thanks for your interest—the feature is coming soon.”` Asana engineers measured the click-through rates over a few days, and only built out the full flow after the data confirmed that it would help with signups

The list of scenarios in which small validations can save your time goes on and on. 

- Maybe you have an idea of a scoring algorightm that you believe will improve ranking for a news feed. Rather than spending weeks building a production-quality system and running it over all the data, you can asses the new scoring metric on a small subset of data. 

- You may have a brilliant product design idea, rather than building it in code, you can hack together a paper prototype or low-fidelity mock to show your teammates or participants in user studies.

Takeaway lesson:

> Invest a small amount of work to gather data to validate your project assumptions and goals.

## Continuously validate product changes with A/B Testing

In an A/B test, a random subset of users sees a change or a new feature; everyone else in the control group doesn’t. An A/B testing framework typically assigns users to buckets based on their browser cookie, user ID, or a random number, and the bucket determines the product variant that they see. Assuming there’s no bias in bucket assignment, each bucket gets affected by traffic fluctuations in the same way. `Therefore, by comparing metrics across the experimental and control groups, any statistically significant differences can then be attributed solely to differences in the change’s variant`. A/B tests provide a scientific way of measuring the effects of the change while controlling for other variations, letting us assess the product’s impact if it’s launched to all users.

A/B tests also encourage an iterative approach to product development, in which teams validate their theories and iterate toward changes that work.

Building your onw A/B testing framework might seem daunting. Fortunately, there are many existing tools that you can use to test your product hypotheses. Free or open source A/B testing frameworks including:
- [Etsy's feature-flagging API](https://github.com/etsy/feature)
- [Vanity](http://vanity.labnotes.org/metrics.html)
- [Genetify](https://github.com/gregdingle/genetify/wiki)

If you want more tooling and support, you can pay a monthly fee for software like Optimizely, Apptimize, Unbounce...

> When deciding what to A/B test, time is your limiting resource. Hone into differences that are high-leverage and practically significant, the ones that actually matter for your particular scale

## Beware the One-Person Team

In hindsight, it’s clear that if I had just committed my code more iteratively and in chunks, my work wouldn’t have existed in isolation for so long and I would have eliminated a large amount of risk. My mentor would have had a much easier time reviewing my code, and I would have received valuable feedback along the way that I could have applied to future code. In the end, I got lucky: I learned a lesson about solo projects early in my career and with little cost.

While there isn't anything inherently wrong with the working on a one-person project, it does introduce additional risks, that if not addressed, can reduce your chance of success.

- First and foremost, it adds friction to the process of getting feedback - and you need feedback to help validate that what you're doing will work. It's hard to get good feedback on a code review, for instance, unless the reviewer works on your team and shares your project context. If you're `not mindful` of setting up a feedback loop, it can be empting to defer getting feedback on something until you think it's nearly perfect. And if you don't find out until the end that you've gone in the wrong direction, you'll waste a lot of effort.

- The lows of a project are more demoralizing when you're working alone. Sand traps that you struggle to get out of monotonous work that you need to grind through, and bugs that seem to defy all understanding become less draining and more bearable when there's someone there to share you pain. A single stall can grind the project to halt, causing deadlines to slip. And similarly, the highs can be less motivating when you're working alone. `Celebrating an achievement with teammates is a great way to boost morale`. If you work alone, who’s going to give you a high-five when you finally fix that frustrating data corruption bug?

Event if you find yourself working a one-peron project, don't despair:

- `Be open and receptive to feedback`: If you adopt a defensive mindset about your work, it will be difficult for you to listen to feedback - and people will be less willing to offer it in the future. `Instead, optimize for learning`. View feedback and criticism not as personal attacks but as opportunities for improvement

- `Commit code early & often`: Large code changes are hard to review, take longer to get feedback, and are a big waste of time and work if it turns out there's a desing flaw. Focus on making iterative progress, and use those iterative commits as forcing functions for soliciting feedback.

- `Request code reviews from thorough critics`: There is a large variance in the rigor with which different engineers review code. If you’re in a hurry to ship something, you might be tempted to send your code review to the engineer who skims and approves. `But if you’re optimizing for quality or if you want to make sure your approach works, you’ll find much more leverage asking for a code review from someone who gives thoughtful criticism`. It’s better to get harsh feedback from a teammate early on than to get it from users later when something doesn’t work.

- `Ask to bounce ideas off your teammates`: the most direct path to getting feedback is to request it. `Research shows that explaining an idea to another person is one of the best ways of learning it yourself; moreover, your explanation might reveal holes in your own understanding`

	> That said, if you want to keep the feedback channel open in the future, be respectful of your co-workers’ time. Prepare beforehand.

- `Design the interface or API of a new system first`: After your interfact is designed, prototype what the client code would look like if your feature were built. `Creating a concrete picture of the interactions will surface poor assumptions or missing requirements, saving you time in the long run`

- `Send out a design document before dvoting your energy to your code`

- `If possible, structure ongoing projects so that there is some shared context with your teammates`: Rather than working on a separate project in parallel with your teammates, consider working together on the same project and tackling the other project together afterwards. Or, consider working in the same focus area as your teammates.

> The goal of all these strategies is to overcome the friction of collecting feedback when you’re working alone so that you can validate your ideas earlier and more often. 

## Build feedback loops for your decisions

Whether you’re working on large implementation efforts, developing products, or working on teams, it’s important to build feedback loops to validate your ideas. But even more broadly, the principle of validation generalizes to any decision you make.


> “When I interviewed Nimrod Hoofien, a Director of Engineering at Facebook, he said that creating a feedback loop is necessary for all aspects of a job. “It applies to recruiting. It applies to team design. It applies to how you build your culture. It applies to your compensation structure,” Hoofien explained. “Any decision you make … should have a feedback loop for it. Otherwise, you’re just … guessing.”

Previously, when Hoofien was the Senior VP of Engineering at Ooyala, he experimented with various aspects of building effective engineering teams, and built feedback loops to learn from those experiments. For example, when figuring out the optimal number of team members to maximize effectiveness, Hoofien varied the size of the team and looked for obvious dysfunctions.

> "The most common dysfunction is that the team starts behaving like two teams and these two groups will only work on their side of the board"

The principle of validation show us that many of our work decisions, which migh take for granted or adopt blindly from other people, in fact are testable hypotheses.

Validation mean:

- formulating a hypotheis about what might work

- designing an experiment to test it,

- understanding what good and bad outcomes look like

-  running the experiment 

-   learning from the result:

