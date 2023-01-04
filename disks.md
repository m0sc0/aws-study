EBS
gp2/gp3 16KIOPS
io1/io2 64KIOPS
io2 block express 256 KIOPS

Only gp2/gp3 and io1/io2 can be used as boot volumes

HDD
troughtput hdd
500iops

cold hdd
250iops

EBS io1/io2 multiattach same az

Migration;
snapshot -> migrate snapshot to other az ->create ebs from snapshot -> attach
Encriptation:
snapshot -> encript snapshot -> create a ebs from snapshot -> attach
