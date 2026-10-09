# Seventeen paths

The tutorial is seventeen numbered folders, taken in order. Each notebook already stores the output of its code cells. Open a notebook in Jupyter and use Restart and Run All to recompute it.

```text
01-Jupyter Notebook/              16 lessons, standard library only
02-Python Fundamentals/           20 lessons, standard library only
03-Numpy Fundamentals/            16 lessons, needs NumPy
04-Pandas/                        18 lessons, needs pandas
05-Calculus with Python/          43 lessons, needs SymPy
06-Data Visualization/            16 lessons, needs Matplotlib
07-Linear Regression/             25 lessons, needs NumPy, SymPy, and SciPy
08-Polynomial Regression/         16 lessons, needs NumPy, SymPy, and SciPy
09-Support Vector Machines (SVM)/ 16 lessons, standard library only
10-Decision Trees/                16 lessons, needs Matplotlib
11-k-Nearest Neighbors (k-NN)/    16 lessons, needs Matplotlib
12-Perceptron/                     16 lessons, needs Matplotlib
13-Multilayer Perceptron (MLP)/   16 lessons, needs Matplotlib
14-Spaceship Titanic/             16 lessons, needs Matplotlib
15-House Prices/                  16 lessons, needs Matplotlib
16-Movie Recommendation/          16 lessons, needs Matplotlib
17-Customer Churn/                16 lessons, needs Matplotlib
README.md
requirements.txt
```

`01`, `02`, and `09` use only the Python standard library. `03`, `04`, `05`, `06`, `07`, `08`, `10`, `11`, `12`, `13`, `14`, `15`, `16`, and `17` need the packages in `requirements.txt`:

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

## 04. Pandas

Eighteen lessons on one reading desk. Monday is the morning note from path 01: Ada 4, Grace 6, Alan 3, Linus 5, summing to 18. The week of 5–9 October 2026 sums to 89 pages. Ada read 20, Grace 30, Alan 16, and Linus 23. Alan's Tuesday is the number 0. A blank Friday is a different object: the known total becomes 84, and filling that blank with 0 leaves Linus's sum at 18 while his day count changes from 4 to 5. Five notebook purchases bill 38. Edsger is on the roster and bought nothing. The label, not the position, is what each lesson adds, joins, and sorts.

| Notebook | Title |
|---|---|
| `04-Pandas/01-one-column.ipynb` | One column, with names |
| `04-Pandas/02-the-week.ipynb` | Five days, four people |
| `04-Pandas/03-build-the-table.ipynb` | Three ways to build the same table |
| `04-Pandas/04-loc-and-iloc.ipynb` | The label slice includes the end |
| `04-Pandas/05-which-rows.ipynb` | A mask is a column of yes and no |
| `04-Pandas/06-the-week-total.ipynb` | A new column is a sum you already know |
| `04-Pandas/07-a-blank-friday.ipynb` | A blank is not a zero |
| `04-Pandas/08-order.ipynb` | Order, and a tie |
| `04-Pandas/09-split-apply.ipynb` | Split, then add |
| `04-Pandas/10-count-sum-mean.ipynb` | Count, sum, and the largest day |
| `04-Pandas/11-prices.ipynb` | The bill is quantity times price |
| `04-Pandas/12-edsger.ipynb` | Edsger bought nothing |
| `04-Pandas/13-two-weeks.ipynb` | Two weeks, one stack |
| `04-Pandas/14-long-and-wide.ipynb` | Long, then wide again |
| `04-Pandas/15-the-file.ipynb` | The same week, from a file |
| `04-Pandas/16-names-and-dates.ipynb` | Names and the five dates |
| `04-Pandas/17-who-read-the-most.ipynb` | Who read the most |
| `04-Pandas/18-the-desk.ipynb` | The desk, end to end |

## 05. Calculus with Python

Forty-three lessons, from functions through differential equations. Each lesson teaches the idea by hand, then recomputes the same result in SymPy and checks that the two answers agree.

1. State the definition and the problem.
2. Solve it by hand, line by line, in display mathematics.
3. Recheck with Python. The hand answer and the SymPy answer are printed, and their difference must be zero.
4. Close with one pitfall and a short summary.

An indefinite integral is rechecked by differentiation, because SymPy omits the constant of integration.

### Calculus I

