# Twelve paths

The tutorial is twelve numbered folders, taken in order. Each notebook already stores the output of its code cells. Open a notebook in Jupyter and use Restart and Run All to recompute it.

```text
01-Jupyter Notebook/              16 lessons, standard library only
02-Python Fundamentals/           20 lessons, standard library only
03-Numpy Fundamentals/            16 lessons, needs NumPy
04-Calculus with Python/          43 lessons, needs SymPy
05-Data Visualization/            16 lessons, needs Matplotlib
06-Linear Regression/             25 lessons, needs NumPy, SymPy, and SciPy
07-Polynomial Regression/         16 lessons, needs NumPy, SymPy, and SciPy
08-Support Vector Machines (SVM)/ 16 lessons, standard library only
09-Decision Trees/                16 lessons, needs Matplotlib
10-k-Nearest Neighbors (k-NN)/    16 lessons, needs Matplotlib
11-Perceptron/                     16 lessons, needs Matplotlib
12-Multilayer Perceptron (MLP)/   16 lessons, needs Matplotlib
README.md
requirements.txt
```

`01`, `02`, and `08` use only the Python standard library. `03`, `04`, `05`, `06`, `07`, `09`, `10`, `11`, and `12` need the packages in `requirements.txt`:

```powershell
py -m pip install -r requirements.txt
```

## 01. Jupyter Notebook

Sixteen lessons, from the first cell to a saved morning note. The page comes before the language. Path 02 teaches Python. Here every code cell is short, the arithmetic is done by hand first, and the output under the cell is the answer key.

1. Read the prediction and the hand result.
2. Compare them with the stored output.
3. The next example changes one detail.
4. One pitfall shows a cell that looks quiet, stale, or easy to run twice.
5. A summary keeps the rule.

The numbers stay small: piles of 2, 3, and 4 cups, then a morning when Ada, Grace, Alan, and Linus read 4, 6, 3, and 5 pages. Restart and Run All uses only the Python standard library.

| Notebook | Title |
|---|---|
| `01-Jupyter Notebook/01-a-stack-of-cells.ipynb` | A notebook is a stack of cells |
| `01-Jupyter Notebook/02-one-cell.ipynb` | The kernel runs one cell |
| `01-Jupyter Notebook/03-story-and-work.ipynb` | The story and the work |
| `01-Jupyter Notebook/04-lists-tables-links.ipynb` | A list, a table, and a link |
| `01-Jupyter Notebook/05-mathematics.ipynb` | Mathematics in the story |
| `01-Jupyter Notebook/06-what-the-cell-shows.ipynb` | What the cell shows you |
| `01-Jupyter Notebook/07-names-in-the-kernel.ipynb` | Names stay in the kernel |
| `01-Jupyter Notebook/08-running-twice.ipynb` | Running a cell twice |
| `01-Jupyter Notebook/09-run-order.ipynb` | The page order and the run order |
| `01-Jupyter Notebook/10-when-a-cell-stops.ipynb` | When a cell stops |
| `01-Jupyter Notebook/11-readable-cells.ipynb` | A cell a person can read |
| `01-Jupyter Notebook/12-numbers-on-the-page.ipynb` | Numbers the full run can see |
| `01-Jupyter Notebook/13-the-notebook-file.ipynb` | The notebook is a file |
| `01-Jupyter Notebook/14-check-a-result.ipynb` | Check a result you already know |
| `01-Jupyter Notebook/15-keys.ipynb` | Keys you will actually use |
| `01-Jupyter Notebook/16-morning-note.ipynb` | One morning note |

## 02. Python Fundamentals

Open the Jupyter Notebook path first. These twenty lessons teach the language, from the first `print` through a small program and recursion. Every example uses the same rhythm.

1. **Predict.** Read the code and decide what it will print.
2. **Run.** Compare your guess with the stored output.
3. **One change.** The next example moves a single detail.
4. **Pitfall.** One case looks almost right and is not.
5. **Summary.** The sentences worth keeping.

