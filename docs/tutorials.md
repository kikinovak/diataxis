Tutorials
=========

A tutorial is an __experience__ that takes place under the guidance of a
tutor. A tutorial is always __learning-oriented__.

![Tutorials][img1]

---

A tutorial is a _practical activity_ in which the student learns by doing
something meaningful towards some achievable goal.

A tutorial serves the user’s _acquisition_ of skills and knowledge - their
study. Its purpose is not to help the user get something done, but to help them
learn.

A tutorial in other words is a lesson.

It’s important to understand that while a student will learn by doing, what the
student _does_ is not necessarily what they _learn_. Through doing, they will
acquire theoretical knowledge (i.e. facts), understanding, familiarity. They
will learn how things relate to each other and interact, and how to interact
with them. They will learn the names of things, the use of tools, workflows,
concepts, commands. And so on.

---


The tutorial as a lesson
------------------------

A lesson entails a relationship between a teacher and a pupil. In all learning
of this kind, _learning takes place as the pupil applies themself to tasks
under the instructor’s guidance_.

A lesson is a _learning experience_. In a learning experience, what matters is
what the learner does and what happens. By contrast, the teacher’s explanations
and recitations of fact are far less important.

A good lesson gives the learner confidence by showing them that they can be
successful in a certain skill or with a certain product.


### Obligations of the teacher

A lesson is a kind of contract between teacher and student, in which nearly all
the responsibility falls upon the teacher. The teacher has responsibility for
what the pupil is to learn, what the pupil will do in order to learn it and for
the pupil’s success. Meanwhile, the only responsibility of the pupil in this
contract is to be attentive and to follow the teacher’s directions as closely
as they can. There is no responsibility on the pupil to learn, understand or
remember.

At the same time, the exercise you put your pupils through must be:

  * _meaningful_ - The pupil needs to have a sense of achievement.

  * _successful_ - The pupil needs to be able to complete it.

  * _logical_ - The path that the pupil takes through it needs to make sense.

  * _usefully complete_ - The pupil must have an encounter with all of the
    actions, concepts and tools they need to become familiar with.

> It’s not easy being a teacher.


### The problem of tutorials

In general, tutorials are rarely done well, partly because they are genuinely
difficult to do well, and partly because they are not well understood. In
software, many products lack good tutorials or lack tutorials completely;
tutorials are often conflated with HOWTO guides.

In an ideal lesson, the teacher is present and interacts with and responds to
the student, correcting their mistakes and checking their learning. In
documentation, none of this is possible.

It’s hard enough to put together a learning experience that meets all the
standards described above; in many contexts the product itself evolves rapidly,
meaning that all that work needs to be done again to ensure that the tutorial
still performs its required functions.

You will also often find that no other part of your documentation is subject to
revisions the way your tutorials are. Elsewhere in documentation, changes and
improvements can generally be made discretely; in tutorials, where the
end-to-end learning journey must make sense, they often cascade through the
entire story.

Finally, tutorials contain the additional complication of the distinction
between _what is to be learned_ and _what is to be done_. Not only must the
creator of a tutorial have a good sense of what the user must learn and when,
they must also devise a meaningful learning journey that somehow delivers all
that.

> Writing and maintaining tutorials can consume a remarkable amount of effort
> and time.

---


Key principles
--------------

A tutorial is a pedagogical problem.

It’s not an easy problem, but neither is it a mystery. The principles outlined
below - repetition, action, small steps, results early and often, concreteness
and so on - are not secrets, but they are not always well understood.

Still, there are straightforward, effective ways to address the problems of
pedagogy in practice.

The first rule of teaching is simply: __don’t try to teach__. Your job as a
teacher is to provide the learner with an experience that will allow them to
learn. A teacher inevitably feels a kind of anxiety to impart knowledge and
understanding, but if you give into it and try to teach by telling and
explaining, you will jeopardise the learning experience.

Instead, _allow learning to take place_ and trust that it will. Give your
learner things to do, through which they can learn. Only your pupil can learn.
Sadly, however much you desire it, you will not be able to learn for your
pupil. You cannot make them learn. All you can do is make it so _they_ can
learn.

> Anti-pedagogical temptations:
> 
> * abstraction, generalisation
> * explanation
> * choices
> * information


### Show the learner where they’ll be going

It’s important to allow the learner to form an idea of what they will achieve
right from the start. As well as helping to set expectations, it allows them to
see themselves building towards the completed goal as they work.

Providing the picture the learner needs in a tutorial can be as simple as
informing them at the outset: _In this tutorial we will create and deploy a
scalable web application. Along the way we will encounter containerisation
tools and services._

This is not the same as saying: _In this tutorial you will learn..._ - which is
presumptuous and a very poor pattern.


### Deliver visible results early and often

Your learner is probably doing new and strange things that they don’t fully
understand. Understanding comes from being able to make connections between
causes and effects, so let them see the results and make the connections
rapidly and repeatedly. Each one of those results should be something that the
user can see as meaningful.

Every step the learner follows should produce a comprehensible result, however
small.


### Maintain a narrative of the expected

At every step of a tutorial, the user experiences a moment of anxiety: will
this action produce the correct result? Part of the work of a successful
tutorial is to keep providing feedback to the learner that they are indeed on
the right path.

Keep up a narrative of expectations: “You will notice that...”; “After a few
moments, the server responds with...”. Show the user actual example output, or
even the exact expected output.

If you know know in advance what the likely signs of going wrong are, consider
flagging them: “If the output doesn’t show..., you have probably forgotten
to...”.

It’s helpful to prepare the user for possibly surprising actions: “The command
will probably return several hundred lines of logs in your terminal.”


### Point out what the learner should notice

Learning requires reflection. This happens at multiple levels and depths, but
one of the first is when the learner observes the signs in their environment.
In a lesson, a learner is typically too focused on what they are doing to
notice them, unless they are prompted by the teacher.

Your job as teacher is to close the loops of learning by pointing things out,
in passing, as the lesson moves along. This can be as simple as pointing out
how a command line prompt changes, for example.

Observing is an active part of a craft, not a merely passive one. It means
paying attention to the environment, a skill in itself. It’s often neglected.


### Target _the feeling of doing_

In all skill or craft, the accomplished practitioner experiences a _feeling of
doing_, a joined-up purpose, action, thinking and result.

As skill develops, it flows in a confident rhythm and becomes a kind of
pleasure. It’s the pleasure of walking, for example.

Your learner’s skill depends upon their discovering this feeling and its
becoming a pleasure.

Your challenge as the creator of a tutorial is to ensure that its tasks tie
together purpose and action so they become a cradle for this feeling.

> Pay attention to your own _feeling of doing_ in your work. What is it like to
> perform a particular operation?


### Encourage and permit repetition

Learners will return to and repeat an exercise that gives them success, for the
pleasure they find in getting the expected result. Doing so reaffirms to them
that they can do it, and that it works.

Repetition is a key to establishing the feeling to doing; being at home with
that feeling is a foundational layer of learning.

In your tutorial, try to make it possible for a particular step and result to
be repeated. This can be difficult, for example in operations that are not
reversible (making it hard to go back to a previous step) - but seek it
wherever you can. Watching a user follow a tutorial, you may often be amazed to
see how often they choose to repeat a step. They are doing it just to see that
the same thing really does happen again.

> Repetition is not the best teacher - sometimes it’s the _only_ teacher.

[img1]: ../img/tutorials.png "Tutorials"
