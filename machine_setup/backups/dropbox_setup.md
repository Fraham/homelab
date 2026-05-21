ssh root@MACHINE

```bash
sudo apt update
sudo apt install rclone -y
```

rclone config

n

dropbox_backup

13

[Leave blank] * 2

n * 2

[Use stored config token]

y

q

Check connection

```bash
rclone lsd dropbox_backup:

cat ~/.config/rclone/rclone.conf
```