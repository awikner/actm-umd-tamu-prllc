---
layout: default
---

# Hybridizing Knowledge-based and Machine Learning Models for Climate Prediction

Our group, composed of researchers at The University of Maryland, Texas A & M University, and Potomac Research LLC, is very excited and eager to begin work on this program, and to interact with other program participants.

## Program Summary
### Introduction
This program is based on combining two components. The first is a conventional knowledge-based model of the evolution of the climate. The second is a machine learning component employing a spatial grid of many, relatively small, reservoir computers trained in parallel on observation-based state evolution data. This approach has been formulated by us through previous DARPA-funded research. We call our scheme Combined Hybrid Parallel Prediction (CHyPP, pronounced “chip”).

In past work, we have successfully implemented CHyPP for weather forecasting. For this implementation, the knowledge-based component of the hybrid was a low-resolution, but realistic, fully 3-dimensional atmospheric global circulation model known as SPEEDY. SPEEDY was formulated for climate studies, and incorporates terrestrial geography, including representations of the Earth’s continents, oceans, ice covered regions, and mountain ranges. This preliminary weather forecasting work has demonstrated the great potential of the CHyPP approach. In particular, it uses the data-driven machine learning component to effectively compensate for the inability of conventional, purely knowledge-based geophysical models to appropriately capture sub-grid scale dynamics, which are known to have crucial fundamental effects on the dynamics at the resolved scale. Such results lead us to anticipate that CHyPP may also facilitate large improvements in climate and tipping-point prediction relative to what is attainable using conventional, purely knowledge-based modeling.

### Tasks
#### **Task I**: Extension of our current SPEEDY-based CHyPP implementation from weather (i.e., short-term atmospheric state prediction) to climate (i.e., long-term prediction of the statistical properties of atmospheric states).
#### **Task II**: Development of new climate and tipping-point prediction concepts and methods through theoretical analysis and numerical exploration on appropriate “small” test models.
#### **Task III**: Incorporation of those discoveries from Task II that are found to be appropriate into the global atmospheric model implemented in Task I, for testing, evaluation, modification, and further development of techniques and concepts.

### Key Issues
- Coupling the atmospheric model to a model of the ocean (part of Task I).
- Scalability to very large, high-resolution systems (part of Task III).
- Computational speed and accuracy of predictions (part of Task III).
- Methods for enhancing prediction system stability for long-term climate runs (part of Task II).
- Methods for enhancing prediction of non-stationary dynamical systems and tipping points (building on our previous DARPA-funded work) (part of Task II).
- Tipping-point concepts for large, spatially heterogeneous, complex systems (part of Task II).
- Capturing behavior near and across tipping-points (part of Task II).
- Potential for CHyPP proxies to be used for computational speed-up relative to conventional purely knowledge-based models at high resolution (part of Task II).
- Identification of high-value data opportunities (part of Task III).


## Progress Reports

TBA

## Publications



## Repositories

[1-Dimensional CHyPP Code (Matlab)](https://github.com/awikner/CHyPP)

## Data

## People

### University of Maryland, College Park
[**Prof. Edward Ott**](https://scholar.google.com/citations?user=z7boxkkAAAAJ&hl=en), PI, Dept. of Electrical and Computer Engineering and Dept. of Physics

[**Prof. Michelle Girvan**](https://scholar.google.com/citations?user=npKBI-oAAAAJ&hl=en), Department of Physics

[**Prof. Brian Hunt**](https://scholar.google.com/citations?user=ten7UlMAAAAJ&hl=en), Department of Mathematics

[**Dhruvit Patel**](https://scholar.google.com/citations?user=mx7LoLsAAAAJ&hl=en), Graduate Student, Department of Physics

[**Alexander Wikner**](https://scholar.google.com/citations?user=J7dAtysAAAAJ&hl=en), Graduate Student, Department of Physics

### Texas A&M University
[**Prof. Istvan Szunyogh**](https://scholar.google.com/citations?user=L4JW_JUAAAAJ&hl=en), Department of Atmospheric Sciences

[**Troy Arcomano**](https://scholar.google.com/citations?user=SBeD6doAAAAJ&hl=en), Graduate Student, Department of Atmospheric Sciences

[**Mitchell Tsokatos**](https://atmo.tamu.edu/people/profiles/students/tsokatosmitchell.html), Graduate Student, Department of Atmospheric Science

### Potomac Research, LLC
**Dr. Andrew Pomerance**