Formulas are written as display mathematics. Code comments name the step you are looking at.

| Notebook | Title |
|---|---|
| `02-Python Fundamentals/01-programs.ipynb` | How a Python program speaks |
| `02-Python Fundamentals/02-names.ipynb` | Names, values, and assignment |
| `02-Python Fundamentals/03-numbers.ipynb` | Numbers and arithmetic |
| `02-Python Fundamentals/04-decisions.ipynb` | Decisions |
| `02-Python Fundamentals/05-strings.ipynb` | Strings: positions and slices |
| `02-Python Fundamentals/06-string-methods.ipynb` | String methods and f-strings |
| `02-Python Fundamentals/07-loops.ipynb` | Loops |
| `02-Python Fundamentals/08-lists.ipynb` | Lists |
| `02-Python Fundamentals/09-tuples.ipynb` | Tuples and unpacking |
| `02-Python Fundamentals/10-dictionaries.ipynb` | Dictionaries |
| `02-Python Fundamentals/11-sets.ipynb` | Sets |
| `02-Python Fundamentals/12-functions.ipynb` | Functions |
| `02-Python Fundamentals/13-comprehensions.ipynb` | Comprehensions |
| `02-Python Fundamentals/14-modules.ipynb` | Modules and the standard library |
| `02-Python Fundamentals/15-files.ipynb` | Files |
| `02-Python Fundamentals/16-exceptions.ipynb` | Exceptions |
| `02-Python Fundamentals/17-classes.ipynb` | Classes |
| `02-Python Fundamentals/18-walking-data.ipynb` | Walking through data |
| `02-Python Fundamentals/19-small-program.ipynb` | A small program, built one step at a time |
| `02-Python Fundamentals/20-recursion.ipynb` | Recursion |

## 03. NumPy

Sixteen lessons, from the first array through a small numerical study. The rhythm matches the Python path, and every formula is computed by hand before NumPy repeats it.

1. **Predict** the values, the shape, or the hand result.
2. **Run** and compare with the stored output.
3. **One change** shows what that detail controls.
4. **A pitfall** is a case that looks almost right.
5. A **summary** keeps the rule.

Broadcasting, reductions, and matrix algebra are written as display mathematics. Every code cell is commented.

| Notebook | Title |
|---|---|
| `03-Numpy Fundamentals/01-creating-arrays.ipynb` | How an array is different from a list |
| `03-Numpy Fundamentals/02-shape-dtype.ipynb` | Shape, dtype, and reshape |
| `03-Numpy Fundamentals/03-indexing.ipynb` | Indexing and slicing |
| `03-Numpy Fundamentals/04-masks.ipynb` | Boolean masks and fancy indexing |
| `03-Numpy Fundamentals/05-vectorized.ipynb` | Vectorized arithmetic |
| `03-Numpy Fundamentals/06-broadcasting.ipynb` | Broadcasting |
| `03-Numpy Fundamentals/07-reductions.ipynb` | Reductions along an axis |
| `03-Numpy Fundamentals/08-ufuncs.ipynb` | Universal functions |
| `03-Numpy Fundamentals/09-missing.ipynb` | Missing values |
| `03-Numpy Fundamentals/10-sorting.ipynb` | Sorting and uniqueness |
| `03-Numpy Fundamentals/11-combining.ipynb` | Stacking and splitting |
| `03-Numpy Fundamentals/12-views-copies.ipynb` | Views and copies |
| `03-Numpy Fundamentals/13-random.ipynb` | Random numbers |
| `03-Numpy Fundamentals/14-vectors.ipynb` | Vector algebra |
| `03-Numpy Fundamentals/15-matrices.ipynb` | Matrix algebra |
| `03-Numpy Fundamentals/16-numerical-study.ipynb` | A numerical study, built one step at a time |

## 04. Calculus with Python

Forty-three lessons, from functions through differential equations. Each lesson teaches the idea by hand, then recomputes the same result in SymPy and checks that the two answers agree.

