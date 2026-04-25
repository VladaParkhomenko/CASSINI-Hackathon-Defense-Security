# 🛰️ Space Rodeo: Close Approach Risk Assessment (CARA)
**National Winners (1st Place Poland) — 8th CASSINI Hackathon: EU Space for Defence & Security**

## 🚀 Project Overview
**Space Rodeo** is a team of students from the **Lodz University of Technology**, formed for the 8th CASSINI Hackathon (November 22-24, 2024). Our project addresses the critical challenge of orbital safety by developing an advanced concept for **Close Approach Risk Assessments (CARA)** to protect satellites from collisions with space debris and other orbiting objects.

## 💡 The Theory: Orbital Cluster Identification
Our model shifts the focus from individual objects to **Cluster Areas**. 
* **Cyclic Proximity:** We identify zones where objects with different orbital parameters converge periodically. 
* **Predictive Analysis:** By measuring relative angular velocity and phase shifts, we determine the frequency of convergences relative to a "body of interest" (a protected satellite).
* **Multi-Object Risk:** Clusters are defined as areas where more than two objects share a common collision risk, allowing for a more holistic view of orbital safety.

## 🛠️ Service Architecture
The Space Rodeo integrates four key technical pillars:

1. **Raw Data Processing:** Utilizing TLEs (Two-Line Element sets) with high-frequency updates, accounting for atmospheric drag, solar pressure, and gravitational perturbations.
2. **The Algorithm:** - **Filtration:** Intelligent sorting to derive a shortlist of potential threats.
   - **Cluster Definition:** Real-time distance calculations and convergence mapping.
   - **Stochastic Simulation:** Modeling perturbations by assigning random vectors to state vectors, running thousands of iterations to compensate for orbital uncertainties.
3. **Database Management:** Maintaining refined, constantly updated catalogues of orbital entities and cluster memberships.
4. **Unified Server:** A centralized hub linking data, algorithms, and databases to ensure seamless service delivery.

## 💼 Business Model
We propose a **Subscription-Based Model (SaaS)**:
* **Continuous Monitoring:** Constant risk assessment for the customer's specific satellite.
* **Early Warning System:** Providing advanced notice for required mitigation maneuvers, ensuring maximum reaction time for satellite operators.

## 🌟 Key Benefits
* **Proactive Defense:** Preliminary modeling allows for mitigation activities to be implemented much earlier than current industry standards.
* **Predictability:** Leveraging the periodic nature of clusters to improve future risk assessment models.
* **Accessibility:** A cost-effective tool for small-scale private companies to assess risks before launching new assets into orbit.
* **Efficiency:** Our method can significantly speed up existing risk assessment protocols (like those used by ESA) by utilizing pre-calculated cluster catalogues.

---
*Developed by Team Space Rodeo at Lodz University of Technology.*
