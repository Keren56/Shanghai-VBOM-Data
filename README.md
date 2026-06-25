# Shanghai-VBOM-Data

This repository provides the travel time and electricity consumption data used in the Shanghai case study.

The underlying road network represents the area within the Shanghai Inner Ring and consists of intersections connected by directed road segments.

## Data Files

The `data/` folder contains road-segment-level data under different traffic conditions:

* `morning_peak_road_segment_data.csv`
* `off_peak_road_segment_data.csv`
* `evening_peak_road_segment_data.csv`

Each CSV file contains the following fields:

| Field                     | Description                                                                                              |
| ------------------------- | -------------------------------------------------------------------------------------------------------- |
| `link_id`                 | Unique identifier of a directed road segment.                                                            |
| `init_node`               | Initial node of the directed road segment.                                                               |
| `term_node`               | Terminal node of the directed road segment.                                                              |
| `travel_time`             | Travel time of the road segment, measured in minutes.                                                    |
| `electricity_consumption` | Electricity consumption of the road segment, expressed as the decrease in battery state-of-charge (SOC). |

## Remark

Details on data processing and estimation procedures are provided in `remark.md`.

## Citation

If you use this dataset, please cite the corresponding paper.

## License

This dataset is released for academic research purposes.
