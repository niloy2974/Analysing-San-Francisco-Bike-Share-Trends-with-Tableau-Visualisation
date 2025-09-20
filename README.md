# Analysing-San-Francisco-Bike-Share-Trends-with-Tableau-Visualisation
This Tableau project explores San Francisco’s bike share system through interactive dashboards that analyse station-level usage, weather patterns, and customer behaviour. The story provides valuable insights for urban planners, bike share operators, and policymakers to optimise services, improve infrastructure, and enhance user experiences.
## Dataset and Tableau Visualisation
This dataset contains trip records, station details, weather conditions, and user information from the San Francisco Bay Area Bike Share program. It includes attributes such as ride duration, station-to-station routes, customer type, and daily weather metrics [Kaggle Dataset Link](https://www.kaggle.com/datasets/benhamner/sf-bay-area-bike-share). The interactive Tableau story explores bike share usage across time, weather, and user behaviour. It can be accessed here: [Tableau Visualisation Link](https://public.tableau.com/views/SanFranciscoBikeShareTrends/Story1?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
# Dashboards and Visualisations
## Weather and User Trends: Station Patterns
![Weather and User Trends: Station Patterns](https://github.com/niloy2974/Analysing-San-Francisco-Bike-Share-Trends-with-Tableau-Visualisation/blob/main/visualisations/Dashboard%20One_Weather%20and%20User%20Trends%20-%20Station%20Patterns.jpg)

This dashboard provides a comprehensive view of where, when, and how customers use bike share stations. By combining geospatial analysis, time-based patterns, and journey metrics, it helps stakeholders identify high-demand hubs, understand commuting behaviour, and differentiate between short urban trips and longer leisure rides. Collectively, these insights are valuable for optimising station placement, planning rebalancing strategies, and improving service efficiency.
### Station Map
Displays all bike stations connected by completed journeys, coloured by ride volume. This enables planners to pinpoint high-demand hubs, visualise connectivity between stations, and detect underserved areas. Businesses can also identify potential retail or café locations near high-traffic stations.
### Total Hour-based Rides from All Stations
Shows clear commuting peaks at 8 AM and 5 PM, confirming heavy office-hour demand. City transport authorities can use this insight to synchronise bike availability with public transport schedules, while operators can allocate bikes more efficiently during peak hours.
### Top Five Destinations
Highlights the most popular end stations, revealing high-demand zones such as business districts, transit hubs, or tourist attractions. This helps in prioritising station upgrades, adding parking capacity, or planning marketing campaigns around those destinations.
### Longest Five Journeys
Identifies the top routes associated with longer ride durations. These often correspond to leisure or recreational rides, offering value for tourism boards, cycling advocacy groups, and businesses catering to weekend riders.
### Key Features
![Features1](https://github.com/niloy2974/Analysing-San-Francisco-Bike-Share-Trends-with-Tableau-Visualisation/blob/main/visualisations/Features_Dashboard%20One.jpg)

Interactive filtering across all visuals allows users to select individual stations and instantly see corresponding patterns across time, destinations, and journey lengths. Hover-enabled details give precise counts and contextual data, turning raw metrics into actionable insights for decision-making.
## Weather Patterns
![Weather Patterns](https://github.com/niloy2974/Analysing-San-Francisco-Bike-Share-Trends-with-Tableau-Visualisation/blob/main/visualisations/Dashboard%20Two_Weather%20Patterns.jpg)

This dashboard demonstrates the impact of weather and seasons on bike share usage. It combines scatterplots and seasonal boxplots to highlight how factors such as temperature, humidity, wind, and visibility influence ride counts and durations. Collectively, the dashboard equips bike share operators, marketers, and city transport departments with data-driven insights to plan weather-adjusted operations, promotional campaigns, and infrastructure needs.
### Total Rides vs Different Weather Attributes
Six scatterplots show how daily rides correlate with temperature, humidity, dew point, visibility, wind speed, and gusts. For instance, higher temperatures typically boost rides, while extreme weather conditions reduce them. Operators can use these relationships to forecast demand under different weather scenarios or adjust staff allocation and bike distribution.
### Season-wise Ride Durations
Four seasonal boxplots compare ride durations, revealing that winter rides often last longer while summer rides are shorter but more frequent. This helps businesses plan seasonal promotions (e.g., winter wellness campaigns, summer commuter discounts) and informs policymakers about infrastructure needs throughout the year.
### Key Features
![Features2](https://github.com/niloy2974/Analysing-San-Francisco-Bike-Share-Trends-with-Tableau-Visualisation/blob/main/visualisations/Features_Dashboard%20Two.jpg)

All weather scatterplots and seasonal boxplots are linked, enabling multi-dimensional analysis. Filtering by season dynamically updates visualisations, while hover functionality provides precise daily ride counts and weather conditions. This allows deeper exploration of anomalies, such as unexpected dips in summer or spikes in winter.
## User Patterns
![User Patterns](https://github.com/niloy2974/Analysing-San-Francisco-Bike-Share-Trends-with-Tableau-Visualisation/blob/main/visualisations/Dashboard%20Three_User%20Patterns.jpg)

This dashboard explores differences between subscriber and casual user behaviour, offering insights into ridership growth, customer segmentation, and future trends. Collectively, it enables bike share companies to tailor marketing strategies, optimise membership models, and plan operational capacity, while also helping policymakers understand public adoption of bike share schemes.
### Forecasting of Subscription-based Rides and Average Duration
Two charts (rides and average duration) break down behaviour by subscribers and casual users. Subscribers dominate ride counts, while casual users often record longer trips. Forecasting models project future demand trends, helping operators design membership packages, estimate required fleet sizes, and plan promotional efforts to convert casual riders into long-term subscribers.
### Season-wise Hourly Rides Heatmap
Displays ride intensity across hours and seasons, with clear commuter peaks in spring and summer mornings. This allows operators to align bike maintenance schedules, station stocking, and marketing campaigns with observed usage trends. For example, promotional push notifications can be targeted during morning rush hours or seasonal tourist peaks.
### Key Features
![Features3](https://github.com/niloy2974/Analysing-San-Francisco-Bike-Share-Trends-with-Tableau-Visualisation/blob/main/visualisations/Features_Dashboard%20Three.jpg)

Forecasting capabilities provide forward-looking insights into subscription growth and trip durations, supporting strategic planning. Seasonal heatmaps combined with filters highlight granular user behaviour, while hover-enabled data points reveal exact ride counts and time distributions. Together, these features empower businesses and policymakers to act both reactively (based on current patterns) and proactively (anticipating future demand).

## Features Summary
1. **Interactive Filtering Across Dashboards:** Users can drill down by station, weather attribute, season, or user group, making the story adaptable for different stakeholders. This flexibility is crucial for city planners, marketing teams, and operational managers.
2. **Hover Tooltips with Contextual Data:** Provide detailed ride counts, station names, weather conditions, and time metrics on demand without cluttering visuals. This makes the dashboards beginner-friendly while still powerful for expert users.
3. **Forecasting Models:** Built-in projections for subscriber rides and durations help anticipate demand, allowing operators to plan resources, design subscription drives, and avoid under- or over-supply scenarios.
4. **Cross-dashboard Connectivity:** All dashboards are interconnected, meaning selections in one visual (e.g., station, season) instantly update related metrics across the board. This promotes deeper storytelling and avoids siloed analysis.
5. **Actionable Insights for Multiple Stakeholders:** From policymakers (urban planning, public transport alignment) to businesses (targeted promotions, station investment) and even environmental groups (encouraging sustainable commuting), the dashboards provide versatile, real-world applications.