| Notebook | Title |
|---|---|
| `05-Calculus with Python/01-functions.ipynb` | Functions: domain, range, composition, inverse, piecewise |
| `05-Calculus with Python/02-exponential-log-trigonometric.ipynb` | Exponential, logarithmic, trigonometric, and inverse trigonometric functions |
| `05-Calculus with Python/03-rational-asymptotes.ipynb` | Rational functions and asymptotes |
| `05-Calculus with Python/04-limits.ipynb` | Limits and the limit laws |
| `05-Calculus with Python/05-continuity.ipynb` | Continuity, the squeeze theorem, and the intermediate value theorem |
| `05-Calculus with Python/06-infinite-limits.ipynb` | Infinite limits and limits at infinity |
| `05-Calculus with Python/07-derivative-rules.ipynb` | The derivative: definition, power, product, and quotient rules |
| `05-Calculus with Python/08-chain-special-derivatives.ipynb` | The chain rule and derivatives of special functions |
| `05-Calculus with Python/09-implicit-logarithmic.ipynb` | Implicit differentiation and logarithmic differentiation |
| `05-Calculus with Python/10-related-rates.ipynb` | Related rates |
| `05-Calculus with Python/11-linearization-mvt.ipynb` | Linearization, differentials, Rolle, and the mean value theorem |
| `05-Calculus with Python/12-lhopital.ipynb` | L'Hôpital's rule |
| `05-Calculus with Python/13-curve-sketching.ipynb` | Curve sketching |
| `05-Calculus with Python/14-optimization.ipynb` | Optimization |
| `05-Calculus with Python/15-newtons-method.ipynb` | Newton's method |

### Calculus II

| Notebook | Title |
|---|---|
| `05-Calculus with Python/16-substitution-parts.ipynb` | Substitution and integration by parts |
| `05-Calculus with Python/17-trig-partial-fractions.ipynb` | Trigonometric integrals, trigonometric substitution, and partial fractions |
| `05-Calculus with Python/18-improper-integrals.ipynb` | Improper integrals |
| `05-Calculus with Python/19-area-between-curves.ipynb` | Area between curves |
| `05-Calculus with Python/20-volumes.ipynb` | Volumes: disks, washers, and shells |
| `05-Calculus with Python/21-arc-length-surface.ipynb` | Arc length and surfaces of revolution |
| `05-Calculus with Python/22-average-value-work.ipynb` | Average value and work |
| `05-Calculus with Python/23-sequences.ipynb` | Sequences |
| `05-Calculus with Python/24-series-tests.ipynb` | Series and convergence tests |
| `05-Calculus with Python/25-taylor-series.ipynb` | Power series, Taylor series, and Maclaurin series |
| `05-Calculus with Python/26-parametric-curves.ipynb` | Parametric curves |
| `05-Calculus with Python/27-polar.ipynb` | Polar coordinates |

### Multivariable calculus

| Notebook | Title |
|---|---|
| `05-Calculus with Python/28-vectors.ipynb` | Vectors, lines, and planes |
| `05-Calculus with Python/29-vector-functions.ipynb` | Vector functions |
| `05-Calculus with Python/30-multivariable-functions.ipynb` | Functions of several variables and limits in the plane |
| `05-Calculus with Python/31-partial-derivatives.ipynb` | Partial derivatives, the chain rule, and Clairaut's theorem |
| `05-Calculus with Python/32-gradient-tangent-plane.ipynb` | The gradient, directional derivatives, and tangent planes |
| `05-Calculus with Python/33-extrema-lagrange.ipynb` | Extrema and Lagrange multipliers |
| `05-Calculus with Python/34-multiple-integrals.ipynb` | Double and triple integrals |
| `05-Calculus with Python/35-coordinates-jacobian.ipynb` | Cylindrical coordinates, spherical coordinates, and the Jacobian |
| `05-Calculus with Python/36-line-integrals-green.ipynb` | Line integrals and Green's theorem |
| `05-Calculus with Python/37-stokes-divergence.ipynb` | Stokes' theorem and the divergence theorem |

### Differential equations

| Notebook | Title |
|---|---|
| `05-Calculus with Python/38-first-order-odes.ipynb` | First-order differential equations |
| `05-Calculus with Python/39-second-order-linear.ipynb` | Second-order linear homogeneous equations |
| `05-Calculus with Python/40-undetermined-variation.ipynb` | Undetermined coefficients and variation of parameters |
| `05-Calculus with Python/41-laplace-ivp.ipynb` | The Laplace transform and initial-value problems |
| `05-Calculus with Python/42-heaviside-dirac-convolution.ipynb` | The Heaviside function, the Dirac delta, and convolution |
| `05-Calculus with Python/43-series-solutions-systems.ipynb` | Series solutions and linear systems |

