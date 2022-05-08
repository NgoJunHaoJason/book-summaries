# The Software Craftsman

*Professionalism, Pragmatism, Pride*

> by Sandro Mancuso

[O'Reilly link](https://www.oreilly.com/library/view/the-software-craftsman/9780134052625/)

---

## Contents

1. [Software Development In the 21st Century](#chapter-1-software-development-in-the-21st-century)
2. [Agile](#chapter-2-agile)
3. [Software Craftsmanship](#chapter-3-software-craftsmanship)
4. [The Software Craftsmanship Attitude](#chapter-4-the-software-craftsmanship-attitude)
5. [Heroes, Goodwill, and Professionalism](#chapter-5-heroes-goodwill-and-professionalism)
6. [Working Software](#chapter-6-working-software)
7. [Technical Practices](#chapter-7-technical-practices)
8. [The Long Road](#chapter-8-the-long-road)
9. [Recruitment](#chapter-9-recruitment)
10. [Interviewing Software Craftsmen](#chapter-10-interviewing-software-craftsmen)
11. [Interview Anti-Patterns](#chapter-11-interview-anti-patterns)
12. [The Cost of Low Morale](#chapter-12-the-cost-of-low-morale)
13. [Culture of Learning](#chapter-13-culture-of-learning)
14. [Driving Technical Changes](#chapter-14-driving-technical-changes)
15. [Pragmatic Craftsmanship](#chapter-15-pragmatic-craftsmanship)
16. [A Career as a Software Craftsman](#chapter-16-a-career-as-a-software-craftsman)

Appendix: [Craftsmanship Myths and Further Explanations](#appendix-craftsmanship-myths-and-further-explanations)

---

## [Chapter 1] Software Development in the 21st Century

We should choose our career path according to our passion.

### Seniority

Seniority is transient and relative; there is no such thing as a senior or junior developer.

### A new reality

Good programming practices and techniques can be applied in many different environments and types of systems, but coding is just one of the things that modern developers do.

In this new reality, where the cost of bugs can bankrupt a company, companies are demanding professional software developers instead of cheap coders who do whatever they are told to do.

[back to contents](#contents)

---

## [Chapter 2] Agile

Agile is a combination of methodologies that can help teams adapt to the ever-changing nature of software projects. The Agile disciplines can be divided into two groups: process-oriented and technical-oriented.

**Process-Oriented Disciplines** help the team to focus on what is valuable to the business, to ensure the team is *building the right thing*.

**Technical-Oriented Disciplines** help the team to focus on the quality of the software, to ensure the team is *building the thing right*.

### What it means to be Agile

We don't *do* Agile. Either we *are* Agile or we *are not*.

Agile methodologies are all about short feedback loops. When we react to some feedback, the act of reacting to new information is what makes us more agile.

Narrowing the feedback loop helps us to make problems visible sooner, allowing us to inspect and adapt quickly. Agile does not solve any problems; it exposes them.

### [Manifesto for Agile Software Development](https://agilemanifesto.org/)

> We are uncovering better ways of developing software by doing it and helping others do it.  
Through this work we have come to value:

:heavy_check_mark: *Individuals and interactions* over processes and tools  
:heavy_check_mark: *Working software* over comprehensive documentation  
:heavy_check_mark: *Customer collaboration* over contract negotiation  
:heavy_check_mark: *Responding to change* over following a plan  

> That is, while there is value in the items onthe right, we value the items on the left more.

### The Agile Hangover

> Many Agile projects are now, steadily and iteratively, producing crap code.

Many companies had a partial Agile transformation

They hired consultancies and Agile coaches to help them change their *process*. However, they got little help to get better at writing quality software.

As a result, companies started to realise that after all this transformation, they were still not delivering quality software fast enough.

The new apps, built in an Agile fashion, were as complex and buggy as apps developed before the Agile transformation.

### Agile versus Software Craftsmanship

Software Craftsmanship is *not* here to replace Agile; it is here to complement Agile.

Agile helps companies to do the *right thing*. Software Craftsmanship helps developers and their companies to do the *thing right*.

[back to contents](#contents)

---

## [Chapter 3] Software Craftsmanship

Software Craftsmanship is *not*:

:x: Beautiful code  
:x: Test-Driven Development  
:x: A self-selected group of people  
:x: Specific technologies or methodologies  
:x: Certifications  
:x: Religion  

**A short definition:**

> Software Craftsmanship is about professionalism in software development.

### [Manifesto for Software Craftsmanship](https://manifesto.softwarecraftsmanship.org/)

> As aspiring Software Craftsmen we are raising the bar of professional software development by practicing it and helping others learn the craft.  
Through this work we have come to value:

:heavy_check_mark: Not only working software, but also *well-crafted software*  
:heavy_check_mark: Not only responding to change, but also *steadily adding value*  
:heavy_check_mark: Not only individuals and interactions, but also *a community of professionals*  
:heavy_check_mark: Not only customer collaboration, but also *productive partnerships*  

> That is, in pursuit of the items on the left we have found the items on the right to be indispensable.

**Not only working software, but also well-crafted software**

An application may be working, but is poorly-crafted. When we encounter the code of such a software, we are afraid to change it over fear of breaking something.

For the software to remain maintainable, we must not shy away from changing its code. TDD, having a simple design and well-expressed business language can give us the confidence to change it.

**Not only responding to change, but also steadily adding value**

It is our job to make sure that the older and bigger the software gets, the more the company will benefit from it. We want to keep adding features at the same speed we have at the beginning of the project.

A paraphrase of a Boy Scout rule states that we should *always leave the code cleaner than we found it*.

The focus on software quality must be the number one priority if we want long-lived applications.

**Not only individuals and interactions, but also a community of professionals**

We are responsible for preparing the next generation of craftsmen. The best way to move our industry forward is by sharing what we learnt, through mentoring and inspiring less-experienced developers.

Learning from each other is the best way for us to become better. Some ways we can do so are to: write blogs, contributing to open source projects, joining local communities and pair programming.

This applies to our work environment. We want to work with people who can make us better, and are willing to share and learn from each other.

**Not only customer collaboration, but also productive partnerships**

We don't believe in the employer/employee type of relationship. We believe in a partnership, in which the company is the customer and the software developer is the one providing a service.

Although extremely important, writing code is just one of the things we need to do to help the project succeed. Other things include: 

- improving processes
- removing unnecessary bureaucracy
- understanding business domain
- questioning requirements in relation to the value they provide
- working on other non-coding tasks.

The core business of many of our clients is not building software, so it is our obligation to help them run a software project in the best way possible.

### But some clients are not ready for a productive partnership...

For some companies, software developers are there just to follow orders / be micro-managed.

Working for these companies is always difficult. We should always try our best to turn this situation around, and try to prove to our clients we could help them far more if they let us.

However, there is a limit to the efforts we can make to help our clients. Knowing how to select clients is also an essential skill for us; we should find another client if we find that the partnership is not good for us.

[back to contents](#contents)

---

## [Chapter 4] The Software Craftsmanship Attitude

If we think that a piece of code we wrote some time in the past is still good enough today, it means we didn't learn anything since.

### Who owns your career

We, as software professionals, own our career. This means we should use our time and money to get better at what we do.

Companies should still invest in their people. However, we should not see that as their obligation, but as a bonus / win-win situation.

### Keeping ourselves up to date

**Books**, be they physical or electronic, are essential.

- *Technology-specific books* are valuable but they expire. They are essential for the immediate need, when we need to learn a new technology. (Example: books on JavaScript)
- *Conceptual books* give us the foundation to advance in our career. Learning new concepts, paradigms and practices is far harder than learning a specific technology, and it may take years for us to be comfortable with them. (Example: books on functional programming)
- *Behavioural books* make us more efficient when working in teams, and be better professionals in general. (Example: books on Agile methodologies)
- *Revolutionary books* (a.k.a. classics) change the way we work or even our personal values. They define the direction of our industry. It may take many years to master the content of these books. (Example: The Mythical Man-Month)

**Blogs** are a great way to keep ourselves up to date.

**Technical websites** are also good for ourselves up to date with what's going on in the market.

**Social media** can be a good tool for information gathering. There are people who contribute massively to move our profession - know who they are and follow them.

### Practice

How it is done is as important as getting it done.

If we want to be good at writing quality code, we need to practice writing quality code. When practicing, the focus should be on the techniques we are using and not in solving the problem.

We should not worry if we take a long time. As long as we tried our best, we should feel great.

**Katas** are simple coding exercises, and are a perfect way to try new techniques and approaches.

**Pet projects** are real projects but without pressure. They are helpful for us to experience several aspects of a real project while having fun.

Contributing to **open source** projects is also a great way to practice, and to see great developers in action.

**Pair programming** is more a social activity than a technical practice, and it helps bring developers together. If we keep our minds open while pairing, we can learn new things.

### Socialise

Finding other developers whome we can bounce ideas off of, pair-program with, and network is essential for a successful career. A great way to do that is to join the local technical community.

### Deliberate discovery

We should always try to create opportunities where we can learn something we don't know.

### Work-Life Balance

Quite often, lack of time is used as an excuse for our own laziness. Do pastimes in moderation instead of spending all free time on them.

One way to help us keep our focus, to use our time wisely, is to use the Pomodoro technique.

Keeping our professional life healthy is essential for a healthy family life. If we are constantly worried about our pay or being made redundant, we may damage our personal lives.

[back to contents](#contents)

---

## [Chapter 5] Heroes, Goodwill, and Professionalism

Very often, we have to deal with very hard deadlines. The best way to deal with them is to analyze everything that needs to be done and raise all possible risks we see and concerns we have.

Most importantly, we need to to state how much we could confidently deliver (i.e. tested and tried in a production-like environment) by the expected date.

When developers say they cannot confidently deliver all features by an imposed deadline, they usually succumb to their manager's pressure by saying "We will try our best".

Saying "try" results in two things:

1. the manager understand that the developers are going to deliver it
2. the developers are implying that they normally don't try their best, which is unprofessional

We usually don't like to say no. However, saying yes (or "will try") to avoid disappointment is just lying. Although doing so looks positive, it is also very selfish. When we say yes, people will take that into account and make plans base on it.

Not being honest and transparent may cause huge damage to the company. Professionalism means being honest with ourselves, our teammates, our managers and our customers.

If we feel that our managers are not being transparent with their boss, we should do the right thing, which includes escalating the issue if need be. As long as we do it in an honest and transparent way, there is a big chance no one will get hurt, and the team and company will win.

### Providing options

Always saying no is also not a professional attitude. Ideally, every no should be followed by a list of alternatives.

Saying no without providing options does not help much because the person receiving our answer will not be able to do much with it.  
Before saying no, we need to analyze the problem and provide options, or at least brainstorm ideas; an incomplete idea can help people find a different alternative.

Sometimes, there are problems that we simply don't know how to solve. When this is the case, we should say it as honestly and as quickly as possible.

We should also demonstrate we are willing to investigate the problem and give our best shot at solving it, making it clear we are *not* making any promises besides sharing what we learn.

Providing updates of our progress as often as we can allows the team to make use of each piece of new information, by contributing other ideas or offering help in areas where they have a better understanding.

This behavior will make the team trust us when we say we know something. Being honest, no matter how bad the situation, is a sign of professionalism.

### Enlightened managers

Good managers understand they are part of the team and need to work with the developers toward the common goal.

Managers should appreciate when we say we cannot deliver certain features. Raising red flags as early as possible, indicating something is wrong, allows the team and all people involved to be pragmatic and come up with alternative solutions.

Enlightened managers understand and expect that certain things are not easy to do or may take a long time to be done. They appreciate when they are challenged and different options are suggested. This attitude shows that everyone is working as a team towards a common goal.

[back to contents](#contents)

---

## [Chapter 6] Working Software

Some say that good and clean code is not enough to guarantee the success of a project; they are right since there are innumerable reasons for a software project to fail.

However, working software is not enough as well.

### Looking after our garden

Like a garden, if we neglect our code base even for a short period of time, it will require much more effort to make it look good again.

Bad design choices, lack of tests, and poor use of language and tools will make the code rot faster, to the point it is painful and costly to maintain it.

### Hostage of your own software

When the code base gets into the situation where additional features take too long to be implemented and developers are scared to touch the existing code, action must be taken immediately.  
This is a very dangerous situation to be in because business progress is being impeded by software instead of being helped by it.

It is *totally* unacceptable to have bad quality code affecting business decisions.

The biggest problem here is that bad code is invisible to everyone besides the developers; others only realise that something is wrong when it is too late. That means it is the developers' responsibility to look after the quality of the code.

Sometimes, developers expose the problem to their managers, but the request to have some time to refactor the code is often ignored for various reasons.

Note that when developers get to a point where they need to ask for some formal time to do refactoring, it means that they neglected the code at some point in the past.

### The wrong notion of time

Adding items to a technical debt backlog is a way developers use to justify the bad code they have written without feeling guilty about it.

Developers may have saved some time for themselves by cutting corners, but it would result in time wasted for quality assurance engineers as well as other developers.

TODO? :thinking:

[back to contents](#contents)

---

## [Chapter 7] Technical Practices

There is a real business value to using certain technical practices.

### The right thing vs the thing right

With a few exceptions, Agile methodologies are better than waterfall and other heavyweight methodologies. They provide a short feedback loop, which helps ensure we are building the right thing.

However, we cannot measure the quality of our applications through Agile practices. 

Software Craftsmanship complements Agile by focusing on technical practices and providing a short feedback loop on the *quality* of our code.

Technical practices help ensure we are building the thing right.

### Practices and values

Extreme Programming (XP) practices provide us with many ways to shorten the feedback loop regarding software quality. However, practices don't magically work just because they are adopted.

Practices are what we consistently do on a daily basis: we either do TDD or not; we either have continuous integration or not.  
Practices must be backed by values, which are shared by all members of the team, to be efficient. An example of a value is wanting to be better.

Values are things are live by; they are recognised based on our actions, not what we say. Practices are the validation of our values.

When trying to convince managers or team members to adopt certain practices, focusing on the practices themselves would not work.  
Instead, discuss the benefits they bring and how they compare to the team's current practices.

### Automated Testing

Automated testing shortens the feedback loop on the correctness of our code from weeks to minutes, enabling us to correct any mistakes almost immediately.

It gives us the confidence to deploy our application into production minutes after the last change was made.

This confidence - that adding new features speedily don't break the system - is the business value automated testing provides.

### Test First

Writing tests first helps us to just write enough code to satisfy the requirements, keeping the code simple; it reduces complexity and overengineering

### Test-Driven Development (TDD)

TDD is an evolution of test first.

Although TDD has "test" in its name, TDD is actually a design practice. When test-driving our code, it becomes difficult to write complex code.

Firstly, writing just enough code to satisfy the requirements / tests would discourage overengineering.

Secondly, complexity in our code is highlighted by the complexity in maintaining and writing new tests.

Using TDD provides a far shorter and objective feedback loop on the design of our code as compared to design reviews.

### Continuous Integrations

In a large project, we can have multiple teams spread across different locations and time zones making changes to the same code base.

Continuous integration, combined with automated tests, helps ensure that the application does not break after someone introduce a change.

### Pair Programming

Code review is commonly used to guarantee code quality, and to spread knowledge of the system and good coding skills to the team.  The problem is that this feedback loop depends on the frequency of code reviews.

Pair programming avoids this problem by giving immediate feedback on the quality of the code written. The other developer can immediately point out when a name is unclear or a function is too big.

Rotating pairs frequently can improve the collective understanding of the entire system and level up developers' skills. It also helps developers define and maintain coding standards.

### Refactoring

Messy code makes developers go slowly, which causes the business to slow down. Constantly refactoring our code mitigates the risk of it becoming messy.

Refactoring without pragmatism can be a dangerous practice. We should focus on refactoring code we need to change or understand.

### Accountability

We should all be accountable for our own decisions - not only for the decision of adopting certain practices, but also for the decision of *not* adopting them.

This applies not just to developers, but to managers as well. We should record these decisions and escalte the issue if necessary.

### Pragmatism

Technologies, methodologies and practices are constantly emerging and evolving; there is always a better way of doing things.

As software craftsmen, we should be pragmatic by choosing the best technologies, methodologies and practices for the job.

If certain practices are not giving us value anymore, we should stop using them. If we find a practice that is better than what we do today, we should adopt this better practice.

[back to contents](#contents)

---

## [Chapter 8] The Long Road

Everyone wants to be good at something. The motivations may vary but one thing is true for all of us: mastering something gives us pleasure.

Our career is a long and hard road to mastery that we must be willing to walk.

### Focus and Determination

Defining the direction we want to go in our careers is important.   It is a long-term goal and many things can change. We have to keep evaluating the sub-goals and adapt when necessary.

When we are not sure where we want to go with our careers, we can create opportunities for ourselves. Some example include:

1. Expanding our technical knowledge, like learning a new language
2. Attending technical community events
3. Networking with other people
4. Blogging about the things we are learning and doing

### Job as investment

Software craftsmen treat every single job as an investment, a step towards a bigger goal.

We invest our knowledge, passion, time, dedication and professional attitude in our job. Therefore, like any other types of investment, we need to be clear about what we expect as a return, and measure it regularly throughout the length of that investment.

Knowledge is the most common return on investment expected from a job.

Our personal lives also play an important role in our career decisions. Sometimes we just need more money, and that is okay. Sometimes we want more stability, security and work-life balance for our family.

When it comes to our career, there is no right or wrong. However, we should keep in mind that knowledge is forever; money, stability and security are not.  
If our job is terminated, knowledge and experience are the only things we can take with us. Being a software craftsman, and hence getting the knowledge and experience, makes finding jobs a lot easier.

> Note: Expecting a return on investment from jobs should not be confused with the selfish and unprofessional attitude of "CV building", where developers choose technologies and methodologies to improve their CVs instead of what is best fit for a purpose.

### Autonomy, Mastery and Purpose

Assuming money is off the table, knowledge workers are motivated by three things:

**Autonomy** - It is when we are in control of what we do, how we do it and when we do it; which should always be the case in a true Agile context

**Mastery** - It is when we are constantly learning and evolving

**Purpose** - It is when we feel our job is important and we are contributing to make things better, instead of just doing what we are told without understanding why

The assumption of money being *off* the table is very important - when our basic needs are not satisfied, it is very difficult to focus and do our job well.

Software craftsmen always choose jobs where they have autonomy, mastery and purpose, instead of choosing jobs just for the money.

### Career inside companies

Our careers will always be more important than any specific job or company. Pursuing a career inside a company is not the same thing as pursuing our own career.

If our job is aligned with our career aspirations, then pursuing a career inside the company is the right thing to do. However, if pursuing a career inside a company means we would deviate from our long-term career aspirations, we should probably find another job regardless of how well we are paid.

[back to contents](#contents)

---

## [Chapter 9] Recruitment

TODO :persevere:

[back to contents](#contents)

---

## [Chapter 10] Interviewing Software Craftsmen

TODO :persevere:

[back to contents](#contents)

---

## [Chapter 11] Interview Anti-Patterns

In order to attract software craftsmen, it is important to know what to avoid when conducting interviews.

### Don't be a smart-ass interviewer

**Don't try to make the candidate look like a fool** - Simply put, don't be an ass. Nobody would want to work with you.

### Don't ask questions that are irrelevant to the job

**Don't use brainteasers** - The ability to answer them has nothing to do with writing well-crafted code, being a team player, or having a professional attitude.

**Don't ask questions to which you don't know the answer** - If you are unsure about the questions and respective answers, they are probably not important to the job.

**Don't use algorithms** - If the main problems we have in our system are not about algorithms, we should not use them in our coding interviews. (If our application is all about algorithms, then we should definitely test for that.)

### Don't conduct interviews in an environment dissimilar to the job

**Don't block the internet** - Being able to research solutions and better ways to solve problems is an essential skill for any software developer.

**Don't code on a piece of paper** - It does not reflect the reality the candidate will face if they get the job.

**Don't conduct phone interviews** - Phone interviews tend to be quite dry, with a series of questions and answers, without much time for a proper conversation.

[back to contents](#contents)

---

## [Chapter 12] The Cost of Low Morale

Low morale can be one of the main reasons for a software project to fail, or even bring the whole company to a halt.

From this chapter onwards, it is assumed that your team's process is based on a combination of Agile processes and disciplines.

This includes:
- working in a cross-functional team
- having daily stand-ups
- working in short iterations (sprints)
- being empowered to estimate the work
- being able to decide what to work on according to priorities
- having a unified backlog prioritised by the product owner
- letting developers be responsible for testing the application

### The Agile hangover: low morale

After a few years Agile transformation, many companies realised their software delivery capability is still very poor.

A common problem found in all these companies is low morale. People complaint about the people they work with and how uninspiring their jobs are. They felt they were not being treated as skilled professionals - who could contribute not only code, but also ideas to make the company better.

Adopting Agile should have been able to easily provide knowledge workers what they need the most to enjoy their jobs: autonomy, mastery and purpose.

The issue is that Agile transformations, although having the positive impact of shortening the feedback loop and improving visibility, did little to make developers better. Old-time developers were still resistant to change the way they work, while newcomers and younger developers struggle to have their voices heard.

For these companies, the outcome of their Agile adoption was developers mechanically following a new process, but still developing software exactly how they were before. If they were not motivated before, they were certainly not motivated after.

### The cost of employing 9-to-5 developers

For many passionate developers, the right thing to do with 9-to-5 developers is to fire them all.

Lack of passion is not what really bothers passionate developers; what frustrates them is to be held back by other developers when they are trying to improve their applications and the way they work.

Having 9-to-5 developers instead of passionate developers in a company would end up costing the company a lot of time and money, due to their poor software delivery capability.

### Constrained by lack of motivation

Every company has problem. However, a lot of employees don't do anything to improve things. The most common reasons include:

1. they don't feel empowered to do it
2. they don't want to be the ones pushing it
3. they find it to be too much hassle
4. they don't believe that things can be changed
5. No one agrees on what the better thing is
6. They don't care; it is *just* a job to them

### Injecting passion

Embedding software craftsmen in a team, either hiring them permanently or bringing on external craftsmen for a period of time, is the most effective way to motivate existing developers.

Software craftsmen are on a mission to make things better, deliver value to their clients and inspire people around them. They are not afraid to lead the way and drive changes.

There is nothing more annoying for a developer than having a manager dictating what she should do. Instead of just telling others what to do, software craftsmen can pair with developers, sharing their knowledge, experience and passion. Besides getting the work done, they are always keen to act like mentors to many other developers.

[back to contents](#contents)

---

## [Chapter 13] Culture of Learning

No change can be made effectively if the people involved are not motivated or don't really care about their jobs.

### Wrong motivation

We will never change an organisation by forcing people to adopt a new process or different practices.

Instead, we should create a culture of learning, where people can find their own motivation to make things better.

### Creating a culture of learning

Creating a culture of learning is one of the most efficient ways of injecting passion into a company.

However, it should not be imposed upon the developers how, when and what they should learn, because then it becomes an obligation, which in turn leads to a lack of interest.

Instead, developers should be given the freedom to decide how, when and what they want to learn, hence embracing a culture of learning.

The better the developers are, the more innovative and agile the company can be. If the company becomes a place where developers are happy, many other good developers will be attracted to it.

There are many things developers can do to create such an environment:

**Start a book club** - Pick a book to start reading, and see if anyone is interested in having a discussion about it, typically once a week.

**Have a tech lunch** - Ask your team if they would like to have lunch together while talking about technical stuff once a week. Make the meeting about learning, not about work.

**Have group discussions (roundtables)** - TODO :persevere:

**Switch projects for an iteration** - Let members of different teams / projects swap with each other for an iteration. Doing can bring about reduced monotony, help in the validation of decisions, facilitate knowledge sharing and lead to improvements.

**Switch projects for a few hours** - A variation of the previous approach; pairing with someone on a different team can expose team members to different technologies.

**Conduct group code reviews** - If done right, group code reviews can bring the whole team together; everyone feels responsible for the decisions of what constitutes quality for them.

**Have hands-on coding sessions** - These are sessions where developers get together to work on an exercise, in pairs. It provides the opportunity for developers to learn from each other.

**Start internal communities of practice** - TODO :persevere:

**Encourage pet-project time** - TODO :persevere:

**Engage with external technical communities** - TODO :persevere:

### What if others don't want to join in?

TODO :persevere:

**Be an example** - TODO :persevere:

**Focus on thos who care** - TODO :persevere:

**Don't force** - TODO :persevere:

**Don't try to change everyone** - TODO :persevere:

**Avoid concensus delays** - TODO :persevere:

**Don't ask for authorisation** - TODO :persevere:

**Don't complicate** - TODO :persevere:

**Establish a rhythm** - TODO :persevere:

[back to contents](#contents)

---

## [Chapter 14] Driving Technical Changes

TODO :persevere:

[back to contents](#contents)

---

## [Chapter 15] Pragmatic Craftsmanship

TODO :persevere:

[back to contents](#contents)

---

## [Chapter 16] A Career as a Software Craftsman

TODO :persevere:

[back to contents](#contents)

---

## [Appendix] Craftsmanship Myths and Further Explanations

TODO :persevere:

[back to contents](#contents)
