
# User Profiling and Segmentation using K-Means (5 Clusters)
## Overview

This project performs user segmentation based on demographics, engagement, and behavioral metrics to enhance digital marketing strategies.
By applying K-Means clustering (k = 5), we uncover five distinct user profiles that reflect different levels of online activity, attention span, and ad interaction effectiveness.

## Methodology

Algorithm: K-Means Clustering (k=5)

## Data Preprocessing:

Label Encoding for categorical variables

Standard Scaling of all features numerical features


## Visual Analysis

The chart (CLUSTER ANALYSIS.png) compares all 5 clusters across six critical behavioral metrics:

Likes & Reactions

Online Activity (Weekdays and Weekends)

Click-Through Rate (CTR)

Conversion Rate

Ad Interaction Time

## Cluster Analysis and Interpretation
### Cluster 0 – “Highly Engaged Social Enthusiasts”

- Likes & Reactions: Very high (≈ 6900)

- Weekday Activity: High (~3.5 hrs)

- Weekend Activity: Also high (~6 hrs)

- CTR: Moderate (~0.13)

- Conversion Rate: Highest among all (~0.075)

- Ad Interaction Time: Longest (~110 sec)
### Interpretation:
These users are socially active and consistent across weekdays and weekends. Their strong engagement and high conversion rates indicate trust and interest in online ads.
Ad Strategy: Use interactive visual content, influencer marketing, and loyalty campaigns.

### Cluster 1 – “Balanced Explorers”

- Likes & Reactions: High (~6200)

- Weekday Activity: Low (~1.6 hrs)

- Weekend Activity: Moderate (~4.8 hrs)

- CTR: Slightly below average (~0.11)

- Conversion Rate: High (~0.07)

- Ad Interaction Time: Moderate (~85 sec)
### Interpretation:
Users with limited weekday time but strong weekend engagement. They browse more selectively, leading to strong conversion efficiency.
Ad Strategy: Launch weekend deals, limited-time offers, and event-based ads.

### Cluster 2 – “Curious Deep Divers”

- Likes & Reactions: Moderate (~5700)

- Weekday Activity: Medium (~3.2 hrs)

- Weekend Activity: Low (~2.6 hrs)

- CTR: Highest (~0.185)

- Conversion Rate: Moderate (~0.05)

- Ad Interaction Time: Shorter (~80 sec)
### Interpretation:
They click more but convert less frequently — suggesting curiosity or information-seeking behavior.
Ad Strategy: Use educational ads, tutorials, and explainer content to sustain their attention and guide them toward conversion.

### Cluster 3 – “Passive Weekend Viewers”

- Likes & Reactions: Low (~2700)

- Weekday Activity: Low (~2.5 hrs)

- Weekend Activity: Average (~3.7 hrs)

- CTR: Lowest (~0.07)

- Conversion Rate: Moderate (~0.03)

- Ad Interaction Time: Medium (~90 sec)
### Interpretation:
This segment is digitally passive — minimal weekday interaction and moderate weekend browsing.
Ad Strategy: Focus on brand awareness, visual storytelling, and retargeting rather than direct conversions.

### Cluster 4 – “Engaged Mobile Achievers”

- Likes & Reactions: Highest (~7000)

- Weekday Activity: Moderate (~3 hrs)

- Weekend Activity: Highest (~6.2 hrs)

- CTR: Strong (~0.13)

- Conversion Rate: Lower (~0.025)

- Ad Interaction Time: High (~95 sec)
### Interpretation:
These users are active mobile consumers, heavy on social engagement but less likely to convert immediately.
Ad Strategy: Use gamified ads, mobile-first video formats, and engagement-based promotions to encourage conversions.

## Summary Insights
Cluster	Persona	CTR	Conversion	Engagement	Interpretation
0	Highly Engaged Social Enthusiasts	0.13	0.075 (Highest)	Very High	Power users with consistent cross-day activity
1	Balanced Explorers	0.11	0.07	High (Weekends)	Selective converters; best targeted on weekends
2	Curious Deep Divers	0.185 (Highest)	0.05	Medium	Click-heavy learners needing guided CTAs
3	Passive Weekend Viewers	0.07	0.03	Low	Low engagement; suited for awareness ads
4	Engaged Mobile Achievers	0.13	0.025	Very High	Socially connected but conversion-lagging users

## Business Implications

Targeting Optimization:

- Prioritize Clusters 0 & 1 for conversion-driven campaigns.

- Use Cluster 2 for content marketing.

- Focus Cluster 4 on engagement-based promotions.

Campaign Timing:

- Weekends → Clusters 1 & 4

- Weekdays → Clusters 0 & 2

Ad Formats:

- Short-form video for Clusters 4

- Long-form storytelling for Cluster 2

- Interactive and loyalty ads for Cluster 0

## Tools & Technologies

- Python Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

- Clustering Model: K-Means (k=5)

- Preprocessing: Label Encoding + StandardScaler

- Visualization: Custom bar plots (shown in CLUSTER ANALYSIS.png)

## Conclusion

The analysis successfully identified five clear audience segments with distinct engagement and conversion patterns.
These insights allow marketers to:

Optimize ad spend toward the most valuable users,

Design platform-specific ad strategies, and

Improve overall conversion efficiency through personalization.
