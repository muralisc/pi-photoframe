https://learn.sparkfun.com/tutorials/how-to-run-a-raspberry-pi-program-on-startup/all


sudo nano /lib/systemd/system/photoframe.service

sudo systemctl daemon-reload
sudo systemctl enable clock.service
systemctl status clock.service


journalctl --unit photoframe

sudo cp ~/src/pi-photoframe/photoframe.service /lib/systemd/system/photoframe.service

# Hyper pixel

https://github.com/pimoroni/hyperpixel4
