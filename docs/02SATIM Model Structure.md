# 2. SATIM Model Structure 

The South African TIMES Model (SATIM) is described as a **full sector, national energy system optimization model**. It aims to address the planning problem of meeting projected future energy demand by considering the least-cost energy mix and investment plan over a specific planning horizon. SATIM utilizes a **linear optimization algorithm** to derive the technology and fuel mix that will minimize the total discounted system costs over the planning horizon, subject to imposed constraints,such as CO2 emission limits, reliability constraint limits, and operational limits, among others.


 ## 2.1. General Model Structure 

![Alt text](image-3.png)*Simple Schematic of the South Africa Times Model.*

Within SATIM, there are three supply sectors **(electricity and liquid fuels)** and five demand sectors **(industry, agriculture, residential, commercial, and transport)**.

 Each sector undergoes further disaggregation into appropriate subsectors. This detailed representation of both supply and demand sectors explicitly captures the impact of structural changes in the economy, such as varying sector growth rates, process modifications, fuel and mode switching, and advancements in technology and efficiency gains. SATIM governs each demand sector through a set of parameters and general assumptions. These include considerations for the sector's structure and energy service needs, the base-year demand for energy by fuel type, technical and cost parameters of available technologies, and the forecasted demand for energy services over the planning horizon.

 ## 2.2 Sets

Sets are responsible for defining the structure of the model (i.e., temporal space, geographic space, elements of the system etc.) In SATIM, the groups of sets include: years, fuels, technologies, emissions and modes of operation. These sets are characterised by parameters that are further explained below.

### 2.2.1 Year
The model planning horizon spans from **2012 (the base year) to 2050** . The base year replicates South Africa’s energy system in **2012** and **2017**. Data in the past is set according to historical information.

### 2.2.2 Fuels 
*Table 2.1: Summary of fuels included in the SATIM model*

### 2.2.3 Technologies 
*Table 2.2 Summary of technologies included in SATIM energy model.*

### 2.2.4 Emissions 
*Table 2.3 Summary of emissions included in SATIM*

| Abbreviations  | Description             |
| ---------------| ------------------------|
| NOX            | Nitrogen Oxides         |
| SOX            | Sulphur Oxides          |
| CO2            | Carbon Dioxides         |
| CH4            | Methane                 |
| CO             | Carbon Monoxide         | 
| NMVOC’s        | Non-methane volatile organic compounds|
| PM10           | Particulate Matter (10 microns or less) |


### 2.2.5 Mode of operation
The model has 1 mode of operation, for representing the normal operation of the system.

### 2.2.6 Region
The model has a nationwide scope, therefore it only has **one** region: South Africa.

## 2.3 Energy Supply Disaggregation 

The energy supply in SATIM is disaggregated into various components to comprehensively capture the complexities of the South African energy system. The disaggregation includes the extraction of primary resources, production of electricity and liquid fuels, as well as imports of electricity, oil, and other liquid fuels products. Coal exports, electricity exports, and overproduction of liquid fuels are also considered within the energy supply sector 

In the power sector, the representation encompasses the generation, transmission, and distribution components, with a detailed modeling of operating power plants, including their decommissioning schedule, planned new builds, retrofits, and technology characteristics such as efficiency and capacity factors. The individual representation of power plants allows for the incorporation of expected decommissioning schedules, planned retrofits, and technology characteristics, providing a detailed view of the power sector within SATIM.


Additionally, the supply mix includes the role of renewables in transitioning the electricity generation mix, reflecting the potential for a transition towards renewables and the utilization of resources such as solar and wind for electricity generation.

## 2.4 Demand Sector Disaggregation

### 2.4.1 Transport

The transport sector in SATIM is represented as a multi-time, multi-sector, bottom-up model that captures the energy demand and supply dynamics specific to South Africa. The sector includes various modes of transportation, such as road, rail, air, freight, and pipeline, as well as specific technologies for each transport type. Given that the transport sector is driven primarily by vehicle-kilometers traveled and the efficiency of travel, SATIM's representation incorporates detailed disaggregated information regarding passenger and freight transport by road, rail, pipeline, and aviation.

Additionally, the detailed representation of transport technologies in SATIM includes specific classifications like Bus Rapid Transport (BRT), Metropolitan Transport (Metro), as well as internal combustion engine and battery electric road vehicles

### 2.4.2 Industrial

The following subsectors are included in the industrial sector:

- **Mining**
- **Chemicals**
- **Food, beverages, and tobacco**
- **Precious and non-ferrous metals**
- **General manufacturing** 

These subsectors encompass a diverse range of industrial activities and energy service needs. Two different approaches are applied to model industrial energy consumption within SATIM.

 The first approach, referred to as **Methodolody 1**, is applied to subsectors such as mining, chemicals, food beverages and tobacco, precious and non-ferrous metals, and general manufacturing. This approach relies on estimates of energy service needs and their efficiency at which energy services are met.
 
  The second approach, **Methodology 2** two, is applied to specific subsectors such as Iron and Steel, Ferroalloys, Aluminium, Non-metallic minerals, and pulp and paper. In this approach, final energy demand is calculated based on the energy intensities specific to technology processes and their level of production.

### 2.4.3 Residential

The residential sector in SATIM is disaggregated based on parameters such as income levels, electrification status, and specific energy service demands pertaining to cooking, water heating, space heating, refrigeration, lighting, and other electrical services. The disaggregation reflects the diversity in energy access, the use of multiple fuels within households to provide the same energy service, fuel subsidies, and technology efficiency.

Furthermore, the representation includes high, medium, and low-income electrified households, as well as medium and low-income non-electrified households. The demand for energy services within the residential sector is governed by specific drivers such as population, household income, and electrification rate.

### 2.4.4 Commerical

The commercial sector in SATIM is represented through the inclusion of energy use by various sub-sectors such as **wholesale, retail, motor trade services, accommodation, finance, real estate, business services, and government**.

The estimation of commercial sector demand for energy services is based on several factors, including the assumed energy intensity of energy services per unit area, the growth in floor area over time, and improvements in energy efficiency due to building code regulations.

Furthermore, SATIM's representation of the commercial sector factors in **total commercial floor area**, estimated to be around 88 million square meters in 2012, with growth projections based on the correlation between changes in floor area and real GDP.

### 2.4.5 Agriculture

The agricultural sector in SATIM is represented by capturing the demand for energy services specific to this sector and is driven by sectoral GDP, reflecting the energy-intensive activities and processes involved in agriculture. The representation includes subsectors such as irrigation, heating, processing, traction, and other agricultural activities, each with distinct energy demands.

The useful energy (UE) demand, which pertains to the demand for energy services, is exogenously specified, and projections for UE demand to 2050 are calculated based on the anticipated growth of primary drivers such as population, GDP, industrial sector production, and agricultural production. These drivers have a significant impact on the energy demand within the agricultural sector.



Information on Data Inputs is avaliable [here](/docs/source/05Data%20Inputs.ipynb).

