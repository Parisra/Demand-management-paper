## config file
Contains the specific information about the networks (tranmsission expansion level, cost assumptions, renewable resource assumptions, solve settings, etc.).
* All the solar panels are assumed to have a DC/AC ratio of [1.25](https://github.com/Parisra/Demand-management-paper/blob/71c66db8dc36103bb75e73f488f6d3e218cd6cbe/scripts/config.yaml#L259 ) (acc. to Danish Energy Agency, which is used for the cost assumptions from [PyPSA Technology data](https://github.com/PyPSA/technology-data)). This is implemented using atlite:
- using dc_ac ratio to calculate power output : https://github.com/Parisra/Demand-management-paper/blob/6148dcb03f6dd0098a5e74675d8ab00b91511fb7/scripts/atlite/pv/solar_panel_model.py#L84 

## Implementing demand flexibility and reduction

Four demand alteration mechanisms are applied using the [reduce_demand function](https://github.com/Parisra/Demand-management-paper/blob/6148dcb03f6dd0098a5e74675d8ab00b91511fb7/scripts/prepare_sector_network.py#L3956) in prepare_sector_network.py

For each mechanisms, different sectors and different ratios of demand reduction/shifitng are tested. For example, a network with 'dmIelecIp40' has constant demand reduction (dm) applied to the electricity sector (elec) by 40% (p40).
