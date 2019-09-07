### ASRock B75M-GL R2.0
> * Chipset:    		Intel B75
> * CPU: 				Intel Xeon E3-1230 V2
> * Audio: 				Realtek ALC662
> * Ethernet:			Realtek RTL8111E
> * Graphics:           Dataland RX470

**notice：**
1. copy ext/AppleAHCIPort.kext to /L/E to fix I/O error while booting, repair the permissions and rebuild the caches. <br/>
As apple has deleted configuration messages that support old hard disk  from AppleAHCIPort.kext, we have to load AppleAHCIPort.kext from old version macOS. The attachment kext is from 10.12.1(16b2657) and still valid on mojave.

### Credits
[Apple Inc.](https://www.apple.com)<br/>
[RehabMan](https://bitbucket.org/RehabMan)<br/>
[DalianSky](https://blog.daliansky.net)<br/>
Special thanks to the enthusiastic commenters on [pcbeta](http://bbs.pcbeta.com) & [tonymacx86](https://www.tonymacx86.com)