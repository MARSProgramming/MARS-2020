**THE DEPLOYING PROBLEM OCCURS WHEN YOU ARE DONE RUNNING LIVE AND THEN BUILD AND RUN AS STARTUP. DON'T DO THAT!**

**RESTART LABVIEW CODE FROM DRIVER STATION OR PHOENIX TUNER BEFORE YOU BUILD AND RUN AS STARTUP!**

To produce error:<br>
Run live<br>
Finish<br>
No code in driver station<br>
Build<br>
run as startup<br>

To fix error:<br>
(still no robot code on driver station)<br>
reboot rio from driver station (code will pop up but fatal errors will come with it)<br>
build<br>
run as startup<br>
(code will pop up but fatal errors will come with it)<br>
reboot rio from driver station<br>

To prevent error after running live:<br>
restart labview code from driver station or phoenix tuner<br>
build<br>
run as startup<br>
