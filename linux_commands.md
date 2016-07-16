#### Networking
```
netstat -tulpn
nslookup google.com

# DNS lookup with TTL info
dig google.com
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
