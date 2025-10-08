# Game Analytics – Player Behavior & Retention Analysis

This repository contains a complete data analytics workflow for **a story-driven mobile game** that combines simulation and puzzle mechanics.  
The analysis focuses on understanding player engagement, retention, and monetization using both real and simulated datasets.

---

## Project Overview
This project evaluates how players interact with the game, where they drop off, and how their behaviors differ.  
The workflow includes:

- **Data Cleaning:** Extracting and structuring event data from Firebase exports.  
- **Data Simulation:** Generating a 10,000-player dataset using Monte Carlo methods.  
- **Player Journey Funnel:** Identifying drop-off points across onboarding and progression.  
- **Player Segmentation:** Clustering players into behavioral groups to guide design and marketing.  
- **Recommendations:** Data-driven strategies to improve engagement, retention, and monetization.

---

## Folder Structure
data/
├── processed/ # Cleaned Firebase data
├── simulated/ # Simulated player-level dataset
images/ # Visualizations (funnel, segmentation)
notebooks/ # Jupyter notebooks (cleaning, simulation, analysis)
