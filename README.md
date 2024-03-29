[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.8400556.svg)](https://doi.org/10.5281/zenodo.8400556)

# openIoTwx STL File Repository

## Base Configuration

The base configuration can capture the following:

* temperature / pressure / humidity
* PM2.5

The configuration consists of:

* a 3.8" 3 opening wxOrb (non-imprint)
* a basic shield housing 
* a basic AQ housing (2 part hooded)
* 1 PVC adapter
* 4 PVC rings
* 2 closed endcaps
* 1 vented endcap

**Print time is estimated at 37.5h on Ender 3 S3 at 60mm/s, PLA+**.

| Part | Location | Est. Print Time | Notes | 
|:---:| :---: | :--: | :-- |
| 3.8" Housing (3 opening) | [./housing/orb38_housing_3open.stl](./housing/orb38_housing_3open.stl) | 12h | 20-25% infill; positioned thread side down |
| basic shield housing ( for BME680) | housing (MF) [./shield/mushroom_shield_MF.stl](./shield/mushroom_shield_MF.stl) | 6h | print cup side up / (M) thread down; use limited support to end of thread for stability; 25% infill |
|a basic AQ housing (2 part hooded) | base (M) [./aq/aq_grill_base_M.stl](./aq/aq_grill_base_M.stl); <br/>vented lid [./aq/aq_grill_lid.stl](./aq/aq_grill_lid.stl)  | **base**: 4h; **lid**: 2h | **base**: print on side with tree support (@2% infill), 20-25% infill everywhere else; **lid**: print grill side down, 20-25% infill  |
| PVC adapter | [./pvcadapter/knurled_pvc_adapter_M.stl](./pvcadapter/knurled_pvc_adapter_M.stl) | 3h | print thread side up, 30-40% infill for maximum strength |
| PVC Rings (4x) | [./solarpanel/solarpanel_ring_clamp_11mm.stl](./solarpanel/solarpanel_ring_clamp_11mm.stl) | 6h | print flat side to plate, 30-40% infill for maximum strength |
| Closed endcaps (2x) | [./endcaps/closed_endcap.stl](./endcaps/closed_endcap.stl) | 3h | flat (cap) side to plate, 30-40% infill for maximum strength |
| Vented endcap (1x) | [./endcaps/vented_endcap.stl](./endcaps/vented_endcap.stl) | 1.5h | flat (vented) side to plate, 30-40% infill for maximum strength |


## Project Links

* openIoTwx Hub :  [https://github.com/NCAR/openiotwx-hub](https://github.com/NCAR/openiotwx-hub)