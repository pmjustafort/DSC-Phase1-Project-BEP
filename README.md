# **Aviation Recommendations**

## **Authors**:
Bobby Daly, DS; Em Jager, DS; and Paul Justafort, DS.

![image](https://github.com/pmjustafort/DSC-Phase1-Project-BEP/assets/137816262/b10f9a2d-5783-4c77-a521-64094b1e16ce)

## **Overview**
Our project involves analyzing aviation data from the National Transportation Safety Board (NTSB) aviation accident database, which contains information spanning from 1962 to 2022. By leveraging this rich dataset, our objective is to gain insights and knowledge that will inform decision-making processes in the aviation industry. We aim to assess trends, patterns, and key factors related to aviation accidents over the past six decades. Through this analysis, we will identify recurring themes, risk factors, and areas of improvement to enhance aviation safety and operational practices. 


## **Business Problem**
Our newly established company, BEP Aviation, is entering the aviation industry, specifically in the purchase and operation of airplanes. In embarking on this exciting venture, we understand the paramount importance of prioritizing safety and establishing a reliable and secure operation right from the outset. Recent aviation incidents, such as the Boeing 737 MAX crisis triggered by the crashes of Lion Air Flight 610 and Ethiopian Airlines Flight 302, have underscored the critical significance of safety in aviation operations. To ensure long-term success and sustainability, we are committed to implementing robust safety practices and procedures that prioritize the well-being of passengers, crew members, and all stakeholders involved. By thoroughly exploring and analyzing decades of aviation data, we aim to make informed decisions that further enhance our commitment to safety and operational excellence.

## **Data**
![image](https://github.com/pmjustafort/DSC-Phase1-Project-BEP/assets/137816262/c91e6b81-8c9d-4672-8a37-ebf45d3cace7)

The data utilized in this project are sourced from the National Transportation Safety Board (NTSB) aviation accident database. We narrowed this data down to approximately 85,000 aviation accidents recorded between 1980 and 2022 in the United States. This comprehensive dataset provides a rich resource for analyzing and exploring various aspects of aviation safety and accident patterns over a significant timeframe. Our main goal is to minimize the risk of your company experiencing a worst-case scenario, a fatality in an aviation accident. To do this, we focused on the relationship between fatalities and airplane make, engine type, and region of flight.

## Methods
We utilize the summation method to calculate the total sum of relevant values. Additionally, we harness the robust technique of time series analysis to explore and analyze the temporal patterns, trends, and relationships within aviation data over a specific period. This comprehensive approach allows us to gain valuable insights into the evolution and dynamics of the aviation industry.

## **Data Understanding**
Mitigating accidents is important, but when they do happen, fatalities represent the worst-case scenario. To ensure comprehensive insights and facilitate proactive risk mitigation, we have diligently filtered and thoroughly analyzed the available dataset. Our analysis focuses on examining the intricate relationship between fatalities and critical variables, including airplane make, engine type, and region of flight. By meticulously exploring these factors, we aim to uncover valuable patterns and trends that can empower your business to make informed decisions, enhance safety protocols, and effectively minimize potential risks and incidents.

## Results
**Fatalities Associated with Each Specific Airplane Make.**

In analyzing the airplane make, summation analysis simply showed that some Makes have large amounts of fatalities. 

![Fatalaties by Make (Summation)](https://github.com/pmjustafort/DSC-Phase1-Project-BEP/assets/137816262/aef42ed4-57c5-4e64-92ca-65a9f72acd16)


However, once we plotted this over time, we observed that certain Makes, despite having a significant number of fatalities over the past 40 years have exhibited a consistent decrease in those numbers.

![Fatalities by Make (Line)](https://github.com/pmjustafort/DSC-Phase1-Project-BEP/assets/137816262/4723356c-b053-44b2-b1c8-4e29f5d5b1b1)

**Fatalities Associated with Engine Type.**

In our analysis, we focused on the two most prevalent engine types in the dataset: the Reciprocating engine and the Turbofan engine. The Reciprocating engines exhibited a higher number of fatalities compared to Turbofan engines. However, they were also much more widespread across different airplane makes. Notably, we observed a downward trend among airplane makes utilizing reciprocating engines, indicating a decrease in fatalities over time. On the other hand, fatal accidents involving Turbofan engines were sporadic before 2005, but a consistent decrease in fatal accidents was observed thereafter. This trend may be attributed to the widespread popularity of Turbofan engines, potentially driving engineers to refine and perfect this engine type, resulting in improved safety measures and a reduction in fatal accidents.


![Fatalities by Engine Type](https://github.com/pmjustafort/DSC-Phase1-Project-BEP/assets/137816262/e496b9fe-3c04-4ebe-861b-a45d1ef12353)


**Fatalities By US Region.**

Upon grouping the states by region, we observed distinct patterns regarding fatalities. The Southwest and Northeast regions stood out with the fewest recorded fatalities, while the Southeast and West regions exhibited the highest number of fatalities.

![Fatalaties by Region (Summation)](https://github.com/pmjustafort/DSC-Phase1-Project-BEP/assets/137816262/838d1360-773e-4258-bbf2-48fdae0741c2)

 
## **Conclusions**
Based on the analysis conducted in this project, the following observations can be made:

Airplane Make: By examining the decrease in fatalities over time as an indicator of improved airplane safety, Cessna and Piper stand out. Despite having higher numbers of fatalities from airplane crashes compared to other airplanes, both Cessna and Piper have shown a consistent decline in fatalities since 1980. This trend suggests advancements in the safety of their planes.

Engine Type: Reciprocating and Turbo Fan engines have been associated with the highest number of fatalities from airplane crashes. However, it is important to note that these engine types are widely used, particularly Turbo Fan engines in commercial airplanes. Analyzing the data over time reveals a decline in fatalities, indicating potential technological advancements and improved safety. Notably, Turbo Fan engines have consistently demonstrated very low fatalities since 2005, highlighting their reliability and safety record.

U.S. Region of Flight: Our analysis reveals that the Northeast region has exhibited relatively lower numbers of fatalities from plane crashes compared to other regions. With major international and domestic air travel hubs in cities like New York, Boston, and Washington, D.C., the Northeast region is a significant market for air travel and offers potential investment opportunities.

These findings highlight the positive trends in airplane safety, particularly in the context of specific airplane makes, engine types, and U.S. regions of flight. They provide valuable insights for industry stakeholders, enabling them to make informed decisions regarding airplane selection, engine choices, and investment considerations.

## **Next Steps**
Based on the project findings, there are several potential next steps to further enhance the analysis of airplane safety and investment. These steps include:

Gathering Additional Data: To make the recommendations more robust, it would be beneficial to obtain more data on the market share of each make of airplane. This would provide greater certainty in determining if a higher rate of fatalities is due to inherent safety issues or simply a result of a larger number of planes of that make in service.

Comparing Fatalities to Successful Flights: By comparing the number of successful flights of each company to the crash data, we can identify types of airplanes that are underrepresented in the crash data, indicating exceptional safety records. This analysis would help highlight specific aircraft options that have a strong track record of safety.

Exploring Weather Patterns: Incorporating data on weather patterns by region could provide insights into how different weather conditions may impact the number of plane crashes. This analysis would contribute to understanding whether certain regions have lower crash rates due to more favorable weather conditions.

Considering Flight Types: Expanding the analysis to include more variation in the types of flights, such as commercial or private, and the size of airplanes, would help refine recommendations for entering the aviation industry. This would allow for tailored insights based on the specific flight contexts and aircraft types.

By pursuing these next steps and further exploring the suggested variables, the analysis of airplane safety and investment could be strengthened, enabling more informed decision-making for companies in the aviation industry.

## Further Details

Further details are available in the full analysis presented in the Jupyter Notebook, as well as our interactive [Interactive Tableau Dashboard](https://public.tableau.com/authoring/Daly_Phase1_Project/Dashboard1#1). The Tableau dashboard provides a comprehensive visual representation of the data, allowing for deeper exploration and analysis.

## **Repository Structure**

