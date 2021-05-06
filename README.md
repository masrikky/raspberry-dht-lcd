## Raspberry Pi - Humidity and Temperature Reader ##

#### Requirements : ####
Hardware :

1. Raspberry Pi 
2. DHT22
3. Wire
4. LCD 16x2 (i2c included/installed)

Pre-installed :

1. Python 3 
2. Adafruit DHT Library

#### Setup ####


Please see the code in file "main.py" for wiring configuration between DHT, Raspberry and LCD. And then do this simple step :

1. Power on and log in into your raspberry using SSH
2. Navigate and upload main.py (or maybe just copy and paste) into your  prefered directory (you can use **scp**).
3. Run program using `python3 main.py`
4. That's it


#### Future Improvement ####

1. Set auto run on startup.