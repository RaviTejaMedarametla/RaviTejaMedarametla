<div align="center">

# Ravi Teja Medarametla

### AI Systems Engineering • Hardware-Aware Machine Learning • Edge AI Optimization

*Building efficient, reliable ML systems for real-world deployment constraints.*

</div>

---

## Overview

This repository serves as a curated portfolio of projects centered on **hardware-aware machine learning** and **applied ML systems engineering**. The focus is not just model accuracy, but full-stack system performance across:

- **Memory efficiency**
- **Latency constraints**
- **Compute and power budgets**
- **Deployment reliability on edge-class hardware**

The projects in this portfolio are built with a systems mindset: each experiment and implementation is evaluated through the lens of practical deployment.

---

## Systems Workflow

The common engineering pipeline reflected across projects:

```text
Data Engineering → Model Training → Model Compression → Hardware Optimization → Edge Deployment
```

This workflow emphasizes reproducibility, measurable efficiency gains, and production-aware model design.

---

## Project Portfolio

### 1) Edge AI Optimization

#### `edge-ai-hardware-optimization`
Design-space exploration for convolutional models with a focus on:
- Structured and unstructured pruning strategies
- Quantization-aware trade-off analysis
- Throughput/latency/resource benchmarking
- Selection of efficient model-hardware operating points

### 2) ML Systems Engineering

#### `neural-network-from-scratch`
A first-principles neural network implementation designed to expose core systems trade-offs:
- Configurable numeric precision
- Controlled training pipeline behavior
- Constraint-aware experimentation for low-resource targets

#### `classification-of-handwritten-digits1`
Comparative study of classical ML approaches for handwritten digit classification:
- Baseline model benchmarking
- Compression-oriented evaluation
- Performance profiling under constrained execution settings

### 3) Data Engineering for ML

#### `data-analysis-for-hospitals`
Healthcare-focused analytics workflow with strong preprocessing discipline:
- Deterministic and repeatable data preparation
- Feature engineering for robust inference
- CPU-optimized model evaluation patterns

#### `nba-data-preprocessing`
Streaming-oriented preprocessing pipeline built for efficiency:
- Memory-aware transformation stages
- Pipeline observability and telemetry-conscious execution
- Clean handoff to model training and inference workloads

---

## Technical Stack

| Category | Tools |
|---|---|
| Core Language | Python |
| Numerical Computing | NumPy |
| Deep Learning | PyTorch |
| Classical ML | scikit-learn |
| Model Interoperability | ONNX, ONNX Runtime |
| Serving / APIs | FastAPI |

---

## Research Themes

- Hardware-aware machine learning architectures
- Model compression and systems-level optimization
- Deterministic ML pipelines for reproducible results
- Statistical benchmarking and empirical evaluation
- Edge inference and deployment-ready model design

---

## Engineering Philosophy

> High-performing ML systems are not defined by accuracy alone.
> They are defined by how efficiently, reliably, and reproducibly they operate in constrained environments.

This portfolio reflects a practical commitment to that philosophy through implementation-driven research and performance-conscious engineering.
