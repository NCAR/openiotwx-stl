# openIoTwx STL File Repository

## Base Configuration

The base configuration can capture the following:

* temperature / pressure / humidity
* PM2.5

The configuration consists of:

* a 3.8" 3 opening wxOrb (non-imprint)
* a basic shield housing 
* a basic AQ housing (3 part hooded)
* 1 PVC adapter
* 4 PVC rings
* 2 closed endcaps
* 1 vented endcap

**Print time is estimated at 41h**.

| Part | Location | Est. Print Time | Notes | 
|:---:| :---: | :--: | :-- |
| 3.8" Housing (3 opening) | [./housing/orb38_3open.stl](./housing/orb38_3open.stl) | 12h | 20-25% infill; positioned thread side down |
| basic shield housing ( for BME680) | housing (MF) [./shield/mushroomshield_MF.stl](./shield/mushroomshield_MF.stl) | 6h | print cup side up / (M) thread down; use limited support to end of thread for stability; 25% infill |
|a basic AQ housing (3 part hooded)) | base (M) [./aq/aq_base_M.stl](./aq/aq_base_M.stl); <br/>vented hood (F) [./aq/aq_vented_locking_list_F.stl](./aq/aq_vented_locking_list_F.stl); <br/> terminating hood (M) [./aq/aq_hood_terminating_M.stl](./aq/aq_base_M.stl)  | **base**: 6h; **hoods**: 4h each; 14h total | **base**: print thread side to plate, 20-25% infill; **hoods**: print sideways with _tree support_ |
| PVC adapter | [./pvcadapter/knurled_pvc_adapter_M.stl](./pvcadapter/knurled_pvc_adapter_M.stl) | 3h | print thread side up, 30-40% infill for maximum strength |
| PVC Rings (4x) | [./solarpanel/solarpanel_ring_clamp_11mm.stl](./pvcadapter/knurled_pvc_adapter_M.stl) | 6h | print flat side to plate, 30-40% infill for maximum strength |
