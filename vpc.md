# VPC
https://d1.awsstatic.com/whitepapers/building-a-scalable-and-secure-multi-vpc-aws-network-infrastructure.pdf
-
# Layer 3 connection
## VPC PEERING
* Connect up to 10 vpc
## TRANSIT GW
* Up to 100s vpc, Transitive Peering with multiple vpc, vpn, and onpremise (Direct Connect) throught a central hub
* one per region and connect vpc on the same region

-
## DIRECT CONNECT
* alternative for using aws service or vpn over internet
* private link to on-premise DC without encription
* Can connect multiple VPC on diferent regions
* DX Resiliency: more than one connection
## AWS VPN CLOUD HUB
* Connect over internet
* connect multiple site to site vpn
## SITE TO SITE VPN
* Connect over internet

-
# Api connection
## PRIVATE LINK
* Expose a service to multiple VPC (1000s) without need of vpc peering
* use a private link
## VPC ENDPOINT
* Allow to connect aws service with other vpc





