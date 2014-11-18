BlueSTM ![alt tag](https://github.com/SkyAndy/BlueSTM/blob/master/app/src/main/ic_launcher-web.png)

einfaches Projekt um mit dem STM32F via Bluetooth mit dem [HC-05](http://www.google.com/search?q=HC-05&oq=HC-05) 
von Android aus zu kommunizieren.

Das Protokoll ist SPP und die UUID ist dabei wichtig.
```java
private static final UUID MY_UUID = UUID
    .fromString("00001101-0000-1000-8000-00805F9B34FB");
```
