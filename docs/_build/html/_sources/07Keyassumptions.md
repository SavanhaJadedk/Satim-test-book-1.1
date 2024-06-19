# 7 Key assumptions

## 7.1 Population growth

Population growth is included in the model exogenously, the United Nations’ world population prospect probabilistic projections are used as estimates for population growth (UN, 2022). The median population growth scenario was chosen and imputed into the model. Figure 12 below represents the median population growth projections taken from the work population prospects.

Figure 12: Median population growth assumptions for South Africa (UN, 2022)

## 7.2 Economic growth

Economic growth is endogenous in the model and adjusts in response to economic “shocks”. A reference GDP growth trajectory is however, imputed into the model by adjusting total factor productivity over the time horizon. This in combination with a simple capital allocation step in the CGE will determine the base growth trajectories for each sector.

These base growth trajectories are then kept constant for all scenarios (except in cases that force higher or lower reference growth). In the short term (up to 2031) GDP growth in the CGE is calibrated to match the growth projections in the 2024 budget review’s economic outlook (National Treasury, 2024). Beyond this economic growth is assumed to gradually increase to 3.5% in the mid-2030s and then hover around this percentage to 2050.

In each scenario the CGE is exposed to various shocks which differ from the reference scenario (e.g. more investment in the power sector to achieve more CO2 emission reductions). These shocks come from processing results of the SATIM model, that is endogenously itself responding to, for example, a CO<sub>2</sub> reduction cap (‘shock’) applied to the power sector. SATIM is able to provide a more robust picture of what the power sector should look like given a particular CO2 trajectory, than the CGE would be able to achieve by itself.

In this way the model provides an estimate of the GDP impact of the CO<sub>2</sub> shock, or other policy interventions applied to the model, and in the context of other given assumptions (e.g. fixed amount of capital, a particular trajectory for FDI, a different mix of local vs imported components for the RE build-out, etc.).

## 7.3 Fuel costs

Coal costs are drawn from data on prices and contract arrangements for coal supplied to Eskom (see section 4.1.1 above).

Current and future oil, gas and liquid fuel cost estimates are derived from IEA data, with future prices dependent on future global scenarios (e.g. there is a significant different in projected oil prices under a ‘Net Zero Energy’ world relative to a ‘Current policies’ world).

## 7.4 Carbon tax

The main tax applied in SATIMGE modelling is South Africa’s domestic carbon tax, and is modelled in two ways:

- Using current tax levels, based on South Africa’s official carbon tax taking current allowances into account.
- Using projected tax levels based on government proposals for ramping up the carbon tax to internationally recommended price levels.

South Africa’s official carbon tax sits at R144 per tonne. However, after accounting for allowances the effective tax rate sits at approximately R30 per tonne. In the 2022 budget the government proposed to strengthen the carbon tax policy the government plans to raise the carbon tax rate to at least US$20/t CO<sub>2</sub> by 2026, to US$30/t CO<sub>2</sub> by 2030, and accelerating to higher levels up to US$120/t CO<sub>2</sub> beyond 2050. Thus, the two approaches to modelling the carbon tax are to (1) maintain the tax at the current levels or (2) ramp it up in accordance with the National Treasury’s 2022 proposal.

## 7.5 Emissions factors

Emissions factors for each type of emission (GHG and air pollutant) are drawn from Eskom and IPCC literature. Combustion emissions factors vary in the model by fuel type, and are summarised as follows:

Table 7: Emissions factors applied in SATIM (Units: kilotonne per PJ)

| Emission | Coal | Gas | AvGas | Diesel | Gaso-line | HFO | Kero-sene | LPG | Wood |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Carbon dioxide (CO<sub>2</sub>) | 96.25 | 56.1 | 70  | 74.0667 | 69.3 | 77.4 | 72.9 | 63.1 | 0   |
| Methane (CH<sub>4</sub>) | 0.001 | 0.001 | 0.003 | 0.003 | 0.003 | 0.003 | 0.003 | 0.003 | 0.015 |
| Nitrous Oxide (N<sub>2</sub>O) | 0.0014 | 0.0001 | 0.0006 | 0.0006 | 0.0006 | 0.0006 | 0.0006 | 0.0001 | 0.0008 |
| Sulphur gases (SOx) | 0.6262 | 0   | 0.0467 | 0.2529 | 0.0467 | 1.5291 | 0.0459 | 5.409 | 0.03 |
| Nitrogen gases (NOx) | 0.3 | 0.15 | 0.3 | 0.2 | 0.6 | 0.2 | 0.2 | 0.01246 | 0.15 |
| Carbon monoxide (CO) | 0.02 | 0.02 | 0.1 | 0.015 | 8   | 0.01 | 0.01 | 0.182 | 2.6 |
| Non-methane volatile organic compounds (NMVOCs) | 0.005 | 0.005 | 0.05 | 0.005 | 1.5 | 0.005 | 0.005 | 0.0237 | 0.04 |
| Particulate Matter 10µm (PM<sub>10</sub>) | 0.046 |     |     |     |     |     |     |     | 0.12 |

## 7.6 Discount rate

The discount rate is set at 8.2 percent and matches the discount rate used by the DMRE in the Integrated Energy Plan. Although it is possible to allocate technology specific discount rates, in each sector, and to change these discount rates over time, a single, consistent, “global” discount rate is currently applied in the model.

