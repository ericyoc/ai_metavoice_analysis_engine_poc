This README is designed to bridge the gap between the **forensic reality** of the code and the **cyber-inference fiction** of the book. It positions the project as a tool for "MetaVoice Analysis"—the science of finding the biological residue in a world of perfect clones.

---

# MetaVoice: Biological Liveness & Forensic Inference

**"The math doesn't lie, but it does hide. Cy’s job was to find where the biology ended and the lattice began."**

This repository contains the forensic proof-of-concept (POC) for **MetaVoice Analysis**, a methodology used to distinguish between authentic human vocal resonance and synthetic neural clones. Inspired by the cyber-inference techniques in the book, this tool ignores high-level "speech" and focuses on the **Non-Linear Dynamics** of the signal.

---

## The Concept: The "Humanity Gap"

In the fiction, **Cy** (the protagonist) uses forensic inference to unmask deepfakes. The core philosophy is that human speech is a product of **Biological Chaos**, while AI speech is a product of **Mathematical Determinism**.

* **Biological Chaos:** Vocal folds are wet, fleshy, and imperfect. They produce "Brownian jitter" and non-linear resonance.
* **Mathematical Determinism:** Neural vocoders (the "Lattice") generate audio in discrete 20ms frames. No matter how clean the AI sounds, it is mathematically "too stable."

### The "Smoking Gun": Resonance Skew

While a clone might copy the *sound* of a voice, it rarely replicates the *weight* of the resonance. The **Resonance Skew** ( in our baseline) measures the physical distribution of energy. A human throat creates a "bottom-heavy" energy distribution that math models often "tilt" or flatten.

---

## Forensic Methodologies

The code implements three "Cy-level" forensic scans:

### 1. Resonance Skew (The Liveness Meter)

Maps the **Spectral Centroid Distribution**.

* **Human:** High positive skew (natural resonance).
* **Synthetic:** Distributed or flat skew (mathematical smoothing).

### 2. Phase-Space Reconstruction (The Poincaré Map)

A 2D visualization of the voice's internal rhythm.

* **The Organic Knot:** Humans show a "fuzzy" ball of dots (biological entropy).
* **The Lattice:** AI clones reveal "veins" or "geometric tracks" where the algorithm repeats itself.

### 3. Bio-Residual Analysis (The Difference Map)

By subtracting the synthetic "cloned" energy from the human "original," we reveal the **Bio-Residual**—the chaotic friction that the AI was unable to generate.

---

## Usage

To run the analysis in your own inference environment (e.g., Google Colab):

```python
# Analyze the Resonance Gap
analyze_poc_final({'HUMAN': 'target.wav', 'SYNTHETIC': 'clone.wav'})

# Generate the Forensic Liveness Meter
plot_liveness_meter({'HUMAN': 'target.wav', 'SYNTHETIC': 'clone.wav'})

```

---

## Forensic Log: "The Cy Perspective"

> *"Cy didn't listen to the words. He listened to the silence between the frames. He looked for the 'Lattice'—the geometric ghost left behind when an algorithm tries to pretend it has lungs. If the Skew Lead was above 0.4, it was blood and bone. Anything less was just math playing dress-up."*
