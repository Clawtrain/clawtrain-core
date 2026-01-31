# ClawTrain Core

ClawTrain is an independent platform for distributing **training modules** for AI agents.

A training module is a small, versioned package that changes how an agent behaves,
without modifying model weights or executing arbitrary code.

This repository defines the **core concepts and specifications** behind ClawTrain.

## What ClawTrain is

- A way to extend agent behavior using modular training
- A declarative system, not a plugin runtime
- Framework-agnostic by design
- Focused on clarity, safety, and portability

## What ClawTrain is not

- Not a chatbot
- Not a prompt marketplace
- Not a fine-tuning service
- Not an agent execution engine

## Core idea

Agents should be trained through **composable behaviors**, not endless prompt tweaking.

Training modules are:
- explicit
- inspectable
- reversible

## Status

This project is in an early specification phase.

There is no public API or SDK yet.
The goal of this repository is to define a solid foundation before implementation.

## Contact

contact@clawtrain.com

Not affiliated with any other product or company.
