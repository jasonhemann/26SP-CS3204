---
title: Syllabus
layout: single
toc: true
toc_label: "Syllabus Contents"
---

This syllabus contains policies and expectations I have established
for {{ site.title }}. Please read carefully the entire syllabus before
continuing in this course. Policies and expectations as set forth in
this syllabus may be modified at any time by the course instructor.
Notice of such changes will be made by announcement in class, by written
or email notice, or by changes to this syllabus posted on the course
website.


## Overview

Some infinities can't be counted. Some programs cannot be written. For
any reasonable theory, there are arithmetical truths it cannot prove.
With the tools of formal systems, finite beings can perceive limits on
what finite beings can do and know.

This course is a book-club style seminar on Gödel, Escher, Bach (GEB).
Nearly all assessment happens in the room: brief reading quizzes,
discussion leadership, live demonstrations, and oral explanations.
These assessments exist to verify understanding under questioning and
cannot be replaced by take-home work.

This course assumes careful reading, baseline fluency with symbolic
logic, and willingness to explain ideas aloud at a board. Students who
are not prepared for sustained reading or live explanation should
expect to struggle and are encouraged to assess their fit early.


---

## Required Textbooks

- Douglas Hofstadter, "Gödel, Escher, Bach: An Eternal Golden Braid"
  (any edition).

- Ernest Nagel and James Newman, "Gödel's Proof"
  (revised ed., NYU Press).


---

## Course Outcomes

By the end of the course you will be able to:

1. Use precise language to reason inside and about formal systems.
2. Present and lead discussion from a difficult text: frame claims,
   surface objections, and land a one-sentence takeaway grounded in the
   assigned chapter(s).
3. Explain and implement meta-programming ideas using simple formal
   models.
4. Explain Gödel's first incompleteness theorem in plain English,
   including what it does and does not claim.
5. Articulate why halting is undecidable and why the busy beaver
   function outruns every computable growth rate.
6. Practice core seminar habits: careful reading of technical prose,
   step-wise informal justification, and clear, short board
   explanations.

The ability to explain ideas clearly and accurately under questioning
is a core learning objective.


---

## Format

- Seminar, not lecture. First ~8 minutes: reading quiz; the remainder is
  discussion and focused technical unpacking.
- This is a discussion course. You are expected to participate nearly
  every meeting with text-tied questions, claims, or challenges.
  Cold-calling is used to ensure shared responsibility for discussion.
  If participation is low over two consecutive meetings, expect a
  check-in.
- Minimal coding, with understanding verified through live explanation.
- Check-offs are live and individual. Group work is permitted during
  preparation; explanations are solo.


---

## Evaluation and Grading

- Reading Quizzes --- 40%

- Participation and Leadership --- 25%
  - Seminar participation (15): regular, text-tied contributions,
    tracked across the term.
  - Discussion leader (8): once.
  - Professionalism (2): prepared, on time, no disruptions.

- Office-Hour Orals --- 20 pts (two vivas, 10 + 10; pass/redo)
  - Oral A (Weeks 4-5): formal systems, invariants, and enumerability
  - Oral B (Week 9): fixed points, diagonalization, or the recursion
    theorem

- 1# Micro-Check-offs --- 5 pts

  Show `self` plus one variant (`self#`, `#self`, or `self2`) with a
  90-second explanation.

- Universal 1# Demo --- 10 pts (pairs; in-room)

  Two-week build once assigned. Live run of `U(P,X)` on:
  (1) a trivial P,
  (2) `write`,
  (3) a quine.
  Answer short follow-up questions probing understanding.

**Logic Diagnostic (prerequisite verification):**
All students must sit a Day-1 symbolic logic diagnostic. Students who do
not pass must retake it during office hours by the end of Week 1.
Failure to pass by this deadline indicates insufficient prerequisite
preparation and requires dropping the course.

**Mastery requirement:**
You must pass Oral A and Oral B to pass the course, regardless of point
totals. These orals verify core understanding. Each oral includes a
redo opportunity before a fixed deadline.

