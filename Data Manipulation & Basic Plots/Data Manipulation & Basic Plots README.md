# **Introduction to data, data manipulation and basic plots**

Processed the Urban Park Rangers dataset to analyze changes over time in animal assistance requests. Filtered and reshaped relevant columns into an importable table, calculated trends, and exported outputs to separate sheets. Consolidated findings into a publication table with informative captions covering:

1. Trends in the number of animals sent to rehabilitators or care centres.
2. Changes in types of animals reported.
3. Evolution of the sources of information.

Constructed the publication table with a clear, well-formatted caption. The caption documented all filtering and data-manipulation steps applied. Tables displayed accurate data reflecting the required trends and met core data-display standards, including effective white space, dividers, and pre-attentive attributes. The importable table was formatted for clean CSV ingestion and contained the same summary statistics as the publication table.

-------

# Conclusion and Insights

**1) Trends in the number of animals sent to rehabilitators and animal care centres over time:**

| Year | Animals to ACC | Animals to Rehabilitators | Total Sent | Trend Note                                                |
| ---- | -------------- | ------------------------- | ---------- | --------------------------------------------------------- |
| 2018 | 332            | 42                        | 374        | Peak volume across all years observed                     |
| 2019 | 173            | 64                        | 237        | Sharp decline from 2018                                   |
| 2020 | 173            | 121                       | 294        | Partial rebound driven by increase in rehabilitator cases |
| 2021 | 98             | 55                        | 153        | Lowest total; continued downward trend                    |

| Summary       | Interpretation                                                                      |
| ------------- | ----------------------------------------------------------------------------------- |
| Overall Trend | Total animals sent for care declined from 2018–2021, with a temporary rise in 2020. |
| Notable Shift | Rehabilitator cases increased in 2020 despite overall decline.                      |


**2) changes in the types of animals reported over time.**

| Animal Type | 2018 Reports | 2019 Reports | 2020 Reports | 2021 Reports | Trend Note                                         |
| ----------- | ------------ | ------------ | ------------ | ------------ | -------------------------------------------------- |
| Native      | 642          | 530          | 456          | 350          | Largest category; consistent decline across years  |
| Domestic    | 94           | 108          | 128          | 71           | Rise until 2020, then sharp drop in 2021           |
| Invasive    | 27           | 35           | 43           | 31           | Steady increase until 2020, slight decline in 2021 |
| Exotic      | Low/Stable   | Low/Stable   | Low/Stable   | Low/Stable   | Minimal fluctuation; consistently low volume       |

| Summary       | Interpretation                                                                                  |
| ------------- | ----------------------------------------------------------------------------------------------- |
| Overall Shift | Declining native animal reports; domestic and invasive species rise until 2020 before dropping. |
| Stability     | Exotic species remain consistently low, indicating limited presence or reporting.               |


**3) Examined how call sources changed over time.**

| Call Source                         | 2018 | 2019 | 2020 | 2021 | Trend Note                                        |
| ----------------------------------- | ---- | ---- | ---- | ---- | ------------------------------------------------- |
| Central                             | 117  | 143  | 163  | 134  | Stable with a peak in 2020                        |
| Conservancies / “Friends of” Groups | 259  | 60   | 43   | 29   | Sharp, continuous decline across all years        |
| Employee                            | 182  | 205  | 281  | 147  | Strong rise until 2020, then notable drop         |
| Observed by Ranger                  | 12   | 28   | 61   | 36   | Upward trend until 2020, slight decline afterward |
| Other                               | 35   | 19   | 16   | 8    | Low and consistently declining                    |
| Public                              | 95   | 180  | 228  | 107  | Large rise until 2020, followed by a decrease     |

| Summary         | Interpretation                                                                                            |
| --------------- | --------------------------------------------------------------------------------------------------------- |
| Overall Change  | Public and employee reports peaked in 2020; conservancy-related calls declined sharply over all years.    |
| Ranger Activity | Ranger-observed cases increased until 2020, indicating growing field-based detection before a later drop. |
