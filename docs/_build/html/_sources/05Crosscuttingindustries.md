# 5 Cross-cutting energy industries and technologies

## 5.1 Energy efficiency and demand-side management

Energy efficiency is considered in all demand sectors in the model to varying degrees depending on the opportunities identified in each sector. End-use energy efficiency is considered in three ways, namely through:

- Technology efficiency, for example if the energy efficiency of a standard electric geyser improves;
- Technology or process change, for example if CFLs are replaced by LEDs for more efficient lighting; and
- Energy service demand reduction, for example if residential heating demand reduces due to installation of insulation.

**All demand-side technologies included in the model are assigned an efficiency.** These efficiencies are end-use, technology, and sub-sector specific and can vary over time in response to technology improvements that occur as a result of general technology learning, or through direct policy intervention. They can therefore be adjusted depending on the energy efficiency gains anticipated in a scenario and are specified exogenously in each scenario.

The exogenously specified levels of energy efficiency take into account policies such as the National Energy Efficiency Strategy (NEES) and the Green Transport Strategy. In all cases it is assumed that mandated minimum energy performance standards are achieved and applied in the reference case.

Demand response (DR), where a consumer changes their load profile shape to balance demand on the grid, is currently not considered in the model. Demand response aggregation can act as a virtual power plant and is therefore an attractive way of balancing supply and demand on the electricity grid. Demand response can be achieved through a forced intervention, for example using geyser control devices, or through voluntary means for example through time of use tariffs. It is possible to allow some endogenous shifting of the profile of specific technologies within the model, however the degree to which consumers may respond to incentives is currently not known, and the parameterisation of DR response is therefore difficult.

## 5.2 Distributed electricity generation and consumption

**Distributed Generation (DG), especially from Photo Voltaic (PV) systems has grown aggressively over the past years particularly as a source of electricity for the residential sector.** Components of Solar systems (Inverters, Photovoltaic cells, and batteries) were imported by South Africa at consistently increasing rates from the first quarter of 2021 to the second quarter of 2023. Over this period, the value of quarterly imports of these components increased from just over $100 million US Dollars in the second quarter of 2021, to just over 1.7 billion US Dollars, in the second quarter of 2023, a 16-fold increase (Figure 10).

![alt text](image-13.png)*Figure 10: Imports to South Africa of solar PV and storage components over time (SALGA, 2023)*

Uptake of this stock has almost certainly been driven by the same factors across all major sectors of the economy, and include:

- **Rising price of grid electricity** relative to the costs (fixed capital and marginal costs) of PV systems. (see for example Borenstein, 2017, Chesser, et al, 2018). Electricity prices, as a whole, have increased at a rate that has consistently been above CPI. For example, Eskom’s aggregate standard tariffs had increased by 408% by the end of 2023, as against an increase of 196% for the CPI basket of goods over the same period. Against this, costs of the elements in PV systems have been falling (see for example Feldman et al, 2023), and, once installed produce electricity at very near to zero marginal cost.
- **Diminishing hours of grid electricity supply** due to steadily longer hours of loadshedding, which disrupt businesses and households. Within this context the largely uninterrupted flow of energy from PV systems has become even more relatively attractive, and, without a doubt, has driven both commercial and industrial concerns, and households, to adopt Solar PV.

**Among the total Distributed Generation installed in South Africa, the Residential Sector** was estimated by SAPVIA (the South African Photovoltaic Industry Association) to account for 621 MWp (megawatts at peak production) of a total national PV peak production capacity of 5 659 MWp by the end of the third quarter 2023 which is the latest period for which this data is currently available. SAPVIA currently estimates, based on extrapolation, that this has increased to 954MWp, however, acknowledges wide bands of uncertainty around this figure.

Many residential PV systems are unregistered with municipal authorities; the City of Cape Town, for example, estimates that only 50% of residential PV systems have applied for registration, are being processed for registration, or have been registered, with SAPVIA also expressing a great deal of uncertainty. Given this, it is difficult to have certainty about the amount of battery storage (MWh) compared to PV generating capacity (MWp) in residential PV systems in South Africa. However, SAPVIA use a confidence interval of a ratio of residential generation to storage of between 1:1 and 1:1.5. Employing these ratios as lower and upper bounds yields an estimate of residential Battery Energy Storage Systems (BESS) installed in South Africa for the first quarter of 2023 of between 621 MWh and 931.5MWh, and between 954 MWh and 1 431 MWh at present, although there is greater uncertainty about the figures for the status at present.

**Going forward, it is likely that the relative cost of grid supply, as well as the quality (for example, incidence of voltage spikes from stressed medium voltage network infrastructure) and quantity of that supply (hours of loadshedding) will remain important drivers of PV adoption**. One factor is the increasing adoption of PV systems by developers and owners of blocks of flats. Large developments of blocks of flats, from lower income developers to developers targeting middle to slightly higher income brackets now build their developments to include PV systems. Partly this is to comply with current building regulations, specifically SANS 10400XA, and Green Building Standards, such as EDGE. Forecasts of residential PV uptake will need to include this as a material factor.

