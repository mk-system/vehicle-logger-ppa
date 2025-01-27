# vehicle-logger-ppa
PPA repository for vehicle-logger

```bash
curl -s --compressed "https://mk-system.github.io/vehicle-logger-ppa/debian/KEY.gpg" | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/vehicle-logger-ppa.gpg >/dev/null

echo "deb [signed-by=/etc/apt/trusted.gpg.d/vehicle-logger-ppa.gpg] https://mk-system.github.io/vehicle-logger-ppa/debian ./" | sudo tee /etc/apt/sources.list.d/vehicle-logger-ppa.list

sudo apt update

sudo apt install vehicle-logger
```