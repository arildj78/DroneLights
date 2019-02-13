# DroneLights
A standalone rig for adding navigation and strobe lights to your drone

# Design Criteria
* No electrical connection to the drone
* Powered by independent battery
* Negligible Electromagnetic Interference (EMI) to drone
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



# Color
The color of the lights should be as defined in FAR [§27.1397]. 
* Aviation red
* Aviation green
* Aviation white

![CIExy1931](/images/543px-CIExy1931.png "CIE 1931 color space")


[ETSO]:     /requirements/ETSO.pdf
[TSO]:      /requirements/TSO_C30_C96.pdf
[§27.1385]: https://www.ecfr.gov/cgi-bin/text-idx?node=14:1.0.1.3.13#se14.1.27_11385
[§27.1401]: https://www.ecfr.gov/cgi-bin/text-idx?node=pt14.1.27&rgn=div5#se14.1.27_11401
[§27.1397]: https://www.ecfr.gov/cgi-bin/text-idx?node=pt14.1.27&rgn=div5#se14.1.27_11397
[AS 8037]:  https://www.sae.org/standards/content/as8037/
[AS 8017]:  https://www.sae.org/standards/content/as8017/
