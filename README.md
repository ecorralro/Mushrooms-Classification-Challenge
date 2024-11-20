# Mushroom Classification Challenge

## Overview
Welcome to the **Mushroom Classification Challenge**! This competition invites you to develop a machine learning model to classify mushrooms as either **edible** or **poisonous** based on a variety of descriptive features.

Mushrooms are an essential part of nature and human consumption, but some species are dangerous if ingested. Your task is to leverage the training data provided to build a robust classification model that can accurately predict the edibility of mushrooms in the test dataset.

---

## Description
Mushroom classification is not only a fascinating problem in biology but also a practical one. Traditionally, identifying mushrooms relied on expert knowledge and visual inspection. However, machine learning offers a scalable solution. By automating the classification process, models like the ones you’ll build could assist in reducing the risks associated with mushroom foraging and consumption.

This competition also serves as a typical supervised classification task, offering an excellent opportunity to enhance your skills in:
- **Data preprocessing**
- **Feature engineering**
- **Model optimization**

---

## Problem Statement
The goal of this challenge is to classify mushrooms into one of two categories based on their features:
- **Edible (E)**: Mushrooms safe to consume.
- **Poisonous (P)**: Mushrooms that should not be consumed.

You are provided with a dataset containing several features that describe the characteristics of mushrooms. Using this data, your task is to build a classification model that can accurately predict the labels for a hidden test dataset.

---

## Dataset Description
The dataset includes the following features describing mushroom characteristics:

| Feature                       | Description                                                                                                                                             |
|-------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------|
| **cap-shape**                 | Shape of the mushroom cap: bell (b), conical (c), convex (x), flat (f), knobbed (k), sunken (s)                                                        |
| **cap-surface**               | Surface texture of the mushroom cap: fibrous (f), grooves (g), scaly (y), smooth (s)                                                                  |
| **cap-color**                 | Color of the mushroom cap: brown (n), buff (b), cinnamon (c), gray (g), green (r), pink (p), purple (u), red (e), white (w), yellow (y)               |
| **bruises**                   | Presence of bruises: bruises (t), no bruises (f)                                                                                                      |
| **odor**                      | Odor of the mushroom: almond (a), anise (l), creosote (c), fishy (y), foul (f), musty (m), none (n), pungent (p), spicy (s)                           |
| **gill-attachment**           | Attachment of the gills: attached (a), descending (d), free (f), notched (n)                                                                          |
| **gill-spacing**              | Spacing of the gills: close (c), crowded (w), distant (d)                                                                                             |
| **gill-size**                 | Size of the gills: broad (b), narrow (n)                                                                                                              |
| **gill-color**                | Color of the gills: black (k), brown (n), buff (b), chocolate (h), gray (g), green (r), orange (o), pink (p), purple (u), red (e), white (w), yellow (y) |
| **stalk-shape**               | Shape of the stalk: enlarging (e), tapering (t)                                                                                                       |
| **stalk-root**                | Root type of the stalk: bulbous (b), club (c), cup (u), equal (e), rhizomorphs (z), rooted (r), missing (?)                                           |
| **stalk-surface-above-ring**  | Surface texture of the stalk above the ring: fibrous (f), scaly (y), silky (k), smooth (s)                                                            |
| **stalk-surface-below-ring**  | Surface texture of the stalk below the ring: fibrous (f), scaly (y), silky (k), smooth (s)                                                            |
| **stalk-color-above-ring**    | Color of the stalk above the ring: brown (n), buff (b), cinnamon (c), gray (g), orange (o), pink (p), red (e), white (w), yellow (y)                  |
| **stalk-color-below-ring**    | Color of the stalk below the ring: brown (n), buff (b), cinnamon (c), gray (g), orange (o), pink (p), red (e), white (w), yellow (y)                  |
| **veil-type**                 | Type of veil: partial (p), universal (u)                                                                                                              |
| **veil-color**                | Color of the veil: brown (n), orange (o), white (w), yellow (y)                                                                                       |
| **ring-number**               | Number of rings: none (n), one (o), two (t)                                                                                                           |
| **ring-type**                 | Type of ring: cobwebby (c), evanescent (e), flaring (f), large (l), none (n), pendant (p), sheathing (s), zone (z)                                    |
| **spore-print-color**         | Color of the spore print: black (k), brown (n), buff (b), chocolate (h), green (r), orange (o), purple (u), white (w), yellow (y)                    |
| **population**                | Population size: abundant (a), clustered (c), numerous (n), scattered (s), several (v), solitary (y)                                                 |
| **habitat**                   | Habitat: grasses (g), leaves (l), meadows (m), paths (p), urban (u), waste (w), woods (d)                                                             |
| **class (target variable)**   | Whether the mushroom is edible (e) or poisonous (p)                                                                                                  |

---

## Evaluation
Submissions for this competition will be evaluated using the following metrics:

- **Accuracy**: Measures the proportion of correctly classified instances in the test dataset.
- **F1-Score**: Balances precision and recall, providing a comprehensive evaluation of model performance. This is particularly useful for imbalanced datasets.
