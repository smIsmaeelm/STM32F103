# STM32F103
At this project I have STM32F103, SSD1306 and an EEPROM. I  used I2C1 to write and read on EEPROM, then I show what is inside EEPROM on OLED screen(SSD1306).
(It is not a commercial project so it is not written perefectly so it is not so clean! you may need to change it a bit.)
The OLED library is written by 4ILO, also I changed it a bit because I need to debug it.
The link of YouTube video is:

I spent about one week to debug my code and the only thing that I got was my code had not any problem! There is a bug in STM32, it is mentioned in errant document. I used the document to debug it but it did not worked so I asked on some question and answer websites; I did not find any help so it was all on my own. I read some related documents and libraries to understand that I2C_DeInit() might solve the problem and fortunately it did. Also, after some try and error, it works perfectly without my debugging code. I just wanted to share my experience because I thought it may help others. Thank you 
