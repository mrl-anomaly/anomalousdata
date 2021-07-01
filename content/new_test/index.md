---
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://wowchemy.com/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget: blank  # See https://wowchemy.com/docs/page-builder/
headless: true  # This file represents a page section.
weight: 15  # Order that this section will appear.
title: "New Test"
subtitle: ""
hero_media: 
design:
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns: '1'
advanced:
  css_style:
  css_class:
---

Unlike most anomaly synthesizers that introduce anomalies by using defected components, our setup supports anomalies that can be introduced dynamically while the plant is running. However, we currently cannot afford to take customized anomaly trajectories online, until we figure out a good way to standardize the input. (This can be added to the link where they submit their ‘quote’). 

Our current setup takes a standardized input. Each run will last 25 seconds at 80 Hz so there will be approximately 2000 (+/-) 50 data points for each run. 

Currently we are only able to support easily interpretable anomalies for submission from the website. Over the 25 seconds duration, input can be customized at the 0,5,10,15,20th seconds.

Specify an anomaly trajectory in the following format: 

If you want to load 5N of force at 5th and 15th seconds, and 10N of force at 10th second, do this: 

  Anomaly type: 1 
  Anomaly trajectory (if applicable): 0,5,10,5,0 

If you want to load 10 Hz of vibration at 10th second, and 15 Hz vibration at 20th second, do this: 

  Anomaly type: 2 
  Anomaly trajectory (if applicable): 0, 0, 10, 0, 10 

Currently we only support anomaly trajectory for anomaly 1,2, and 6. The anomaly ranges are as follows: 

Type 1 (Lateral force): 0 – 10N 
Type 2 (Active Vibration):  0 – 50Hz 
Type 6 (Rotational Damping): 1-15 (15 → no damping, 1 → max damping)

The status of the GPASS system is publicly available via sensor and video online:  
https://thingspeak.com/channels/1289599 
Please check regularly to fetch real time info. 
