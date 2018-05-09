# DRCF
Rainfall forecasting is a very important problem in the field of hydrology and meteorology. Especially, short-term rainfall forecasting is closely related to resident's daily life. For example, forecasting the situation of stagnant water on the road, providing weather guidance for the flight, and providing short-term heavy rainfall warning in the city.However, existing solutions achieve low prediction accuracy for short-term rainfall forecasting. Numerical forecasting models can achieve overall accuracy but always perform worth in some short-term conditions. Data-driven approaches always neglect the influences of physical factors in upstream or downstream regions, which lead to the forecasting accuracy fluctuates in different areas. Rainfall forecasting is affected by many factors, such as high-altitude physical factors and surface factors.High-altitude physical factors play important roles in the movement of rainfall system. Surface factors on the Earth also cause different rainfall. Difference surface factors represent different factors between region and surrounding area. Therefore, it is very reasonable to forecast rainfall by studying the relations between high-altitude physical factors, surface factors and rainfall. In this project, a Dynamic Regional Combined short-term rainfall forecasting model (DRCF) using Multi-Layer Perceptron (MLP) is proposed. The input of the model includes five high-altitude factors and seven different surface factors. In summary, we have addressed a series of techniques challenges in this work, and the central contributions are summarized as follows: 1.Principle Component Analysis (PCA) is used to determined the input of of MPL and a special greedy algorithm is proposed to determine the suitable structure of MLP. 2.The relation between forecasting area and surrounding area is established using MPL. Based on the relation, a dynamic regional combined rainfall forecasting model is proposed. The strategy of dynamically adjusting area is also enhanced to effectively improve prediction accuracy. 3.The model is finally validated by a large number of meteorological site data, including 56 sites, and these sites are distributed in all parts of China.