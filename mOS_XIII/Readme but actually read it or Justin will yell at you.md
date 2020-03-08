**THE PROBLEM OCCURS WHEN YOU ARE DONE RUNNING LIVE AND THEN BUILD AND RUN AS STARTUP. DON'T DO THAT!

**RESTART LABVIEW CODE FROM DRIVER STATION OR PHOENIX TUNER BEFORE YOU BUILD AND RUN AS STARTUP!**

To produce error:
Run live
Finish
No code in driver station
Build
run as startup

To fix error:
(still no robot code on driver station)
reboot rio from driver station (code will pop up but fatal errors will come with it)
build
run as startup
(code will pop up but fatal errors will come with it)
reboot rio from driver station

To prevent error after running live:
restart labview code from driver station or phoenix tuner
build
run as startup
