# **Plots, Flowcharts and Cognitive Load: Pretty and Ugly plots**

## **Project Summary**

This project focuses on creating a **Pretty Plot** and an **Ugly Plot** using the **Maricopa Covid19 dataset** to answer the following questions:

* How do the vaccination totals between age groups compare?
* How have the average vaccination totals changed over time in Maricopa County?

The dataset reports COVID vaccinations by **age group** and **postal code** in Maricopa County from **June 2021 to February 2022**.

---

## **1. Pretty Plot**

Constructed a publication-quality graphic that simultaneously shows:

* **Total vaccinations by age group** across the study period.
* **Average monthly vaccinations** over time in Maricopa County.
* Cleaned variable names for readability.
* Informative axis labels (e.g., “Age Group”, “Total Vaccinations”, “Average Monthly Vaccinations”).
* Consistent color mapping, appropriate shapes, and correct scales.
* Annotations and/or lines where needed to highlight trends.
* No artifacts such as underscores, code-style names, or stray punctuation.

---

## **2. Data Artifact Removal + Legibility**

The Pretty Plot ensures:

* No data artifacts (cleaned variable names, readable labels).
* Legible fonts for titles, axes, ticks, and legends.
* Informative captions that describe all data transformations and visual choices.
* Clean background with subtle gridlines and rotated x-tick labels to avoid overlap.
* High-resolution export (300 DPI) for publication quality.

---

## **3. Scale and Resolution**

* Figure size optimized for legibility (e.g., wide layout to accommodate age groups and time series).
* Titles and axis labels set to prominent, readable sizes.
* Tight layout applied to prevent label clipping.
* Plot saved at high resolution to maintain clarity for digital and print formats.

---

## **4. Pretty Plot Caption**

Caption explains:

* Data cleaning and aggregation steps (e.g., combining age-specific counts, grouping by month).
* How total and average vaccinations were calculated.
* The reasoning behind plot choices (bar plot for totals, line plot for averages).
* The connection between visualized trends and the scenario questions.

---

## **5. Ugly Plot**

Created the same general plot as the Pretty Plot but with intentional display errors, including:

* Too-small font for labels and title.
* Misleading or inconsistent axis scales.
* Distracting color palette.
* Wrong plot type for one of the metrics.
* Poorly formatted or confusing caption.

The Ugly Plot answers the same questions but highlights common pitfalls in data visualization.

---

## **6. Code and Reproducibility**

* All data manipulation, cleaning, and plotting steps are fully reproducible.
* .ipynb file includes Pretty Plot first, Ugly Plot second, and the accompanying Python code third.
