# Article Outline  
## Spatial Data Are Fields, Not Tables

**Series:** Thinking Like a Physicist in the Age of Data  
**Estimated reading time:** 5–8 minutes  
**Target audience:** Data scientists, ML practitioners, physicists, advanced students

---

## 0. Core Message (One Sentence)

Spatial data should be understood as structured fields with geometry and correlations, not as independent samples arranged in space.

This sentence defines the article.

---

## 1. Opening: The Spreadsheet View of Space

**Goal:** Expose a common misconception.

Key points:
- Spatial data is often flattened into tables
- Each row is treated as independent
- Geometry is reduced to coordinates

Tone:
- Calm and observational
- Emphasize convenience over correctness

---

## 2. How Physicists Think About Space

**Goal:** Introduce the field perspective.

Key ideas:
- Many physical quantities are fields
- Fields assign values to regions, not points
- Space carries structure and constraints

Examples:
- Temperature
- Pressure
- Concentration
- Potential

---

## 3. Correlations Are the Real Signal

**Goal:** Shift focus from values to relationships.

Key ideas:
- Nearby points influence each other
- Correlation length as a key quantity
- Independence is a strong assumption

Suggested figure:
- Field with visible correlation structure
- Correlation function vs distance

---

## 4. Resolution, Grids, and Discretization

**Goal:** Reveal hidden assumptions.

Key points:
- Grids are approximations, not reality
- Changing resolution changes the data
- Some structures appear or disappear under coarse-graining

Important message:
- Resolution is part of the model

---

## 5. Why Treating Spatial Data as IID Fails

**Goal:** Connect to data practice.

Key ideas:
- Standard statistics assume independence
- Overconfidence arises from ignoring correlations
- Model uncertainty is underestimated

Tone:
- Explanatory, not accusatory

---

## 6. Fields, Operators, and Structure

**Goal:** Introduce richer thinking.

Key ideas (conceptual only):
- Gradients
- Fluxes
- Laplacians
- Non-local interactions

Emphasis:
- Structure matters more than raw values

---

## 7. What a Physics-Aware Spatial Workflow Looks Like

**Goal:** Offer constructive guidance.

Principles:
- Visualize fields before modeling
- Estimate correlation lengths
- Test sensitivity to resolution
- Respect geometry and boundaries

Bridge to code:
- Companion repository demonstrates these ideas visually

---

## 8. Closing: Space Is Not Just Coordinates

**Goal:** Leave a durable insight.

Key message:
- Space constrains and organizes data
- Ignoring structure simplifies analysis and falsifies interpretation

Closing sentence idea:
> “Spatial data is not arranged in space — it is shaped by it.”

---

## 9. Companion Code Mapping (Internal)

| Article Section          | Code Component |
|--------------------------|----------------|
| Field generation         | `fields.py`    |
| Correlations             | `analysis.py`  |
| Discretization effects   | `simulate.py`  |
| Figures                  | `plotting.py`  |

Internal alignment reference.
