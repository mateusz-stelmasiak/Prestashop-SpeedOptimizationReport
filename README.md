# Prestashop-SpeedOptimizationReport
<img width="3832" height="2172" alt="image" src="https://github.com/user-attachments/assets/46b1f41e-aaa1-4a1a-943b-0f01a1968eba" />


## ABSTRACT
The site began as pretty but consistently slow. Through minor code changes I managed to make it 200x faster. All messurements taken were obtained on the main customer path (homepage -> category -> custom set -> checkout).
 <img width="1600" height="909" alt="Code_Generated_Image (4)" src="https://github.com/user-attachments/assets/aff5bded-21a8-4b5f-be13-d262519ff22c" />

### RESULTS
| METRIC | BEFORE | AFTER
|---|---|---|
| **[DESKTOP]** Page load time (7- day avg) | 3.41 s | 0.20 s|
| - Total blocking time (main thread) | 3.41 s | 0.20 s |
| - First Containtfull paint | 3.41 s | 0.04 s|
| **[MOBILE]** Page load time (7- day avg) | 2.51 s | 0.02s |
| — Total blocking time (main thread) | 2.51 s | 0.02 s|
| **[DESKTOP]** Page size (total) | 3.83 MB | 300.40 KB |
| — JS | 2.66 MB | 153.9 KiB |
| — IMG | 658.03 KB | 1.20 MB |
| — CSS | 310.21 KB | 78.30 KB|
| — Fonts / other | 229 KB | 67 KB|


## STATE BEFORE
<img width="1855" height="1515" alt="image" src="https://github.com/user-attachments/assets/b394c4a4-bce1-4c7a-baa8-9ecf2d5a5c17" />
<img width="3837" height="2027" alt="image" src="https://github.com/user-attachments/assets/7a9eadec-1ea7-499a-9c81-836e036d86d9" />

### Daily load time

| Date | Load time |
|---|---|
| 13.09.2026 | no data |
| 14.09.2026 | 3.64 s |
| 15.09.2026 | 3.38 s |
| 16.09.2026 | 3.85 s |
| 17.09.2026 | 3.26 s |
| 18.09.2026 | 3.61 s |
| 19.09.2026 | 3.46 s |

## CHANGELOG
19/09/2026 
1. Cache modules
   - hsrediscache [hsrediscache.zip](https://github.com/user-attachments/files/32438297/hsrediscache.zip)
   - litespeedcache [litespeedcache.zip](https://github.com/user-attachments/files/32438302/litespeedcache.zip)
   - smprestaspeed [smprestaspeed.zip](https://github.com/user-attachments/files/32438305/smprestaspeed.zip)
  

## STATS AFTER
<img width="3835" height="1942" alt="image" src="https://github.com/user-attachments/assets/01198bb6-93fe-4776-af27-da696fa3647c" />
<img width="1600" height="659" alt="Code_Generated_Image (3)" src="https://github.com/user-attachments/assets/04d639b4-a41f-46b6-a85f-7989f4f92425" />

## RESOURCES
[Raport_Monitoring_WWW_www.alhambrasklep.pl.pdf](https://github.com/user-attachments/files/32439879/Raport_Monitoring_WWW_www.alhambrasklep.pl.1.1.pdf)
