On-Demand Instances: short workload, predictable pricing
Reserved: (MINIMUM 1 year)
 * Reserved Instances: long workloads 
 * Convertible Reserved Instances: long workloads with flexible instances
 * Scheduled Reserved Instances: example – every Thursday between 3 and 6 pm
Spot Instances: short workloads, cheap, can lose instances (less reliable)
 * spot block: for time 1 to 6 hours
Dedicated Hosts (3 YEARS): book an entire physical server, control instance placement, compliance
Dedicated Instances: no other customers will share your hardware

Spot fleets: spot instances + on-demand instances
# ASG
Launch configuration:
* legacy
Launch template:
* provision spot and on-demand instances
* multiple versions

ASG Default Termination Policy:
1: spot or on-demand
2: older launch template or configuration
3: next billing hour

After a scaling activity happens, you are in the cooldown of 300s

Target Tracking Scaling: I want the average ASG CPU to stay at around 40%
Simple / Step Scaling: When a CloudWatch alarm is triggered (example CPU > 70%), then add 2 units
Scheduled Actions: increase the min capacity to 10 at 5 pm on Friday