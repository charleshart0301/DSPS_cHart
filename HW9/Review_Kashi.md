#Review of HW9 Visualizations — Charles Hart

1. Overview

This review evaluates the four plots included in Charles Hart’s HW9 submission:

Original feature-importance plot (from Higgs Boson HW)

Improved version of the feature-importance plot

“Bad” plot (coral phylogeny diagram)

“Good” plot (superconductor upper critical field curves)

Each visualization is analyzed according to the course evaluation framework:

*Ambiguity

*Distortion

*Distraction

*The 5 Tufte principles

*Color practices and accessibility

*Whether the improvement meaningfully enhanced the visualization

#2. Review of Original vs. Improved Coursework Plot


A) Original Plot:
![Initial Plot](https://github.com/charleshart0301/DSPS_cHart/blob/main/HW9/initialplot.png)

$Issues:$

$Ambiguity$

The y-axis labels overlapped heavily, making many feature names unreadable.

X-axis values were misplaced (15 → 14), causing confusion about scale and meaning.

$Distortion$

The x-axis range was inappropriate, leaving large unused space; this artificially minimized bar lengths (lie-factor distortion).

Visual impression of feature importance did not scale properly because the plot area compressed the bars.

$Distraction$

Extremely cluttered labels produced visual noise.

The plot area was dominated by empty whitespace, distracting from the data.

$Tufte’s Rules$

Effect size ≠ 1: bar lengths appeared smaller relative to the axis scaling.

Data-ink ratio was low: too much empty space and overlapping labels.

Chart junk present: unreadable text acted as noise.

Redundancy: none, but poor layout exacerbated ambiguity.

No small multiples needed — single-variable plot.

$Color Practices$

Blue bars were acceptable and accessible to color-blind users.

No legend issues.

B)Improved Plot (Feature Importance — Reworked Version):

![remade plot](https://github.com/charleshart0301/DSPS_cHart/blob/main/HW9/remadeplot.png)

$Positive Improvements:$

$Ambiguity Reduced$

Labels now readable, properly spaced, and aligned.

X-axis range corrected to match the actual values.

Clearer representation of the 0–0.5 feature importance interval.

$Distortion Removed$

Axis corrected → bar lengths now faithfully represent feature importances.

Plot dimensions properly allocated, giving honest proportionality.

$Distraction Minimized$

No overlapping labels.

Reduced whitespace → higher data/ink ratio and cleaner presentation.

$Tufte’s Principles Respected$

Effect size ≈ 1: bar lengths honestly reflect numerical values.

Higher data-ink ratio: more plot area dedicated to meaningful data.

No chart junk: labels are clear; no unnecessary elements.

No redundancy.

Appropriate color use: simple, effective.

$Color & Accessibility$

Single-color (blue) palette is safe for color-blind accessibility.

Contrast is sufficient for both bars and error lines.

$Conclusion$

This plot is significantly improved and now conveys feature importances accurately and cleanly with minimal ambiguity and distortion.
It satisfies Tufte’s principles much more effectively than the original.

#3. Evaluation of the “Bad” Plot (Coral Phylogeny Circle)

![coral plot](https://github.com/charleshart0301/DSPS_cHart/blob/main/HW9/coralplot.png)

$Ambiguity$

Extremely dense labeling makes many group names difficult to trace to branches.

Circular phylogeny layout makes hierarchical relationships harder to follow compared to a standard dendrogram.

$Distortion$

The radial time scale introduces geometric distortion: equal evolutionary distances do not appear visually equal.

Time expressed via radial distance (0 → 60 Myr segment) is not intuitive, creating perceptual distortion.

$Distraction$

Many overlapping colors and branch styles crowd the figure.

The circular layout introduces decorative complexity that competes with the data.

$Tufte’s Rules$

Effect size distorted due to radial layout.

Data-ink ratio moderate, but too much design ink (curved lines, colored segments).

Chart junk present due to unnecessary radial styling.

Redundancy: family labels repeated frequently.

Small multiples could have clarified subsets (e.g., separate clades).

$Color Practices$

Uses many hues; some low-contrast red–green combinations may not be color-blind safe.

Gradient scale is acceptable but small.

$Overall$

Not a terrible plot for expert users, but too dense and visually overloaded for general readability.

Removing the radial time axis or splitting into multiple panels would improve clarity.

4. Evaluation of the “Good” Plot (Superconductor Upper Field Limit)

![limit plot](https://github.com/charleshart0301/DSPS_cHart/blob/main/HW9/limitplot.png)

$Strengths$

$Ambiguity$

Axes clearly labeled (temperature, normalized upper critical field).

Legend clearly maps parameters (λ_f and λ_kF p).

Line curves are distinct and non-overlapping.

$Distortion$

Axes use uniform scales, and curves appear proportional — no misrepresentation.

No misleading grid or shape scaling.

$Distraction$

Minimal visual noise; no unnecessary markings.

Plot uses space efficiently and focuses attention on data.


$Tufte’s Rules Followed Well$

Effect size accurate: curves visually track true values.

High data-ink ratio: nearly all elements contribute meaningful information.

No chart junk.

No redundancy.

Color as small-multiple surrogate: each curve functions as a comparison category.

$Color & Accessibility$

Lines use distinct hues.

Some colors may approach color-blind pitfalls (orange–green), but overall contrast is good; line stylings could help further.

$Conclusion$

Excellent example of a clear, data-focused scientific plot that adheres well to best practices.

$5. Final Assessment$

Charles Hart’s HW9 shows clear understanding of visualization principles.

The coursework plot improvement is strong and meaningfully addresses ambiguity, distortion, and distraction.

The bad plot is correctly identified and critiqued with insightful reasoning about time dimension and overload.

The good plot is appropriately justified, with correct emphasis on space efficiency and color clarity.

Overall, the submission demonstrates thoughtful application of the criteria covered in the course and satisfies the expectations of HW9.
