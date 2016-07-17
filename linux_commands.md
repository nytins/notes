#### Networking
```
netstat -tulpn
nslookup google.com

# DNS lookup with TTL info
dig google.com

# SSH tunneling. localhost:8085-->remote:22-->remote:20005
ssh -i key.pem -L 8085:10.207.182.20:20005 ec2-user@10.207.182.20

# Listen to port 10000 and write anything received to log
nc -l localhost 10000 > log.txt
```
#### Disc and Volumes
```
# List volumes and mount points
lsblk

# See volume content type
file -s /dev/xvdf

# Make ext4 file system on /dev/xvdf volume
mkfs -t ext4 /dev/xvdf

# Mount /dev/xvdf volume on /fileserver directory
mount /dev/xvdf /fileserver

umount /dev/xvdf
```
