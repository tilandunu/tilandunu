# Tilan Dunuwila

Software engineer. I build the system underneath and the interface on top of it, and I don't treat the second as decoration.

[tilandunuwila.dev](https://tilandunuwila.dev) · [LinkedIn](https://www.linkedin.com/in/tilandunuwila)

---

## What I Actually Do

I write backends for applications where the rules matter — stock that several places read and write at once, money moving through a transaction, records that only certain people may open. That work is mostly data modelling, API design, and access control: deciding what the system considers true, who is allowed to change it, and what the contract looks like to everything downstream.

Then I build the client that consumes it. Not as a separate discipline handed off to someone else, but because I have usually already decided what the interface needs to say by the time I have designed the endpoint that feeds it.

---

## On the Backend

- **The contract comes first.** The API surface is the part other people build against and the hardest thing to change once they have. I design it before I implement behind it.
- **The server is the authority.** Validation and authorization belong where they cannot be bypassed. The client is untrusted input, however convenient it would be to assume otherwise.
- **Authorization is a relationship, not a flag.** A role by itself rarely answers the question. What matters is this user, this record, this scope — and that check runs server-side every time.
- **Shared state is where systems break.** When several modules write to the same data, correctness lives in the write paths, not in each module's private view of the world.
- **Model the domain, not the screens.** Schemas that follow business meaning survive redesigns. Schemas that follow the current UI do not.

---

## On the Interface

I came to engineering with a design background — UI/UX, graphic design, and motion — and I have kept it because it makes me faster at the part most backend engineers hand off.

- I can work from a Figma file without losing intent in translation, because I have been on the other side of that handoff and know which details were decisions and which were placeholders.
- Motion is engineering as much as taste: animating transform and opacity rather than layout properties, keeping interactions inside the frame budget, using timing and easing to explain what the system just did, and respecting reduced-motion preferences instead of overriding them.
- Interface states are product states. Loading, empty, partial, error, and unauthorized are not edge cases to bolt on later — they are the honest surface of what the backend is doing, and they get designed alongside the endpoint.
- Accessibility and responsiveness are structural. They come from correct semantics and layout early, not from a pass at the end.

---

## Why That Combination

Most teams split this in two, and the seam is where quality leaks: the API returns something the interface cannot express cleanly, the design assumes data the backend does not have, and both sides negotiate through tickets.

I work across that seam. It means I design endpoints with the eventual interaction already in mind, catch the mismatch while it is still cheap to fix, and communicate the tradeoff in the vocabulary of whichever side I am talking to. On a small team, that is one less translation layer.

---

## How I Work With People

Code review is where design gets corrected cheaply — I would rather spend the hour there than debugging the same decision later. I document what is not obvious from reading the code: setup, environment, and the reasoning behind choices that look arbitrary from the outside. And I have spent enough time leading student engineering groups to know that the technical answer is only useful once the rest of the team understands why it is the answer.

---

## Working Vocabulary

**Primary** — Java, Spring Boot, React, MongoDB
**Also** — Node.js, Express, JavaScript, Python, C++, MySQL
**Infrastructure** — Docker, Kubernetes, Git
**Design** — Figma, motion and interaction design, visual and brand work

---

## Currently

Deepening backend architecture — service boundaries, data modelling under real load, and the operational side of running what I build. Alongside that, working on context-aware credibility verification: knowledge graphs and multi-source analysis applied to claims where the truth is contested and incomplete at the moment it matters most.

---

Open to software engineering roles and technical collaboration.
[tilandunuwila.dev](https://tilandunuwila.dev) · [LinkedIn](https://www.linkedin.com/in/tilandunuwila)
