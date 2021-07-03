---
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://wowchemy.com/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget: blank  # See https://wowchemy.com/docs/page-builder/
headless: true  # This file represents a page section.
weight: 15  # Order that this section will appear.
title: "About the Testbed"
subtitle: ""
hero_media: 
design:
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns: '1'
advanced:
  css_style:
  css_class:
---
We are the MIT Mechatronics Research Laboratory (MRL). We are currently conducting research in health monitoring/anomaly detection on physical machines. We previously proposed a general purpose anomalous scenario synthesizer (GPASS) to generate various forms of reproducible, controlled dynamic anomalies to a rotary plant. 

In the latest set up, the GPASS collects around 28 real-time sensor signals in multiple domains, e.g., angular displacement, velocity, acceleration, magnetic field, strain and so on. Most sensors run at a minimum of 80Hz. So, that’s a lot of data points.  

Here, we published the data as we ran experiments locally for ourselves. The data are preliminarily pre-processed, such as fusing data streams from multiple sensors, synchronizing the time-frame, etc. However, the contents are intact. 

Good news is that we want to do more than just share the data. The GPASS works as a ‘cloud hardware platform’ that accepts ‘quotes’ for anomalous scenarios. If you want a characterized test run for your experiment, fill out the survey. The setup currently supports:

1. Large lateral force (~20N)
2. High frequency vibration (contact method: 50Hz, contactless method: regulated at 100Hz max)
3. Grinding (force customizable)
4. Scratching
5. Rotational damping 

There is still more to come in the future! Feel free to contact us to develop a new anomalous mode together. The status of the GPASS is publicly available via sensor and video online <a href="https://thingspeak.com/channels/1289599"> here </a>.
