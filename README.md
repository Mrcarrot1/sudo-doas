# sudo-doas
A utility for Linux-based systems to randomly choose between "sudo" and "doas" every time one or the other is run.

# Installing
sudo-doas has the following dependencies: `sudo`, `doas`, and `bash`. It also depends on systemd to set global aliases.
If you are using a Linux or Unix-based system that does not have systemd, you can use another method to set a global alias. Anyone who cares enough to run one of these systems likely has enough technical knowledge to figure it out.

To install, place the `sudo-doas` script in `/usr/bin` and place the `sudo-doas.sh` script in `/etc/profile.d`.



Note that using this script is considered a Very Bad Idea™.
