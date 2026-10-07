# حسابان با پایتون

چهل و سه درس، از تابع تا معادلهٔ دیفرانسیل. هر درس اول مطلب را با حل دستی می‌گوید، بعد همان جواب را با SymPy دوباره حساب می‌کند و برابری را بررسی می‌کند. خروجی هر خانه از پیش ذخیره شده است.

## روش هر درس

۱. تعریف و صورت مسئله.
۲. حل ریاضی، خط به خط.
۳. بازبینی با پایتون: جواب دستی و جواب SymPy چاپ می‌شوند و اختلافشان باید صفر باشد.
۴. یک نکته، و جمع‌بندی کوتاه.

اگر انتگرال نامعین باشد، بازبینی با مشتق‌گیری است، چون ثابت انتگرال در SymPy نوشته نمی‌شود.

## اجرا

پایتون ۳ و SymPy کافی است.

```powershell
py -m pip install -r requirements.txt
```

دفترچه‌ها را با Jupyter باز کنید. برای حساب دوباره، Restart و Run All.

## مسیر دوره

### ریاضی عمومی ۱

| دفترچه | عنوان |
|---|---|
| `01-functions.ipynb` | تابع: دامنه، برد، ترکیب، وارون، چندضابطه‌ای |
| `02-exponential-log-trigonometric.ipynb` | نمایی، لگاریتم، مثلثاتی و وارون مثلثاتی |
| `03-rational-asymptotes.ipynb` | تابع گویا و مجانب |
| `04-limits.ipynb` | حد و قانون‌های حد |
| `05-continuity.ipynb` | پیوستگی، فشردگی، مقدار میانی |
| `06-infinite-limits.ipynb` | حد نامتناهی و حد در بی‌نهایت |
| `07-derivative-rules.ipynb` | مشتق: تعریف، توان، ضرب، خارج‌قسمت |
| `08-chain-special-derivatives.ipynb` | قاعدهٔ زنجیره‌ای و مشتق تابع‌های خاص |
| `09-implicit-logarithmic.ipynb` | مشتق ضمنی و مشتق لگاریتمی |
| `10-related-rates.ipynb` | آهنگ‌های مرتبط |
| `11-linearization-mvt.ipynb` | خطی‌سازی، دیفرانسیل، رول و مقدار میانگین |
| `12-lhopital.ipynb` | قاعدهٔ هوپیتال |
| `13-curve-sketching.ipynb` | رسم نمودار |
| `14-optimization.ipynb` | بهینه‌سازی |
| `15-newtons-method.ipynb` | روش نیوتن |

### ریاضی عمومی ۲

| دفترچه | عنوان |
|---|---|
| `16-substitution-parts.ipynb` | جانشینی و جزءبه‌جزء |
| `17-trig-partial-fractions.ipynb` | انتگرال مثلثاتی، جانشینی مثلثاتی، کسرهای جزئی |
| `18-improper-integrals.ipynb` | انتگرال ناسره |
| `19-area-between-curves.ipynb` | مساحت بین دو خم |
| `20-volumes.ipynb` | حجم: قرص، واشر، پوسته |
| `21-arc-length-surface.ipynb` | طول قوس و سطح دوار |
| `22-average-value-work.ipynb` | مقدار میانگین و کار |
| `23-sequences.ipynb` | دنباله |
| `24-series-tests.ipynb` | سری و آزمون‌های همگرایی |
| `25-taylor-series.ipynb` | سری توانی، تیلور و مکلورن |
| `26-parametric-curves.ipynb` | خم پارامتری |
| `27-polar.ipynb` | مختصات قطبی |

### حسابان چندمتغیره

| دفترچه | عنوان |
|---|---|
| `28-vectors.ipynb` | بردار، خط و صفحه |
| `29-vector-functions.ipynb` | تابع برداری |
| `30-multivariable-functions.ipynb` | تابع چندمتغیره و حد در صفحه |
| `31-partial-derivatives.ipynb` | مشتق جزئی، زنجیره و کلرو |
| `32-gradient-tangent-plane.ipynb` | گرادیان، مشتق سویی و صفحهٔ مماس |
| `33-extrema-lagrange.ipynb` | اکسترمم و ضرایب لاگرانژ |
| `34-multiple-integrals.ipynb` | انتگرال دوگانه و سه‌گانه |
| `35-coordinates-jacobian.ipynb` | استوانه‌ای، کروی و ژاکوبی |
| `36-line-integrals-green.ipynb` | انتگرال خطی و قضیهٔ گرین |
| `37-stokes-divergence.ipynb` | استوکس و دیورژانس |

### معادلات دیفرانسیل

| دفترچه | عنوان |
|---|---|
| `38-first-order-odes.ipynb` | معادلهٔ دیفرانسیل مرتبهٔ اول |
| `39-second-order-linear.ipynb` | معادلهٔ خطی مرتبهٔ دوم همگن |
| `40-undetermined-variation.ipynb` | ضرایب نامعین و تغییر پارامتر |
| `41-laplace-ivp.ipynb` | لاپلاس و مسئلهٔ مقدار اولیه |
| `42-heaviside-dirac-convolution.ipynb` | پله، ضربه و پیچش |
| `43-series-solutions-systems.ipynb` | حل سری و دستگاه خطی |
