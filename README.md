<picture>
  <source media="(prefers-color-scheme: dark)" srcset="hero-dark.svg">
  <img alt="A hospital corridor at dawn. Trần Thế Trường — machine learning for clinical work in Vietnam." src="hero-light.svg" width="100%">
</picture>

I'm a student in Vietnam building machine learning for clinical work. The thread through all of it: a hospital runs on people, and the useful thing software can do is hand them back their time.

### → [**Walk the ward**](https://truong-tt.github.io/) — the long version, as a 3D night walk through a clinic

## What I'm building

**[CarePath](https://github.com/truong-tt/carepath-kpi)** — an AI medical scribe that listens in Vietnamese and writes the clinical note.

Vietnamese is tonal and low-resource: one syllable carries six words depending on a mark above it, and real consultations braid dialect through Latin drug names. So the work is fine-tuning that survives the transcriber's own mistakes, and measuring **entity-level error on the drug, the dose, the diagnosis** — not a flattering average over every word in the sentence. The repo is the weekly engineering log: pipeline freeze, error logging, beta monitoring, held-out numbers.

**[HopeGait](https://github.com/truong-tt/parkinson-fog-device)** — real-time freezing-of-gait detection from a wearable IMU.

Freezing of gait is a sudden mid-step arrest in Parkinson's and a primary fall risk. A causal temporal convolutional network reads the sensor — causal because a model that needs the future is no use mid-stride — quantised to int8 for a microcontroller at the hip. Cueing only helps if it arrives before the fall, so the whole design is an argument about latency. *Student research. Not a medical device.*

**[fpl-ml-manager](https://github.com/truong-tt/fpl-ml-manager)** — an autonomous Fantasy Premier League manager.

The same modelling, none of the stakes: quantile regression for point distributions, two-stage minutes prediction, Poisson match goals, and a MILP optimiser picking squad, XI, captain, and chips. It runs itself twice a day on GitHub Actions and is wrong in public all season. Most of what I know about shipping a model I learned somewhere with a scoreboard and no patients.

## Reach me

[tranth3truong@gmail.com](mailto:tranth3truong@gmail.com) · Việt Nam, UTC+7

<br>

> *Der Mensch kann tun was er will.*
> A person can do what they will.
