#Research into Bluetooth and SSP Protocols
none of this is fact, this is basically a placeholdering section for notes, and things as i change machines quiet often, hopefully able to keep researching when out. 
## <b><u>IN PROGRESS</u></b>

### Links (My own reading list basically)
[Writeup on SSP (Secure Simple Pin)](http://www.ellisys.com/technology/een_bt07.pdf)


[More](http://www.fte.com/docs/ssp.pdf)


[MitM Attacks via SSP public key](http://www.idosi.org/wasj/wasj13(4)/22.pdf)

#### Notes. 
Seems that the controller will work with console turned on and the PC, Does not connect though.

|Address      | Devices           | Class  |
| ------------- |:-------------:| -----:|
|1C:66:6D:1F:69:8E| [`WirelessController`](https://github.com/R3zk0n/BluetoothProject/blob/master/Controller1Info)| 9480|
|78:D7:5F:95:04:F6   | `iPhone`      |   7995916 |

### Bluetooth Related notes 
Bluetooth protcol notes. 
1. 2.4 GHz unlicensed band, with a default range of 10 meters.

Bluetooth 2.0 uses frequencies between 2.4000 and 2.4835 GHz divides the band into 79 MHz channels (numbered 0-78), with frequency hopping at a rate of 1600 times per second

The PS4 has a class of Device/Service (CoD) of 0x2c0100:

Major Service Class: Audio (0x200000)
Major Service Class: Capturing (0x80000)
Major Service Class: Rendering (0x40000)
Major Device Class : Computer (0x100)

(The dualshock 4 in a game controller mode has a class of Device/Service (CoD) of 0x002508.



##Weaknesses.
When the attacker forces the devices to use Just Works assocication model by beging present from the beginning of the SSP process or by jamming the whole Bluetooth band.
Possible to push the controller into that method?. 

####Funded by:
Centerlink..hopefully.





