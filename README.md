# pi-hole-raspberry-monitor
Modify some php files from pi-hole to get some monitoring over a raspberry

# MODIFY SUDOERS (for using shell_exec)
sudo nano /etc/sudoers

add this line under  User privilege specification
<br>www-data ALL=(ALL) NOPASSWD: ALL
