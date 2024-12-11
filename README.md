# Breast Cancer Analysis

**Source**: <https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data>

This dataset contains information about breast cancers in 1995 in Wisconsin, USA.

**Columns**:

-   **id**: ID number of the patient;

-   **diagnosis**: the diagnosis of breast tissues (M = malignant, B = benign);

-   **radius**: distances from center to points on the perimeter;

-   **smoothness**: of local variation in radius lengths;

-   **texture:** standard deviation of gray-scale values;

-   **area**;

-   **compactness**: (perimeter\^2 / area - 1.0)

-   **concavity**(severity of concave portions of the contour)

-   **concave points** (number of concave portions of the contour)

-   **symmetry**

-   **fractal dimension** ("coastline approximation" - 1)

The dataset consists of 32 columns, which essentially represent 11 core variables. Nine of these variables are further characterized by their mean, standard deviation, and worst values, offering a detailed perspective on tumor characteristics.

**Goal**: develop and evaluate predictive models that can accurately classify whether a tumor is malignant or benign based on various features.
