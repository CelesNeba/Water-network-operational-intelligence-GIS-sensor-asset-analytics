# Water-network-operational-intelligence-GIS-sensor-asset-analytics
GIS + sensor analytics project for detecting water leaks, mapping asset risk, and building operational dashboards for utility decision-making.

### Project overview

This project demonstrates an end-to-end geospatial and data analytics workflow for a water utility network. It combines sensor data, GIS asset information, maintenance records, and operational events to generate actionable insights for network monitoring, leak detection, and asset risk management.

The objective is to simulate how modern water utilities use data to move from reactive maintenance to proactive, data-driven decision-making.

### Business context

Water utility networks are large, distributed, and ageing infrastructures that rely on a mix of physical assets and real-time monitoring systems.

In practice, operational teams face several challenges:

- Leak and burst detection is often reactive rather than predictive
- Sensor data is high-volume but underutilised
- Asset failure risk is not proactively prioritised
- Operational datasets exist in silos (GIS, sensors, maintenance systems)
- Resource allocation is not always optimised spatially
- Customer impact is not fully quantified geographically

These challenges result in increased operational cost, service disruption, and delayed response times.

### Problem statement

Water companies lack a unified analytical approach to:

- Detect anomalies in sensor pressure and flow data
- Identify spatial clusters of leaks and bursts
- Quantify risk at the asset (pipe) level
- Understand customer and infrastructure impact of failures
- Prioritise maintenance based on evidence rather than reactive reporting

  ### Project objectives

The goal of this project is to design a data-driven operational intelligence framework that enables:

#### 1. Sensor-based anomaly detection
- Identify abnormal pressure behaviour in near real-time
- Flag potential leak events using statistical thresholds and trend analysis
- Detect early warning signals before failure escalation

#### 2. Geospatial analysis of network failures

- Map historical leak and burst events
- Identify spatial hotspots and clustering patterns
- Analyse pressure zones and geographic vulnerability

#### 3. Asset Risk Scoring

- Develop a risk model for water assets based on:
- Asset age
- Material type
- Historical failure frequency
- Local pressure conditions
- Environmental exposure
- Produce a ranked list of high-risk infrastructure

#### 4. Operational impact assessment

- Estimate customer impact per incident
- Identify proximity of failures to critical infrastructure (e.g. hospitals, schools)
- Highlight high-impact zones within the network

#### 5. Decision support dashboarding

- Build an interactive Power BI dashboard for operational teams
- Provide KPI-level visibility of network health
- Enable spatial exploration of leaks, assets, and risk zones

### Data sources (Synthetic / simulated)

To replicate a realistic utility environment, multiple interconnected datasets are generated:

- Sensor readings: Pressure and flow readings over time
- Water assets: Pipes, materials, installation year, location
- Leak events: Recorded bursts and failures
- Repair logs: Maintenance activity and response time
- Customer complaints: Service disruption reports
- Weather data: Environmental conditions influencing failures
- Pressure zones: Operational segmentation of the network
- Critical infrastructure:  Hospitals, schools, and key sites

All datasets are structurally linked via spatial and relational identifiers.

### Methodology

The analysis follows a structured workflow:

#### 1. Data engineering
- Data cleaning and validation
- Handling missing values and inconsistencies
- Standardisation of time-series sensor data
- Integration of spatial and non-spatial datasets

#### 2. Exploratory data analysis (EDA)
- Pressure trend analysis
- Leak frequency distribution
- Asset age vs failure correlation
- Temporal patterns in bursts and complaints

#### 3. GIS analysis
- Spatial joins between assets, sensors, and incidents
- Hotspot detection of leak clusters
- Buffer analysis around critical infrastructure
- Zone-based aggregation of network performance

#### 4. Feature engineering
- Leak probability indicators
- Asset risk scoring variables
- Aggregated sensor anomaly features
- Environmental exposure factors

#### 5. Operational analytics
- Identification of high-risk zones
- Ranking of critical assets
- Customer impact estimation
- Network vulnerability assessment

#### 6. Dashboard development
- Power BI dashboard design for operational users
- KPI visualisation and filtering
- Map-based exploration of network health
- Trend and anomaly tracking


### Key outputs

#### 1. Leak detection insights
- Sensors exhibiting abnormal pressure behaviour are flagged
- Early warning indicators of potential pipe failure are identified

#### 2. Spatial hotspot maps
- Geographic clusters of leaks and bursts are visualised
- High-risk zones within the network are identified

#### 3. Asset risk ranking
- Water infrastructure is ranked by predicted failure risk
- Prioritisation list for maintenance planning is generated

#### 4. Customer impact analysis
- Estimated number of affected customers per incident
- Identification of high-impact failure zones

#### 5. Executive Dashboard

An interactive Power BI dashboard providing:

- Network health overview
- Leak and burst monitoring
- Asset risk distribution
- Geographic hotspot visualisation
- Operational performance KPIs

#### Tools & technologies
- Python (Pandas, NumPy)
- GeoPandas (Spatial Analysis)
- Matplotlib / Seaborn (Visualisation)
- Power BI (Dashboarding)
- GIS concepts (Buffers, Hotspots, Spatial Joins)

### Key insights (Expected)

- Leak events are spatially clustered rather than randomly distributed
- Older assets show significantly higher failure probability
- Pressure instability is a leading indicator of bursts
- Certain zones consistently contribute disproportionately to network failures
- Combining sensor + GIS data significantly improves operational visibility

### Business value

This type of analytics enables water utilities to:

- Reduce reactive maintenance costs
- Improve leak detection speed
- Prioritise infrastructure investment
- Reduce customer disruption
- Improve regulatory reporting quality
- Transition toward predictive asset management

Project Structure
- data/
- notebooks/
- powerbi/
- outputs/
- docs/
- README.md

### Disclaimer

This project uses synthetic data only and is intended for educational and portfolio purposes. It is inspired by real-world challenges faced by UK water utilities.

### Author
- Neba Celestine Che
- Geospatial & Data Analytics Project
- Focus: GIS, Sensor Analytics, Operational Intelligence
