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

---


The four kinds of documentation
-------------------------------

The core idea of Diataxis is that there are fundamentally four identifiable
kinds of documentation that respond to four different needs. The four kinds
are: _tutorials_, _HOWTO guides_, _reference_ and _explanation_. Each has a
different purpose and needs to be written in a different way.


### Tutorials

A __tutorial is a lesson__ that takes a student by the hand through a learning
experience. A tutorial is always _practical_: the user _does_ something, under
the guidance of an instructor. A tutorial is designed around an encounter that
the learner can make sense of, in which the instructor is responsible for the
learner’s safety and success.

A driving lesson is a good example of a tutorial. The purpose of the lesson is
to develop skills and confidence in the student, not to get from A to B. A
software example could be: _Let’s create a simple game in Python_.

_The user will learn through what they do_ - not because someone has tried to
teach them.

In documentation, the special difficulty is that the instructor is condemned to
be absent. He's not there to monitor the learner and correct their mistakes.
The instructor must somehow find a way to be present through written
instruction alone.

> * Tutorials in more detail
> * Why tutorials are completely different from HOWTO guides


### HOWTO guides


__A HOWTO guide addresses a real-world goal or problem__ by providing practical
directions to help the user who is in that situation.

A HOWTO guide always addresses an already-competent user who is expected to be
able to use the guide to help them get their work done. In contrast to a
tutorial a HOWTO guide is concerned with _work_ rather than _study_.

A HOWTO guide might be: _How to store cellulose nitrate film_ (in motion
picture photography) or _How to configure frame profiling_ (in software). Or
even: _Troubleshooting deployment problems_.

> * HOWTO guides in more detail


### Reference

__Reference guides contain the technical description__ - facts - that a user
needs in order to do things correctly: accurate, complete, reliable
information, free of distraction and interpretation. They contain
_propositional or theoretical knowledge_, not guides to action.

Like a HOWTO guide, reference documentation serves the user who is at _work_,
and it’s up to the user to be sufficiently competent to interpret and use it
correctly.

_Reference material is neutral_. It is not concerned with what the user is
doing.  A marine chart could be used by a ship’s navigator to plot a course but
equally well by a prosecuting magistrate in a legal case.

Where possible, the architecture of reference documentation should reflect the
structure or architecture of the thing it’s describing - just like a map does.
If a method is part of a class that belongs to a certain module, then we should
expect to see the same relationship in the documentation too.

> * Reference in more detail


### Explanation

__Explanatory guides provide context and background__. They serve the need to
understand and put things in a bigger picture. Explanation joins things
together and helps answer the question _why?_

Explanation often needs to circle around its subject and approach it from
different directions. It can contain opinions and take perspectives.

Like reference, explanation belongs to the realm of propositional knowledge
rather than action. However its purpose is to serve the user’s study - as
tutorials do - and not their work.

Often, writers of tutorials who are anxious that their students should know
things overload their tutorials with distracting and unhelpful explanation. It
would be much more useful to give the learner the most minimal explanation
(“Here, we use HTTPS because it’s safer”) and then link to an in-depth article
(_Secure communication using HTTPS encryption_) for when the user is ready for
it.

> * Explanation in more detail
> * Understanding the difference between reference and explanation

---


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

---


The Diataxis compass
--------------------

As you can see from the map:

  * Tutorials and HOWTO guides are concerned with what the user _does_
    (__action__).

  * Reference and explanation are about what the user _knows_ (__cognition__).

On the other hand:

  * Tutorials and explanation serve the _acquistion_ of skill (the user’s
    __study__).

  * HOWTO guides and reference serve the _application_ of skill (the user’s
    __work__).

But a map doesn’t tell you what to _do_ - it’s reference. To guide your action
you need a different sort of tool. In this case, a kind of Diataxis compass.

The compass is useful in two different ways.

When creating documentation, it helps clarify your own intentions and helps
make sure you’re actually doing what you think you’re doing.

When looking at documentation, it helps understand what’s going on in it and
makes problems stand out.

The compass is not nearly as eye-catching as the map, but when you’re at work
puzzling over a documentation problem it’s what will help you move forward.

If the content... | ...and serves the user's... | ...then it must belong to...
----------------- | --------------------------- | ----------------------------
informs action    | acquisition of skill        | a tutorial
informs action    | application of skill        | a HOWTO guide
informs cognition | application of skill        | reference
informs cognition | acquisition of skill        | explanation

> * The compass in more detail

---


Working
-------

  1. Consider what you see in the documentation in front of you right now
     (which might be literally nothing if you haven’t started yet).

  2. Ask: _is there any way in which it could be improved?_

  3. Decide on _one_ thing you could do to it right now, however small, that
     would improve it.

  4. Do that thing.

And then repeat.

That’s it.

> * Diataxis as a guide to work

---


Do what you like
----------------

You can do what you like with Diataxis. You don’t have to believe in it and
there is no exam. It is a wholly pragmatic approach. I think it’s _true_, but
what matters is that it actually helps people create better documentation. If
you find one idea or insight in it that seems to be worthwhile, help yourself
to that.

There is an extensively elaborated theory around Diataxis, but you don’t need
to subscribe to it or even read about it. Diataxis doesn’t require a
commitment to pursue it to a final end.

You can do just one thing, right now, and even if you do nothing else ever
after, you will at least have made that one improvement. In practice what you
will find is that each thing you do will give you a clue as to the next thing
to do - you only need to keep doing them.


Get started
-----------

At this point, you have read everything you need to get started with Diataxis.

You can read more if you want, and eventually you probably should, but you will
get the most value from the guidance in this website when you turn to it with a
problem or a question. That’s when it comes alive.

[img1]: ../img/diataxis.png "The Diataxis map"
