<p align="center">
  <img src="./assets/hero.svg" alt="Alon Baron — systems-minded full-stack developer" width="900">
</p>

<p align="center">
  <a href="https://numra.co.il">
    <img src="./assets/numra-card.svg" alt="NUMRA — live classroom math racing platform" width="445">
  </a>
  <a href="https://dogsocial.vercel.app">
    <img src="./assets/pawpals-card.svg" alt="PawPals — social network for dog owners" width="445">
  </a>
</p>

## The bigger picture

I’m a second-year Computer Science student and a developer in a healthcare Information Systems team.
I’m interested in what makes software dependable: the boundaries between components, the shape of the
data, the rules enforced by the backend, and the decisions that keep a system understandable as it grows.

Syntax is a tool. **Architecture, trade-offs, and ownership of complexity are the real work.**

That mindset carries across the systems I build—from enterprise healthcare environments to real-time
products used by actual people.

## Production work

### [NUMRA](https://numra.co.il) — real-time classroom math racing

A Hebrew-first educational platform where teachers launch live races and students solve arithmetic
questions from their own devices. I designed it around a server-authoritative game engine: scoring,
difficulty, power-ups, route decisions, catch-up logic, and final rankings all belong to the backend.

`React 19` · `Spring Boot 4` · `PostgreSQL` · `SSE` · `AWS EC2/RDS` · `Docker` · `Caddy`

### [PawPals](https://dogsocial.vercel.app) — a social platform for dog owners

A full-stack social network with user and dog profiles, posts, follows, reactions, image uploads, and
playdate scheduling. It gave me practical experience with authentication, relational data modeling,
ownership rules, pagination, race conditions, production error handling, and deployment.

`React` · `Spring Boot` · `MySQL` · `JWT` · `Railway` · `Vercel`

[View the PawPals source →](https://github.com/alonbaron/dogsocial)

### More live work

**[Gal Baron Insurance](https://www.galb-ins.co.il)** — a production Hebrew/RTL website for an
independent insurance agent, with accessible service discovery, a lead funnel, EmailJS contact flows,
WhatsApp integration, SEO metadata, and AWS Amplify hosting. The source remains private because it is
client work.

## Other systems & experiments

| Project | What it explores |
|---|---|
| **ALMAS / Virtual Try-On** | Architecture for a high-end jewelry configurator and image-based virtual try-on workflow using Next.js, TypeScript, Python, and FastAPI. |
| **[Dining Philosophers](https://github.com/alonbaron/DiningPhilosophers)** | A Java concurrency visualizer using global lock ordering and `ReentrantLock` to prevent deadlock and race conditions. |
| **[Mortal Madmach](https://github.com/alonbaron/MortalMadmachGame)** | A Java Swing arena game with AI behavior, combat state, custom art, audio, rounds, and power-ups. |
| **[Telegram Survey Bot](https://github.com/alonbaron/TelegramApiSurveyBot)** | A Java desktop app that creates Telegram surveys, collects inline-button votes, and presents results in Swing. |
| **[Connect Four](https://github.com/alonbaron/connect4)** | A configurable React game with local/AI modes, timers, undo, responsive UI, and animated state transitions. |
| **[ID Validator & Wordle](https://github.com/alonbaron/IDChecker_WordleGame)** | Input validation, checksum logic, and a two-pass repeated-letter algorithm for correct Wordle feedback. |

## How I build

<p align="center">
  <img src="./assets/architecture.svg" alt="Alon's engineering approach: model, enforce, observe, evolve" width="900">
</p>

- Start with invariants and data flow, not framework choices.
- Keep business rules where they can be enforced and tested.
- Design failure paths as deliberately as happy paths.
- Use AI to accelerate execution while keeping engineering judgment human.
- Prefer small, reviewable changes over impressive rewrites.

## Working toolkit

**Core:** Java · Python · TypeScript · JavaScript · SQL<br>
**Application:** Spring Boot · React · REST APIs · JWT · JPA/Hibernate<br>
**Data & delivery:** PostgreSQL · MySQL · Docker · AWS · Railway · Vercel<br>
**Workflow:** Git · testing · architecture docs · Codex · Claude · agentic development

## Connect

[Email](mailto:alonbaron123@gmail.com) · [GitHub](https://github.com/alonbaron)

<p align="center">
  <sub>Build the model. Define the rules. Then write the code.</sub>
</p>
