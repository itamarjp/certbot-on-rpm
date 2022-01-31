To GET a new Cert

sudo certbot certonly --standalone -d domain.name


To start the timer:
sudo systemctl start certbot-renewal.timer

To enable the timer to be started on boot-up:
sudo systemctl enable certbot-renewal.timer

To show status information for the timer:
sudo systemctl status certbot-renewal.timer


To show journal entries for the timer:
sudo journalctl -u certbot-renewal.service