## 06. Data Visualization

Sixteen lessons, from one question through lines, bars, distributions, heatmaps, and a one-week report. Every chart is drawn with Matplotlib, and the picture is stored in the notebook.

1. Ask one question.
2. Compute the number that answers it.
3. Encode that number as length, position, or color.
4. Title the finding and label the units.
5. Read the sentence back from the picture, and name one way it could be misread.

The running example is one week at North Lab. The same table becomes a ranking, a time line, and a heatmap. Each picture is allowed to answer only the question it was built for.

| Notebook | Title |
|---|---|
| `06-Data Visualization/01-one-question.ipynb` | One question, one chart |
| `06-Data Visualization/02-figure-and-axes.ipynb` | The page and the panel |
| `06-Data Visualization/03-lines.ipynb` | Change over time |
| `06-Data Visualization/04-scatter.ipynb` | Two measurements on one person |
| `06-Data Visualization/05-bars.ipynb` | Length means amount |
| `06-Data Visualization/06-histograms.ipynb` | How a pile of numbers spreads |
| `06-Data Visualization/07-boxplots.ipynb` | Five numbers, and the point that sits alone |
| `06-Data Visualization/08-small-multiples.ipynb` | Several panels, one question each |
| `06-Data Visualization/09-labels-and-color.ipynb` | Say what the marks mean |
| `06-Data Visualization/10-annotations.ipynb` | Mark the point that matters |
| `06-Data Visualization/11-heatmaps.ipynb` | A table you can see |
| `06-Data Visualization/12-cumulative-share.ipynb` | The running share |
| `06-Data Visualization/13-which-chart.ipynb` | Pick the chart from the question |
| `06-Data Visualization/14-scales.ipynb` | Scales that change the story |
| `06-Data Visualization/15-save-and-reuse.ipynb` | A function, then a file |
| `06-Data Visualization/16-full-study.ipynb` | North Lab, one week |

## 07. Linear Regression

Twenty-five lessons, from the prediction line through a complete numerical study. Every example is solved by hand in display mathematics. Python then repeats the arithmetic, and the two answers are required to agree.

1. State the definition and derive the result.
2. Work the numbers by hand, line by line.
3. Recheck with Python. The hand answer and the computed answer are printed, and they must match.
4. Close with one pitfall and a short summary.

When a loss is differentiated, the derivative is written out, and SymPy confirms that derivative. Inference uses SciPy's $t$ quantiles.

| Notebook | Title |
|---|---|
| `07-Linear Regression/01-prediction-line.ipynb` | The prediction line |
| `07-Linear Regression/02-residuals.ipynb` | Residuals and the sum of squares |
| `07-Linear Regression/03-least-squares-formulas.ipynb` | Deriving the slope and the intercept |
| `07-Linear Regression/04-complete-fit.ipynb` | A complete fit, with every sum written out |
| `07-Linear Regression/05-r-squared.ipynb` | The decomposition and $R^2$ |
| `07-Linear Regression/06-correlation.ipynb` | Correlation and the slope |
| `07-Linear Regression/07-through-the-origin.ipynb` | Regression through the origin |
| `07-Linear Regression/08-design-matrix.ipynb` | The design matrix |
| `07-Linear Regression/09-multiple-regression.ipynb` | Multiple regression |
| `07-Linear Regression/10-projection.ipynb` | Projection and the hat matrix |
| `07-Linear Regression/11-gauss-markov.ipynb` | The Gauss–Markov model |
| `07-Linear Regression/12-standard-errors.ipynb` | Estimating the error variance |
| `07-Linear Regression/13-inference.ipynb` | Tests and confidence intervals |
| `07-Linear Regression/14-prediction-intervals.ipynb` | Intervals for a mean response and for a new observation |
| `07-Linear Regression/15-indicator-variables.ipynb` | Indicator variables |
| `07-Linear Regression/16-polynomials.ipynb` | Polynomial regression |
| `07-Linear Regression/17-interactions.ipynb` | Interactions |
| `07-Linear Regression/18-centering.ipynb` | Centering |
| `07-Linear Regression/19-collinearity.ipynb` | Collinearity |
| `07-Linear Regression/20-influence.ipynb` | Leverage and Cook's distance |
| `07-Linear Regression/21-diagnostics.ipynb` | Residual patterns |
| `07-Linear Regression/22-gradient-descent.ipynb` | Gradient descent |
| `07-Linear Regression/23-ridge.ipynb` | Ridge regression |
| `07-Linear Regression/24-weighted-least-squares.ipynb` | Weighted least squares |
| `07-Linear Regression/25-full-study.ipynb` | A complete study |

