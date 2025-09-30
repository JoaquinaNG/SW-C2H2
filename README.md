# 🧪 Synoptic Data Synthesis: August 2025 Campaign

This repository serves as a **centralized synthesis** of data collected during a **synoptic water quality campaign** conducted on **August 21, 2025**. It pulls together multiple **continuous environmental datasets** collected across the **Calumet River system** and surrounding tributaries over the window of **August 18–24, 2025**, to provide context for the point-in-time sampling.

---

## 📅 Overview

* **Synoptic sampling date:** August 21, 2025
* **Data window:** August 18–24, 2025
* **Location:** Little Calumet River Watershed, Illinois

---

## 📦 Contents

This repository includes:

* 📈 **Continuous Water Quality Data** (e.g., temperature (°C), turbidity (FNU), FDOM (RFU), specific conductance (µS/cm), and dissolved oxygen (mg/L))
* 🌧️ **Precipitation Data** (from MRSM data 2min frequency intensity)
* 💧 **Flow/Discharge Data** (from USGS gages in the watershed)
* 🗺️ **Scripts** for loading, processing, and plotting integrated time series data

---

## 🔍 Purpose

The goal of this repository is to:

* Provide **temporal context** for discrete measurements taken during the synoptic campaign
* Support **comparative analysis** across locations and parameters
* Facilitate **data-driven interpretation** of hydrologic and water quality conditions in the week surrounding the synoptic sampling

## 🗃️ Data Sources

| Data Type      | Source                    | Frequency               |
| -------------- | ------------------------- | ----------------------- |
| Water Quality  | MWRD, H2NOW & NU sites    | High-frequency (< 1hr ) |
| Precipitation  | MRMS                      | 2-min                   |
| Flow/Discharge | USGS NWIS                 | Instantaneous or 15-min |

---

## 📌 Notes

* Not all sites currently have complete data; namely H2NOW and MWRD have to be updated.
* Precipitation and flow are visualized in tandem with water quality trends to contextualize the influence of hydrologic events on these parameters.
