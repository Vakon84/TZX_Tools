Tool to help you use and update your MaxDuino, TZXduino, CASDuino, ArduiTape, ZXuiTape, CPCuiTape, BeebuiTape, MSXuiTape, MZuiTape (soon) and some features like UEF Extraction (coming soon)

MaxDuino:
  If you want to have the splash screen(logo) loaded you have to upload that before uploading the firmware
  
General:
  Make sure you select the right arduino board. For Nano most of the time it will be the OLD Bootloader type but if you find it wont upload then try the New bootloader
  NOTE: If you get a false positive malware warning you can ignore it. I have tried to make sure false postives have been eliminated. But let me know if you get one.

Very Simple tool to use:

Step1: Plug your Device into the USB port

Step2: Open TZXduino Uploader and select the COM port

Step3: Choose which type of Arduino you use

Step4: Choose which Firmware you need

Step5: Display you are using

Step6: If you are using an LCD display with an I2C adapter you need to specify the I2C address

Step7: Upload

If you do not know the I2C address use an I2C scanner sketch to find out > https://playground.arduino.cc/Main/I2cScanner/

I'll try to keep updating it as and when new Firmwares get released

TZXduino, CASduino and ArduiTape developed by Duncan Edwards and Andrew Beer
MaxDuino developed by Rafael Molina Chasserot
DigiWavuino developed by ME! 
