# Remark

The travel time and electricity consumption associated with each road segment were estimated from large-scale vehicle trajectory data collected in Shanghai. Following standard data-cleaning procedures, records with invalid locations, abnormal speeds, or missing observations were removed. The remaining trajectories were map-matched to the road network to obtain segment-level travel information.

For each road segment, the average travel time was computed from the observed traversal times of vehicles traveling through that segment during the corresponding time period. To capture temporal variations in traffic conditions, separate travel time estimates were generated for different time intervals throughout the day.

Electricity consumption was estimated using observed battery state-of-charge (SOC) changes from electric vehicle trajectory data. After filtering abnormal SOC records and interpolating SOC variations between consecutive observations, the average electricity consumption associated with each road segment was calculated by aggregating the energy usage of vehicles traversing that segment. The resulting segment-level electricity consumption values therefore reflect both roadway characteristics and prevailing traffic conditions.

The travel time and electricity consumption between network nodes were obtained by applying shortest-path searches over the underlying road network and aggregating the corresponding segment-level impedance values.
