# Undervolt-Timer

Timer to apply an undervolt after PC startup. 

Undervolt.service and Undervolt.timer are placed in /etc/systemd/system.
Enable Undervolt.timer so that on startup it will countdown 2 minutes and then activate undervolt.service.

The startupuv script goes to your /usr/local/bin location and is used to apply the undervolt after two minutes.
