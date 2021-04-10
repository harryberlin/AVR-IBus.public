# AVR-IBus - Logging/Logfile
## Logging with Terminal by Br@y
**Wehere to get the Tool Terminal**
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

<img src="Pics/Misc/Logging_Terminal_01.png">


