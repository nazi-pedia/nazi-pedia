# Three paths

The tutorial is three numbered folders, taken in order. Each notebook already stores the output of its code cells. Open a notebook in Jupyter and use Restart and Run All to recompute it.

```text
01-Python Fundamentals/     20 lessons, standard library only
02-Numpy Fundamentals/      16 lessons, needs NumPy
03-Calculus with Python/    43 lessons, needs SymPy
README.md
requirements.txt
```

`01` uses only the Python standard library. `02` and `03` need the packages in `requirements.txt`:

```powershell
py -m pip install -r requirements.txt
```

## Python Fundamentals

Twenty lessons, from the first `print` through a small program and recursion. Every example uses the same rhythm.

1. **Predict.** Read the code and decide what it will print.
2. **Run.** Compare your guess with the stored output.
3. **One change.** The next example moves a single detail.
4. **Pitfall.** One case looks almost right and is not.
5. **Summary.** The sentences worth keeping.

Formulas are written as display mathematics. Code comments name the step you are looking at.

| Notebook | Title |
|---|---|
| `01-Python Fundamentals/01-programs.ipynb` | How a Python program speaks |
| `01-Python Fundamentals/02-names.ipynb` | Names, values, and assignment |
| `01-Python Fundamentals/03-numbers.ipynb` | Numbers and arithmetic |
| `01-Python Fundamentals/04-decisions.ipynb` | Decisions |
| `01-Python Fundamentals/05-strings.ipynb` | Strings: positions and slices |
| `01-Python Fundamentals/06-string-methods.ipynb` | String methods and f-strings |
| `01-Python Fundamentals/07-loops.ipynb` | Loops |
| `01-Python Fundamentals/08-lists.ipynb` | Lists |
| `01-Python Fundamentals/09-tuples.ipynb` | Tuples and unpacking |
| `01-Python Fundamentals/10-dictionaries.ipynb` | Dictionaries |
| `01-Python Fundamentals/11-sets.ipynb` | Sets |
| `01-Python Fundamentals/12-functions.ipynb` | Functions |
| `01-Python Fundamentals/13-comprehensions.ipynb` | Comprehensions |
| `01-Python Fundamentals/14-modules.ipynb` | Modules and the standard library |
| `01-Python Fundamentals/15-files.ipynb` | Files |
| `01-Python Fundamentals/16-exceptions.ipynb` | Exceptions |
| `01-Python Fundamentals/17-classes.ipynb` | Classes |
| `01-Python Fundamentals/18-walking-data.ipynb` | Walking through data |
| `01-Python Fundamentals/19-small-program.ipynb` | A small program, built one step at a time |
| `01-Python Fundamentals/20-recursion.ipynb` | Recursion |

## NumPy

Sixteen lessons, from the first array through a small numerical study. The rhythm matches the Python path, and every formula is computed by hand before NumPy repeats it.

1. **Predict** the values, the shape, or the hand result.
2. **Run** and compare with the stored output.
3. **One change** shows what that detail controls.
4. **A pitfall** is a case that looks almost right.
5. A **summary** keeps the rule.

Broadcasting, reductions, and matrix algebra are written as display mathematics. Every code cell is commented.

| Notebook | Title |
|---|---|
| `02-Numpy Fundamentals/01-creating-arrays.ipynb` | How an array is different from a list |
| `02-Numpy Fundamentals/02-shape-dtype.ipynb` | Shape, dtype, and reshape |
| `02-Numpy Fundamentals/03-indexing.ipynb` | Indexing and slicing |
| `02-Numpy Fundamentals/04-masks.ipynb` | Boolean masks and fancy indexing |
| `02-Numpy Fundamentals/05-vectorized.ipynb` | Vectorized arithmetic |
| `02-Numpy Fundamentals/06-broadcasting.ipynb` | Broadcasting |
| `02-Numpy Fundamentals/07-reductions.ipynb` | Reductions along an axis |
| `02-Numpy Fundamentals/08-ufuncs.ipynb` | Universal functions |
| `02-Numpy Fundamentals/09-missing.ipynb` | Missing values |
| `02-Numpy Fundamentals/10-sorting.ipynb` | Sorting and uniqueness |
| `02-Numpy Fundamentals/11-combining.ipynb` | Stacking and splitting |
| `02-Numpy Fundamentals/12-views-copies.ipynb` | Views and copies |
| `02-Numpy Fundamentals/13-random.ipynb` | Random numbers |
| `02-Numpy Fundamentals/14-vectors.ipynb` | Vector algebra |
| `02-Numpy Fundamentals/15-matrices.ipynb` | Matrix algebra |
| `02-Numpy Fundamentals/16-numerical-study.ipynb` | A numerical study, built one step at a time |

## Calculus with Python

Forty-three lessons, from functions through differential equations. Each lesson teaches the idea by hand, then recomputes the same result in SymPy and checks that the two answers agree.