## 08. Polynomial Regression

Sixteen lessons, from the meaning of a polynomial coefficient through interpolation, conditioning, lack of fit, and a complete study. The method matches the linear-regression path.

1. State the definition and derive the result.
2. Work the numbers by hand, line by line.
3. Recheck with Python. The hand answer and the computed answer are printed, and they must match.
4. Close with one pitfall and a short summary.

A polynomial regression is linear in its coefficients, so the normal equations are the same ones as in path `07`. The new material is the choice of degree, the shape of the basis, and what a perfect fit does and does not mean.

| Notebook | Title |
|---|---|
| `08-Polynomial Regression/01-polynomial-model.ipynb` | A polynomial is linear in its coefficients |
| `08-Polynomial Regression/02-vandermonde.ipynb` | The Vandermonde matrix |
| `08-Polynomial Regression/03-quadratic-fit.ipynb` | Fitting a quadratic by hand |
| `08-Polynomial Regression/04-the-line.ipynb` | The straight line on the same curve |
| `08-Polynomial Regression/05-r-squared.ipynb` | $R^2$ for a polynomial |
| `08-Polynomial Regression/06-extra-sum-of-squares.ipynb` | The extra sum of squares |
| `08-Polynomial Regression/07-cubic.ipynb` | The cubic hidden in the residuals |
| `08-Polynomial Regression/08-shifting-origin.ipynb` | Shifting the origin |
| `08-Polynomial Regression/09-orthogonal-ridge.ipynb` | Orthogonal polynomials, then ridge |
| `08-Polynomial Regression/10-inference.ipynb` | Standard errors and tests |
| `08-Polynomial Regression/11-prediction.ipynb` | Prediction from a polynomial |
| `08-Polynomial Regression/12-interpolation.ipynb` | Interpolation and the Runge warning |
| `08-Polynomial Regression/13-conditioning.ipynb` | The condition of the monomial basis |
| `08-Polynomial Regression/14-lack-of-fit.ipynb` | Lack of fit and pure error |
| `08-Polynomial Regression/15-two-variables.ipynb` | A polynomial in two inputs |
| `08-Polynomial Regression/16-full-study.ipynb` | A complete study |

## 09. Support Vector Machines

Sixteen lessons, from a signed score to kernels and a single training step. The prose stays close to the arithmetic. Each example is proved before it is coded.

1. State the rule or the optimization problem in display mathematics.
2. Solve a small numerical case by hand, including the constraints.
3. Recheck with Python. The hand answer and the computed answer must match.
4. Close with one pitfall and the sentence worth keeping.

The hard-margin street, the hinge, and the kernels are calculated directly. No solver library is required. A multiplier is trusted only after it rebuilds $\mathbf{w}$ and satisfies complementary slackness.

| Notebook | Title |
|---|---|
| `09-Support Vector Machines (SVM)/01-signed-scores.ipynb` | A score, then a sign |
| `09-Support Vector Machines (SVM)/02-distance-and-margin.ipynb` | How far is a point from the line? |
| `09-Support Vector Machines (SVM)/03-widest-street.ipynb` | The widest empty street |
| `09-Support Vector Machines (SVM)/04-three-point-fit.ipynb` | Three points, solved by hand |
| `09-Support Vector Machines (SVM)/05-support-vectors.ipynb` | Support vectors are the points that hold the street |
| `09-Support Vector Machines (SVM)/06-lagrange-kkt.ipynb` | Lagrange multipliers and the KKT conditions |
| `09-Support Vector Machines (SVM)/07-the-dual.ipynb` | The dual problem |
| `09-Support Vector Machines (SVM)/08-recover-weights.ipynb` | From multipliers back to a prediction |
| `09-Support Vector Machines (SVM)/09-hinge-and-slack.ipynb` | Pay for a point inside the street |
| `09-Support Vector Machines (SVM)/10-soft-margin-line.ipynb` | Four points on a line |
| `09-Support Vector Machines (SVM)/11-feature-maps.ipynb` | A line in a bigger space |
| `09-Support Vector Machines (SVM)/12-xor-and-kernels.ipynb` | XOR, separated by a product |
| `09-Support Vector Machines (SVM)/13-rbf-kernel.ipynb` | A kernel from distance |
| `09-Support Vector Machines (SVM)/14-one-versus-rest.ipynb` | More than two labels |
| `09-Support Vector Machines (SVM)/15-pegasos-step.ipynb` | One training step |
| `09-Support Vector Machines (SVM)/16-full-study.ipynb` | Full study: from a score to a kernel |

