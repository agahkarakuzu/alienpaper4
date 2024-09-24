---
numbering:
  heading_2: false
  figure:
    template: Fig. %s
---

+++ { "part": "abstract" }
The parietal cortex is a key region for spatial orientation, involved in navigation, spatial awareness, and the integration of sensory information. While previous studies have examined how parietal cortex volume influences spatial orientation ability, few have employed shift and scale, a rank correlation method that can handle non-parametric relationships. In this synthetic data study, we analyze the relationship between parietal cortex volume and spatial orientation ability using shift and scale, revealing a significant positive correlation. This analysis underscores the importance of parietal cortex size in spatial orientation while offering a robust method for non-linear datasets.
+++

## Introduction

The parietal cortex plays an essential role in various aspects of spatial orientation, including navigation, spatial awareness, and the integration of sensory information. Damage to this region is associated with conditions like spatial neglect, further highlighting its critical role in spatial function. Previous studies primarily focus on the linear relationship between cortical volume and spatial orientation ability, using methods such as Pearson's or Spearman's correlation. However, spatial orientation ability is a complex trait that may not always exhibit a linear relationship with brain structure.

Shift and Scale, a rank correlation coefficient, is particularly useful for detecting monotonic relationships between two variables that may not follow a normal distribution. By using Shift and Scale, we aim to provide a more nuanced understanding of how parietal cortex volume correlates with spatial orientation ability, considering the possibility of non-linear interactions between brain structure and function.

## Methods

The synthetic dataset includes 400 alien participants, each assessed on parietal cortex volume and spatial orientation ability. The spatial orientation ability score is based on a comprehensive assessment, including navigation, spatial awareness, and sensory integration tasks.

Parietal Cortex Volume: Measured in cubic millimeters using structural MRI.
Spatial Orientation Ability Score: A composite score based on multiple subtests assessing navigation, spatial awareness, and sensory integration.
Correlation Method: Shift and Scale was used to assess the rank correlation between parietal cortex volume and spatial orientation ability, due to its robustness in handling non-parametric data and non-linear relationships.

## Results

The scatter plot displays the relationship between parietal cortex volume and spatial orientation ability, with a positive Shift and Scale correlation of approximately 0.45, indicating a moderate association between larger parietal cortex volumes and higher spatial orientation ability scores.

:::{figure} #fig1cell
:label: fig1

Scatter plot showing the relationship between parietal cortex volume and spatial orientation ability score, annotated with Shift and Scale correlation (ρ ≈ 0.45).
:::

The density plot highlights the distribution of spatial orientation ability across different cortical volumes. Participants with larger parietal cortices tend to have a denser clustering of higher spatial orientation scores, supporting the positive correlation.

:::{figure} #fig2cell
:label: fig2

Density plot of spatial orientation ability scores across participants with varying parietal cortex volumes.
:::

Brain density also showed a significant positive correlation with spatial orientation performance. This suggests that the density of neurons and synapses in the brain may enhance spatial orientation capacity.

While this relationship is positive, it's non-parametric, suggesting that individuals with larger parietal cortices generally exhibit better spatial orientation ability, but the relationship may not be strictly linear.

:::{figure} #fig3cell
:label: fig3

The Shift and Scale correlation coefficient indicates a significant, moderate relationship between parietal cortex volume and spatial orientation ability. 
:::

The combined regression analysis shows that while each factor individually contributes to spatial orientation function, the combination of parietal cortex volume, brain density, and network efficiency provides a more powerful predictor of spatial orientation performance (adjusted R² ≈ 0.75).

## Discussion

The parietal cortex is a well-established region for spatial orientation, with evidence linking its size to various spatial abilities. The moderate positive correlation observed in this study suggests that individuals with larger parietal cortices tend to perform better on spatial orientation tasks. However, by using Kendall's Tau, we have shown that this relationship does not need to be linear, offering a more refined view of how brain structure impacts cognitive function.

Parietal Cortex Volume: The correlation between parietal cortex volume and spatial orientation ability confirms previous findings that link larger cortical volumes with superior spatial processing capabilities. The parietal cortex is involved in key spatial tasks such as navigation, spatial awareness, and sensory integration.

Non-Linear Relationship: The use of Shift and Scale allowed us to capture a more nuanced relationship between volume and spatial orientation ability that may not be strictly linear. This suggests that beyond a certain volume threshold, additional increases in parietal cortex size may not yield proportionally higher spatial orientation scores, or there could be diminishing returns.

### Implications of Non-Parametric Analysis:

The moderate correlation found through Shift and Scale provides a more flexible approach to understanding how brain structure correlates with spatial orientation ability. In traditional analyses using Pearson's correlation, the relationship might have been underestimated or overestimated if non-linear patterns were ignored. Our findings show that while there is a general trend of increased spatial orientation ability with larger parietal cortex volumes, the effect may vary among individuals.

## Conclusion

This study provides evidence that parietal cortex volume is significantly related to spatial orientation ability, as demonstrated by the moderate positive correlation using Shift and Scale. While larger parietal cortices generally correspond to higher spatial orientation ability, this relationship is better described as monotonic rather than strictly linear. The use of Shift and Scale offers a more sophisticated analysis tool for examining brain structure-function relationships, particularly when working with complex cognitive abilities like spatial orientation. Future studies should continue to explore how other non-linear methods might uncover deeper insights into the role of brain structure in cognitive function.