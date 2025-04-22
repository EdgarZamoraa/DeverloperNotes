# Conectar Zebra DS457

## Conectar escaner
## Abrir Scan123
```
Zebra_123Scan_64bit_v6.00.0033.exe
```
[Scan123](https://www.zebra.com/us/en/support-downloads/software/scanner-software/123scan-utility.html)

tenermos que abrir el programa pero antes conectar el escaner despues validamos que lo detecta la aplicacion scan123 de zebra
## Configurar Escaner

El escaner se configura a diferentes tipos ya sea
- **HID Keyboard Emulation**: es te lo que hace es que escanea es cualquier entrada de texto y al final ejecuta la tecla enter, practicamente emula el comportamiento del teclado
- **SNAPI**: permite establecer una comunicación entre el escáner y un host USB mediante el protocolo SNAPI. Este protocolo se utiliza principalmente en aplicaciones que requieren interfaces USB OPOS (Se usa un SDK dentro de la aplicacion para acceder a los eventos del dispositivo en el sistema)

## Instalar SDK ZEBRA
```
Zebra_Scanner_SDK_(64bit)_v3.07.0005.exe
```
[Zebra Scanner SDK](https://www.zebra.com/us/en/support-downloads/software/scanner-software/scanner-sdk-for-windows.html?downloadId=7a204d66-3110-48e8-98c9-7adc1fa4b5b3)
