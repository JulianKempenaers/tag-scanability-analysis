# Tag Detection Analysis: Optimising Tag visibility through Obstructions

## Goal
To determine the optimal net height and camera aperture settings that maximize the frequency of successful tag detections in the presence of a physical barrier (a net). 

## Tools & Libraries
- **Python** (pandas, numpy, matplotlib, seaborn
- Statistical testing (Kruskal-Wallis H-test, Mann-Whitneu U)
- Jupyter Lab

## Methodology
- Calculated tag detection rates on a frame-by-frame basis
- Normalisation of variable video duration segments
- Statistical comparison of detection performance across different net heights and aperture settings. 
- Visualised detection trends using violin plots with jittered data points for clarity.

---

## Summary
This Analysis addressed a key experimental question: 
> Is the low tag detection rate caused by the net being in focus? Can raising the net improve visibility, or is adjusting the aperture sufficient?
- Under a narrow aperture setting, raising the net to 30cm significantly improved tag detection
- When aperture was widened, all net heights showed improved detection performance, indicating that a 22cm net height is sufficient when aperture is appropriately adjusted.

Figure 1: Narrow aperture

<img width="459" height="257" alt="image" src="https://github.com/user-attachments/assets/432402c5-6bee-45a7-a655-bad229b27886" />

Figure 2: Wide aperture

<img width="459" height="254" alt="image" src="https://github.com/user-attachments/assets/21d23d5b-007c-4c7a-bde0-2bb3a9e4e100" />

**Conclusion**: 22cm net height is sufficient if aperture is widened. 

 [View full analysis in Python notebook](netheight_analysis.ipynb)