1. State the definition and the problem.
2. Solve it by hand, line by line, in display mathematics.
3. Recheck with Python. The hand answer and the SymPy answer are printed, and their difference must be zero.
4. Close with one pitfall and a short summary.

An indefinite integral is rechecked by differentiation, because SymPy omits the constant of integration.

### Calculus I

| Notebook | Title |
|---|---|
| `04-Calculus with Python/01-functions.ipynb` | Functions: domain, range, composition, inverse, piecewise |
| `04-Calculus with Python/02-exponential-log-trigonometric.ipynb` | Exponential, logarithmic, trigonometric, and inverse trigonometric functions |
| `04-Calculus with Python/03-rational-asymptotes.ipynb` | Rational functions and asymptotes |
| `04-Calculus with Python/04-limits.ipynb` | Limits and the limit laws |
| `04-Calculus with Python/05-continuity.ipynb` | Continuity, the squeeze theorem, and the intermediate value theorem |
| `04-Calculus with Python/06-infinite-limits.ipynb` | Infinite limits and limits at infinity |
| `04-Calculus with Python/07-derivative-rules.ipynb` | The derivative: definition, power, product, and quotient rules |
| `04-Calculus with Python/08-chain-special-derivatives.ipynb` | The chain rule and derivatives of special functions |
| `04-Calculus with Python/09-implicit-logarithmic.ipynb` | Implicit differentiation and logarithmic differentiation |
| `04-Calculus with Python/10-related-rates.ipynb` | Related rates |
| `04-Calculus with Python/11-linearization-mvt.ipynb` | Linearization, differentials, Rolle, and the mean value theorem |
| `04-Calculus with Python/12-lhopital.ipynb` | L'Hôpital's rule |
| `04-Calculus with Python/13-curve-sketching.ipynb` | Curve sketching |
| `04-Calculus with Python/14-optimization.ipynb` | Optimization |
| `04-Calculus with Python/15-newtons-method.ipynb` | Newton's method |

### Calculus II

| Notebook | Title |
|---|---|
| `04-Calculus with Python/16-substitution-parts.ipynb` | Substitution and integration by parts |
| `04-Calculus with Python/17-trig-partial-fractions.ipynb` | Trigonometric integrals, trigonometric substitution, and partial fractions |
| `04-Calculus with Python/18-improper-integrals.ipynb` | Improper integrals |
| `04-Calculus with Python/19-area-between-curves.ipynb` | Area between curves |
| `04-Calculus with Python/20-volumes.ipynb` | Volumes: disks, washers, and shells |
| `04-Calculus with Python/21-arc-length-surface.ipynb` | Arc length and surfaces of revolution |
| `04-Calculus with Python/22-average-value-work.ipynb` | Average value and work |
| `04-Calculus with Python/23-sequences.ipynb` | Sequences |
| `04-Calculus with Python/24-series-tests.ipynb` | Series and convergence tests |
| `04-Calculus with Python/25-taylor-series.ipynb` | Power series, Taylor series, and Maclaurin series |
| `04-Calculus with Python/26-parametric-curves.ipynb` | Parametric curves |
| `04-Calculus with Python/27-polar.ipynb` | Polar coordinates |

### Multivariable calculus

| Notebook | Title |
|---|---|
| `04-Calculus with Python/28-vectors.ipynb` | Vectors, lines, and planes |
| `04-Calculus with Python/29-vector-functions.ipynb` | Vector functions |
| `04-Calculus with Python/30-multivariable-functions.ipynb` | Functions of several variables and limits in the plane |
| `04-Calculus with Python/31-partial-derivatives.ipynb` | Partial derivatives, the chain rule, and Clairaut's theorem |
| `04-Calculus with Python/32-gradient-tangent-plane.ipynb` | The gradient, directional derivatives, and tangent planes |
| `04-Calculus with Python/33-extrema-lagrange.ipynb` | Extrema and Lagrange multipliers |
| `04-Calculus with Python/34-multiple-integrals.ipynb` | Double and triple integrals |
| `04-Calculus with Python/35-coordinates-jacobian.ipynb` | Cylindrical coordinates, spherical coordinates, and the Jacobian |
| `04-Calculus with Python/36-line-integrals-green.ipynb` | Line integrals and Green's theorem |
| `04-Calculus with Python/37-stokes-divergence.ipynb` | Stokes' theorem and the divergence theorem |

