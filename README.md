# Two paths

This folder holds two courses. Each notebook already stores the output of its code cells. Open a notebook in Jupyter and use Restart and Run All to recompute it.

The Python path uses only the standard library. The calculus path also needs SymPy:

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
| `python-fundamentals/01-programs.ipynb` | How a Python program speaks |
| `python-fundamentals/02-names.ipynb` | Names, values, and assignment |
| `python-fundamentals/03-numbers.ipynb` | Numbers and arithmetic |
| `python-fundamentals/04-decisions.ipynb` | Decisions |
| `python-fundamentals/05-strings.ipynb` | Strings: positions and slices |
| `python-fundamentals/06-string-methods.ipynb` | String methods and f-strings |
| `python-fundamentals/07-loops.ipynb` | Loops |
| `python-fundamentals/08-lists.ipynb` | Lists |
| `python-fundamentals/09-tuples.ipynb` | Tuples and unpacking |
| `python-fundamentals/10-dictionaries.ipynb` | Dictionaries |
| `python-fundamentals/11-sets.ipynb` | Sets |
| `python-fundamentals/12-functions.ipynb` | Functions |
| `python-fundamentals/13-comprehensions.ipynb` | Comprehensions |
| `python-fundamentals/14-modules.ipynb` | Modules and the standard library |
| `python-fundamentals/15-files.ipynb` | Files |
| `python-fundamentals/16-exceptions.ipynb` | Exceptions |
| `python-fundamentals/17-classes.ipynb` | Classes |
| `python-fundamentals/18-walking-data.ipynb` | Walking through data |
| `python-fundamentals/19-small-program.ipynb` | A small program, built one step at a time |
| `python-fundamentals/20-recursion.ipynb` | Recursion |

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
| `01-functions.ipynb` | Functions: domain, range, composition, inverse, piecewise |
| `02-exponential-log-trigonometric.ipynb` | Exponential, logarithmic, trigonometric, and inverse trigonometric functions |
| `03-rational-asymptotes.ipynb` | Rational functions and asymptotes |
| `04-limits.ipynb` | Limits and the limit laws |
| `05-continuity.ipynb` | Continuity, the squeeze theorem, and the intermediate value theorem |
| `06-infinite-limits.ipynb` | Infinite limits and limits at infinity |
| `07-derivative-rules.ipynb` | The derivative: definition, power, product, and quotient rules |
| `08-chain-special-derivatives.ipynb` | The chain rule and derivatives of special functions |
| `09-implicit-logarithmic.ipynb` | Implicit differentiation and logarithmic differentiation |
| `10-related-rates.ipynb` | Related rates |
| `11-linearization-mvt.ipynb` | Linearization, differentials, Rolle, and the mean value theorem |
| `12-lhopital.ipynb` | L'Hôpital's rule |
| `13-curve-sketching.ipynb` | Curve sketching |
| `14-optimization.ipynb` | Optimization |
| `15-newtons-method.ipynb` | Newton's method |

### Calculus II

| Notebook | Title |
|---|---|
| `16-substitution-parts.ipynb` | Substitution and integration by parts |
| `17-trig-partial-fractions.ipynb` | Trigonometric integrals, trigonometric substitution, and partial fractions |
| `18-improper-integrals.ipynb` | Improper integrals |
| `19-area-between-curves.ipynb` | Area between curves |
| `20-volumes.ipynb` | Volumes: disks, washers, and shells |
| `21-arc-length-surface.ipynb` | Arc length and surfaces of revolution |
| `22-average-value-work.ipynb` | Average value and work |
| `23-sequences.ipynb` | Sequences |
| `24-series-tests.ipynb` | Series and convergence tests |
| `25-taylor-series.ipynb` | Power series, Taylor series, and Maclaurin series |
| `26-parametric-curves.ipynb` | Parametric curves |
| `27-polar.ipynb` | Polar coordinates |

### Multivariable calculus

| Notebook | Title |
|---|---|
| `28-vectors.ipynb` | Vectors, lines, and planes |
| `29-vector-functions.ipynb` | Vector functions |
| `30-multivariable-functions.ipynb` | Functions of several variables and limits in the plane |
| `31-partial-derivatives.ipynb` | Partial derivatives, the chain rule, and Clairaut's theorem |
| `32-gradient-tangent-plane.ipynb` | The gradient, directional derivatives, and tangent planes |
| `33-extrema-lagrange.ipynb` | Extrema and Lagrange multipliers |
| `34-multiple-integrals.ipynb` | Double and triple integrals |
| `35-coordinates-jacobian.ipynb` | Cylindrical coordinates, spherical coordinates, and the Jacobian |
| `36-line-integrals-green.ipynb` | Line integrals and Green's theorem |
| `37-stokes-divergence.ipynb` | Stokes' theorem and the divergence theorem |

### Differential equations

| Notebook | Title |
|---|---|
| `38-first-order-odes.ipynb` | First-order differential equations |
| `39-second-order-linear.ipynb` | Second-order linear homogeneous equations |
| `40-undetermined-variation.ipynb` | Undetermined coefficients and variation of parameters |
| `41-laplace-ivp.ipynb` | The Laplace transform and initial-value problems |
| `42-heaviside-dirac-convolution.ipynb` | The Heaviside function, the Dirac delta, and convolution |
| `43-series-solutions-systems.ipynb` | Series solutions and linear systems |
