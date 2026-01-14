# HueBridgePro-Rooting
Informations about the rooting for Philips Hue Bridge Pro (`BSB003`).

# UART
**Baudrate:** `921600`

# First Hello
```
AOCPU: configure PMP for memory 0xf7018000 ~ 0xf7023c00
AOCPU: configure PMP end

Starting AOCPU FreeRTOS...
AOCPU image version='bl-3.5.7 d1430ee372a6e6996304956e3d4ad44b8ff4dc35 05:50:16 2025-11-25'
AOCPU_IRQ_SEL=0x0
AOCPU_IRQ_SEL=0x0
AOCPU_IRQ_SEL=0x0
AOCPU_IRQ_SEL=0x0
[AOCPU]: mailbox init start
[AOCPU]: mailbox init end
Starting timer ...
Starting task scheduler ...
env_init: Environment MMC init done (ret=-2)
```

# Questions
- Why is it not possible to enter anything?
- Why is the baud rate different from the old bridges (`BSB002`)?
- How do we disrupt the boot process?
