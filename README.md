# IBM Data Science Capstone SpaceX
## Applied Data Science Capstone

In this capstone, we will predict if the Falcon 9 first stage will land successfully. SpaceX advertises Falcon 9 rocket launches on its website, with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because SpaceX can reuse the first stage. Therefore if we can determine if the first stage will land, we can determine the cost of a launch. This information can be used if an alternate company wants to bid against SpaceX for a rocket launch. In this module, you will be provided with an overview of the problem and the tools you need to complete the course.

**Objetives:**
- Use data science methodologies to define and formulate a real-world business problem.
- Use your data analysis tools to load a dataset, clean it, and find out interesting insights from it.

**Methodology:**
- Data collection methodology: API & Web Scraping
- Perform data wrangling
- Perform exploratory data analysis (EDA) using visualization and SQL
- Perform interactive visual analytics using Folium and Plotly Dash
- Perform predictive analysis using classification models


**Conclusions:**

The model from this report can predict with an **83,3%** of accuracy when SpaceX will successfully land the 1st stage booster.

This results can help SpaceX to reduce costs, sacrificing $15+ million predicting and reusing the 1st stage booster.

*Technicities:*
- As the flight number increases, the first stage is more likely to land successfully.
- The highest success rates were reported for the ES-L1, GEO, HEO, and SSO orbits. 
- Heavy payloads (higher than 9000) report positive landing rates for LEO, ISS and PO orbit.
- Launch success rate is increasing significantly since 2013.
- Launch sites are close to the Equator lane and to the cost (logistic and security issues?).
- KSC LC-39A presents the most successful launches from all the sites (41,7%).
- Highest booster landing success rate obtained when Payload  < 5000 kg.
