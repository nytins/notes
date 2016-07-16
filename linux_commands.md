```
# List volumes and mount points
lsblk

# See volume content type
file -s /dev/xvdf

# Make ext4 file system on /dev/xvdf volume
mkfs -t ext4 /dev/xvdf
```
