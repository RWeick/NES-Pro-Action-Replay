# NES-Pro-Action-Replay
Everything necessary to produce the Pro Action Replay for the NES. Happy making.

The PAL's logic decodes to:

/SRAM.CS1.OE = ROMSEL.Sys and Addr: 0x5000 - 0x5FFF

/CPU_FF_CLK = /ROMSEL.Sys and PPU_EN and Addr: 0x7FFA

/PPU_FF_CLK = /ROMSEL.Sys and Addr: 0x7FF8

PCB Thickness: 1.6 mm

![image](https://github.com/RWeick/NES-Pro-Action-Replay/blob/main/NES3.png)
