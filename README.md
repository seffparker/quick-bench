# quick-bench
BASH script to asses linux server performance of various resources
___

The script asseses the performance of CPU, Disk I/O, Memory I/O and Network Up/Down link speed. 
The referance benchmark score is set to ~4000 on the following referance machine:

- **Provider:** AWS
- **Region:** N. Virgina (us-east-1)
- **Service:** EC2
- **Tier:** t2.micro
- **CPU**: 1-core
- **RAM**: 1 GB
- **Storage:** EBS SSD gp2 (100 iops)
- **OS:** CentOS 7.6 Core
- **Kernel:** 3.10.0
