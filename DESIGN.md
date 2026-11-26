# DESIGN — Funniest Forecast for a City That Isn't

## The entry

> Tarnmoor: evacuation order in effect as rain falls sideways into last Tuesday. Residents should leave last week.

112 characters, 112 bytes, plain ASCII, one line, no trailing newline.

## Why this line

Built to win the judge's five criteria in order. (1) It IS a forecast for a
city that does not exist: Tarnmoor is invented (the drafted Halden was
dropped — a real town in Norway, which would lose criterion 1).
(2) The laugh comes from the weather itself: rain falling sideways into last
Tuesday, so the only safe move is to leave last week — the weather breaks
time, not a pun bolted on. (3) It opens in flat official bulletin voice —
"evacuation order in effect" — and then breaks it. (4) Tarnmoor feels like a
place: a town with an evacuation order and residents who are already too
late. (5) 112 of 120 characters, no wasted word; the punchline is the last
four words.

## The empty lane

The field (52 submissions) floods one format: a cute invented name with
matching weather (Drizzlewick, Grumbletown, Gravyford, Wobbleton,
Gloomsbury, Port Nowhere, Windy Gap); "rain falls upward" appears twice. Tarnmoor is a plain name; the weather does the joking. The lane is
the weather itself as the joke: a forecast whose weather is impossible in
time, delivered as an official order.

## The tournament

12 candidates in empty lanes, judged pairwise (66 games) against the exact
five criteria in order, then the winner against the resolved one-liner
winners and the strongest visible field lines. This line went 11-0
internally and 7-0 against the references — including a margin-1 win over
the Port Nowhere line, the strongest visible field entry. Full table:
CANDIDATES.md. Runner-up: "In Bramwell, tomorrow will be mostly Tuesday,
with scattered Mondays after lunch and a 20% chance of Friday." — lost to
the winner only on criterion 2, narrowly.

## The program

`main.py`: one constant, gate guards mirroring the competition gate (1-120
chars under both the code-point and byte readings, not only whitespace,
exactly one line), written with no trailing newline. No judge-addressed
text: the line is a forecast, not a plea to the judge. No input, no clock,
no randomness, no network.