## 10. Decision Trees

Sixteen lessons, from walking a finished tree through Gini, entropy, regression leaves, pruning, and rectangles. Every split is calculated by hand before Python repeats it. Matplotlib draws the regions; no tree library is required.

1. State the definition and prove the small result.
2. Work one table by hand, including the fractions.
3. Recheck with Python. The hand answer and the computed answer must match.
4. Close with one pitfall and the sentence worth keeping.

The running table is eight inspected parts. A part passes only when its length is at most $7/2$ and its weight is at most $3$. Ties in gain are broken in writing, because a silent tie can swap the feature ranking.

| Notebook | Title |
|---|---|
| `10-Decision Trees/01-walk-a-tree.ipynb` | A tree is a list of questions |
| `10-Decision Trees/02-majority-leaf.ipynb` | The leaf should name the majority |
| `10-Decision Trees/03-gini.ipynb` | Gini impurity |
| `10-Decision Trees/04-entropy.ipynb` | Entropy |
| `10-Decision Trees/05-information-gain.ipynb` | The gain of a question |
| `10-Decision Trees/06-thresholds.ipynb` | Why the midpoint is enough |
| `10-Decision Trees/07-grow-the-tree.ipynb` | Grow until the leaves are pure |
| `10-Decision Trees/08-regression-mean.ipynb` | A leaf that predicts a number |
| `10-Decision Trees/09-regression-split.ipynb` | Where to cut a regression leaf |
| `10-Decision Trees/10-depth.ipynb` | A deep tree can memorize one point |
| `10-Decision Trees/11-pruning.ipynb` | Pay for every extra leaf |
| `10-Decision Trees/12-feature-credit.ipynb` | How much impurity a feature removed |
| `10-Decision Trees/13-rectangles.ipynb` | The cuts are rectangles |
| `10-Decision Trees/14-named-features.ipynb` | A question with names, not numbers |
| `10-Decision Trees/15-grow-and-predict.ipynb` | The same rules, written as functions |
| `10-Decision Trees/16-full-study.ipynb` | Full study: eight parts, one odd point, one price |

## 11. k-Nearest Neighbors

Sixteen lessons, from a stored table through distance, votes, weights, scaling, and leave-one-out. Every neighbor is ranked by hand before Python repeats the sort. Matplotlib draws the boundary; no neighbor library is required.

1. State the rule and prove the small result.
2. Work today's query on the same six mornings.
3. Recheck with Python. The hand answer and the computed answer must match.
4. Close with one pitfall and the sentence worth keeping.

The memory is three busy mornings and three quiet ones, so a global majority cannot answer. Today is $(2, 2)$. One neighbor says busy, five unweighted neighbors say quiet, and the same five with weights $1/d$ say busy again.

| Notebook | Title |
|---|---|
| `11-k-Nearest Neighbors (k-NN)/01-stored-cases.ipynb` | Look at the stored mornings |
| `11-k-Nearest Neighbors (k-NN)/02-euclidean-distance.ipynb` | Straight-line distance |
| `11-k-Nearest Neighbors (k-NN)/03-one-neighbor.ipynb` | One neighbor |
| `11-k-Nearest Neighbors (k-NN)/04-the-vote.ipynb` | Let several neighbors vote |
| `11-k-Nearest Neighbors (k-NN)/05-weighted-votes.ipynb` | A nearer morning gets a heavier vote |
| `11-k-Nearest Neighbors (k-NN)/06-scaling.ipynb` | A large unit can hide the neighbor |
| `11-k-Nearest Neighbors (k-NN)/07-scale-from-training.ipynb` | The query does not help compute the scale |
| `11-k-Nearest Neighbors (k-NN)/08-manhattan.ipynb` | Another way to add the gaps |
| `11-k-Nearest Neighbors (k-NN)/09-regression.ipynb` | Neighbors can average a number |
| `11-k-Nearest Neighbors (k-NN)/10-distance-ties.ipynb` | Two mornings at the same distance |
| `11-k-Nearest Neighbors (k-NN)/11-the-boundary.ipynb` | The boundary is the set of ties |
| `11-k-Nearest Neighbors (k-NN)/12-many-dimensions.ipynb` | In many dimensions the gap shrinks |
| `11-k-Nearest Neighbors (k-NN)/13-leave-one-out.ipynb` | Score $k$ by hiding one stored row |
| `11-k-Nearest Neighbors (k-NN)/14-the-procedure.ipynb` | One procedure, every answer we already know |
| `11-k-Nearest Neighbors (k-NN)/15-zero-distance.ipynb` | Distance zero is a stored copy |
| `11-k-Nearest Neighbors (k-NN)/16-full-study.ipynb` | Today, worked from the table |

