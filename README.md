[한국어](https://github.com/FTIndustries/QMC6310-Breakout/blob/main/readme-ko.md)
# FTIndustries QMC6310 3-Axis hall sensor breakout
![preview](https://github.com/FTIndustries/QMC6310-Breakout/blob/main/3dpreview.png?raw=true)\
Sensor breakout using QST's QMC6310 3-Axis hall sensor, supporting Adafruit STEMMA QT / Sparkfun Qwiic system. You can use same [code for QMC5883L](https://github.com/DFRobot/DFRobot_QMC5883) without heavy modification. All you need to do is changing I2C address to 0x3C. You should power this board 3.3V, not 5V. Higher voltages will damage the board.