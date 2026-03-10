# Tutorial_Uso FPGA Tanq Nano 9K_Diseño Lógico

[0] En este tutorial se explican los primeros pasos para utilizar la herramienta FPGA Tanq Nano 9k. Iniciando desde el setup, pasando por ejemplo tipo "Hello world" llamado "BlinkyLed", además de dos ejemplos más complejos "LCD_SPI" y "Seven_Seg" y finaliza con la explicación de plantillas y sus partes para generar proyectos propios, utilizando Git y GitHub como control de versiones y repositorio.

## Indice
[0] 1. Inicio del Tutorial                     (Explicación)

[0] 2. Instalación de herramientas             (VSCode, LushayCode, Verilog, OSS-CAD-Suite)

[0] 3. Entorno de desarrollo                   (Toolchain FPGA Tanq Nano 9k)

[0] 4. Uso plantilla para proyectos            (Git & Github)

[0] 5. Ejemplo Display 7 Segmentos             (Circuito, Código, Simulación, Resultados)

## Abreviaturas y definiciones
- **FPGA**: Field Programmable Gate Arrays

## Referencias
[0] David Harris y Sarah Harris. *Digital Design and Computer Architecture. RISC-V Edition.* Morgan Kaufmann, 2022. ISBN: 978-0-12-820064-3

[0] FZumb4do. *open_source_fpga_environment.* https://github.com/FZumb4do/open_source_fpga_environment.git

[0] LUSHAYLABS. *Tang Nano 9K: Getting Setup.* https://learn.lushaylabs.com/getting-setup-with-the-tang-nano-9k/

[0] Sipeed Wiki — Tang Nano 9K: https://wiki.sipeed.com/hardware/en/tang/Tang-Nano-9K/Nano-9K.html