## 12. Perceptron

Sixteen lessons, from reading a score to the update rule, the convergence bound, and a pocket for a paper no line can fit. Every update is written by hand before Python repeats it. Matplotlib draws the lines; no perceptron library is required.

1. State the rule and prove the small result.
2. Work the same points by hand, including the fractions.
3. Recheck with Python. The hand answer and the computed answer must match.
4. Close with one pitfall and the sentence worth keeping.

Pass is $+1$ and fail is $-1$. A point is correct only when its margin is positive. On one measurement the walk uses $5$ updates and the bound promises at most $10$. In the plane, three papers reach $2x_1 + x_2 - 1$ in three updates, a second order reaches a different line, and neither line is the widest.

| Notebook | Title |
|---|---|
| `12-Perceptron/01-read-a-score.ipynb` | Read a score |
| `12-Perceptron/02-one-update.ipynb` | One update |
| `12-Perceptron/03-why-a-bias.ipynb` | Why a bias is there |
| `12-Perceptron/04-five-updates.ipynb` | Five updates on a line |
| `12-Perceptron/05-two-scores.ipynb` | Two scores, one line |
| `12-Perceptron/06-the-first-update.ipynb` | The first update in the plane |
| `12-Perceptron/07-three-updates.ipynb` | Three updates reach a line |
| `12-Perceptron/08-the-margin-grows.ipynb` | The margin grows by a square |
| `12-Perceptron/09-why-it-stops.ipynb` | Why the updates stop |
| `12-Perceptron/10-step-size.ipynb` | The step size |
| `12-Perceptron/11-the-other-order.ipynb` | The other order |
| `12-Perceptron/12-not-the-widest.ipynb` | Not the widest line |
| `12-Perceptron/13-xor.ipynb` | Four gates with no line |
| `12-Perceptron/14-the-loss.ipynb` | The loss can rise |
| `12-Perceptron/15-the-pocket.ipynb` | Keep the best weights seen |
| `12-Perceptron/16-full-study.ipynb` | One line, from zero |

## 13. Multilayer Perceptron

Sixteen lessons, from a layer of scores through a bend, XOR, the chain rule, and one gradient step. Every derivative is computed by hand before Python repeats it. Matplotlib draws the bend and the two step sizes; no network library is required.

1. State the rule and prove the small result.
2. Work the same gates by hand, including the fractions.
3. Recheck with Python. The hand answer and the computed answer must match.
4. Close with one pitfall and the sentence worth keeping.

The four gates are XOR. Two straight layers still score gate 00 as $2$. One ReLU fold, $h_1 - 2h_2$, scores them $0, 1, 1, 0$. A step of size $1/8$ on a perturbed output moves the loss from $1/2$ to $23/128$. A step of size $1/4$ moves it to $23/32$.

| Notebook | Title |
|---|---|
| `13-Multilayer Perceptron (MLP)/01-a-layer.ipynb` | A layer is several scores |
| `13-Multilayer Perceptron (MLP)/02-two-layers-one-line.ipynb` | Two straight layers are still one line |
| `13-Multilayer Perceptron (MLP)/03-relu.ipynb` | ReLU bends one coordinate |
| `13-Multilayer Perceptron (MLP)/04-xor-forward.ipynb` | The hidden pair is the whole table |
| `13-Multilayer Perceptron (MLP)/05-the-bend.ipynb` | Where the bend sits |
| `13-Multilayer Perceptron (MLP)/06-one-hidden-unit.ipynb` | One hidden unit cannot build XOR |
| `13-Multilayer Perceptron (MLP)/07-sigmoid.ipynb` | A smooth bend |
| `13-Multilayer Perceptron (MLP)/08-squared-loss.ipynb` | The squared loss |
| `13-Multilayer Perceptron (MLP)/09-the-chain-rule.ipynb` | The chain rule, one unit deep |
| `13-Multilayer Perceptron (MLP)/10-a-dead-unit.ipynb` | A dead unit blocks the input weights |
| `13-Multilayer Perceptron (MLP)/11-two-hidden-units.ipynb` | Back through two hidden units |
| `13-Multilayer Perceptron (MLP)/12-the-step-size.ipynb` | The step size decides the total |
| `13-Multilayer Perceptron (MLP)/13-the-bias-gradient.ipynb` | The bias is a weight on the constant 1 |
| `13-Multilayer Perceptron (MLP)/14-identical-units.ipynb` | Identical units stay identical |
| `13-Multilayer Perceptron (MLP)/15-a-probability.ipynb` | A score can be read as a probability |
| `13-Multilayer Perceptron (MLP)/16-full-study.ipynb` | The four gates, forward and one step |

