# send-temperature-from-Raspberry-pi-to-a-distant-Linux-host-via-paho-mqtt
3 scripts:
* a shell script that initializes the kernel module for AHT10 temperature sensor
* a python script (publisher) on the raspberry pi that publishes temperature values
* a python script (subscriber) on the linux host that recieves the temperature values and prints them
## getting-started:

```bash
clone https://github.com/mimou-77/send-temperature-from-Raspberry-pi-to-a-distant-Linux-host-via-paho-mqtt.git
```
```bash
sudo apt install python3
```
```bash
pip install paho-mqtt
```


