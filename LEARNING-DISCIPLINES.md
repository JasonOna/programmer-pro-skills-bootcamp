There are 4 principles we want to actively practice each step in the course. They are:

- [System Thinking](#system-thinking)
  - [Action Item](#action-item)
- [Just Enough Up-front Design](#just-enough-up-front-design)
  - [Action item](#action-item-1)
- [Confident Working Software](#confident-working-software)
  - [Action Item](#action-item-2)
- [Evolutionary Maintainable Software](#evolutionary-maintainable-software)

Each lesson you go through ensure that you are following these principles by following their action items.

# System Thinking

We tend to jump straight into solution-mode working on a work item. We tend to fail taking a step back and looking at our surrounding environment.

The feature we build, or even the subtask, has an impact on the whole system. Not always physically close (ie another class in the same folder or some where in the project).

Our work could impact another team member on what they are doing or cause a major upset onto a downstream service.

> Systems thinking is a way of making sense of the complexity of the world by looking at it in terms of wholes and relationships rather than by splitting it down into its parts.
>
> — [Wikipedia](https://en.wikipedia.org/wiki/Systems_thinking)

In every step ask yourself "_How does my solution affect the application as a whole and its dependencies; as well, the people who will be and is working on those applications_?"

[![Watch the video](https://img.youtube.com/vi/xcQVgYzlj8k/hqdefault.jpg)](https://www.youtube.com/embed/xcQVgYzlj8k)

## Action Item

List out the impact of the problem space and the solution space. Impact should be current impact and future impact.


# Just Enough Up-front Design

> Big design up front is dumb. Doing no design up front is even dumber.
>
> — [Dave Thomas](https://en.wikipedia.org/wiki/David_A._Thomas_(software_developer))

We aren't talking about writing multiple diagrams and architecture documents. We are talking about  a simple one-pager not a short story length description of what the solution will be and how it can potentially progress into - _just enough_.

Another reason why you don't want to design everything up front is that development changes quickly when new knowledge is found. Your documents will become stale and irrelevant fast.

Drawing some diagrams and writing short words (_like a [Lightweight Architecture Decision Record](https://peterevans.dev/posts/lightweight-architecture-decision-records/)_) is way cheaper to trash compared to written code.

> Prototypes and prototyping are not substitutes for analysis and design, not excuses for sloppy thinking.
>
> — [Larry Constantine and Lucy Lockwood, Software for Use: A Practical Guide to the Models and Methods of Usage-Centered Design](https://www.goodreads.com/book/show/1987217.Software_for_Use)

If you want insights on how to architect in a agile progressive manner, here's a [great talk on architecting for a start-up to a scale-up](https://www.youtube.com/watch?v=9Q7GANXn02k).

There's even a white paper on this topic! Here's the [link](https://www.researchgate.net/publication/221098986_Little_Design_Up-Front_A_Design_Science_Approach_to_Integrating_Usability_into_Agile_Requirements_Engineering) if you're into academic papers (_I'm not but your choice_)
.

[![Watch the video](https://img.youtube.com/vi/NigZf0kqseA/hqdefault.jpg)](https://www.youtube.com/watch?v=NigZf0kqseA)

## Action item

For each PR, write an LADR (Lightweight Architecture Decision Record).

Here are some resources to help you:

* https://cognitect.com/blog/2011/11/15/documenting-architecture-decisions
* https://gist.github.com/wilkesybear/b4d412f1ac89437d6fa308ae16a311b8
* tool to create LADR: https://github.com/npryce/adr-tools

> _"When do I stop adding stuff to my documentation?_"

Good question! [Simon Brown](https://dev.to/simonbrown/software-architecture-isn-t-about-big-design-up-front-4hol) has something to say about it:

![stop doing up front design when You understand the significant architectural drivers (requirements, quality attributes, constraints).
You understand the context and scope of what you're building.
You understand the significant design decisions (i.e. technology, modularity, etc).
You have a way to communicate your technical vision to other people.
You are confident that your design satisfies the key architectural drivers.
You have identified, and are comfortable with, the risks associated with building the software.](https://res.cloudinary.com/practicaldev/image/fetch/s--rcWCtwNn--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_800/https://dev-to-uploads.s3.amazonaws.com/i/johcnp4ryqcplaofrpsf.png)

# Confident Working Software

When you are presented with a set of requirements. How do you know your code meets the accepted criteria? How do you know that the next person coming on that project won't misunderstand your intentions and break the criteria? How do we know it is going to work in production?

How can we answer all that question effectively, efficiently, repeatedly, quickly and consistently?

That's a lot of -lys!

It is one thing to write elegant inteligent code, it's another to know what you're writing ticks all the acceptance criteria without missing anything.

One practice is [TDD](https://tidyfirst.substack.com/p/canon-tdd). Many think that TDD is just so there will be test. You can always write your test as an after-thought (_there are reasons why that's a not always the best_). TDD allows us to experiment our way to first lay out the requirements and "_test_" that our code meets the mark. [TDD is way of developing software](https://dev.to/gervg/test-driven-development-isnt-about-unit-tests-48e3). _BTW, through this practice you get your test coverage for free_!

[![Watch the video](https://img.youtube.com/vi/fPlBLlE8vOI/hqdefault.jpg)](https://youtu.be/fPlBLlE8vOI)

## Action Item

Think about how you will convey that the code you've written will work by showing tangible results (if its measurable that's a bonus!).

# Evolutionary Maintainable Software