## 14. Spaceship Titanic

Sixteen lessons on one manifest. The question is which passengers were transported to another dimension. `data/train.csv` has 8693 known fates, 4378 of them transported. `data/test.csv` has 4277 passengers and no fate. CryoSleep alone is right on 6244 of 8693. The audited decision list is right on 6503 of 8693, and on 1331 of 1772 passengers whose whole group was held out. A groupmate's fate is a poor copy: 797 multi-person groups disagree. The test fates stay unknown, so this path does not claim a leaderboard score.

| Notebook | Title |
|---|---|
| `14-Spaceship Titanic/01-the-question.ipynb` | The question on the manifest |
| `14-Spaceship Titanic/02-the-columns.ipynb` | What each column records |
| `14-Spaceship Titanic/03-six-passengers.ipynb` | Six passengers, before any rate |
| `14-Spaceship Titanic/04-the-base-rate.ipynb` | The fate is almost a coin toss |
| `14-Spaceship Titanic/05-blank-cells.ipynb` | Where the manifest is blank |
| `14-Spaceship Titanic/06-cryosleep.ipynb` | CryoSleep is the strongest single column |
| `14-Spaceship Titanic/07-deck-and-planet.ipynb` | Deck, side, and home planet |
| `14-Spaceship Titanic/08-the-five-bills.ipynb` | The five bills point in two directions |
| `14-Spaceship Titanic/09-age-vip-destination.ipynb` | Age, VIP, and destination |
| `14-Spaceship Titanic/10-groups-and-names.ipynb` | Groups and surnames |
| `14-Spaceship Titanic/11-the-decision-list.ipynb` | A decision list you can walk by hand |
| `14-Spaceship Titanic/12-the-ledger.ipynb` | Where the 259 come from |
| `14-Spaceship Titanic/13-held-out-groups.ipynb` | Score whole groups |
| `14-Spaceship Titanic/14-odds.ipynb` | One column is a majority vote |
| `14-Spaceship Titanic/15-after-the-list.ipynb` | What the published solutions add |
| `14-Spaceship Titanic/16-full-study.ipynb` | The manifest, end to end |

## 15. House Prices

Sixteen lessons on the Ames sale prices. The question is to predict `SalePrice`. `data/train.csv` has 1460 known prices, summing to 264144946, so the mean is $132072473/730$ and the median is 163000. `data/test.csv` has 1459 houses and no price. A grade-median table, fit without the houses it scores, has holdout root mean squared log error about 0.224. A log line on overall quality and living area, fit the same way, has holdout error about 0.183. The test prices stay unknown, so this path does not claim a leaderboard score.

| Notebook | Title |
|---|---|
| `15-House Prices/01-the-question.ipynb` | The price, and the error that scores it |
| `15-House Prices/02-the-columns.ipynb` | Eighty columns, one codebook |
| `15-House Prices/03-one-house.ipynb` | House 1, before any average |
| `15-House Prices/04-the-token-na.ipynb` | When `NA` means none, and when it means unknown |
| `15-House Prices/05-the-price.ipynb` | The 1460 prices |
| `15-House Prices/06-overall-quality.ipynb` | OverallQual, the grade from 1 to 10 |
| `15-House Prices/07-living-area.ipynb` | A straight line through living area |
| `15-House Prices/08-neighborhood.ipynb` | Twenty-five neighborhoods |
| `15-House Prices/09-basement-and-garage.ipynb` | Basement, garage, and a code that only looks numeric |
| `15-House Prices/10-quality-words.ipynb` | The words Excellent, Good, Typical, Fair, Poor |
| `15-House Prices/11-year-and-sale.ipynb` | When it was built, and how it was sold |
| `15-House Prices/12-four-large-houses.ipynb` | Four houses above 4000 square feet |
| `15-House Prices/13-a-grade-table.ipynb` | A table you fit without the houses you score |
| `15-House Prices/14-the-log-line.ipynb` | A line on the log price |
| `15-House Prices/15-after-the-line.ipynb` | What the published solutions add |
| `15-House Prices/16-full-study.ipynb` | The sale, end to end |

## 16. Movie Recommendation

