# digital-modes

NOTE: For all of these modes, we will be using the DigiRig as our audio/serial interface.

Radio | Winlink | APRS
|-|-|-|
Baofeng UV-5R | SQL: OFF. VOX: 10 | SQL: 1. VOX: 10
Yaesu FT-818nd | SQL doesn't seem to matter. VOX not used |SQL doesn't seem to matter. VOX not used

NOTE: On the Baofeng, when SQL is on, _and_ on *Winlink*, `direwolf` will complain that the `Audio input level is too low`.

NOTE2: Baofeng seems to work just fine with SQL: 10 and VOX: OFF. 

## Using Baofengs with FLdigi

General configuration for `fsq 4.5`:
1. Go to `Modem -> FSQ`
2. Check `MYCALL lower case`
3. Disable `Message Loggin`
4. Disable the `Logging` options (click on `Enable` to disable the `Audit log` and `Heard log`)
   
![image](https://github.com/user-attachments/assets/142d6c24-4fab-4ca3-8f82-423c6877654c)


Under Devices choose the USB PnP Sound Device (Linux)

![image](https://github.com/user-attachments/assets/aa6506e4-7dda-4e31-af15-b18428598497)

For PTT, go to `Hardware PTT` and choose the following:

* Select the correct COM port (or /dev/ port under Linux)
* Check `Activate RTS`
* Check `use separate serial port PTT`
* Initialize

![image](https://github.com/user-attachments/assets/be0ed5dc-0e92-49e5-89a1-949dd9815ecd)
