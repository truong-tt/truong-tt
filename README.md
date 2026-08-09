<picture>
  <source media="(prefers-color-scheme: dark)" srcset="hero-dark.svg">
  <img alt="Dawn over layered mountain ridges. Trần Thế Trường — clinical machine learning, built in Vietnam." src="hero-light.svg" width="100%">
</picture>

Incoming **BSc Data Science at VinUniversity** (September 2026). I build software for care work — the unglamorous, high-stakes kind that happens in clinics and in people's homes.

The through-line: a machine should carry the load and a person should keep the judgement. Which means the interesting engineering problem is usually not the model, but deciding exactly where the system has to stop — and making it say so plainly when it has not actually done the thing.

### → [**truong-tt.github.io**](https://truong-tt.github.io/)

## What I'm building

**[Kề](https://ke-elder-care-web.vercel.app/)** — voice-first care coordination for an older adult and their family. *(live demo)*

Spoken check-ins and everyday requests in Vietnamese become explicit states the family can review and act on, through a bounded coordinator with eight case states and a full event log. Every action stops at coordination or a handoff: an appointment request records a manual clinic contact and returns `booked: false`, a refill records that medicine is running low and orders nothing, marking a bill paid changes a local reminder and nothing else. Drawing that line — and making the system refuse to claim it acted — was the hard part.

**[HopeGait](https://github.com/truong-tt/parkinson-fog-device)** — real-time freezing-of-gait detection from a wearable IMU.

Freezing of gait is a sudden mid-step arrest in Parkinson's and a primary fall risk. A causal temporal convolutional network reads the sensor — causal because a model that needs the future is no use mid-stride — quantised to int8 for a microcontroller at the hip. Cueing only helps if it arrives before the fall, so the whole design is an argument about latency. *Student research. Not a medical device.*

**[CarePath](https://github.com/truong-tt/carepath-kpi)** — an AI medical scribe that listens in Vietnamese and writes the clinical note.

Vietnamese is tonal and low-resource, and real consultations braid dialect through Latin drug names. So the work is fine-tuning that survives the transcriber's own mistakes, and measuring **entity-level error on the drug, the dose, the diagnosis** — not a flattering average over every word in the sentence.

**[fpl-ml-manager](https://github.com/truong-tt/fpl-ml-manager)** — an autonomous Fantasy Premier League manager.

The same modelling, none of the stakes: quantile regression for point distributions, Poisson match goals, and a MILP optimiser picking squad, XI, captain and chips. It runs itself twice a day on GitHub Actions and is wrong in public all season. Most of what I know about shipping a model I learned somewhere with a scoreboard and no patients.

## Reach me

[tranth3truong@gmail.com](mailto:tranth3truong@gmail.com) · Việt Nam, UTC+7
