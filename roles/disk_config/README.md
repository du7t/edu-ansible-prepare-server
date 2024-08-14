# Disk config role

Role:
- encrypts second drive with partition created using luks_keyfile
- checks that partition on first drive, after root partition, has the minimum required size for LUKS
- if success, encrypts that partition
