# Airfoil_predection
Data-driven parametric analysis and machine learning models for predicting NASA airfoil self-noise levels and defining low-noise stealth envelopes.

## 👥 Project Team

**TEAM 404**  
*Department of Computer Science and Engineering, Panimalar Engineering College, Chennai, Tamil Nadu, India*

** TEAM-MEMBERS**
* **Jasvinguru S.(LEAD)**
* **Karthick S.**
* **Janak S. V.**
* **Kirithic M.**

  ## 📌 Project Overview

Airfoil self-noise is a critical factor influencing acoustic signatures in stealth aircraft design, unmanned aerial vehicles (UAVs), and wind turbine systems. This repository presents a data-driven aeroacoustic analysis and predictive machine learning workflow based on the **NASA Airfoil Self-Noise Dataset**.

The primary objectives of this study are:
1. **Parametric Sensitivity Analysis:** Quantify how key operational parameters—such as Angle of Attack (\(\alpha\)), Displacement Thickness (\(\delta\)), Frequency (\(f\)), Chord Length (\(c\)), and Free-Stream Velocity (\(U_\infty\))—impact Sound Pressure Levels (\(SSPL\)).
2. **Stealth Envelope Definition:** Map optimal operational regimes that meet strict thresholds for minimal noise (\(SSPL \le 118\text{ dB}\)) and low boundary layer turbulence (\(\delta \le 0.0025\text{ m}\)).


  ## 📊 Key FindingsCorrelation Dynamics
  
  Feature correlation analysis reveals a strong positive correlation ($0.75$) between Angle of Attack (alpha) and Displacement Thickness (delta), demonstrating that higher pitch angles exponentially grow boundary layer disruption.Acoustic Skewness: Sound Pressure Levels exhibit a left-skewed distribution peaking between 125 dB and 130 dB, indicating that unoptimized flight conditions operate significantly above stealth noise targets.Stealth Envelope Boundaries: Isolates a distinct low-observable flight envelope operating primarily at low pitch angles ($\le 10^\circ$) to keep acoustic emissions below $118\text{ dB}$.
