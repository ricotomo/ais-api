# AIS API

This repo is discontinued. Please use [github.com/transparency-everywhere/position-api/](https://github.com/transparency-everywhere/position-api/) in future =)


# Paths
**/getVesselsByDestionPort/:shipPort**  

Extended the functionality with a path which returns all vessels headed to a port. This uses the next Port broadcast by the ais system and may not be the final destination port. Ports are named after the MT nomenclature example: http://localhost:5000/getVesselsByDestinationPort/piraeus

Output format identical to getVesselsInArea
