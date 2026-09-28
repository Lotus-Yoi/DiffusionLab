# DiffusionLab

> A laboratory for systematic Stable Diffusion experiments.

DiffusionLab is a personal experimental project for exploring **how prompts actually affect image generation**, rather than treating prompt writing as pure trial and error.

The project starts from a simple question:

**Which prompt terms are actually doing the work?**

Instead of manually changing prompts one image at a time, DiffusionLab aims to turn prompt exploration into reproducible experiments: keep selected variables fixed, change prompt terms or combinations, generate batches of images, and compare the results.

## Current idea

The first stage will focus on prompt experiments with a local Stable Diffusion setup.

Possible experiments include:

- testing individual prompt terms;
- testing combinations of prompt terms;
- generating multiple seeds for the same prompt;
- keeping the seed fixed while changing prompts;
- comparing batches side by side;
- recording prompts, seeds and generation parameters;
- gradually identifying which terms and combinations strongly affect the result.

## Why this project?

Good results often come from a combination of model choice, prompt wording, seed and generation parameters. When several things change at once, it becomes difficult to know **why** an image worked.

DiffusionLab is an attempt to make that process observable.

The goal is not to automate aesthetic judgment. The experiments provide evidence and comparisons; the final judgment of what looks good remains human.

## Roadmap

For now, the project is intentionally small.

**Phase 1 — Prompt experiments**

Build a simple script that can systematically vary prompt terms and generate image batches through the local Stable Diffusion environment.

**Later**

The project may grow to explore seeds, models, LoRAs, samplers, parameters and more complex workflows.

The direction will evolve from actual experiments rather than being fixed in advance.

---

**Status:** Project initialized. No experimental code yet.
