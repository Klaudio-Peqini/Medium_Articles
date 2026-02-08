# Spatial Data Are Fields, Not Tables  
## Structure, Correlations, and Geometry

This repository accompanies the Medium article:

**“Spatial Data Are Fields, Not Tables”**  
(part of the series *Thinking Like a Physicist in the Age of Data*)

The article argues that spatial data should be understood as realizations of fields with structure, correlations, and geometry — not as collections of independent rows in a table.

This repository provides concrete examples illustrating how spatial structure changes interpretation, modeling, and inference.

---

## Core Ideas

This project is built around a few central principles:

- Spatial data encodes geometry and correlations
- Nearby points are rarely independent
- Resolution and discretization matter
- Many spatial datasets are better understood as fields than as samples
- Ignoring spatial structure leads to misleading conclusions

The code emphasizes intuition, visualization, and physical meaning.

---

## Repository Structure

```text
05_Spatial_Data_and_Fields/
├── README.md
├── article_outline.md
├── notebooks/
│   └── main.ipynb
├── src/
│   ├── fields.py
│   ├── simulate.py
│   ├── analysis.py
│   └── plotting.py
├── figures/
└── requirements.txt
