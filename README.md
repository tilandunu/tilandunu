# Tilan Dunuwila

Frontend-focused software engineer. I build the interface, I design it, and I can build the API behind it when that is what the work needs.

[tilandunuwila.dev](https://tilandunuwila.dev) · [LinkedIn](https://www.linkedin.com/in/tilandunuwila)

---

## What I Actually Do

I build the layer people use. Most of my work is React: component architecture, state that stays predictable as a feature grows, and the unglamorous parts — forms, permissions, loading and error paths — that decide whether an application feels solid or fragile.

The interface is where the system is judged. Everything the backend gets right is invisible until the client expresses it clearly, and everything it gets wrong surfaces here first. I treat that as an engineering responsibility, not a styling one.

---

## On the Frontend

- **State goes where it is used.** Most complexity comes from state lifted higher than it needs to be. I colocate first and lift only when something genuinely shared demands it.
- **Components are contracts.** A component's props are an API. If it needs six flags to behave correctly, the boundary is drawn in the wrong place and I redraw it rather than add a seventh.
- **Server data is not component state.** Remote data has its own lifecycle — stale, loading, failed, refetching — and pretending it is ordinary local state is where most frontend bugs start.
- **Every state gets designed.** Loading, empty, partial, error, unauthorized. These are the honest surface of what the system is doing, and they are part of the feature, not cleanup afterwards.
- **Trust nothing from the client, including my own.** I validate in the interface for speed of feedback, and never assume that check is the one protecting the data.
- **Performance is structural.** Wasted renders, layout thrash, and animating the wrong properties are architecture problems that show up as jank. Cheaper to design out than to profile away.
- **Semantics before styling.** Correct structure, keyboard reachability, and focus handling come first — accessibility and responsiveness follow from them instead of being retrofitted.

---

## The Design Half

I came in through design — UI/UX, graphic, and motion work — and kept it, because it changes what I can do as a frontend engineer.

- I read a Figma file for intent, not just measurements. I know which details were decisions and which were placeholders, because I have been the one making them.
- Motion is engineering with taste attached: animating transform and opacity rather than layout properties, staying inside the frame budget, using timing and easing to explain what just happened in the system, and honouring reduced-motion instead of overriding it.
- I can define a visual system — type scale, spacing, colour, states — and then implement it as components that hold up, rather than a set of one-off screens that drift apart.
- When a design cannot survive real data, long strings, empty results, an unexpected locale, I catch it while it is still a file rather than after it ships.

---

## The Backend Behind It

I have built and shipped backend work — REST APIs, authentication, role-based access control, and the data models underneath — and I still do when a project calls for it.

Its real value is what it does to my frontend work. I know what a given endpoint costs, why a response is shaped the way it is, and when the right fix is in the client versus one layer down. I can propose a contract that serves the interface instead of accepting one that fights it, and I can have that conversation in the backend team's own terms.

---

## Why That Combination

Design, frontend, and API usually sit with three different people, and the seams between them are where quality leaks: the endpoint returns something the interface cannot express cleanly, the design assumes data that does not exist, and the negotiation happens through tickets.

I work across those seams. Less translation, fewer mismatches discovered late, and one person who can carry a feature from the intent behind the design through to what the interface actually does with the response.

---

## How I Work With People

Review is where design gets corrected cheaply — I would rather spend the hour there than debugging the same decision later. I document what the code cannot say for itself: setup, environment, and the reasoning behind choices that look arbitrary from the outside. Leading student engineering groups taught me the rest of it, which is that the right technical answer is only useful once the team understands why it is the answer.

---

## Working Vocabulary

**Primary** — React, JavaScript, HTML, CSS
**Backend** — Java, Spring Boot, Node.js, Express, MongoDB, MySQL
**Also** — Python, C++
**Infrastructure** — Docker, Kubernetes, Git
**Design** — Figma, motion and interaction design, visual and brand work

---

## Currently

Going deeper on frontend architecture — component boundaries that hold under growth, and the data layer between client and API. Alongside that, working on context-aware credibility verification: knowledge graphs and multi-source analysis applied to claims where the truth is contested and still incomplete at the moment it matters.

---

Open to frontend and full-stack engineering roles, and to technical collaboration.
[tilandunuwila.dev](https://tilandunuwila.dev) · [LinkedIn](https://www.linkedin.com/in/tilandunuwila)
