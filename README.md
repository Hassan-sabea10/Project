# BuildVision
**Smart Construction Calculator — Iraq 2024**

---

## What is BuildVision?

BuildVision is a C++ console application designed to help anyone planning to build a house in Iraq get an instant estimate of the materials they need and the total construction cost — without needing an engineer.

The program supports calculating and comparing **two houses** side by side so the user can make smarter decisions before starting construction.

---

## The Problem It Solves

Most people in Iraq who want to build a house have no easy way to estimate how much bricks, cement, sand, or iron they need — or how much it will cost — before they hire a contractor. BuildVision gives them that estimate in seconds.

---

## What the User Provides

| Input | Details |
|---|---|
| Floor area | Size of one floor in m² |
| Number of floors | Between 1 and 5 |
| Floor height | Between 2.5m and 6.0m (default: 3.0m) |
| Build type | Economic / Standard / Luxury |

---

## What the Program Returns

| Output | Details |
|---|---|
| Wall area | Total wall surface in m² |
| Bricks | Number of bricks needed |
| Cement | Number of 50kg bags |
| Sand | Quantity in tons |
| Iron | Quantity in kg |
| Total cost | Estimated cost in USD |

> All material quantities include a **2% waste factor** for transport and handling losses.

---

## Build Types

| Type | Price per m² |
|---|---|
| Economic | $180 |
| Standard | $320 |
| Luxury | $550 |

---

## Comparison Feature

After calculating both houses, BuildVision generates a **comparison report** showing:
- Which house costs more and by how much
- Which house is taller
- Which house requires more materials

---

## Goals

- Make construction planning accessible to everyone
- Provide estimates based on Iraqi engineering standards
- Help users compare options before making financial decisions

---

## Author

**Hassan Sabea** — Computer Science Student, Iraq  
GitHub: [@Hassan-sabea10](https://github.com/Hassan-sabea10)