### Differential equations

| Notebook | Title |
|---|---|
| `04-Calculus with Python/38-first-order-odes.ipynb` | First-order differential equations |
| `04-Calculus with Python/39-second-order-linear.ipynb` | Second-order linear homogeneous equations |
| `04-Calculus with Python/40-undetermined-variation.ipynb` | Undetermined coefficients and variation of parameters |
| `04-Calculus with Python/41-laplace-ivp.ipynb` | The Laplace transform and initial-value problems |
| `04-Calculus with Python/42-heaviside-dirac-convolution.ipynb` | The Heaviside function, the Dirac delta, and convolution |
| `04-Calculus with Python/43-series-solutions-systems.ipynb` | Series solutions and linear systems |

## 05. Data Visualization

Sixteen lessons, from one question through lines, bars, distributions, heatmaps, and a one-week report. Every chart is drawn with Matplotlib, and the picture is stored in the notebook.

1. Ask one question.
2. Compute the number that answers it.
3. Encode that number as length, position, or color.
4. Title the finding and label the units.
5. Read the sentence back from the picture, and name one way it could be misread.

The running example is one week at North Lab. The same table becomes a ranking, a time line, and a heatmap. Each picture is allowed to answer only the question it was built for.

| Notebook | Title |
|---|---|
| `05-Data Visualization/01-one-question.ipynb` | One question, one chart |
| `05-Data Visualization/02-figure-and-axes.ipynb` | The page and the panel |
| `05-Data Visualization/03-lines.ipynb` | Change over time |
| `05-Data Visualization/04-scatter.ipynb` | Two measurements on one person |
| `05-Data Visualization/05-bars.ipynb` | Length means amount |
| `05-Data Visualization/06-histograms.ipynb` | How a pile of numbers spreads |
| `05-Data Visualization/07-boxplots.ipynb` | Five numbers, and the point that sits alone |
| `05-Data Visualization/08-small-multiples.ipynb` | Several panels, one question each |
| `05-Data Visualization/09-labels-and-color.ipynb` | Say what the marks mean |
| `05-Data Visualization/10-annotations.ipynb` | Mark the point that matters |
| `05-Data Visualization/11-heatmaps.ipynb` | A table you can see |
| `05-Data Visualization/12-cumulative-share.ipynb` | The running share |
| `05-Data Visualization/13-which-chart.ipynb` | Pick the chart from the question |
| `05-Data Visualization/14-scales.ipynb` | Scales that change the story |
| `05-Data Visualization/15-save-and-reuse.ipynb` | A function, then a file |
| `05-Data Visualization/16-full-study.ipynb` | North Lab, one week |

## 06. Linear Regression

Twenty-five lessons, from the prediction line through a complete numerical study. Every example is solved by hand in display mathematics. Python then repeats the arithmetic, and the two answers are required to agree.

1. State the definition and derive the result.
2. Work the numbers by hand, line by line.
3. Recheck with Python. The hand answer and the computed answer are printed, and they must match.
4. Close with one pitfall and a short summary.

When a loss is differentiated, the derivative is written out, and SymPy confirms that derivative. Inference uses SciPy's $t$ quantiles.

