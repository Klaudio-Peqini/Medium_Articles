# Time Is Not a Column  
## A Physicist’s View on Time Series

This repository accompanies the Medium article:

**“Time Is Not a Column: A Physicist’s View on Time Series”**  
(part of the series *Thinking Like a Physicist in the Age of Data*)

The goal of this project is to illustrate how physicists think about time-dependent data, and why many common time-series approaches fail when physical structure is ignored.

The article focuses on intuition and concepts.  
This repository provides the **scientific and computational backbone**.

---

## Core Ideas

This project is built around a few key principles:

- A time series is **not** just a column of numbers
- Observations are typically **projections of hidden dynamical states**
- Noise can be **intrinsic** to the system, not just a measurement error
- Predictability is a **physical property**, not a modeling trick
- Short-term accuracy does not imply long-term understanding

The code examples are intentionally simple, minimal, and physically interpretable.

---

## Repository Structure

```text
01_Time_Series_Physics/
├── README.md
├── article_outline.md
├── notebooks/
│   └── main.ipynb
├── src/
│   ├── systems.py
│   ├── simulate.py
│   ├── analysis.py
│   └── plotting.py
├── figures/
└── requirements.txt
