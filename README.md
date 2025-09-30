# Weather Predictor – Probabilistic Reasoning with Markov Chains

## Overview

This repository demonstrates the use of **Markov chains** for reasoning under uncertainty, applied to a simple yet illustrative task: **weather prediction**.

It contains:

* A Python implementation of a Markov Chain–based weather predictor.
* Supporting documentation that introduces probabilistic reasoning concepts and situates Markov models within broader AI techniques.

---

## Repository Contents

* **`weather_predictor.py`**
  A Python script implementing a weather forecasting system using Markov chains. Includes:

  * Transition matrix definition
  * Next-day prediction
  * Multi-day sequence forecasting
  * Probability distributions
  * Steady-state (long-term) analysis
  * Demonstration examples

* **`Reasoning_uncertain_environments.md`**
  Documentation covering:

  * Fundamentals of probabilistic reasoning
  * Comparison of Markov chains and Markov networks
  * Applications in weather prediction, medical diagnosis, recommendation systems, fraud detection, and web optimization
  * Key takeaways for building intelligent agents under uncertainty

* **`README.md`**
  (this file) – entry point for understanding the project.

---

## Getting Started

### Requirements

* Python 3.8+
* NumPy

Install dependencies:

```bash
pip install numpy
```

### Running the Example

Execute the predictor with:

```bash
python weather_predictor.py
```

The script will:

1. Display the transition matrix.
2. Predict the next day’s weather based on current conditions.
3. Simulate multi-day forecasts.
4. Show long-term probability distributions.
5. Run multiple simulations for comparison.

---

## Example Output (excerpt)

```
STATE TRANSITION MATRIX
------------------------------------------------------------
Current State     | Sunny        | Cloudy       | Rainy
------------------------------------------------------------
Sunny             | 70.0%        | 20.0%        | 10.0%
Cloudy            | 30.0%        | 40.0%        | 30.0%
Rainy             | 20.0%        | 30.0%        | 50.0%
```

---

## Use Cases

* **Education**: Demonstrates Markov models in AI coursework.
* **Research**: Provides a baseline implementation for reasoning under uncertainty.
* **Practical Extensions**: Can be adapted for recommendation systems, fraud detection, or user behavior modeling.

---
