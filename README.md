# Nazi Pedia

A leveled, runnable reference for learning calculus with Python.
Each file is a Jupyter notebook. Restart it and run every cell from the top.
The cell checks its own result, so a finished run is a passing review of the lesson.

## How a lesson is taught

Every new idea moves in four steps:

1. **See** it — a picture, a story, or a small table, before the definition.
2. **Name** it — the mathematical word and the Python spelling.
3. **Do** it — a worked example.
4. **Own** it — a short task, then an answer key.

From complex numbers onward, a result is not finished until a **second method** agrees with it:
a numerical table, a derivative, Vieta's formulas, or an independent solver.

## The path

| Notebook | Level | Subject |
|---|---|---|
| 001 | 0 | Names, values, and types |
| 002 | 0 | Decisions, repetition, and functions |
| 003 | 1 | Complex numbers |
| 004 | 1 | Roots of polynomials |
| 005 | 1 | Graphs of functions |
| 006 | 2 | Limits |
| 007 | 2 | Derivatives |
| 010 | 2 | Critical points (after 007; integrals are not required) |
| 008 | 3 | Indefinite integrals |
| 009 | 3 | Definite integrals |
| 011 | 4 | Laplace transform |
| 012 | 4 | First-order linear differential equations |

Lesson 010 keeps its original number. Its place in the sequence is immediately after derivatives.

## Run

```text
py -m pip install -r requirements.txt
```

Open the notebooks in Jupyter or VS Code / Cursor and run them in path order.
Python 3.10 or newer is required, because lesson 002 uses `match`.
