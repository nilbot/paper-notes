# Cloud Platform Usage Notes

## AWS
AWS seems to have higher networking performance, while the EBS based SSD drives
performance really poor. AWS is relatively easy to setup, community AMI provide
also wide range of choices in development platform.

### Publicity induced Contra
currently observed web crawler running on aws will get blocked more frequently 
than DO

### GPU instance
AWS provide GPU compute instances, which is unique in industrial offerings. 
However the GPU in question is K520, much weaker than general purpose K40 
because the former is designed for entertainment. 

### Platform software stack
Provide official images
- Amazon Linux AMI (blend of RHEL6 with custom repository)
- Ubuntu 14
- Suse 12

Community AMI provides much wider selection of platforms.

## DigitalOcean
DO provides excellent easy to setup environment for compute instances. Also the
disk performance (SSD) is approaching theoretical limit of 500MB/s. However the 
networking performance seems to less wide coverage of throughput optimisations
for major hubs. (Google connection is fast but aws connection is slower)

### Platform software stack
- CoreOS
- Ubuntu 12-16
- Debian 6-7
- Fedora
- CentOS
- FreeBSD

