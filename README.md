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
