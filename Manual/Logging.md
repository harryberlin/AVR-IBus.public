# AVR-IBus - Logging/Logfile
## Logging with AVR-IBus-Settings Tool
**Where to get the AVR-IBus-Settings**
You can get the Application from [Tools Section](https://github.com/harryberlin/AVR-IBus.public/tree/master/Tools/).
**Steps to create Log File**
1. Select the Serial/COM Port of AVR-IBus Device

2. Click Open Button to start Connection.

3. Choose Settings Tab.

4. Enable `RX` and `TX` Toggle-Button in Ext. RxTx Section.

5. Enable `autom.` Toggle-Button. This Option enables the next Step to send directly to the Device.

6. Click `|>` Button to generate the Setting Command.

7. Enable Logging Toggle-Button to activate Logging to File. Everytime you enable the Button, a new logfile will be stored to the Subfolder Logs in the Application Path.

8. If you like you can swap the Application Layout to Terminal.

9. Enable AutoScroll Toggle-Button.

10. When you have finised the log process, just close the connection.

11. Go to logfile path and copy the logfile to E-Mail or what ever you want.

<img src="https://raw.githubusercontent.com/harryberlin/AVR-IBus.public/master/Pics/Misc/Logging_AVR-IBus-Settings_01.png"  width="450">

<img src="https://raw.githubusercontent.com/harryberlin/AVR-IBus.public/master/Pics/Misc/Logging_AVR-IBus-Settings_02.png"  width="450">

## Logging with Terminal by Br@y
**Where to get the Tool Terminal**
Homepage about the Tool [Terminal b Br@y](https://sites.google.com/site/terminalbpp/)
You should Download the Version 1.93b_20130116, because the current has a bug by Autoscroll.

**Steps to create Log File**
1. Select the Serial/COM Port of AVR-IBus Device

2. set Serial/COM Port Settings to:<br>`Baud: 38400`, `DataBits:0 8`, `Parity: None`, `StopBits: 1`, `Handshaking: None`

3. Activate '+CR' Checkbox for Send function.

4. Start Connection

5. To be sure the In and Out IBus Messages are enabled, type `SET:RXTX:3`.

6. Press '-> sent' Button. You should get answer from AVR-IBus: 'SET:20:3'

7. Press StartLog. The Application asks where to save the log file. After closing the filedialog, everthing will be logged to the file.

8. When you have finised the log process, just press StopLog.

9. You can close the connection.

10. Go to logfile path and copy the logfile to E-Mail or what ever you want.

<img src="https://raw.githubusercontent.com/harryberlin/AVR-IBus.public/master/Pics/Misc/Logging_Terminal_01.png"  width="450">


