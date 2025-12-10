# CS598 Project Progress Report

**Kevin Cruz, Manu Pillai, Junu Jeon**  
{kcruz28, mpilla6, junuj2}@illinois.edu

# Overview

### Motivation
Public transit systems are deeply influenced by environmental factors such as temperature, precipitation, humidity, and wind. Chicago’s multimodal transit ecosystem, which includes CTA bus, CTA rail ("L"), and Divvy bike-share, provides an ideal environment for studying these relationships. Understanding how weather impacts ridership helps cities plan service adjustments, allocate resources, improve resilience, and better serve communities.

### Context
This project was created for CS598: Foundations of Data Curation, and its purpose is to produce a curated, reproducible dataset integrating multiple official transit and weather sources. The curated output is intended for reuse by analysts, researchers, and policy planners who wish to study multimodal travel patterns and climate impacts in urban settings.

The project follows the USGS Data Lifecycle Model and includes fully documented metadata, provenance, reproducibility information, and workflow scripts to support long-term accessibility and transparent reuse.

### Research Question
**How do daily weather conditions (temperature, precipitation, wind speed) affect daily ridership in Chicago across CTA bus, CTA rail, and Divvy bike-share systems?**

```bash
cd data
pip install -r requirements.txt