1. State the definition and the problem.
2. Solve it by hand, line by line, in display mathematics.
3. Recheck with Python. The hand answer and the SymPy answer are printed, and their difference must be zero.
4. Close with one pitfall and a short summary.

An indefinite integral is rechecked by differentiation, because SymPy omits the constant of integration.

### Calculus I

| Notebook | Title |
|---|---|
| `03-Calculus with Python/01-functions.ipynb` | Functions: domain, range, composition, inverse, piecewise |
| `03-Calculus with Python/02-exponential-log-trigonometric.ipynb` | Exponential, logarithmic, trigonometric, and inverse trigonometric functions |
| `03-Calculus with Python/03-rational-asymptotes.ipynb` | Rational functions and asymptotes |
| `03-Calculus with Python/04-limits.ipynb` | Limits and the limit laws |
| `03-Calculus with Python/05-continuity.ipynb` | Continuity, the squeeze theorem, and the intermediate value theorem |
| `03-Calculus with Python/06-infinite-limits.ipynb` | Infinite limits and limits at infinity |
| `03-Calculus with Python/07-derivative-rules.ipynb` | The derivative: definition, power, product, and quotient rules |
| `03-Calculus with Python/08-chain-special-derivatives.ipynb` | The chain rule and derivatives of special functions |
| `03-Calculus with Python/09-implicit-logarithmic.ipynb` | Implicit differentiation and logarithmic differentiation |
| `03-Calculus with Python/10-related-rates.ipynb` | Related rates |
| `03-Calculus with Python/11-linearization-mvt.ipynb` | Linearization, differentials, Rolle, and the mean value theorem |
| `03-Calculus with Python/12-lhopital.ipynb` | L'Hôpital's rule |
| `03-Calculus with Python/13-curve-sketching.ipynb` | Curve sketching |
| `03-Calculus with Python/14-optimization.ipynb` | Optimization |
| `03-Calculus with Python/15-newtons-method.ipynb` | Newton's method |

### Calculus II

| Notebook | Title |
|---|---|
| `03-Calculus with Python/16-substitution-parts.ipynb` | Substitution and integration by parts |
| `03-Calculus with Python/17-trig-partial-fractions.ipynb` | Trigonometric integrals, trigonometric substitution, and partial fractions |
| `03-Calculus with Python/18-improper-integrals.ipynb` | Improper integrals |
| `03-Calculus with Python/19-area-between-curves.ipynb` | Area between curves |
| `03-Calculus with Python/20-volumes.ipynb` | Volumes: disks, washers, and shells |
| `03-Calculus with Python/21-arc-length-surface.ipynb` | Arc length and surfaces of revolution |
| `03-Calculus with Python/22-average-value-work.ipynb` | Average value and work |
| `03-Calculus with Python/23-sequences.ipynb` | Sequences |
| `03-Calculus with Python/24-series-tests.ipynb` | Series and convergence tests |
| `03-Calculus with Python/25-taylor-series.ipynb` | Power series, Taylor series, and Maclaurin series |
| `03-Calculus with Python/26-parametric-curves.ipynb` | Parametric curves |
| `03-Calculus with Python/27-polar.ipynb` | Polar coordinates |

### Multivariable calculus

| Notebook | Title |
|---|---|
| `03-Calculus with Python/28-vectors.ipynb` | Vectors, lines, and planes |
| `03-Calculus with Python/29-vector-functions.ipynb` | Vector functions |
| `03-Calculus with Python/30-multivariable-functions.ipynb` | Functions of several variables and limits in the plane |
| `03-Calculus with Python/31-partial-derivatives.ipynb` | Partial derivatives, the chain rule, and Clairaut's theorem |
| `03-Calculus with Python/32-gradient-tangent-plane.ipynb` | The gradient, directional derivatives, and tangent planes |
| `03-Calculus with Python/33-extrema-lagrange.ipynb` | Extrema and Lagrange multipliers |
| `03-Calculus with Python/34-multiple-integrals.ipynb` | Double and triple integrals |
| `03-Calculus with Python/35-coordinates-jacobian.ipynb` | Cylindrical coordinates, spherical coordinates, and the Jacobian |
| `03-Calculus with Python/36-line-integrals-green.ipynb` | Line integrals and Green's theorem |
| `03-Calculus with Python/37-stokes-divergence.ipynb` | Stokes' theorem and the divergence theorem |

### Differential equations

| Notebook | Title |
|---|---|
| `03-Calculus with Python/38-first-order-odes.ipynb` | First-order differential equations |
| `03-Calculus with Python/39-second-order-linear.ipynb` | Second-order linear homogeneous equations |
| `03-Calculus with Python/40-undetermined-variation.ipynb` | Undetermined coefficients and variation of parameters |
| `03-Calculus with Python/41-laplace-ivp.ipynb` | The Laplace transform and initial-value problems |
| `03-Calculus with Python/42-heaviside-dirac-convolution.ipynb` | The Heaviside function, the Dirac delta, and convolution |
| `03-Calculus with Python/43-series-solutions-systems.ipynb` | Series solutions and linear systems |
