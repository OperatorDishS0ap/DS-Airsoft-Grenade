# PLEASE READ THE INSTRUCTIONS BELOW THOROUGHLY AND WATCH THE VIDEO LINKED BELOW BEFORE ASKING QUESTIONS

Assembly video can be found here: 

A video showing how to order the PCB can be found here: 

For further questions and resources join the [Discord](https://discord.gg/FcNPHcn7kz) server 

| Navigation |
| :------------------------: |
| [File Outline](#file-outline) |
| [Print Settings and Materials](#print-settings-and-materials) |
| [Printed Parts](#printed-parts) |
| [Impact Fuse BOM](#impact-fuse-bill-of-materials) |
| [Timed Fuse BOM](#impact-fuse-bill-of-materials) |
| [Impact Fuse Assembly](#impact-fuse-assembly) |
| [Timed Fuse Assembly](#timed-fuse-assembly) |
| [Body Assembly and Function](#body-assembly-and-function) |
| [Additional Material Info](#additional-material-info) |


# File Outline:
Files are organized into assigned folders and named with association to each component  

- Numbers indicate the diamter of the body
- Files ending with a **P** are primer bodies
- Files ending with an **8** are 8-shot cap bodies
- Files ending with a **S** are adult,thunder, super snap bodies
- For the 38 bodies, an ending with **F** is a hexagon capped version of the body
- For the 38 bodies, an ending with **L** is a longer body
- Spoons are matched by the body diameter number (38, 55, 61, etc.)
- The thumb spoon is universal


# Print Settings and Materials:
It is critical that your printer and filament are tuned correctly for good results. Please verify that your printer is printing accurate parts. Additional slicer hacks to resolve fitment issues will be demonstrated later in the instructions.

## Slicer Settings:
- 0.20mm layer height or smaller for the bodies and fuses
- 0.16mm layer height or smaller for the cam, bolt guide, and spring plate
- Smaller layers may yield more accurate dimensions
- 2mm Wall, Top, and Bottom Thickness (5 walls for 0.4mm nozzle)
- 35% Gyroid or Cubic Infill
- For the TPU spoons 2mm wall, top and bottom layers with 100% infill. The wall thickness is important for the layer orientation.

## Material:
- Use PLA+ For all components excluding the spoons
- For the spoons use 95A TPU. It is critical that you use this variant of TPU. Other durometers will yield varying results. It is highly recommended that you use TPU spoons. They will yield drastically better performance and impact strength.
- The bottoms of the snap bodies may be printed from TPU.
- **DO NOT** use ABS, ASA, or PETG. These materials exhibit weaker layer adhesion and will break easily. Carbon Fiber or Glass Fiber composite materials will exhibit weaker layer adhesion as well and are not recommended for the primary body and fuse components
- Better materials will be discussed at the end of the document; however it is recommended that you use PLA and standard TPU 95A to establish a baseline.

## Print Orientation:
- For both the Impact and Timed Fuse place the bottom on the build plate. Support will not be required, they are built in.
- All bodies will be printed with their bottoms on the build plate. Support is not needed. The 55S body is the only exception and will need support.
- The spoons can be printed sideways without the need for support.
- The bolt guide, timer cam, and spring plate can be printed without support.


# Printed Parts:
The tables below outline the printed parts necissary for each core component. You will need a fuse type and a body type. All fuses and bodies are interchangable. Links are to the corresponding file folders.
## Printed Parts for Impact Fuse:
| Part | QTY |
| --- | --- |
| [Fuse](ImpactFuse/FuseV4.5.STL) | 1 |
| [Bolt Guide](ImpactFuse/BoltGuide.STL) | 1 |
| [Spring Plate](ImpactFuse/SpringPlate.STL) | 1 |
| [Spoon](ImpactFuse/Spoons) | 1 |

## Printed Parts for Timed Fuse:
| Part | QTY |
| --- | --- |
| [Fuse](TimedFuse/PCBFuseV4.5.STL) | 1 |
| [Bolt Guide](TimedFuse/BoltGuide.STL) | 1 |
| [Spring Plate](TimedFuse/SpringPlate.STL) | 1 |
| [Cam](TimedFuse/Cam.STL) | 1 |
| [Cap](TimedFuse/Cap.STL) | 1 |

## Printed Parts for Primer Body:
| Part | QTY |
| --- | --- |
| [Body](PrimerBody) | 1 |

## Printed Parts for Snap Body
| Part | QTY |
| --- | --- |
| [Top](SnapBody/Top) | 1 |
| [Bottom](SnapBody/Bottom) | 1 |

## Printed Parts for 8-Cap Body
| Part | QTY |
| --- | --- |
| [Body](8CapBody) | 1 |
| [Retainer](8CapBody/Retainer.STL) | 1 |


# Impact Fuse Bill of Materials:
Please **VERIFY** that you are ordering the same component listed below. The links do not direct you to the exact size/specification you will need.

| Item | Quantity | Amazon | ALiExpress | Notes |
| ---- | -------- | ------ | ----------- | ------ |
| M4x40mm SHCS Half Thread | 1 | [link](https://www.amazon.com/dp/B0DDKFXLC5?ref_=ppx_hzsearch_conn_dt_b_fed_asin_title_1) | [link](https://www.aliexpress.us/item/3256802084429657.html?spm=a2g0o.detail.pcDetailTopMoreOtherSeller.1.6f82ZPX0ZPX0kQ&gps-id=pcDetailTopMoreOtherSeller&scm=1007.40050.354490.0&scm_id=1007.40050.354490.0&scm-url=1007.40050.354490.0&pvid=2657d297-fe94-4c6a-a7d7-3aed59752187&_t=gps-id:pcDetailTopMoreOtherSeller,scm-url:1007.40050.354490.0,pvid:2657d297-fe94-4c6a-a7d7-3aed59752187,tpp_buckets:668%232846%238116%232002&pdp_ext_f=%7B%22order%22%3A%22688%22%2C%22eval%22%3A%221%22%2C%22sceneId%22%3A%2230050%22%7D&pdp_npi=4%40dis%21USD%211.10%211.05%21%21%211.10%211.05%21%402151e6dc17399251117425329eb501%2112000019845613095%21rec%21US%212397384802%21XZ&utparam-url=scene%3ApcDetailTopMoreOtherSeller%7Cquery_from%3A) | Main Bolt |
| M3x30mm SHCS | 1 | [link](https://www.amazon.com/M3x30mm-Socket-Screws-Thread-Suspension/dp/B0F31RVVGR/ref=sr_1_3?sr=8-3) | [link](https://www.aliexpress.us/item/2251832624557792.html?spm=a2g0o.order_list.order_list_main.172.62f11802i8AwSc&gatewayAdapt=glo2usa) | Spoon Bolt |
| 12mm OD x 40mm 1.2mm Diameter Spring | 1 | [link]() | [link]() | Primary Spring<br>See Comments Below |
| 8mm OD x 40mm 0.8mm Diameter Spring | 1 | [link]() | [link]() | Secondary Spring<br>See Commenst Below |
| M3x25mm Countersunk Self-Tapping Screw | 4 | [link]() | [link]() | Fuse Reinforcement |
| 25mm/1" Keyring | 1 | [link]() | [link]() | |
| M2.5x35mm Cotter Pin | 1 | [link]() | [link]() | |
| M3 Brass Heat Insert 5mmODx4mmL | 1 | [link]() | [link]() | Not necissary, only for increased durability |

Primary springs ordered from other locations may have differing coil counts. The recommended coil count is ~10-11, however, some experimentation may be needed. Both springs linked will work without modification. In the case the spring is unable to compress enough, either cut and stretch the spring, or purchase a shorter length and stretch to fit. If you find your springs too weak, increase in length. I recommend purchasing a few varying lengths or further discuss with others on the discord to find a good spring.  

The secondary spring is to add spring strength for the primer and 8-cap and is not necessary for the snap rounds.  

Springs will lose their strength over time and will need to be replaced. Avoid leaving the fuses cocked over long periods of time, this will rapidly decrease their lifespan.

# Timed Fuse Bill of Materials:
Please **VERIFY** that you are ordering the same component listed below. The links do not direct you to the exact size/specification you will need.

| Item | Quantity | Amazon | ALiExpress | Notes |
| ---- | -------- | ------ | ----------- | ------ |
| M4x40mm SHCS Half Thread | 1 | [link](https://www.amazon.com/dp/B0DDKFXLC5?ref_=ppx_hzsearch_conn_dt_b_fed_asin_title_1) | [link](https://www.aliexpress.us/item/3256802084429657.html?spm=a2g0o.detail.pcDetailTopMoreOtherSeller.1.6f82ZPX0ZPX0kQ&gps-id=pcDetailTopMoreOtherSeller&scm=1007.40050.354490.0&scm_id=1007.40050.354490.0&scm-url=1007.40050.354490.0&pvid=2657d297-fe94-4c6a-a7d7-3aed59752187&_t=gps-id:pcDetailTopMoreOtherSeller,scm-url:1007.40050.354490.0,pvid:2657d297-fe94-4c6a-a7d7-3aed59752187,tpp_buckets:668%232846%238116%232002&pdp_ext_f=%7B%22order%22%3A%22688%22%2C%22eval%22%3A%221%22%2C%22sceneId%22%3A%2230050%22%7D&pdp_npi=4%40dis%21USD%211.10%211.05%21%21%211.10%211.05%21%402151e6dc17399251117425329eb501%2112000019845613095%21rec%21US%212397384802%21XZ&utparam-url=scene%3ApcDetailTopMoreOtherSeller%7Cquery_from%3A) | Main Bolt |
| 12mm OD x 40mm 1.2mm Diameter Spring | 1 | [link]() | [link]() | Primary Spring<br>See Comments Below |
| 8mm OD x 40mm 0.8mm Diameter Spring | 1 | [link]() | [link]() | Secondary Spring<br>See Commenst Below |
| M2.5x25mm Countersunk Self-Tapping Screw | 4 | [link]() | [link]() | Fuse Cap Fastners and Reinforcement |
| 25mm/1" Keyring | 1 | [link]() | [link]() | |
| M2.5x35mm Cotter Pin | 1 | [link]() | [link]() | |
| Motor 12V 30RPM | 1 | [link]() | [link]() | **DO NOT ORDER THE WRONG MOTOR**<br>See Comments Below To ensure you order the correct motor |
| 100mAh 3.7V Li-Po w/ JST PH2.0mm Connector | 2 | [link]() | [link]() | See the Image Below for Battery Space Measurements |
| Male JST PH2.00mm 3P Connector | 1 | [link]() | [link]() | Charger Cable |
| Male JST XH2.54mm 3P Connector | 1 | [link]() | [link]() | This is for charging the 2S Li-Po in the fuse. I recommend purchasing a 2S Li-Po balance lead and crimping the JST PH2.0mm connector to the end. Otherwise, you can crimp the connectors on both ends. |
| M2.5x3mm Set Screw | 1 | [link]() | [link]() | Timer Cam |
| Limit Switch SPDT | 1 | [link]() | [link]() | Ensure is a side mount switch and facing in the correct orientation<br>The [switch](Images/switch.JPEG) is imaged below |
| PCB | 1 | | | PCB [Files]() are above<br>A [video]() showing how to order the board is linked above |
| Female JST PH2.0mm 2P Vertical Header | 2 | [link]() | [link]() | Battery PCB Header |
| Female JST PH2.0mm 3P Horizontal Header | 1 | [link]() | [link]() | Battery PCB Charge Port Header |

**DO NOT ORDER THE WRONG MOTOR.** It is Very important that you purchase a 12V-30rpm/6V-15rpm motor. The gearbox is 12.5mm vs the standard 9mm. The gearbox has a 1:1000 ratio. Please be careful to order the correct motor others will not work. I recommend ordering from the Alibaba link, please specify the **“KGM12-N20-C. 6V 1/1000 reduction ratio”** when ordering.  

Primary springs ordered from other locations may have differing coil counts. The recommended coil count is ~10-11, however, some experimentation may be needed. Both springs linked will work without modification. In the case the spring is unable to compress enough, either cut and stretch the spring, or purchase a shorter length and stretch to fit. If you find your springs too weak, increase in length. I recommend purchasing a few varying lengths or further discuss with others on the discord to find a good spring.  

The secondary spring is to add spring strength for the primer and 8-cap and is not necessary for the snap rounds.  

Springs will lose their strength over time and will need to be replaced. Avoid leaving the fuses cocked over long periods of time, this will rapidly decrease their lifespan.
Battery compartment dimensions are below in millimeters. You will have to explore options for batteries since listings change per country. Verify that it has a JST PH 2.0mm connector or crimp your own.

![Top Battery Space](Images/battery_top.png)
![Side Battery Space](Images/battery_side.png)


# Impact Fuse Assembly:


# Timed Fuse Assembly:

![Timer Fuse Function](Images/gif.gif)


# Body Assembly and Function:


# Additional Material Info:
