# Lab 02 · NumPy for Numerical Computing

**Course:** CS-3105 Machine Learning Lab
**Lab Instructor:** Engr. Muhammad Awais
**Student:** Mahdi Ali
**Roll No:** 2024-SE-16
**CLO 5 (C-3 Apply, PLO 5 Modern Tool Usage):** Use Python programming and tools to perform data handling and basic operations.

## Files

| File | Description |
|------|-------------|
| `Lab02_2024-SE-16_Mahdi Ali.ipynb` | Completed notebook with code, labelled outputs, interpretations and reflection |
| `README.md` | This file |

## Requirements

- Python 3.8+
- NumPy
- Matplotlib (only for the optional image display in Task 10)

```bash
pip install numpy matplotlib
```

## How to run

1. Open the notebook in Jupyter or Google Colab.
2. Choose **Runtime → Restart and run all** (Colab) or **Kernel → Restart & Run All** (Jupyter).
3. Run the dataset cell first. It defines `units`, `pop_2023`, `pop_2017`, `cities`, `months`, `tmax`, `rain`, `cpi_months`, `cpi` and `marks`.

## Tasks covered

| Task | Topic | Main NumPy functions |
|------|-------|----------------------|
| 1 | Setup | `np.__version__` |
| 2 | Creating arrays | `zeros`, `ones`, `full`, `arange`, `reshape`, `eye` |
| 3 | Randomness and reproducibility | `random.seed`, `rand`, `randn`, `randint`, `unique`, boolean masks |
| 4 | Spacing and reshaping | `arange`, `linspace`, `reshape`, `sum(axis)`, `argmax` |
| 5 | Indexing and slicing (exam hall) | slicing, `sum`, `std` |
| 6 | Census 2023 data | `sum`, `argmax`, boolean indexing, vectorised growth formula |
| 7 | Climate of five cities | `mean(axis)`, `argmax(axis)`, comparisons, column slicing |
| 8 | Inflation FY2024 vs FY2025 | boolean indexing, `np.where` |
| 9 | Grace marks | `clip`, `mean`, `where`, z-score |
| 10 | An image is an array | slicing, `[:, ::-1]`, `clip`, `shape`, `dtype` |
| 11 | Reflection | Markdown cell |

## Datasets

- **Census 2023:** Pakistan Bureau of Statistics, 7th Population and Housing Census.
- **Climate:** 1991–2020 climate normals (PMD / WMO).
- **Inflation:** Pakistan Economic Survey 2024-25, Chapter 7, Fig 7.1 (PBS CPI, year-on-year %).
- **Marks:** Sample lab-section marks.

## Rules followed

- No Python loops where a NumPy function exists.
- Every output is labelled, e.g. `print("T6b:", ...)`.
- Notebook run top to bottom with a fresh kernel.

## Submission

Push to `ML-Lab-<RollNo>/Lab02/Lab02.ipynb` by **Thursday 29 Oct, 11:59 PM**.

```bash
git add Lab02/Lab02.ipynb
git commit -m "Add Lab 02 NumPy"
git push
```