**A further consideration will be market saturation of PV systems beginning to interact with the capital cost of those systems more meaningfully**. Efforts are underway across the industry, and this project, to assess this using industry reports and other data resources, such as satellite imagery. Nevertheless, the extent to which the strong growth in residential PV installations will continue is uncertain.

**Commercial & Industrial Distributed Generation (DG),** accounted for 3 174 MWp out of 5 659 MWp of PV system energy in South Africa by the end of the first quarter of 2023 (the most recent data available at time of writing. This is just over 56% of total PV capacity, indicating how important commercial and industrial clients have been for PV system uptake in South Africa.

**Increased uptake of distributed solar PV systems is captured in the model for each sector individually**. It is possible to extend this to the sub-sector level where appropriate. PV uptake is captured at this level to allow for differences in the capital costs, largely driven by installation costs, and capacity factors. Within the model all sector investments in PV systems have a higher capital cost than grid based PV systems, however they provide electricity directly to the sectors and do not see the transmission losses that all grid-based generation sees. DG PV systems in all sectors currently have the same capacity factor, which is assumed to be lower than the capacity factor of grid PV systems.

## 5.3 Hydrogen

Hydrogen is the most abundant element in the universe. On Earth however, hydrogen comes mostly in the form of dihydrogen monoxide (water). Hydrogen is used predominantly in industries, and mostly for the production of Ammonia which is used for fertilizer production. Hydrogen is also used for refining petroleum products – notably for reducing the sulphur content of diesel (WHA International, 2023 – see Figure 11).

![alt text](image-14.png)Figure 11: Current global uses of hydrogen (WHA International, 2023)

Globally, natural gas reforming is the most economical and widely used method to produce hydrogen. This process involves mixing natural gas with high temperature steam to produce a syngas consisting of hydrogen, CO, and CO2. In South Africa however, the majority of hydrogen production is located at SASOL’s synthetic fuels and chemicals production facilities, and coal (not natural gas) is the main source of hydrogen (Bergh et al., 2022).

**Outlook for hydrogen technologies**

There is recent interest worldwide in the applications of technologies utilising hydrogen that is produced from electrolysis of water using renewable electricity, called ‘green hydrogen’. Hydrogen can be used as an energy carrier, or as it is in most cases today, a chemical feedstock.

Green hydrogen production has the potential to decarbonise the carbon intensive **chemicals** industry, the **steel** industry, industries with high temperature requirements, and potentially some applications in **transportation** either with hydrogen directly (using a fuel cell), or with synthetic fuel produced with biocarbon and hydrogen. Hydrogen once produced, can be stored as a form of **energy storage** and later turned back into electricity (or heat) – potentially aiding a power system with large amounts of renewable electricity generation.

**Hydrogen in SATIM**: There are several sectors, processes, and commodities linked to the use and production of hydrogen. The table below lists all the sectors and processes currently in SATIM that either produce, use, or are related closely to hydrogen, now and into the future, as shown in

Table 4: Current and future hydrogen processes included in SATIM

| Sector in SATIM | Process | Current or future capacity | Comment |
| --- | --- | --- | --- |
| Chemicals - ammonia | Ammonia production from gas feedstock | Current | linked to SASOL |
| Ammonia production from coal feedstock | Current | linked to SASOL |
| Ammonia production using Hydrogen | Future |     |
| Chemicals - methanol | Methanol production from gas feedstock | Current | linked to SASOL |
| Methanol production from hydrogen and carbon | Future | Inputs are green hydrogen, and carbon from direct air capture, or CCU |
| Chemicals – overall | Generic heat requirement for chemical industry processes using coal and gas | Current | Most heat requirements in the chemicals industry today are met with coal, and gas |
| Generic heat requirement for chemical industry processes using hydrogen | Future | Hydrogen can provide high grade heat |
| Iron and Steel | Hydrogen based Direct Reduction of Iron (DRI) for steel production | Future | Large scale worldwide investment is currently flowing into developing this technology. This technology is largely based off a natural gas process of DRI. |
| Mining | Generic heating requirement using hydrogen | Future |     |
| Non-metallic minerals | Generic heating requirement using hydrogen | Future | Mostly this is for unproven brick kilns that require high temperatures |
| Generic industry other | Generic heating requirement using hydrogen | Future |     |
| Synthetic aviation fuel | Production of aviation kerosene from hydrogen and carbon | Future | This is Fischer-Tropsch based process, with hydrogen, and carbon from air capture or CCU. |
| Hydrogen for vehicles | Hydrogen fuel cell vehicles for commercial heavy duty vehicle, and for some public passenger busses | Future | A myriad of vehicle options for different freight categories, mostly fuel cell based |
| Hydrogen production | Large scale centralised hydrogen production using PEM electrolysers | Future |     |
| Large scale centralised hydrogen production using alkaline electrolysers | Future |     |

