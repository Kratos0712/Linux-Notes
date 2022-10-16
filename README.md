## Monitoring in Linux

Configured in /etc/monitrc

#### Install Monit
- apt-get update
- apt-get install monit
- systemctl enable monit
- systemctl start monit

Edit /etc/monit/monitrc

#### systemd

systemd is monitoring init system used to manage services
```
systemctl <command> <unitname>
```
  
  - ## enable
  Make sure this usnit always starts at boot.
  - ## disable
  Opposite of enable
  - ## start
  Start this unit now(will not automatically starts at next boot)
  - ## stop
  Stop a running unit(will not prevent starting at boot, if enabled)
  - ## reload
  Reread the program configuration files
  - ## restart
  Kill the process and start again, rereading the configuration files
  - ## status
  Check status of unit, show last few lines of log output
  
  ### Log mangaement commands
  
  - Journalctl
  - journactl -u <unit>
  - journactl --since "2 min ago"











