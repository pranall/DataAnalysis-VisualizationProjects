# Advanced Plots and Illusions: Pretty and Illusion Plots

## **Project Summary**

This project focuses on creating a **Pretty Plot** and an **Illusion Plot** using the **Slugs and Snails dataset** to answer the following questions:

* How do the number of slugs and snails found by biologists change over time in this dataset?
* How do the number of slug and snail species found by biologists change over time in this dataset?

Slugs and snails are highly temperature- and moisture-dependent organisms. They **hibernate in winter** (too cold) and **aestivate in summer** (too hot). Because of this, surveys are conducted only in **spring** and **fall**, and the evaluation is restricted to those two seasons.

---

## **1. Pretty Plot**

Constructed a publication-quality multi-panel graphic that simultaneously shows:

• **Total number of slugs and snails found across survey years** (e.g., line plot, area plot, or scatter+LOWESS).
• **Total number of species recorded across survey years** (e.g., separate panel or overlay with clear encoding).
• Cleaned variable names for readability.
• Informative axis labels (e.g., “Year”, “Total Individuals Found”, “Total Species Observed”).
• Consistent color scheme, meaningful shapes, appropriate transparency, and correct scales.
• Use of annotations when necessary to highlight seasonal patterns.
• No artifacts such as Python-style variable names, stray punctuation, truncated labels, or code-generated noise.

---

## **2. Illusion Plot**

Created the same general plot design as the Pretty Plot—same variables, same structure, same multi-panel layout—but added intentional distortions based on visualization illusions, such as:

• A truncated y-axis that exaggerates changes.
• A misleading color ramp (e.g., inverted or non-linear).
• An Ebbinghaus-like size illusion using bubble sizes that distort comparisons.
• Overlapping transparency that changes perceived density.
• Misaligned scales between panels that falsely suggest different trends.

The plot still answers the two required questions, but the distortions hinder proper interpretation.

---

## **3. Removal of Data Artifacts + Legibility + Resolution**

Both the Pretty Plot and Illusion Plot follow these quality standards:

• Clean, human-readable variable names.
• Fully informative axis labels and legend titles.
• No underscores, coding artifacts, or ambiguous tick labels.
• High resolution (300 DPI) for print quality.
• Adequate figure size for readability.
• Consistent, legible font sizes for titles, labels, ticks, legends.
• Tight layout to avoid clipping.

Only the illusion mechanism distinguishes the two plots; everything else remains publication-acceptable.

---

## **4. Pretty Plot Caption Requirements**

The Pretty Plot includes a caption that:

• Clearly explains the data being shown.
• States the time range of the surveys.
• Specifies that the dataset was cleaned (e.g., standardized season names, removed duplicates, formatted date fields).
• Describes the statistical or visual decisions (e.g., grouping by year, counting species per survey event).
• Connects the visualization directly to the two main scenario questions.
• States the logic behind choosing the plot type (e.g., line trends, species richness over time).

---

## **5. Discussion of the Illusions Used**

The Illusion Plot intentionally incorporates distortions discussed in class, such as:

• **Truncated Axis Illusion** – exaggerates changes and creates false steepness.
• **Color Illusion** – inverted or misleading color scale alters perceived magnitude.
• **Size-Based Perception Illusion (Ebbinghaus Effects)** – bubble sizes distort quantity comparisons.
• **Misaligned Panel Scales** – identical values appear different due to inconsistent axes.
• **Area vs. Length Illusion** – using area encodings creates non-linear perception of changes.
• **Overplotting Density Illusion** – excessive overlap changes interpretation of trend strength.

The caption explicitly highlights the illusion used so the reader understands how the visual cue distorts interpretation.
