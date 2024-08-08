---
layout: page
title: Model
---

### Gravity Model

Gravity models are widely used in urban planning and transportation research to estimate the movement of people between different locations. The underlying assumption is that larger population centers and closer neighborhoods have a higher level of attractivity, which influences the flow of people.

**How Gravity Models Work**

At their core, gravity models predict that the number of trips between two locations is inversely related to the distance between them. This means that the closer two places are, and the larger their populations, the more likely it is that people will travel between them.

***The model inputs typically include:***

**Total outflows:** The number of people leaving a location.

**Historical flow data:** Past movement patterns to inform predictions.

**Functional form of the distance function(f):** How distance impacts movement.

**Population and location data:** The size and position of the areas being studied.

<img src="{{ site.url }}{{ site.baseurl }}/assets/img/gravity_formula.png">

***Output:***

The primary output of a gravity model is an Origin-Destination (OD) matrix, which estimates the flow of people between different locations.



---

**Types of Gravity Models**

**Non-Constrained Models:** These are used when the goal is to approximate mobility flows and transport demand based on indirect socio-economic variables, without specific flow measurements.

**Constrained Models:** These models are employed when either outgoing or incoming flows are empirically measured, and the objective is to estimate the elements of the OD matrix. For instance:

* **Singly Constrained Models:** Estimate destinations based on how many people are leaving from one place.

* **Globally Constrained Models:** Estimate movements by considering both the number of people leaving a place and the number arriving at another.


---

**Model Limitations**

While gravity models are powerful tools, they do have drawbacks:

**Simplification of Travel Flows:** Gravity models can be overly simplistic, sometimes failing to capture the complexity of actual empirical observations.

**Sensitivity to Data Quality:** The need to estimate several free parameters makes gravity models sensitive to fluctuations or incompleteness in the data.
