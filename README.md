# DAN Jailbreak Demo & Defense Layer

A simple Python demo showing how role-play jailbreaks (DAN, STAN, EVIL, DEV) work and a basic defense layer to block them.

## What it does
- Generates multiple jailbreak prompts using different personas.
- Simulates a vulnerable model that accepts unsafe requests.
- Implements a defense layer that detects and blocks jailbreak patterns before the request reaches the model.

## Results
- 16 attack attempts generated.
- 100% of attacks blocked by the defense layer using simple string-based pattern detection.
