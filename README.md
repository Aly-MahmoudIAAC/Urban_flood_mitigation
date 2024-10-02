# Mitigating Urban Floods: A Parametric Approach to Rainwater Management

<div align="center">
<img src=Images/cover04.png alt="Project Overview Image" width="1000"/>
</div>

**Authors**:  
Farida Fidvi, Aly Mahmoud, Christopher Mina  
**Faculty Advisor**: German Otto Bodenbender  
**Program**: Master in Advanced Computation for Architecture and Design  
**Thesis Year**: 2024

---

## Project Overview

This repository contains the source code, scripts, and datasets used in the research project titled **Mitigating Urban Floods: A Parametric Approach to Rainwater Management**. The project focuses on providing innovative green roof solutions to mitigate urban flooding, with a specific case study in **Tardeo, Mumbai**. By leveraging **parametric design** and **machine learning**, we aim to optimize rainwater absorption and reduce surface runoff, contributing to flood mitigation in dense urban areas.

## Table of Contents

1. [Problem Statement](#problem-statement)
2. [Goal and Objectives](#goal-and-objectives)
3. [Methodology](#methodology)
4. [Model and Workflow](#model-and-workflow)
5. [User Interface](#user-interface)
6. [Precedent Studies](#precedent-studies)
7. [Future Work](#future-work)
8. [How to Use](#how-to-use)
9. [References](#references)

---

## Problem Statement

Urban floods are an escalating challenge, especially in regions like Mumbai, India, where rapid urbanization, climate change, and inadequate infrastructure exacerbate flooding events. This project focuses on mitigating floods by implementing scalable green roof solutions that enhance rainwater retention and reduce surface runoff.

---

## Goal and Objectives

The main goal of this thesis is to develop adaptable, parametric green roof designs to manage excess rainwater during heavy rainfall events. This is achieved through a modular design approach combined with machine learning to model and optimize rainwater absorption and surface runoff reduction.

### Key Objectives:
- **Flood Mitigation**: Enhance the ability of urban landscapes to absorb and redirect rainwater.
- **Adaptability**: Implement flexible, responsive design strategies adaptable to various rainfall conditions and site-specific needs.
- **Reduction of Surface Runoff**: Use green infrastructure to reduce runoff and ease the burden on drainage systems.

---

## Methodology

Our approach combines **parametric design tools**, **machine learning**, and **user-driven customization** to optimize rainwater management in urban areas. The methodology includes:

1. **Literature Review**: Understanding green roof technologies and their stormwater management benefits.
2. **Data Collection and Simulation**: Using real-world data to simulate rainfall, runoff, and retention behavior.
3. **Precedent Analysis**: Studying large-scale urban projects that integrate water retention systems.
4. **Development**: Building a user-friendly interface for designers to implement our solution in diverse urban environments.

---

## Model and Workflow

### Green Roof Design
- **Modular Design**: A scalable green roof solution using pre-assembled components.
- **Parametric Modelling**: By applying Grasshopper and Rhino, we allow for flexible design adjustments based on building type, roof slope, and rainfall data.
  
### Machine Learning Integration
- **XGBoost Model**: Predicts surface runoff reduction based on urban density, rainfall data, and green roof area.
- **Linear Regression**: Provides a baseline model for comparison with XGBoost.

[Machine learning colab link](https://colab.research.google.com/drive/1zIrEJm34ajxBBQKzXi5fq405CAjR7uCS?usp=drive_link)
---

## User Interface

We developed a **Human UI** interface within Grasshopper, allowing users to:
- Define focus regions for analysis.
- Adjust green roof parameters.
- Calculate the Run off reduction.
- Visualize the Green Roof design
  
The UI also supports customization for different building types, allowing the selection of flat and sloped roofs. This enables designers to integrate the solution into various architectural contexts. (yet it still not made to solve for pitched roofs in the current update)

---

## Precedent Studies

Our research is inspired by several large-scale water retention projects, including China's **Sponge City initiative**. These studies provided insights into the technological and ecological impacts of green infrastructure on urban water management.

---

## Future Work

The potential future enhancements of this project include:
- Extending the model to integrate pitched roof designs.
- Incorporating street-level runoff reduction techniques, such as permeable pavements and tensile structures over open spaces.
  
These additions aim to further improve urban flood resilience in dense city centers.

---

## How to Use

### 1. Download the Repository

Clone or download the repository from GitHub.

### 2. Install Dependencies

Ensure you have Rhino 8, Grasshopper, and all relevant plugins (e.g., Human UI, Ladybug).

### 3. Run the Grasshopper Script

Open the script in Grasshopper to launch the UI.

### 4. Go Macro First

[Macro scale Notebook](https://colab.research.google.com/drive/1L0AFO0ew2kDGoL1DWifYGX11eO9e9vLP?usp=drive_link).

<p float="left">
  <img src="Images/How_to_use/How_to_p01 (2).jpg" width="400" />
  <img src="Images/How_to_use/How_to_p01 (3).jpg" width="400" />
</p>

### 5. Refine Your Context

<p float="left">
  <img src="Images/How_to_use/How_to_p01 (4).jpg" width="400" />
  <img src="Images/How_to_use/How_to_p01 (5).jpg" width="400" />
</p>

### 6. Zone Analysis

<p float="left">
  <img src="Images/How_to_use/How_to_p01 (6).jpg" width="400" />
  <img src="Images/How_to_use/How_to_p01 (7).jpg" width="400" />
</p>
<p float="left">
  <img src="Images/How_to_use/How_to_p01 (8).jpg" width="400" />
  <img src="Images/How_to_use/How_to_p01 (9).jpg" width="400" />
</p>

### 7. Preliminary predictions

Use the interface to select a region, define roof parameters, and visualize the impact of green roof installations.

<p float="left">
  <img src="Images/How_to_use/How_to_p01 (10).jpg" width="400" />
  <img src="Images/How_to_use/How_to_p01 (11).jpg" width="400" />
</p>

### 7. Generic Green Roof

Generate simulations for runoff reduction based on user-defined parameters.

<p float="left">
  <img src="Images/How_to_use/How_to_p01 (12).jpg" width="400" />
  <img src="Images/How_to_use/How_to_p01 (13).jpg" width="400" />
</p>

### 8. Design Your Own Roof

Generate simulations for runoff reduction based on user-defined parameters.

<p float="left">
  <img src="Images/How_to_use/How_to_p01 (14).jpg" width="400" />
  <img src="Images/How_to_use/How_to_p01 (15).jpg" width="400" />
</p>

### 9. Analyse Results

Generate simulations for runoff reduction based on user-defined parameters.

<p float="left">
  <img src="Images/How_to_use/How_to_p01 (16).jpg" width="400" />
  <img src="Images/How_to_use/How_to_p01 (17).jpg" width="400" />
</p>

### 10. Visualize 

Generate simulations for runoff reduction based on user-defined parameters.

<p float="left">
  <img src="Images/How_to_use/How_to_p01 (18).jpg" width="400" />
  <img src="Images/How_to_use/How_to_p01 (19).jpg" width="400" />
</p>
---

## References

The references section includes key studies and resources used to develop this project. For more detailed information, refer to the full thesis document.

- Yavaş, S., Baysan, C., & Önal, A. E. (2022). *Analysis of the natural disasters in the last century and the people who were consequently displaced*.  
- Jia, H., Qiao, Y., & Xiao, R. (2017). *A Comprehensive Review of the Sponge City Construction in China: Policy and Regulation, Technologies, and Flood Control Management*.  
- Zhang, J., Li, F., & Yu, G. (2021). *Integrated Urban Flood Management: From Concept to Implementation*.  
- See the full list of references in the repository or the [booklet](./link-to-thesis-booklet.pdf).

---