| Notebook | Title |
|---|---|
| `06-Linear Regression/01-prediction-line.ipynb` | The prediction line |
| `06-Linear Regression/02-residuals.ipynb` | Residuals and the sum of squares |
| `06-Linear Regression/03-least-squares-formulas.ipynb` | Deriving the slope and the intercept |
| `06-Linear Regression/04-complete-fit.ipynb` | A complete fit, with every sum written out |
| `06-Linear Regression/05-r-squared.ipynb` | The decomposition and $R^2$ |
| `06-Linear Regression/06-correlation.ipynb` | Correlation and the slope |
| `06-Linear Regression/07-through-the-origin.ipynb` | Regression through the origin |
| `06-Linear Regression/08-design-matrix.ipynb` | The design matrix |
| `06-Linear Regression/09-multiple-regression.ipynb` | Multiple regression |
| `06-Linear Regression/10-projection.ipynb` | Projection and the hat matrix |
| `06-Linear Regression/11-gauss-markov.ipynb` | The Gauss–Markov model |
| `06-Linear Regression/12-standard-errors.ipynb` | Estimating the error variance |
| `06-Linear Regression/13-inference.ipynb` | Tests and confidence intervals |
| `06-Linear Regression/14-prediction-intervals.ipynb` | Intervals for a mean response and for a new observation |
| `06-Linear Regression/15-indicator-variables.ipynb` | Indicator variables |
| `06-Linear Regression/16-polynomials.ipynb` | Polynomial regression |
| `06-Linear Regression/17-interactions.ipynb` | Interactions |
| `06-Linear Regression/18-centering.ipynb` | Centering |
| `06-Linear Regression/19-collinearity.ipynb` | Collinearity |
| `06-Linear Regression/20-influence.ipynb` | Leverage and Cook's distance |
| `06-Linear Regression/21-diagnostics.ipynb` | Residual patterns |
| `06-Linear Regression/22-gradient-descent.ipynb` | Gradient descent |
| `06-Linear Regression/23-ridge.ipynb` | Ridge regression |
| `06-Linear Regression/24-weighted-least-squares.ipynb` | Weighted least squares |
| `06-Linear Regression/25-full-study.ipynb` | A complete study |

## 07. Polynomial Regression

Sixteen lessons, from the meaning of a polynomial coefficient through interpolation, conditioning, lack of fit, and a complete study. The method matches the linear-regression path.

1. State the definition and derive the result.
2. Work the numbers by hand, line by line.
3. Recheck with Python. The hand answer and the computed answer are printed, and they must match.
4. Close with one pitfall and a short summary.

A polynomial regression is linear in its coefficients, so the normal equations are the same ones as in path `06`. The new material is the choice of degree, the shape of the basis, and what a perfect fit does and does not mean.

| Notebook | Title |
|---|---|
| `07-Polynomial Regression/01-polynomial-model.ipynb` | A polynomial is linear in its coefficients |
| `07-Polynomial Regression/02-vandermonde.ipynb` | The Vandermonde matrix |
| `07-Polynomial Regression/03-quadratic-fit.ipynb` | Fitting a quadratic by hand |
| `07-Polynomial Regression/04-the-line.ipynb` | The straight line on the same curve |
| `07-Polynomial Regression/05-r-squared.ipynb` | $R^2$ for a polynomial |
| `07-Polynomial Regression/06-extra-sum-of-squares.ipynb` | The extra sum of squares |
| `07-Polynomial Regression/07-cubic.ipynb` | The cubic hidden in the residuals |
| `07-Polynomial Regression/08-shifting-origin.ipynb` | Shifting the origin |
| `07-Polynomial Regression/09-orthogonal-ridge.ipynb` | Orthogonal polynomials, then ridge |
| `07-Polynomial Regression/10-inference.ipynb` | Standard errors and tests |
| `07-Polynomial Regression/11-prediction.ipynb` | Prediction from a polynomial |
| `07-Polynomial Regression/12-interpolation.ipynb` | Interpolation and the Runge warning |
| `07-Polynomial Regression/13-conditioning.ipynb` | The condition of the monomial basis |
| `07-Polynomial Regression/14-lack-of-fit.ipynb` | Lack of fit and pure error |
| `07-Polynomial Regression/15-two-variables.ipynb` | A polynomial in two inputs |
| `07-Polynomial Regression/16-full-study.ipynb` | A complete study |

