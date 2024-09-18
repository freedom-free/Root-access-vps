# Root-access-vps
# Getting Started
1) Type: sudo nano /etc/ssh/sshd_config
✓ Scroll Down until you see #PermitRootLogin prohibit-password change that to PermitRootLogin yes then Save.
2) Type sudo passwd
✓ Enter New Password, then again.
3) Once that is done do: {service sshd restart}
✓ Then login using user root and password your_password
