# Softwares

1. Arduino : https://www.arduino.cc/en/software
2. Anaconda : https://www.anaconda.com/download#downloads

# Yolov5 + Deep Sort with PyTorch

`anaconda prompt`

1. conda create -n traffic-signal-switching python=3.8
2. conda activate traffic-signal-switching
3. conda install pytorch==1.7.1 torchvision==0.8.2 torchaudio==0.7.2 -c pytorch
4. pip install -r requirements.txt
5. python stream.py

# Arduino

`board-manager-url` : https://dl.espressif.com/dl/package_esp32_index.json

# PIN Connections

## ESP32 CAM + USB TO TTL

(usb-to-ttl) : (esp32)
3v : 3v (purple)
5v : breadboard (brown)
gnd : gnd
rx (white) : tx
tx (grey) : rx
connect breadboard pins 3 & 4 for re-upload code.

(oled) : (esp32)
breadboard pins start from 22 to 25 (totally 4 pins)
breadboard 25th: GND
breadboard 24th: VCC
breadboard 23rd (SCL): breadboard 6th (IO14)
breadboard 22nd (SDA): breadboard 5th (IO15)

red colour led (IO12) : breadboard 29th to breadboard (3rd)
green colour led (IO13) : breadboard 29th to breadboard (4th)

led's small flag (+ve) in breadboard 29th.
