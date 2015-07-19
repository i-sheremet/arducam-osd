1./
First you need to enable this function in APM. Go to APM\_Config.h and add: "#define RECEIVER\_RSSI\_PIN 6"

Note that 6 is the analog pin number where you have RSSI port connected. I have changed it to 6 as I use analog port 6. If you use a different port, replace 6 with your analog port number.

If you use APM2 or 2.5 than add:
"#define CONFIG\_APM\_HARDWARE APM\_HARDWARE\_APM2"
in APM\_Config.h

After this you can compile and upload.


2./
You have to teach OSD to "read your receiver".

http://arducam-osd.googlecode.com/svn/wiki/images/frmv2/7.PNG

Open Config. Tool check the "RSSI Enable Raw" check-box so when you power up your OSD with APM, you will see the raw values. After APM have booted up and you have your TX working (antenna pulled out), than it will show the raw value that you set in "RSSI Max Value" box.
Than turn your tx off, so it will show the raw value that you set in "RSSI Min Value" box.
Than plug your OSD to FTDI again, and uncheck "RSSI Raw Value" check-box, than save it to OSD.
After this OSD will show RSSI normally.