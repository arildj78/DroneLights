# DroneLights
A standalone rig for adding navigation and strobe lights to your drone

# Design Criteria
* No electrical connection to the drone
* Powered by independent battery
* Negligible Electromagnetic Interference (EMI) to drone
* Fulfull the requirement for lighting in *Standardised European Rules of the Air* ([SERA]) 3215
* Comply with Norwegian regulation [Forskrift om luftfartøy som ikke har fører om bord mv.][DroneForskrift] §59, §60, §67, §68
* Light emission in compliance with FAR part 27

# Power source
* 11.1V 450mAh 3S1P
* 5Wh
* 25C

![Battery](https://github.com/arildj78/DroneLights/raw/master/images/IMG_8416.JPG)

# EMI
* Operation of the device shall not interfere with any up- or downlinks to or from the aircraft. A reduction of the effective transmission range of less than 5% is acceptable.
* The device should preferably be compliant with MIL-STD-461G *(Requirements for the control of Electromagnetic Interference Characteristics of Subsystems and Equipment)* dated 11-DEC-2015 although running a full test is outside of the budget of this project.

# Minimum performance standard
## Technical standard orders
The FAA issues Technical Standard Orders ([TSO]) which sets a *minimum performance standard* for aviation design approvals. EASA publishes the European Technical Standard Order ([ETSO]) which is similar. Both sets of orders identifies the Society of Automotive Engineers (SAE) AS8037 and AS8017 as the minimum performance standard for *Aircraft Position Lights* and *Anticollision Light Systems*

| System               | FAA      | EASA      |
|----------------------|----------|-----------|
| Navigation lights    | TSO-C30c | ETSO-C30c |
| Anticollision lights | TSO-C96a | ETSO-C96a |

##  Minimum performance standard
The Society of Automotive Engineers Aerospace Standards are not available for free download. In absence of the SAE documents, FAR Part 27 - *Airworthiness Standards: Normal Category Rotorcraft* - can be used.

| System               | SAE        | FAR part 27   |
|----------------------|------------|---------------|
| Navigation lights    | [AS 8037]  | [§27.1385]    |
| Anticollision lights | [AS 8017]  | [§27.1401]    |

## Position Light Intensity Distribution
### Minimum intensities in the horizontal plane of forward and rear position lights.
| Position Light | Angle from Right or Left of Longitudal Axis Measured from Dead Ahead (deg) | Minimum Intensity (Candelas) |
|----------------|----------------------------------------------------------------------------|------------------------------|
| L and R        |   0 to 10   | 40 |
| L and R        |  10 to 20   | 30 |
| L and R        |  20 to 110  |  5 |
| Aft            | 110 to 180  | 20 |

### Minimum intensities in any vertical plane of forward and rear position lights FAR [§27.1393]
| Angle above or below the horizontal plane	| Intensity, I |
|-------------------------------------------|--------------|
| 0°                                        | 1.00         |
| 0° to 5°                                  | 0.90         |
| 5° to 10°                                 | 0.80         |
| 10° to 15°                                | 0.70         |
| 15° to 20°  	                            | 0.50         |
| 20° to 30°                                | 0.30         |
| 30° to 40°                                | 0.10         |
| 40° to 90°                                | 0.05         |


# Color
The color of the lights should be as defined in FAR [§27.1397]. 
* Aviation red
* Aviation green
* Aviation white

![CIExy1931](/images/543px-CIExy1931.png "CIE 1931 color space")


[ETSO]:     /requirements/ETSO.pdf
[TSO]:      /requirements/TSO_C30_C96.pdf
[§27.1385]: https://www.ecfr.gov/cgi-bin/text-idx?node=14:1.0.1.3.13#se14.1.27_11385
[§27.1393]: https://www.ecfr.gov/cgi-bin/text-idx?node=pt14.1.27&rgn=div5#se14.1.27_11393
[§27.1397]: https://www.ecfr.gov/cgi-bin/text-idx?node=pt14.1.27&rgn=div5#se14.1.27_11397
[§27.1401]: https://www.ecfr.gov/cgi-bin/text-idx?node=pt14.1.27&rgn=div5#se14.1.27_11401
[AS 8037]:  https://www.sae.org/standards/content/as8037/
[AS 8017]:  https://www.sae.org/standards/content/as8017/
[SERA]:     https://lovdata.no/static/NLX3/32012r0923.pdf
[DroneForskrift]: https://lovdata.no/dokument/SF/forskrift/2015-11-30-1404