## 08. Support Vector Machines

Sixteen lessons, from a signed score to kernels and a single training step. The prose stays close to the arithmetic. Each example is proved before it is coded.

1. State the rule or the optimization problem in display mathematics.
2. Solve a small numerical case by hand, including the constraints.
3. Recheck with Python. The hand answer and the computed answer must match.
4. Close with one pitfall and the sentence worth keeping.

The hard-margin street, the hinge, and the kernels are calculated directly. No solver library is required. A multiplier is trusted only after it rebuilds $\mathbf{w}$ and satisfies complementary slackness.

| Notebook | Title |
|---|---|
| `08-Support Vector Machines (SVM)/01-signed-scores.ipynb` | A score, then a sign |
| `08-Support Vector Machines (SVM)/02-distance-and-margin.ipynb` | How far is a point from the line? |
| `08-Support Vector Machines (SVM)/03-widest-street.ipynb` | The widest empty street |
| `08-Support Vector Machines (SVM)/04-three-point-fit.ipynb` | Three points, solved by hand |
| `08-Support Vector Machines (SVM)/05-support-vectors.ipynb` | Support vectors are the points that hold the street |
| `08-Support Vector Machines (SVM)/06-lagrange-kkt.ipynb` | Lagrange multipliers and the KKT conditions |
| `08-Support Vector Machines (SVM)/07-the-dual.ipynb` | The dual problem |
| `08-Support Vector Machines (SVM)/08-recover-weights.ipynb` | From multipliers back to a prediction |
| `08-Support Vector Machines (SVM)/09-hinge-and-slack.ipynb` | Pay for a point inside the street |
| `08-Support Vector Machines (SVM)/10-soft-margin-line.ipynb` | Four points on a line |
| `08-Support Vector Machines (SVM)/11-feature-maps.ipynb` | A line in a bigger space |
| `08-Support Vector Machines (SVM)/12-xor-and-kernels.ipynb` | XOR, separated by a product |
| `08-Support Vector Machines (SVM)/13-rbf-kernel.ipynb` | A kernel from distance |
| `08-Support Vector Machines (SVM)/14-one-versus-rest.ipynb` | More than two labels |
| `08-Support Vector Machines (SVM)/15-pegasos-step.ipynb` | One training step |
| `08-Support Vector Machines (SVM)/16-full-study.ipynb` | Full study: from a score to a kernel |

## 09. Decision Trees

Sixteen lessons, from walking a finished tree through Gini, entropy, regression leaves, pruning, and rectangles. Every split is calculated by hand before Python repeats it. Matplotlib draws the regions; no tree library is required.

1. State the definition and prove the small result.
2. Work one table by hand, including the fractions.
3. Recheck with Python. The hand answer and the computed answer must match.
4. Close with one pitfall and the sentence worth keeping.

The running table is eight inspected parts. A part passes only when its length is at most $7/2$ and its weight is at most $3$. Ties in gain are broken in writing, because a silent tie can swap the feature ranking.

| Notebook | Title |
|---|---|
| `09-Decision Trees/01-walk-a-tree.ipynb` | A tree is a list of questions |
| `09-Decision Trees/02-majority-leaf.ipynb` | The leaf should name the majority |
| `09-Decision Trees/03-gini.ipynb` | Gini impurity |
| `09-Decision Trees/04-entropy.ipynb` | Entropy |
| `09-Decision Trees/05-information-gain.ipynb` | The gain of a question |
| `09-Decision Trees/06-thresholds.ipynb` | Why the midpoint is enough |
| `09-Decision Trees/07-grow-the-tree.ipynb` | Grow until the leaves are pure |
| `09-Decision Trees/08-regression-mean.ipynb` | A leaf that predicts a number |
| `09-Decision Trees/09-regression-split.ipynb` | Where to cut a regression leaf |
| `09-Decision Trees/10-depth.ipynb` | A deep tree can memorize one point |
| `09-Decision Trees/11-pruning.ipynb` | Pay for every extra leaf |
| `09-Decision Trees/12-feature-credit.ipynb` | How much impurity a feature removed |
| `09-Decision Trees/13-rectangles.ipynb` | The cuts are rectangles |
| `09-Decision Trees/14-named-features.ipynb` | A question with names, not numbers |
| `09-Decision Trees/15-grow-and-predict.ipynb` | The same rules, written as functions |
| `09-Decision Trees/16-full-study.ipynb` | Full study: eight parts, one odd point, one price |

## 10. k-Nearest Neighbors

Sixteen lessons, from a stored table through distance, votes, weights, scaling, and leave-one-out. Every neighbor is ranked by hand before Python repeats the sort. Matplotlib draws the boundary; no neighbor library is required.

1. State the rule and prove the small result.
2. Work today's query on the same six mornings.
3. Recheck with Python. The hand answer and the computed answer must match.
4. Close with one pitfall and the sentence worth keeping.

The memory is three busy mornings and three quiet ones, so a global majority cannot answer. Today is $(2, 2)$. One neighbor says busy, five unweighted neighbors say quiet, and the same five with weights $1/d$ say busy again.

| Notebook | Title |
|---|---|
| `10-k-Nearest Neighbors (k-NN)/01-stored-cases.ipynb` | Look at the stored mornings |
| `10-k-Nearest Neighbors (k-NN)/02-euclidean-distance.ipynb` | Straight-line distance |
| `10-k-Nearest Neighbors (k-NN)/03-one-neighbor.ipynb` | One neighbor |
| `10-k-Nearest Neighbors (k-NN)/04-the-vote.ipynb` | Let several neighbors vote |
| `10-k-Nearest Neighbors (k-NN)/05-weighted-votes.ipynb` | A nearer morning gets a heavier vote |
| `10-k-Nearest Neighbors (k-NN)/06-scaling.ipynb` | A large unit can hide the neighbor |
| `10-k-Nearest Neighbors (k-NN)/07-scale-from-training.ipynb` | The query does not help compute the scale |
| `10-k-Nearest Neighbors (k-NN)/08-manhattan.ipynb` | Another way to add the gaps |
| `10-k-Nearest Neighbors (k-NN)/09-regression.ipynb` | Neighbors can average a number |
| `10-k-Nearest Neighbors (k-NN)/10-distance-ties.ipynb` | Two mornings at the same distance |
| `10-k-Nearest Neighbors (k-NN)/11-the-boundary.ipynb` | The boundary is the set of ties |
| `10-k-Nearest Neighbors (k-NN)/12-many-dimensions.ipynb` | In many dimensions the gap shrinks |
| `10-k-Nearest Neighbors (k-NN)/13-leave-one-out.ipynb` | Score $k$ by hiding one stored row |
| `10-k-Nearest Neighbors (k-NN)/14-the-procedure.ipynb` | One procedure, every answer we already know |
| `10-k-Nearest Neighbors (k-NN)/15-zero-distance.ipynb` | Distance zero is a stored copy |
| `10-k-Nearest Neighbors (k-NN)/16-full-study.ipynb` | Today, worked from the table |

## 11. Perceptron

Sixteen lessons, from reading a score to the update rule, the convergence bound, and a pocket for a paper no line can fit. Every update is written by hand before Python repeats it. Matplotlib draws the lines; no perceptron library is required.

1. State the rule and prove the small result.
2. Work the same points by hand, including the fractions.
3. Recheck with Python. The hand answer and the computed answer must match.
4. Close with one pitfall and the sentence worth keeping.

Pass is $+1$ and fail is $-1$. A point is correct only when its margin is positive. On one measurement the walk uses $5$ updates and the bound promises at most $10$. In the plane, three papers reach $2x_1 + x_2 - 1$ in three updates, a second order reaches a different line, and neither line is the widest.

