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

TODO :persevere:

---

## [Chapter 2] Agile

Agile is a combination of methodologies that can help teams adapt to the ever-changing nature of software projects.  
The Agile disciplines can be divided into two groups: process-oriented and technical-oriented.

**Process-Oriented Disciplines** help the team to focus on what is valuable to the business. Using these methodologies ensure the team is *building the right thing*.

**Technical-Oriented Disciplines** help the team to focus on the quality of the software, and to ensure the team is *building the thing right*.

### What it means to be Agile

We don't *do* Agile. Either we *are* Agile or we *are not*.

Agile methodologies are all about short feedback loops.  
When we react to some feedback, the act of reacting to new information is what makes us more agile.

Narrowing the feedback loop helps us to make problems visible sooner, allowing us to inspect and adapt quickly.  
Agile does not solve any problems; it exposes them.

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

They hired consultancies and Agile coaches to help them change their *process*.  
However, they got little help to get better at writing quality software.

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
:x: Self-selected group of people  
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

We do not believe in the employer/employee type of relationship. We believe in a partnership, in which the company is the customer and the software developer is the one providing a service.

Although extremely important, writing code is just one of the things we need to do to help the project succeed. Other things (non-exhaustive) include: improving processes, removing unnecessary bureaucracy, understanding business domain, questioning requirements in relation to the value they provide, and working on other non-coding tasks.

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

We, as software professionals, own our career.  
This means we should use our time and money to get better at what we do.

Companies should still invest in their people. However, we should not see that as their obligation, but as a bonus / win-win situation.

### Keeping ourselves up to date

**Books**, be they physical or electronic, are essential.

- TODO

**Blogs** TODO

**Technical websites** are also good for ourselves up to date with what's going on in the market.

**Social media** can be a good tool for information gathering. There are people who contribute massively to move our profession - know who they are and follow them.

### Practice

How it is done

[back to contents](#contents)

---

## [Chapter 5] Heroes, Goodwill, and Professionalism

TODO :persevere:

[back to contents](#contents)

---

## [Chapter 6] Working Software

TODO :persevere:

[back to contents](#contents)

---

## [Chapter 7] Technical Practices

TODO :persevere:

[back to contents](#contents)

---

## [Chapter 8] The Long Road

TODO :persevere:

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

TODO :persevere:

[back to contents](#contents)

---

## [Chapter 12] The Cost of Low Morale

TODO :persevere:

[back to contents](#contents)

---

## [Chapter 13] Culture of Learning

TODO :persevere:

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
