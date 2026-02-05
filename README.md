
<p align="center">
  <img src="https://github.com/gabrielrenanpp/Student-Lifestyle-Nutrition-Analytics-File/blob/main/Images/Student%20Lifestyle%20&%20Nutrition%20Analytics.png?raw=true" width="600">
</p
<br>

  
# Student-Lifestyle-Nutrition-Analytics
## Behavioral Patterns Influencing Health Perception and Academic Performance

### Executive Summary

This project explores how lifestyle behaviors and dietary patterns influence students’ perceived health and academic performance.

By combining behavioral, nutritional, and wellness variables, the analysis aims to uncover performance drivers, health risk indicators, and population lifestyle segments.

The work simulates a real-world analytics engagement where institutions seek data-driven strategies to improve student well-being and academic outcomes.

### Dataset Scope

The dataset contains self-reported student data, including:

- Nutrition habits

- Vegetable consumption

- Coffee intake

- Vitamin usage

- Exercise frequency

- Sports participation

- Caloric intake

- Emotional eating triggers

- Body weight

- GPA

### Analytical Approach

The analysis was structured across three dimensions:

- Behavioral Drivers

- Health Indicators

- Academic Performance Impact

- Advanced SQL techniques were applied, including:

- CTE modeling

- Window functions

- Composite scoring

- Behavioral segmentation

 ## Health Perception vs Academic Performance

<p align="left">
  <img src="https://github.com/gabrielrenanpp/Student-Lifestyle-Nutrition-Analytics-File/blob/main/Images/First%20SQL.png?raw=true" width="600">
</p>

This analysis evaluates how students’ perceived health levels relate to their academic performance. By comparing average GPA across different health perception groups, stakeholders can observe whether students who feel healthier also demonstrate stronger academic outcomes. The results provide an initial behavioral indicator linking wellness awareness to performance.

### Exercise Frequency Impact Model
<p align="left">
  <img src="https://github.com/gabrielrenanpp/Student-Lifestyle-Nutrition-Analytics-File/blob/main/Images/second%20SQL.png?raw=true" width="600">
</p>

This model measures the impact of physical activity on both health perception and academic results. It allows stakeholders to understand whether more active students not only feel healthier but also perform better academically. The dual-metric structure highlights exercise as a potential driver of both well-being and performance.

## Nutrition Quality vs Body Weight

<p align="left">
  <img src="https://github.com/gabrielrenanpp/Student-Lifestyle-Nutrition-Analytics-File/blob/main/Images/third%20SQL.png?raw=true" width="600">
</p>

This analysis examines the relationship between vegetable consumption frequency and average body weight. Vegetable intake is used as a proxy for nutritional quality. Stakeholders can use this view to understand how healthier eating patterns translate into measurable physical health indicators.

## Coffee Consumption vs Academic Performance

<p align="left">
  <img src="https://github.com/gabrielrenanpp/Student-Lifestyle-Nutrition-Analytics-File/blob/main/Images/fourth%20SQL.png?raw=true" width="600">
</p>

This query evaluates whether coffee consumption correlates with academic performance. By comparing GPA averages between consumers and non-consumers, stakeholders can observe whether stimulant use aligns with improved productivity or reflects behavioral coping mechanisms tied to academic pressure.

## Emotional Drivers of Comfort Food Consumption

<p align="left">
  <img src="https://github.com/gabrielrenanpp/Student-Lifestyle-Nutrition-Analytics-File/blob/main/Images/Fifth%20SQL.png?raw=true" width="600">
</p>
This behavioral analysis identifies the primary emotional triggers behind comfort food consumption. By ranking the most frequent drivers, stakeholders gain visibility into psychological factors — such as stress or sadness — influencing eating behaviors. This insight supports mental health and wellness intervention planning.

## Lifestyle Performance Matrix

<p align="left">
  <img src="https://github.com/gabrielrenanpp/Student-Lifestyle-Nutrition-Analytics-File/blob/main/Images/Sixth%20SQL.png?raw=true" width="600">
</p>
This matrix evaluates how combined lifestyle behaviors influence academic outcomes. Instead of analyzing habits in isolation, it reveals performance clusters formed by the intersection of caffeine consumption and exercise frequency. Stakeholders can identify which behavioral combinations are associated with the strongest academic results.

## Composite Health Score Model
<p align="left">
  <img src="https://github.com/gabrielrenanpp/Student-Lifestyle-Nutrition-Analytics-File/blob/main/Images/Seventh%20SQL.png?raw=true" width="600">
</p>

A composite wellness index was developed to quantify overall student lifestyle quality. Multiple behavioral indicators — nutrition, exercise, and supplement intake — were standardized into a unified health score. This model allows stakeholders to evaluate how cumulative lifestyle habits influence both academic performance and perceived well-being.

## Lifestyle Segmentation Framework
<p align="left">
  <img src="https://github.com/gabrielrenanpp/Student-Lifestyle-Nutrition-Analytics-File/blob/main/Images/eighth%20SQL.png?raw=true" width="600">
</p>
Students were segmented into lifestyle cohorts based on combined nutrition and exercise behaviors. This segmentation translates raw behavioral data into executive population groups, enabling stakeholders to identify high-performance wellness segments and at-risk profiles requiring targeted intervention.

## Sports Participation Impact Analysis
<p align="left">
  <img src="https://github.com/gabrielrenanpp/Student-Lifestyle-Nutrition-Analytics-File/blob/main/Images/Ninth%20SQL.png?raw=true" width="600">
</p>

This analysis measures the physical and academic impact of sports participation. By comparing weight and GPA across participation groups, stakeholders can assess whether structured athletic engagement contributes to both healthier body composition and improved academic performance.



## During analysis, the following transformations were required:

- Textual numeric fields standardized via TRY_CAST

- Null-safe aggregations implemented

- Behavioral variables categorized via CASE logic

- Composite scoring engineered through CTE modeling

## Analytical Conclusions

- Higher lifestyle scores correlate with improved GPA averages.

- Exercise frequency shows the strongest relationship with perceived health.

- Emotional stress is the dominant comfort food trigger.

- Nutrition quality aligns with lower body weight distribution.

- Lifestyle segmentation reveals measurable academic variance.

 # 📌 Final Stakeholder Action Statement

Based on the behavioral and performance patterns identified, it is recommended that the institution implement a data-driven Student Wellness Strategy focused on promoting physical activity, improving nutritional access, and expanding mental health support programs.

By targeting at-risk lifestyle segments and incentivizing healthier behaviors, the organization can simultaneously enhance student well-being and drive measurable improvements in academic performance outcomes.

To access my repository and the files used in this analysis, click [here](https://github.com/gabrielrenanpp/Student-Lifestyle-Nutrition-Analytics-File/tree/main).
