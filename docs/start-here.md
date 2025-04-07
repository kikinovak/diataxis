Start here - Diataxis in five minutes
=====================================

You don’t need to read everything on this website to make sense of Diataxis or
to start using it in practice. In fact I recommend that you don’t. The best way
to get started with Diataxis is by applying it - to something, however small.

Read this page for a brief primer. Each section contains links to more in-depth
material; refer to that when you need it - when you’re actually at work, or
reflecting on the documentation problems you have encountered.

> Treat this website as a handbook or a toolbox that you make use of when you
> need it.


The four kinds of documentation
-------------------------------

The core idea of Diataxis is that there are fundamentally four identifiable
kinds of documentation that respond to four different needs. The four kinds
are: *tutorials*, *HOWTO guides*, *reference* and *explanation*. Each has a
different purpose and needs to be written in a different way.


### Tutorials

A **tutorial is a lesson** that takes a student by the hand through a learning
experience. A tutorial is always *practical*: the user *does* something, under
the guidance of an instructor. A tutorial is designed around an encounter that
the learner can make sense of, in which the instructor is responsible for the
learner’s safety and success.

A driving lesson is a good example of a tutorial. The purpose of the lesson is
to develop skills and confidence in the student, not to get from A to B. A
software example could be: *Let’s create a simple game in Python*.

*The user will learn through what they do* - not because someone has tried to
teach them.

In documentation, the special difficulty is that the instructor is condemned to
be absent. He's not there to monitor the learner and correct their mistakes.
The instructor must somehow find a way to be present through written
instruction alone.

> * Tutorials in more detail
> * Why tutorials are completely different from HOWTO guides


### HOWTO guides


**A HOWTO guide addresses a real-world goal or problem** by providing practical
directions to help the user who is in that situation.

A HOWTO guide always addresses an already-competent user who is expected to be
able to use the guide to help them get their work done. In contrast to a
tutorial a HOWTO guide is concerned with *work* rather than *study*.

A HOWTO guide might be: *How to store cellulose nitrate film* (in motion
picture photography) or *How to configure frame profiling* (in software). Or
even: *Troubleshooting deployment problems*.

> * How-to guides in more detail


### Reference

**Reference guides contain the technical description** - facts - that a user
needs in order to do things correctly: accurate, complete, reliable
information, free of distraction and interpretation. They contain
*propositional or theoretical knowledge*, not guides to action.

Like a HOWTO guide, reference documentation serves the user who is at *work*,
and it’s up to the user to be sufficiently competent to interpret and use it
correctly.

*Reference material is neutral*. It is not concerned with what the user is
doing.  A marine chart could be used by a ship’s navigator to plot a course but
equally well by a prosecuting magistrate in a legal case.

Where possible, the architecture of reference documentation should reflect the
structure or architecture of the thing it’s describing - just like a map does.
If a method is part of a class that belongs to a certain module, then we should
expect to see the same relationship in the documentation too.

> * Reference in more detail


### Explanation

**Explanatory guides provide context and background**. They serve the need to
understand and put things in a bigger picture. Explanation joins things
together and helps answer the question *why?*

Explanation often needs to circle around its subject and approach it from
different directions. It can contain opinions and take perspectives.

Like reference, explanation belongs to the realm of propositional knowledge
rather than action. However its purpose is to serve the user’s study - as
tutorials do - and not their work.

Often, writers of tutorials who are anxious that their students should know
things overload their tutorials with distracting and unhelpful explanation. It
would be much more useful to give the learner the most minimal explanation
(“Here, we use HTTPS because it’s safer”) and then link to an in-depth article
(*Secure communication using HTTPS encryption*) for when the user is ready for
it.

> * Explanation in more detail
> * Understanding the difference between reference and explanation


The Diataxis map
----------------

The four kinds of documentation and the relationships between them can be
summarised in the Diataxis map.

Diataxis is not just a list of four different things but a conceptual
arrangement of them. It shows how the four kinds of documentation are related
to each other and distinct from each other.

Crossing or blurring the boundaries described in the map is at the heart of a
vast number of problems in documentation.

![The Diataxis map][img1]

> * The map in more detail

[img1]: ../img/diataxis.png "The Diataxis map"

