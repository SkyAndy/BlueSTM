BlueSTM

einfaches Projekt um mit dem STM32F via Bluetooth zu kommunizieren.

Das Protokoll ist SSP und die UUID ist dabei wichtig.

```java
    private static final UUID MY_UUID = UUID
            .fromString("00001101-0000-1000-8000-00805F9B34FB");
```