| Notebook | Title |
|---|---|
| `11-Perceptron/01-read-a-score.ipynb` | Read a score |
| `11-Perceptron/02-one-update.ipynb` | One update |
| `11-Perceptron/03-why-a-bias.ipynb` | Why a bias is there |
| `11-Perceptron/04-five-updates.ipynb` | Five updates on a line |
| `11-Perceptron/05-two-scores.ipynb` | Two scores, one line |
| `11-Perceptron/06-the-first-update.ipynb` | The first update in the plane |
| `11-Perceptron/07-three-updates.ipynb` | Three updates reach a line |
| `11-Perceptron/08-the-margin-grows.ipynb` | The margin grows by a square |
| `11-Perceptron/09-why-it-stops.ipynb` | Why the updates stop |
| `11-Perceptron/10-step-size.ipynb` | The step size |
| `11-Perceptron/11-the-other-order.ipynb` | The other order |
| `11-Perceptron/12-not-the-widest.ipynb` | Not the widest line |
| `11-Perceptron/13-xor.ipynb` | Four gates with no line |
| `11-Perceptron/14-the-loss.ipynb` | The loss can rise |
| `11-Perceptron/15-the-pocket.ipynb` | Keep the best weights seen |
| `11-Perceptron/16-full-study.ipynb` | One line, from zero |

## 12. Multilayer Perceptron

Sixteen lessons, from a layer of scores through a bend, XOR, the chain rule, and one gradient step. Every derivative is computed by hand before Python repeats it. Matplotlib draws the bend and the two step sizes; no network library is required.

1. State the rule and prove the small result.
2. Work the same gates by hand, including the fractions.
3. Recheck with Python. The hand answer and the computed answer must match.
4. Close with one pitfall and the sentence worth keeping.

The four gates are XOR. Two straight layers still score gate 00 as $2$. One ReLU fold, $h_1 - 2h_2$, scores them $0, 1, 1, 0$. A step of size $1/8$ on a perturbed output moves the loss from $1/2$ to $23/128$. A step of size $1/4$ moves it to $23/32$.

| Notebook | Title |
|---|---|
| `12-Multilayer Perceptron (MLP)/01-a-layer.ipynb` | A layer is several scores |
| `12-Multilayer Perceptron (MLP)/02-two-layers-one-line.ipynb` | Two straight layers are still one line |
| `12-Multilayer Perceptron (MLP)/03-relu.ipynb` | ReLU bends one coordinate |
| `12-Multilayer Perceptron (MLP)/04-xor-forward.ipynb` | The hidden pair is the whole table |
| `12-Multilayer Perceptron (MLP)/05-the-bend.ipynb` | Where the bend sits |
| `12-Multilayer Perceptron (MLP)/06-one-hidden-unit.ipynb` | One hidden unit cannot build XOR |
| `12-Multilayer Perceptron (MLP)/07-sigmoid.ipynb` | A smooth bend |
| `12-Multilayer Perceptron (MLP)/08-squared-loss.ipynb` | The squared loss |
| `12-Multilayer Perceptron (MLP)/09-the-chain-rule.ipynb` | The chain rule, one unit deep |
| `12-Multilayer Perceptron (MLP)/10-a-dead-unit.ipynb` | A dead unit blocks the input weights |
| `12-Multilayer Perceptron (MLP)/11-two-hidden-units.ipynb` | Back through two hidden units |
| `12-Multilayer Perceptron (MLP)/12-the-step-size.ipynb` | The step size decides the total |
| `12-Multilayer Perceptron (MLP)/13-the-bias-gradient.ipynb` | The bias is a weight on the constant 1 |
| `12-Multilayer Perceptron (MLP)/14-identical-units.ipynb` | Identical units stay identical |
| `12-Multilayer Perceptron (MLP)/15-a-probability.ipynb` | A score can be read as a probability |
| `12-Multilayer Perceptron (MLP)/16-full-study.ipynb` | The four gates, forward and one step |
