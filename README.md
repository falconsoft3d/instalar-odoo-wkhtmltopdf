# Instalar wkhtmltopdf para linux


Opcional
```
sudo apt-get -f install
```

```
sudo apt-get install libxrender1 fontconfig xvfb libjpeg-turbo8
cd /opt
git clone https://github.com/falconsoft3d/instalar-odoo-wkhtmltopdf
cd instalar-odoo-wkhtmltopdf
sudo dpkg -i wkhtmltox-0.12.1_linux-trusty-amd64.deb
sudo cp /usr/local/bin/wkhtmltoimage /usr/bin/wkhtmltoimage
sudo cp /usr/local/bin/wkhtmltopdf /usr/bin/wkhtmltopdf
```
