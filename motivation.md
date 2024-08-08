---
layout: page
title: 
---

### Questions

In exploring the development and application of generative mobility models, we seek to address critical inquiries regarding their fairness and effectiveness. Specifically, we aim to investigate:



**How can generative mobility models be assessed to ensure they are fair?**

**What are the effective methods for measuring fairness in generative mobility models?**

**Are there inherent biases introduced by generative mobility models, and how can they be identified?**



---

### Background

In the modern world, accurate and equitable modeling of human mobility patterns is crucial for effective spatial planning and management, as it provides valuable insights into how people navigate their environments, enabling the design of infrastructure and services that cater to diverse community needs and ultimately shape the dynamics of cities and the quality of life of their inhabitants.

Despite their potential, existing mobility models often fall short in addressing the critical issue of fairness. Traditional models may inadvertently perpetuate biases, leading to inequitable outcomes for different demographic and geographic groups.

Our project addresses these critical issues by focusing on the fairness of generative mobility models. Inspired by recent advancements in the field, we aim to develop a comprehensive framework for assessing the fairness of these models. By developing a comprehensive fairness metric, our goal is to evaluate generative mobility models to ensure they produce equitable predictions. This metric will help us assess the fairness of various generative models and identify any inherent biases in their outputs, promoting more just and unbiased mobility solutions.


---

### Stakeholders

#### PSRC (Puget Sound Regional Council)

<img src="{{ site.url }}{{ site.baseurl }}/assets/img/psrc.jpg">


The Puget Sound Regional Council (PSRC) is a key stakeholder in our project. As a metropolitan planning organization, PSRC plays a crucial role in transportation planning and policy development in the Puget Sound region. Their commitment to integrating equity into transportation models, adherence to federal mandates, and use of advanced data transformation and reliability assessment techniques provide invaluable insights for our work. Engaging with PSRC enabled us to align our models with industry standards, regulatory requirements, and best practices in transportation planning, ensuring our project effectively addresses fairness and equity in crowd-flow generation.

***Key takeaways from stakeholder meeting:***

* **Equity in Data and Modeling**

    * **Insight:** PSRC emphasized the incorporation of equity into their transportation models, following federal mandates and using specific socio-demographic metrics.

    * **Relevance:** Understanding PSRC's approach helps us refine our models to better address equity considerations, ensuring our analysis aligns with broader equity goals and regulatory standards.

* **Granularity and Interpretation Challenges**

    * **Insight:** PSRC discussed the challenges of interpreting data at different granularities, such as block groups versus census tracts.
    
    * **Relevance:** This insight underscores the importance of context in our analysis, ensuring our models accurately represent and interpret data across various geographic levels.

* **Model Optimization and Trade-offs**

    * **Insight:** PSRC highlighted the complexity of optimizing models for equity, noting that improvements in one area can lead to unintended consequences in another.

    * **Relevance:** This perspective is crucial as we balance various equity metrics within our crowd-flow generation models, considering the broader implications of our optimization choices.

* **Long-Term Projections and Demographic Forecasting**

    * **Insight:** PSRC builds activity-based crowd flow projections looking forward 50 years using current household surveys and forecasted demographic information.

    * **Relevance:** Understanding PSRC's long-term projection methods and demographic forecasting techniques can guide our approach to modeling future scenarios. This can help us better account for demographic changes over time and their impact on equity and fairness in our models.

* **Data Reliability and Equity Analysis**

    * **Insight:** PSRC measures the reliability of census data explicitly before incorporating it into their models and performs fairness analysis through upsampling and downsampling of data for six defined "equity populations." They assess transportation policies for sensitivity to metrics such as access to cars, distance to high-capacity transport, and displacement risk.

    * **Relevance:** This approach highlights the importance of ensuring data reliability and conducting targeted fairness analysis to address equity concerns effectively. Incorporating similar practices can enhance the robustness of our models and ensure that our analyses address diverse equity metrics comprehensively.


#### StreetLight

<img src="{{ site.url }}{{ site.baseurl }}/assets/img/streetlight.jpg">

Streetlight, a leader in transportation analytics, is one of our key stakeholders. Their expertise lies in leveraging data from multiple sensors and connected vehicles to provide comprehensive insights into transportation patterns. For our project, which aims to ensure fairness and equity in crowd-flow models, Streetlight's data and methodologies offer critical perspectives. Their approaches to data robustness, bias detection, and representativeness are particularly relevant as we develop theoretical frameworks and practical tools to analyze and improve the equity of transportation systems. Engaging with Streetlight allowed us to align our efforts with industry standards and incorporate cutting-edge practices into our research.

***Key takeaways from stakeholder meeting:***


* **Representativeness of Groups**

    * **Insight:** The white paper from Streetlight includes distributions based on rural vs. urban areas, race, and LBS device penetration rates. These distributions provide insights into the representativeness of different demographic groups.

    * **Relevance:** These insights are directly applicable to our work. By understanding and utilizing these distributions, we can better assess and ensure the representativeness of various demographic groups in our crowd-flow models.

* **Time Periods and Data Representativeness**

    * **Insight:** The significance of time periods for the representativeness of origin-destination data was emphasized. Time influences the data's accuracy and relevance.
    
    * **Relevance:** For our project, which utilizes weekly data, considering time periods is crucial. It affects the fairness and equity of our models, making it essential to understand and incorporate temporal dynamics.

* **Sample Penetration and Data Evaluation**

    * **Insight:** Sample penetration is a critical factor in evaluating data accuracy. Streetlight highlighted the challenges in achieving complete data coverage.
    
    * **Relevance:** Recognizing these challenges is essential for our project. By understanding sample penetration issues, we can develop strategies to ensure our models are built on representative and reliable data.

* **Privacy Concerns and Infrastructure**

    * **Insight:** The extensive infrastructure for tracking individuals raises significant privacy concerns. Streetlight noted the importance of customer-side validation to address these issues.
    
    * **Relevance:** Balancing data accuracy with privacy is crucial for our project. Ensuring that our models respect privacy while maintaining fairness and equity is fundamental to our ethical standards.

* **Sparse Data Extraction**

    * **Insight:** Streetlight's platform can extract sparse data, focusing on processing rather than statistical modeling.
    
    * **Relevance:** Handling sparse data effectively is valuable for our project. Understanding the limitations and biases in this process helps us create fair and equitable crowd-flow models.



---


### Ethics


Our ethical considerations primarily revolve around defining fairness and equity for our project and models. We have extensively reviewed literature in the field to understand various philosophies and approaches to fairness, and we have worked to align these concepts with our specific problem statement. By grounding our definitions in established theories and ethical standards, we aim to ensure that our evaluations and outcomes promote justice and equity for all communities.

Below is an example of some of the fairness and equity definitions we explored and how they translate into crow flow case.

<img src="{{ site.url }}{{ site.baseurl }}/assets/img/ethics_table.png">


