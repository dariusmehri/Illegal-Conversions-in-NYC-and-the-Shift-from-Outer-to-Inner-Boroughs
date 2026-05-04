## Illegal Conversions in NYC: The Shift from Outer to Inner Boroughs (1990s-Present)
Illegal conversions are unauthorized alterations to a building—such as turning basements, attics, or single-family homes into multiple apartments—without approval from the New York City Department of Buildings, and often in violation of safety regulations. These conversions frequently create overcrowded, substandard living conditions with unsafe electrical systems, inadequate ventilation, and blocked or insufficient exits. They also produce layouts that are unknown to responders from the Fire Department of the City of New York, delaying emergency response and increasing risk during any incident—not just fires, but medical emergencies, structural issues, and other hazards. Compromised living conditions significantly elevates the likelihood of serious injury or death, making illegal conversions a critical indicator when identifying high-risk buildings [1].

Illegal conversions have become a critical issue in New York City due to their direct connection to housing affordability pressures and their significant implications for fire and life safety. As demand for housing has outpaced supply, particularly in lower-density and gentrifying neighborhoods, property owners and tenants have increasingly created unpermitted units within existing buildings, often in structures not designed for additional occupancy [2]. 

Enforcement is largely complaint-driven, with the majority of cases identified through 311 reports, FDNY incident responses, and follow-up inspections by the Department of Buildings, meaning that many hazardous conditions may remain undetected until they generate complaints or emergencies [3].

The data for this project consist of New York City Department of Buildings ECB violations, filtered for hazardous illegal conversions, and the Department of City Planning PLUTO dataset sourced from NYC Open Data and analyzed using Python, Power BI, and generative AI to clean and visualize insights [5][6].

### The Shift from Outer to Inner Boroughs
Illegal conversion violations shifted from outer boroughs like Queens in the 1990s to inner boroughs like Brooklyn and Manhattan by the 2010s due to rising housing costs, gentrification, and stronger enforcement in dense areas. Earlier, conversions were easier in low-density neighborhoods with one- and two-family homes, while later they became more common in high-demand areas where landlords had greater financial incentive to create additional units within existing buildings. At the same time, agencies like the New York City Department of Buildings increasingly focused on higher-risk, higher-density environments, making illegal conversions both more prevalent and more visible in the inner boroughs [4].

#### 1990s
In the 1990s, illegal conversion violations were overwhelmingly concentrated in Queens (87.7%), with much smaller shares in Brooklyn (6.2%) and The Bronx (5.8%), and almost none in Manhattan and Staten Island (0.1%). This pattern reflects how illegal conversions at the time were largely driven by the abundance of one- and two-family homes in Queens, where it was easier to subdivide properties to meet growing housing demand, while denser boroughs saw far fewer such violations.

<img width="1068" height="646" alt="image" src="https://github.com/user-attachments/assets/e02ea5d9-47be-4765-80fc-3fcb00f79ea8" />

The majority of affected buildings in the 1990s were one- and two-family homes and walk-up apartments, accounting for roughly 74% of cases, highlighting the role of structurally adaptable, lower-density housing in enabling informal unit expansion (see below image). Walk-up apartments in particular were attractive targets because units could be subdivided at relatively low cost by leveraging existing plumbing lines, electrical systems, and stacked layouts, avoiding the need for major structural alterations. 

Building age further reinforces this pattern, with approximately 45% of properties constructed before 1939 and nearly 70% built prior to 1960. These older structures, not designed for modern occupancy or infrastructure demands, were particularly vulnerable to unsafe modifications. Taken together, the data suggests that illegal conversions during this period were not isolated incidents, but rather a broad, systemic response to housing demand, concentrated in aging residential stock and carrying significant implications for fire and life safety.

<img width="1324" height="575" alt="image" src="https://github.com/user-attachments/assets/050543ba-386f-468d-b2ef-22643661717e" />





#### 2000s
In the 2000s, illegal conversion violations remained concentrated in Queens but declined to 64%, while Brooklyn rose sharply to 23.6%, with smaller shares in The Bronx (6.3%) and Manhattan (4.6%), indicating a clear shift from an almost exclusively Queens-driven pattern in the 1990s toward broader distribution across denser boroughs as housing demand and redevelopment intensified.

<img width="1065" height="657" alt="image" src="https://github.com/user-attachments/assets/ca60d968-367a-4323-9f8a-b42c6ab78100" />

While one- and two-family homes and walk-up apartments still accounted for a significant share of activity—approximately 43% in Queens—the dominance of these building types declined compared to the 1990s, indicating a gradual diversification of conversion patterns. At the same time, Brooklyn neighborhoods such as Williamsburg and Greenpoint began to appear among the top hotspots, with 17% of affected buildings consisting of two-family homes and walk-up apartments. This reflects the early stages of gentrification-driven pressure, where rising rents incentivized the internal subdivision of existing units rather than the horizontal expansion more common in Queens. 

