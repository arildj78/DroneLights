# DroneLights
A standalone rig for adding navigation and strobe lights to your drone

# Design Criteria
* No electrical connection to host system
* Powered by independent battery

# Power source
* 11.1V 450mAh 3S1P
* 5Wh
* 25C

![Battery](https://github.com/arildj78/DroneLights/raw/master/images/IMG_8416.JPG)

# EMI
Operation of the light rig shall not reduce up- or downlink ranges by more than 5%. The rig should preferably be compliant with relevant EMI standards.

# FAR airworthiness
The US Code of Federal Regulations Title 14 - also known as the Federal Aviation Regulations states in its part 27 [AIRWORTHINESS STANDARDS for NORMAL CATEGORY ROTORCRAFT].



# Minimum performance standard
## Technical standard orders
The FAA issues Technical Standard Orders ([TSO]) which sets a *minimum performance standard* for aviation design approvals. EASA publishes the European Technical Standard Order ([ETSO]) which is similar. Both sets of orders identifies the Society of Automotive Engineers (SAE) AS8037 and AS8017 as the minimum performance standard for *Aircraft Position Lights* and *Anticollision Light Systems*

| System               | FAA      | EASA      |
|----------------------|----------|-----------|
| Navigation lights    | TSO-C30c | ETSO-C30c |
| Anticollision lights | TSO-C96a | ETSO-C96a |

##  Minimum performance standard
The Society of Automotive Engineers Aerospace Standards are not available for free download. In absence of the SAE documents, the AIRWORTHINESS STANDARDS: NORMAL CATEGORY ROTORCRAFT from FAR can be used.

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

!
[ETSO]:     /requirements/ETSO.pdf
[TSO]:      /requirements/TSO_C30_C96.pdf
[§27.1385]: https://www.ecfr.gov/cgi-bin/text-idx?node=14:1.0.1.3.13#se14.1.27_11385
[§27.1401]: https://www.ecfr.gov/cgi-bin/text-idx?node=pt14.1.27&rgn=div5#se14.1.27_11401
[§27.1397]: https://www.ecfr.gov/cgi-bin/text-idx?node=pt14.1.27&rgn=div5#se14.1.27_11397
[AS 8037]:  https://www.sae.org/standards/content/as8037/
[AS 8017]:  https://www.sae.org/standards/content/as8017/
