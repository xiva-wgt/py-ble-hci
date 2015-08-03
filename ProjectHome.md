A binary parser for Bluetooth 4.0 HCI packets along with a TCP controlled serial port server allowing a remote, interactive and scriptable HCI session.

Serial commands are built from Python objects and responses are parsed into objects for easy programmatic access. Controller responses are parsed and their success status is checked before each command returns.

Example image shows two servers controlled by one client.

Made in order to control DTM sessions, but easily expandable to other HCI commands/events. Parser built from [construct](http://construct.wikispaces.com) package, serial from [pyserial](http://pyserial.sourceforge.net/). **Both required to run**. I used construct 2.06 and pyserial 2.6 on python 2.7.3.

Built with a  focus on the Texas Instruments CC2540 USB dongle, with the 'host\_test\_release' firmware which emulates a serial port when connected to a PC.

[View the code](https://code.google.com/p/py-ble-hci/source/browse/)

[CC2540 info](http://processors.wiki.ti.com/index.php/Category:BluetoothLE)


License:
  * Legally speaking:
    * Do whatever you want
    * Do it at your own risk

  * Morally speaking:
    * Credit where credit is due
    * Code contributions welcome
    * 'Thank you's appreciated

## Sample run ##

---

[Full Size](https://py-ble-hci.googlecode.com/hg/demo_run.png)

![![](https://py-ble-hci.googlecode.com/hg/demo_run.png)](https://py-ble-hci.googlecode.com/hg/demo_run.png)