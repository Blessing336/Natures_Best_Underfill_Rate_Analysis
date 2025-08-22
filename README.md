# Project Background

Natures Best Juice Co., a leading producer of fresh orange fruit juices, **launched an operational analysis project in response to a rising trend of underfilled bottles across its production lines**. 

Over the past several weeks, the **number of underfilled bottles has steadily increased**, with a recent spike showing higher-than-expected underfill counts per batch. This issue has led to growing internal costs, batch inconsistencies, and concerns over meeting both regulatory standards and customer expectations.

The primary objective of this project is to **analyze, visualize, and interpret production line data with a focus on understanding the drivers of underfill**. Specific attention will be given to machine-level performance and nozzle activity, in order to quantify their impact on production quality. The investigation will **track key performance indicators such as underfill rate (%), underfill cost (₦), juice wasted (litres), and months since last replacement**.

Ultimately, the goal is to **identify actionable insights** and **develop recommendations that will reduce underfill by at least 50%** in the coming quarter. Control measures will also be proposed to help the operations sustain improvements, and prevent recurrence of the recent spike.


<br/>

Interact with Report *[here](https://app.powerbi.com/view?r=eyJrIjoiOTliYzQ1OWItNjdiZS00ZTk5LTkxNDQtNmNjNzM0YzBlMWVlIiwidCI6IjY5M2I4NzFiLTNhMjItNDUxOS04ZjZhLTFhYjNjOTI4Y2FlMSJ9)*

<br/>

## Key Analysis and Recommendation Areas

* Determine when the underfill trend began and how it has evolved
* Compare the KPIs before vs. after the issue became noticeable
* Identify patterns tied to nozzles
* Deliver a data-backed Root Cause Analysis with clear explanations and recommendations for the Operations team 

<br/>

# Data Structure

![Data Structure](https://github.com/Blessing336/Natures_Best_Underfill_Rate_Analysis/blob/47cdab9e3cb2ebd9dd7059eb54678f9fdb9147d3/Resources/Natures%20Data%20Structure.png)

<br/>

# Executive Summary

Natures Best Juice Co. is facing a concentrated underfill problem that escalated rapidly after **June 28, 2025**. From that date, **underfill cost increased by 675% within just 18 days** compared with the entire four months prior, indicating a clear inflection point and sustained deterioration across recent batches.

The issue is not evenly distributed. Line 1 is the major cause, with **filler nozzles 2 and 4 showing the highest underfill rates** relative to peer nozzles. Before the spike, core KPIs (underfill rate, units underfilled cost, and juice waste (litres)) were stable and within tolerance; after the spike, these KPIs rose sharply, with repeated exceedances across multiple consecutive batches.

This issue is as a result of how long we replaced the nozzles.


<br/>

# Insights

![Natures](https://github.com/Blessing336/Natures_Best_Underfill_Rate_Analysis/blob/c256d2b172bcd0b1446e02789bbd14ce666212d5/Resources/natures_full.gif)

<br/>

1. **When did underfill trend began and how it has evolved?**

**It began suddenly**. For months, underfill levels were relatively stable, staying close to 1% with only minor fluctuations. **That changed sharply on June 28, 2025**, when the underfill rate spiked. Within two weeks, the rate soared as high as **46.72%**, a level never seen before, and the curve on the chart shows that it has yet to stabilise. This single date marks the **turning point** where a low, predictable problem escalated into a major operational concern.

<br/>

2. **Compare the KPIs before vs. after the issue became noticeable**

In the four months leading up to June 28, the company lost ₦62.6K in underfill costs at an average rate of 0.5% and just 4.6 litres of wasted juice. In the short 18-day period after the spike, those numbers exploded: **₦485.2K in costs (+675%)**, an **average underfill rate of nearly 6%**, and **33.4 litres of waste (+624%)**. In other words, the **financial and operational impact** seen in less than three weeks outweighed everything accumulated across four months, showing how quickly the issue compounded once it began.

<br/>

3. **What patterns are tied to nozzles?**

The nozzle-level data reveals that this surge is not spread evenly across equipment. **Line 1 emerges as the central problem area, with Nozzles 2 and 4 consistently recording the highest underfill rates**. While other nozzles on the same filler line fluctuated only slightly, these two nozzles stand out as persistent outliers, confirming that the trend is driven more by localised equipment behaviour than by a system-wide issue.


<br/>


# Root Cause Analysis

**Both Nozzles 2 and 4 have been in service significantly longer than their counterparts**, with **41 months and 47 months since last replacement, compared to 19–24 months for the others**. 

The chart commentary reinforces this: **“as a nozzle condition deteriorates over time, the risk of underfilling increases.”** The steep escalation in juice waste, a nearly 1,700% increase from week 26 to week 27, capped by 17.4 litres of loss in a single week, lines up directly with their extended usage history. 

One thing is clear, **Underfill is not a random occurrence; it is highly correlated with nozzle age and wear**.

<br/>

# Recommendations

* Replace Nozzles 2 and 4 as soon as possible to prevent further juice waste and restore underfill rates to acceptable levels.

* Implement a proactive nozzle replacement cycle (e.g. every 18–24 months): 

Alongside replacements, operators should monitor underfill waste daily for early warning signals of deterioration, rather than waiting for extreme spikes.



<br/>

# Key Questions for Stakeholders Prior to Project Advancement

* Is there a standard threshold for allowable underfill?

*Response*: Yes, there is. Since 500ml is the standard fill for each bottle, -4 ml was given as the standard thresholds for allowable underfill. This means that, any bottle containing less than 496ml juice is considered underfill.

* Has the spike after June 28, 2025 coincided with any changes in raw materials, production volume, or machine settings that could explain the surge?

*Response*: No.


<br/>


# Assumptions and Caveats

* Nozzle replacement dates in the system are considered accurate.

* Operator error factors are not considered in the analysis, given that nozzle issues dominated.

* It is considered that all underfilled bottles are unsellable and are not recoverable through rework processes.



<br/><br/>

Go to my *[github homepage](https://github.com/Blessing336)*

