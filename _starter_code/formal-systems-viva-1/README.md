# Formal Systems (Viva 1)

You will demonstrate that you can reason inside and about formal
systems, derive small instances, use an invariant or an
interpretation, run bottom-up and/or top-down decision procedures, and
correctly use and explain vocabulary like "axiom", "rule", "schema",
"well-formed string", "theorem", "non-theorem", and "decision
procedure". You must know the alphabets, axioms, and rules for `MIU`,
`pq`, `tq`, and `DND`.

## Booking
- Book a 10 minute slot between **2026-01-27** and **2026-02-04**
  (Note I will be out of town and unavailable after the 4th).
- Use this link: https://calendar.app.google/3166Pn3ALoct8XKA8
- If none of the posted times work, email alternatives early

## Format
Approximately 8-10 minutes. No notes. Expect to do boardwork. I will
choose a system and a question style at the door

## What you must be ready to do

  1. State, without notes, the alphabet, axiom(s), and rules for MIU,
     pq, tq, DND
  2. Derive or refute a small target string in the named system
  3. Run a bottom-up decision procedure, and explain why that suffices
     to decide theorem-hood
  4. Run a top-down decision procedure on a given goal string, and
     explain how that decides theorem-hood
  5. Separate inside vs outside reasoning; use an invariant or an
     interpretation mapping correctly

## Question styles (examples)

I will pick the system and the style on the spot. You may get one or
more of these, and you should prepare all systems.

- Derivation challenge (any system): "Is S derivable?" If yes, show a
  short derivation. If no, give the reason that rules it out
  (invariant or search argument).
- Bottom-up procedure (like in `pq`): show me how to enumerate all
  theorems up to length N and decide if a given target T is in;
  explain why your bound N is sufficient.
- Top-down procedure (like in `pq`): attempt to derive a given target
  T.
- Interpretation (pq or tq): define mappings from strings to
  arithmetic claims; demonstrate worked examples; explain why the
  rule(s) are sound under this mapping.
- Inside vs outside analysis (any system): identify which steps are
  legal inside the system; explain what outside facts you used and why
  they are not permitted inside.
- Rule change thought experiment (any system): if rule R is altered as
  stated, what breaks and what new strings become possible? justify
  briefly.
- Invariant (MIU): Name the invariant that rules out MU and show
  preservation for each rule.

## What happens in the room

| Phase              | Time    | Description                                                                                                                          |
|--------------------|---------|--------------------------------------------------------------------------------------------------------------------------------------|
| Topic reveal       | 15 s    | I name the system and question style.                                                                                                |
| Setup              | 45-60   | You write the alphabet, axiom(s), and rules relevant to the task.                                                                    |
| Core demonstration | 4-5 min | You run either the bottom-up or top-down procedure as requested, or present the invariant/interpretation and apply it to the target. |
| Concrete instance  | 1-2 min | You show a small derivation or a short trace that illustrates your mechanism.                                                        |
| Follow-ups         | 2-3 min | I ask short variations to test transfer (see below). Decision: pass/redo.                                                            |

## Pass/Redo

Typical non-passes will include one or more of the following:

- Misstating a rule or using an illegal step without noticing
- Using outside facts as if they were inside rules
- Failing to justify the bottom-up bound when claiming a decision
- Claiming a top-down procedure in a system where you cannot make it sound or terminating
- Invariant or interpretation named but not actually applied to the target

## Redo policy

One redo window in the week after the original sign-up window.

## Preparation checklist

- Memorize alphabets, axiom(s), and rules for MIU, pq, tq, DND
- MIU: be able to state and use the mod-3 invariant; show preservation per rule
- pq: be able to state the addition mapping and justify the rule on two examples
- tq: be able to state the multiplication mapping and generate a simple composite example
- DND: be able to state the intended property (non-divisibility / primes up to) and what the rules give you
- Bottom-up: practice enumerating all theorems up to a bound and saying why the bound is enough
- Top-down: practice a backward-chaining derivation with explicit dead ends and a successful path
- Be ready to say, for any step, whether it is inside or outside the system and why
