# Object-Centric Process Mining with OCEL 1.0

## Dataset
- Used the `example.jsonocel` log from the OCEL 1.0 standard.

## Experiment
- Loaded the OCEL 1.0 log in Google Colab using PM4Py.
- Ran the **object-centric directly-follows discovery** algorithm.
- Visualized the **Object-Centric Directly-Follows Graph (OC-DFG)**.

## Results
- The OC-DFG shows how events are connected across multiple objects.
- Unlike traditional case-based logs, the OCEL format allows linking one event to multiple objects.
- This avoids convergence/divergence issues and gives a more accurate process picture.

## How to Reproduce
1. Install PM4Py:
   ```bash
   pip install pm4py