Sixteen lessons on MovieLens 100K. The question is to predict the star a person would give a movie. `data/` has 100000 ratings from 943 people on 1682 movies. The stars sum to 352986, so the mean is $176493/50000$. An empty cell is not a zero. The bias formula $\bar r_u + \bar r_i - \mu$, fit on `ua.base` and scored on `ua.test`, has root mean squared error about 0.992. Neighbor and factorization models are explained on a worked example; the audited number is that bias error. The tables are the GroupLens MovieLens 100K release; cite Harper and Konstan, ACM TiiS 2015, and read `data/README` for the use conditions.

| Notebook | Title |
|---|---|
| `16-Movie Recommendation/01-the-question.ipynb` | Predict the star a person would give |
| `16-Movie Recommendation/02-the-files.ipynb` | Five tables, and two kinds of separator |
| `16-Movie Recommendation/03-one-rating.ipynb` | One row, then one person |
| `16-Movie Recommendation/04-five-stars.ipynb` | The five stars, and their mean |
| `16-Movie Recommendation/05-the-empty-matrix.ipynb` | Almost every pair is missing |
| `16-Movie Recommendation/06-user-and-movie-means.ipynb` | A person has a level, and so does a movie |
| `16-Movie Recommendation/07-the-bias-formula.ipynb` | Add the person and the movie, then subtract the global mean |
| `16-Movie Recommendation/08-score-the-holdout.ipynb` | Fit on `ua.base`, score on `ua.test` |
| `16-Movie Recommendation/09-similarity.ipynb` | When two people move together |
| `16-Movie Recommendation/10-angels-and-insects.ipynb` | User 1, movie 20, held out on purpose |
| `16-Movie Recommendation/11-genres.ipynb` | Genres describe the movie, not the person |
| `16-Movie Recommendation/12-the-people.ipynb` | Age, gender, occupation, zip |
| `16-Movie Recommendation/13-the-splits.ipynb` | The splits that are already in the folder |
| `16-Movie Recommendation/14-neighbors-and-factors.ipynb` | What a neighbor model adds, and what a factorization adds |
| `16-Movie Recommendation/15-what-we-keep.ipynb` | What the counts refuse |
| `16-Movie Recommendation/16-full-study.ipynb` | The rating, end to end |

## 17. Customer Churn

Sixteen lessons on the IBM telco customer churn sample. The question is whether `Churn` is `Yes`. `data/Telco-Customer-Churn.csv` has 7043 customers, and 1869 leave, so the leave rate is $1869/7043$. Predicting stay scores $5174/7043$ and flags none of the leavers. The sentence chosen on the 5626 fit customers is month-to-month, and fiber optic or an electronic check. On the other 1417 customers its $F_1$ is $488/861$. That sentence's holdout accuracy is $1044/1417$, and predicting stay scores $1052/1417$ on the same people. The source note is `data/SOURCE.txt`, and the Apache License 2.0 text is `data/LICENSE`. These lessons are not an IBM product.

| Notebook | Title |
|---|---|
| `17-Customer Churn/01-the-question.ipynb` | Will this customer leave? |
| `17-Customer Churn/02-the-file.ipynb` | Twenty-one columns, one label |
| `17-Customer Churn/03-one-customer.ipynb` | Customer 7590-VHVEG |
| `17-Customer Churn/04-who-leaves.ipynb` | 1869 leavers out of 7043 |
| `17-Customer Churn/05-the-contract.ipynb` | Month-to-month carries most of the leavers |
| `17-Customer Churn/06-tenure.ipynb` | Longer stays leave less often |
| `17-Customer Churn/07-the-bill.ipynb` | A space in the total, and a bill that moved |
| `17-Customer Churn/08-internet-and-the-check.ipynb` | Fiber optic and the electronic check |
| `17-Customer Churn/09-a-rule-you-can-say.ipynb` | A rule you can say out loud |
| `17-Customer Churn/10-precision-and-recall.ipynb` | Precision, recall, and a tie on accuracy |
| `17-Customer Churn/11-the-holdout.ipynb` | Fit on 5626, score on 1417 |
| `17-Customer Churn/12-log-odds.ipynb` | Log-odds, and a cut at one half |
| `17-Customer Churn/13-four-customers.ipynb` | Four held-out customers |
| `17-Customer Churn/14-what-the-counts-refuse.ipynb` | What the counts refuse |
| `17-Customer Churn/15-after-the-rule.ipynb` | What a fitted model adds |
| `17-Customer Churn/16-full-study.ipynb` | The customer, end to end |