Building age patterns further support this transition, with Queens showing a reduced share of pre-war buildings (33%), while Brooklyn’s pre-war stock (19%) provided a foundation for higher-density modifications. Overall, the 2000s represent a transitional period in which traditional outer-borough conversion patterns persisted, while new, density-driven dynamics began to take hold in emerging inner-borough markets.

<img width="1189" height="531" alt="image" src="https://github.com/user-attachments/assets/691aa709-7a9b-4a1c-b40d-3e05a80807e6" />



#### 2010s
In the 2010s, illegal conversion violations shifted decisively to the inner boroughs, with Brooklyn (35.5%) and Manhattan (26.5%) overtaking Queens (23.4%), while The Bronx accounted for 10.6%. This reversal from the 2000s was driven by rising rents, gentrification, and stronger enforcement in dense, high-demand areas, alongside the growth of short-term rental platforms like Airbnb, which created additional financial incentives to subdivide or repurpose units—sometimes illegally—particularly in high-tourism neighborhoods, further concentrating violations in the inner boroughs.

<img width="1067" height="657" alt="image" src="https://github.com/user-attachments/assets/b3673d80-de64-4fd6-9954-c4236b9e011c" />

Illegal conversions in the 2010s reflect a clear shift toward high-density, rent-driven activity concentrated in Manhattan and Brooklyn neighborhoods, including Chelsea/Clinton, the Lower East Side, Bed-Stuy, and East New York, with Queens locations such as Flushing remaining secondary hotspots. Building class patterns show a strong presence of walk-up apartments in both Brooklyn (12%) and Manhattan (11%), alongside smaller but notable shares of two-family homes and emerging activity in elevator buildings (5% in Manhattan), indicating that conversions are increasingly occurring within larger, more regulated structures. 

This shift is reinforced by building age, with pre-war buildings (1900-1939) representing 58% of affected properties, highlighting the role of pre-war housing stock with flexible layouts and aging infrastructure. Unlike earlier decades characterized by the expansion of units in lower-density homes, the 2010s are defined by the internal subdivision and overcrowding of existing multifamily buildings, significantly increasing fire and life safety risks due to higher occupant loads and constrained egress.

image here


#### 2020s
By the 2020s, illegal conversion violations became more evenly distributed across boroughs, with Brooklyn still leading at 35.3%, but Queens rebounding to 27.6% and overtaking Manhattan (21.6%), followed by The Bronx (13%) and Staten Island (2.6%). This pattern suggests a rebalancing of housing pressure, where sustained affordability challenges and enforcement efforts have spread illegal conversion activity across both outer and inner boroughs rather than being concentrated in just one area.

<img width="1064" height="660" alt="image" src="https://github.com/user-attachments/assets/5b3f2ba2-3d88-40d0-a4c1-64c9f0745678" />

Illegal conversions in the 2020s reflect a mature and fully distributed pattern across New York City, with activity spanning Queens, Brooklyn, and Manhattan neighborhoods. While Flushing and Bay Terrace in Queens remain the leading hotspot, neighborhoods such as Bed-Stuy in Brooklyn and core Manhattan areas including Chelsea/Clinton, Midtown, and the Lower East Side also rank among the highest. 

Building class patterns show a convergence around the most adaptable structures, with two-family homes and walk-up apartments accounting for 39% of cases across boroughs, alongside emerging activity in mixed-use buildings (6.1% in Brooklyn) and store buildings (4.6% in Queens), indicating a growing extension of residential use into commercial spaces. 

This trend is reinforced by building age, with the majority of affected properties constructed between 1900 and 1939, underscoring the continued role of aging pre-war housing stock. Overall, the 2020s represent a stabilized, citywide system of illegal conversions that combines both horizontal expansion and internal subdivision, while introducing new risks associated with mixed-use and commercial building adaptations.

In the 2020s, while illegal conversions have become a more citywide issue Staten Island still shows relatively low levels of activity, largely because it lacks the dense, older, and easily subdivided housing stock that drives conversions elsewhere. Its predominance of newer, detached homes, combined with lower rental demand, weaker transit access, and fewer complaint-driven inspections, continues to limit both the occurrence and detection of illegal conversions compared to the other boroughs.

image here

### Citations
[1] https://www.nyc.gov/site/buildings/tenant/illegal-conversion.page

[2] https://www.nyc.gov/site/hpd/services-and-information/basement-and-cellar.page

[3] https://portal.311.nyc.gov/article/?kanumber=KA-02025

[4] New York's Housing Underground: A Refuge and a Resource: https://chhayacdc.org/wp-content/uploads/2019/11/New-Yorks-Housing-Underground.pdf?utm_source=chatgpt.com

[5] DOB ECB Violations, NYC Open Data: https://data.cityofnewyork.us/Housing-Development/DOB-ECB-Violations/6bgk-3dad/about_data

[6] Department of City Planning PLUTO Data: https://www.nyc.gov/content/planning/pages/resources/datasets/mappluto-pluto-change