Late and make-up work:
In-room work has fixed windows and no extensions. For cause, you will be
offered the next available window or may arrange a swap with another
student.


---

## Reading Quizzes (Mechanics)

- Closed book; short answers only; 6 to 8 minutes.
- Confidence box per item begins Week 2.
- Three quizzes are dropped automatically. Your quiz grade is the
  percentage over the reduced denominator times 40.


---

## Office-Hour Orals (Details)

Format (both orals): 8 to 10 minutes; no notes; board welcome.

Orals function as live interrogation of your understanding. You may be
asked to trace a concrete example, name an abstract mechanism, explain
why it is necessary, or say what would break under a change.

To pass an oral, you must demonstrate:
- correct statement of the relevant claim,
- command of the underlying mechanism,
- ability to instantiate it concretely,
- ability to answer follow-up questions.

Orals are scored pass/redo on core correctness, clarity of mechanism,
precision of language, and Q&A. Each oral has one redo window before a
fixed deadline.


---

## TRM / 1# Project

We will follow a short sequence of lessons on the one-hash (1#)
language:

1. Basics
2. Programs-for-programs (`write`, `s1^1`)
3. Self-replication (`diag`, `self`)
4. Universal 1#.

1# is used as a minimal, explicit model of computation to make
meta-programming, self-reference, and universality concrete.

Exact spec, encoding, and a meta-language generator will be posted with
the assignment. All assessment is via live check-offs to verify
individual understanding.


---

## Policies

- Academic integrity:
  Discussion of readings is encouraged; quizzes are individual.
  For 1#, collaboration on ideas is allowed, but you must be able to
  explain your own work live. Failure to explain equals no credit.

- Use of AI tools:
  Allowed for preparation and brainstorming. Any AI assistance must be
  disclosed in one line on code or prompts. Understanding is verified in
  the room.

- Devices and recording:
  Laptops and tablets are not permitted in class; phones must be away.
  Recording requires prior permission.

- Attendance:
  This is a seminar. Absence results in lost participation and quiz
  credit. If you are ill or have accommodations, email before class.


---

## Participation

Attendance is a prerequisite for participation, which constitutes a
substantial portion of your grade. You are expected to attend each
meeting and remain for the full session. Absence or tardiness impacts
your ability to meet course objectives and may affect your grade.
Lecture content quizzes serve as proxies for participation and
attendance, as well as checks on reading comprehension.


---

## Contact

The best way to get in contact for personal, private (FERPA, etc)
messages is via my email address
[{{ site.author.emailaddr }}]({{ site.author.email }}). You should expect a
response within 48 hours.


### Course Evaluations

If 85 percent or more of enrolled students complete course evaluations,
one point will be added to the class-wide final average.


---

## Academic Accommodations

It is the policy and practice of Seton Hall University to promote
inclusive learning environments. If you have a documented disability
you may be eligible for reasonable accommodations in compliance with
University policy, the Americans with Disabilities Act, Section 504 of
the Rehabilitation Act, and/or the New Jersey Law against
Discrimination. Please note, students are not permitted to negotiate
accommodations directly with professors. To request accommodations or
assistance, please self-identify with the Office for Disability
Support Services (DSS), Duffy Hall, Room 67 at the beginning of the
semester. For more information or to register for services, contact
DSS at (973) 313-6003 or by [e-mail](mailto:DSS@shu.edu), or visit
their [webpage](https://www.shu.edu/disability-support-services/index.cfm).


---

## Equity and Compliance

Seton Hall University is committed to maintaining a safe learning
environment. Information about Title IX and related policies is
available at:
https://www.shu.edu/title-ix/index.cfm

Federal regulations and university policy require instructors to
convey certain disclosures to the Title IX Coordinator when applicable.
Information is shared only with those who need to know to provide
support.


---

## Acknowledgments

Thanks over the years for inspiration and content from Dan Friedman,
Shriram Krishnamurthi, Lindsey Kuper, and Marco Morazan.

![In the syllabus]({{ site.baseurl }}/assets/images/syllabus.gif
"Might just be worth checking.")
