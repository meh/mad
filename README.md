Management & Developers
=======================
The new form of role playing adventures.

Problems
========
These are qualms I have with any form of project management process and tool.

People are resources
--------------------
The assumption that people are resources is one of the biggest mistakes project
management ever came up with.

It objectifies people and completely ignores the fact that every person is
different and no person is equivalent to another.

### Equivalent experience means equivalent technical skills

This couldn't be further from the truth.

Take for instance two developers, both with 10 years of experience with C, one
has worked 8 of those years with kernel development and embedded, the other all
those 10 years with desktop applications using GTK.

While they have equivalent experience with C they don't have equivalent
experience for their respective fields.

The GTK guy will be more used to closures, object oriented programming with
inheritance and interfaces (gobject) and other such things. While the kernel
developer will be more used to bare metal programming, interrupts, operating
systems, compiler bullshit.

While you can put the GTK guy working on an operating system and the kernel guy
working on an office suite, is that really what you want to do?

In short, what's missing is a way to represent people and their knowledge in
more than "efficiency" or "junior" and "senior". People have depth. People have
skills. People have experience.

### To have the best team, pick the best people

This is another huge mistake people tend to make, the best team is the team
with the most balanced group of people, you need people in a team to complement
and reinforce each other strengths while keeping in check the weaknesses.

Putting in the same team three very strong personalities, extremely opinionated
and with a huge amount of experience is not going to end well, for anyone.

And even if you manage to make a balanced team if two people in the team hate
each other, it's also not going to go well, so relationships take a huge part
in forming a good team.

### I can replace resources with other resources

Yet again, one of the biggest mistakes is assuming that two equivalent resource
can replace each other.

Let's say I have two teams, team A and team B, and sadly Sam from team A goes
under a bus and is unable to work for the forseeable future.

Sam is a senior engineer, he's been working on project Foo for a number of
years, and luckily we have John from team B, another senior engineer who's been
working on project Bar for a number of years.

For all means and purposes their technical skills and experiences are the same,
they've both been using the same programming languages, libraries, processes,
managers.

Yet, replacing Sam with John will result in a much lower production throughput,
possibly even negative.  What happened? You forgot to account for two things:
domain knowledge and relationships within the team.

Sam had been the single person to work on two extremely important modules, and
he's the only one who knows what those modules do and knows his way around it.
John has no idea what anything means and touching anything may cause bugs or
crashes.  This is domain knowledge that cannot be shared through documentation,
this is time spent on the project.

John on the other hand was breaking the tension between Chad and Brad every
time an argument ensued resulting in tissues being resolved constructively,
he's gone now, hell breaks loose.  John also used to give advice to Nicholas
when he needed help or he wasn't sure about something, without him Nicholas'
production lowers considerably.

You broke two teams with a single change, good job project manager!

Projects are well defined
-------------------------
No, projects are not well defined, even having perfect requirements there would
be no way to give perfect time estimates.

Some parts of a project may have no time duration, they may ongoing, or
recurring.

Some parts may not be known yet, as when suddenly a library you need doesn't
exist, so you have to make it.

Some parts may take much longer than expected, bugs in a library, in the
compiler, in the operating system.

Some parts may have to be thrown out completely, and suddenly your plan has
gone insane.

Teams are fixed and exclusive
-----------------------------
A common idea is that teams are fixed, if you're in team A you cannot be in
team B, and vice versa.

You can have a project that requires multiple teams to work together, but is it
really two teams working together or is it all the people from each team
working with each other? 

Solutions
=========
These are the solutions I propose, while also making management a fun game.

People are characters
---------------------
They're characters in a role playing game called a job, they have classes,
level, abilities, orientations, relationships, everything an RPG character has.

You can model efficiency, technical skills and other innate attributes of each
person into their data sheet, and then more complex calculations can be done
other than "efficiency".

Their relationships with other characters, their general orientation, their
mood, they can all be used to make the best decision.

Projects are quests
-------------------
Projects don't exist, quests do, and products are just story arcs.

You start a quest, you know what the quest is about, making this software
thing, but to do that we need to work towards objectives, that may require
other objectives and quests.  Some objectives may even loop.

Different parties may be best suited for different objectives and quests, and
time estimates are based on parties picked and paths taken.

Teams don't exist, only parties
-------------------------------
Teams are static, parties are flexible, parties can be merged, people can be in
different parties at the same time, they can be in some but not in others.

You want the most optimized party composition possible for a specific quest or
objective, and you don't want to limit yourself to people in a "team".

But then you may ask, where do I sit people if anyone can work with anyone? And
that brings us to the next point.

Teams kind of exist, as guilds
------------------------------
Guilds are groups of characters united by a specific area of expertise or
interest, for instance a Backend Developers would all be part of the Backend
guild, Embedded Developers of the Embedded guild and so on.

For one quest I may need two Embedded Developers, three Backend Developers and
one App Developer, and while they will all have to camp together to regain
energy and plan the next move, they'll get the most help out of their other
guild members.
