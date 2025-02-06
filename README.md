# Adolescent Mental Health Dynamics: Integrating Social Network Effects and Adaptive Intervention Strategies with EEG Data

## Overview

Adolescent mental health is a pressing global concern, closely linked to the developmental challenges and unique vulnerabilities of this critical life stage. To address the limitations of traditional static methodologies, we propose an innovative computational framework—the **Adolescent Mental Health Dynamic Representation Model (AMHDRM)**—which integrates multi-dimensional feature embedding, temporal dynamics, and graph-based social network coupling. 

Additionally, the **Dynamic Intervention Optimization Strategy (DIOS)** is introduced to design personalized, cost-effective interventions based on predictive analytics and causal inference.

## Key Features

- **Multi-dimensional Feature Embedding**: Captures various aspects of adolescent mental health data.
- **Temporal Dynamics Modeling**: Understands changes in mental health status over time.
- **Graph-based Social Network Coupling**: Integrates social interactions to enhance predictive accuracy.
- **Dynamic Intervention Optimization Strategy (DIOS)**: Provides personalized and cost-effective intervention strategies.
- **High Predictive Accuracy**: Outperforms state-of-the-art models on multiple benchmark datasets.

## Experimental Results

Our framework was evaluated on multiple benchmark datasets, achieving **state-of-the-art performance**:

| Dataset  | Accuracy | F1-score | AUC  |
|----------|---------|---------|------|
| PhyAAt   | **91.21%** | **88.90%** | **89.45%** |
| AMIGOS   | **89.33%** | **88.02%** | **87.98%** |

Our model outperforms existing methods by **2.76% on PhyAAt** and **2.03% on AMIGOS**, demonstrating **superior predictive power and interpretability**. Ablation studies reveal performance drops of over **5%** when key components are removed.

## Installation

To set up the environment and run the experiments, follow these steps:

```bash
# Clone the repository
git clone https://github.com/yourusername/adolescent-mental-health-dynamics.git

# Navigate to the project directory
cd adolescent-mental-health-dynamics

# Create a virtual environment (optional)
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

# Install dependencies
pip install -r requirements.txt
