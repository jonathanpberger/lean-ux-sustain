# todo
- search twitter for design complaints
- review my blog posts that may be germane
- get talk from Sha
- interview byron: what are his pain points?
- send out some public surveys
- get all these ideas out on index cards or post its and move them around

---
= id=complaints
# Complaints
- "I got tired of nothing I designed ever being built"
- "Where are you hiding the people who yell at you" - FIND A PLACE FOR THIS STORY


---
= id=title
# Sustainable Pace, Agile, and The Big Design Refactor
Lean UX NYC, 2013

Jonathan Berger, Pivotal Labs

---
# Hi!

---

# I'm @jonathanpberger

---
= id=background
My
# background
is in
- **philosophy** and then
- **design** and now
- **development**

---

I read and write code every day to build products and practice at **@pivotallabs**

---

# What it says on the tin
> How much design should a project start with? Why is Agile so tough for designers? How can designers achieve sustainable pace? There are a handful of perennial agile-and-design questions that keep coming up. Part of solving them involves acknowledging that the pace of design changes over the course of a project. Acknowledging the different rhythms—and identifying the beats that are in sync—can help teams work together in harmony.

---

# The order
of the title is scrambled. We're gonna tackle

- Agile
- The Big Design Refactor
- Sustainable Pace

---

<!-- ## Learning Outcomes

- How sustainable pace can contribute to better design (and happier designers)
- How the natural rhythms of design can drive expectations and deliverables in an agile environment
- How designers can work more comfortable in agile environments
- How agile techniques can benefit design

---
 -->

This session is the result of a lot of thinking and blogging over the past few years. The rhythms of design and development (and how they intersect) has been under-explored, and there's a lot of light to be shed on common points of friction between designers and developers on agile teams.

---
# Empathy
- There's a homunculus inside of us, and we're treating him like shit.
- Why do we practice empathy professionally for everyone but ourselves?

---
# Problems

- Why is Agile so tough for designers?
- How much design should a project start with?
- How can designers achieve sustainable pace?

---

# Why is Agile so tough for designers?

---

## Because we don't know when we're done
- "done" is objective in TDD development (a passing build)
- "done" is subjective in design (client sign-off? implemented & accepted designs?)

---

## Because we're in the deliverables business
- the deliverable for development is working, user-facing code
- the deliverable for design ought to be Design Solutions
- we're set up as a business to bill for mockups instead

---

# How much design should a project start with?

---

# How can designers achieve sustainable pace?


---

# Solutions

- Agile techniques can benefit design
- the natural rhythms of design can drive expectations and deliverables in an agile environment
- Acknowledging that the pace of design changes over the course of a project can help teams work together in harmony.
- Designers can work more comfortably in agile environments
- sustainable pace can contribute to better design (and happier designers)

---

# NOTES

---

# What can Agile bring to Design?
- Sustainable pace.
- Shared ownership of product.
- More predictable acceptance criteria.
- All the benefits of pairing.
- All the benefits of testing.

---


## Techniques to Explore
- [Object oriented CSS](https://github.com/stubbornella/oocss/wiki)
- [Scalable and Modular architecture for CSS](http://smacss.com/)

---

## Testing
- CSS performance optimization. Worth it? http://css-tricks.com/efficiently-rendering-css/

## Deliverables

### Early
- [Style Tiles](http://styletil.es/)
- Mobile-First sketching techniques

---

# BLog Posts

---

# 3 challenges
Software development has been revolutionized by Agile development practices, but designers struggle to adapt to the very same techniques—despite suffering many of the same challenges that led to Agile. What exactly are these problems? And how can Agilists and designers address them?

---
= id=done
Challenge #1
# WHEN IS DESIGN DONE?

---

Agile development preaches

## “Done means Done”.

<!-- - When a story is accepted by the Product Owner, it’s ready to be deployed out into the world.  -->

What does “done” mean for design?

---

## Automated testing

guarantees that on every story, developers will enjoy Acceptance Criteria: a concrete measure of what counts as “done”.

---

Designers, on the other hand, rely on
## subjective criteria
to determine when they’re done.

---

### In the best case,
this means the product team—or often, the designer working alone—if only they had a partner to pair with!

### In the worst case
this is purely subjective sign-off from the client.

---

Agile developers have access to tools like
## velocity
 to plan their work,

---

designers have structural difficulties in
## estimation,
and are consequently less able to plan.

---

questions like “when will that feature be done?” are more easily answered by a developer than a designer. That’s not because designers are less responsible than developers.
It’s because it’s harder to know when you’re done with design

---

that’s of little comfort to anyone who needs to budget time and resources to manage the project.

---

Because Acceptance Criteria—or an answer to the question “what does ‘done’ mean?”—for design is in different units of work than “done” for development, there’s an impedance mismatch in coordinating between the two.

---

Breaking design into units of work with more discrete Acceptance Criteria helps coordinate design work with development work.

---

Challenge #2
# WHAT’S WRONG WITH THE DELIVERABLES BUSINESS?

---

Agile Developers ultimately deliver user-facing code, but designers output thinking: solutions to design problems, traditionally expressed via mock-ups or assets. How should the two interact? Should design stay an iteration ahead of development? What does it mean when a developer discovers an interaction problem in a design they’re implementing? Should they stop work? Developers are the tip of the spear when it comes to experience design: in the process of building software, they’re often the first people ever to use it. Sometimes this means they uncover interactions on UX problems that the designers didn’t anticipate. If the necessary design changes cascade into other work, what should the designer do: stop work and refactor (and fall behind), or come back to it later?

Furthermore, it can be difficult to determine how much design is required for developers to complete their work. The best design deliverable is the Simplest Thing That Can Possibly Communicate the Design Solution, and this can vary from team to team and design problem to design problem. Under ideal circumstances, an experienced designer may be able to reasonably estimate how long it will take to 1) solve the design problem, 2) communicate the solution, and 3) iterate on the problem / solution once it’s usable and testable as working software. But. BUT! That’s asking a lot. And it absolutely shreds the question “how far ahead should design stay of development?”.

# WHY DO DESIGNERS FEEL UNWELCOME IN AGILE?
Let’s take stock: we’ve got gallant developers, accurately estimating stories and delivering working software, and the goofus designers, unable to tell you what they’re doing or when they’ll be done. Knowing “how much design is enough?” is hard. Knowing how much design to start with is hard. Reared in a culture that prizes individuality, that venerates Rock Star Designers, that applauds Working On It Til Its Done, that publicly shreds less-than-perfect work in Crit as a rite of passage, that (with the occasional exception) is alien to the notion of sustainable development—it shouldn’t be surprising that designers are uncomfortable. That starts to lead to discord on the team: designers hating agile; feeling rushed, feeling like they don’t get the benefit of iterative design; feeling that once they touch something, they don’t get to go back and refactor it. Let’s throw in a bit of rah-rah agile ideology, a few jargon-y IPMs and retros, promises that “we’ll come back and refactor that later”, and the creeping suspicion that this whole Agile thing is nothing but smoke, mirrors, and Kool-Ade. Is it any wonder that designers can be hostile to agile?

What can we do? Looking to the example that Agile Development sets, we can see several concepts that may help: Acceptance Criteria-delimited design stories. Meaningful estimation of work for design. A culture that values Sustainable Pace. Translating these ideas from development to design may do more than just help designers work more comfortably in Agile environments—it may help us practice better design.