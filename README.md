# CPEN-412
# Embedded 68k Microcomputer System Design - DE1 SoC    
*System Verilog, C
  * Engineered microcomputer system with a soft-core Motorola 68k processor on an Altera DE1-SoC FPGA platform.
  spanned memory architecture, peripheral interfacing, firmware development, real-time systems, and networking   <br>
  * Built a full memory hierarchy with 64 MB SDRAM, 256 KB SRAM, and 32 KB ROM; created a custom SDRAM
  controller and memory-mapped I/O   <br>
  * Wrote a 68000 debug monitor in C with integrated memory diagnostics and bootloader functionality from SPI
  Flash   <br>
  * Interfaced 3 analog sensors and 2 memory peripherals over I2C; constructed C drivers for EEPROM and
  ADC/DAC modules, enabling real-time analog input capture and programmable waveform output   <br>
  * Boosted CPU clock speed from 25 MHz to 45 MHz, utilizing both direct-mapped and set-associative cache designs,
  increase speed by 1.67 times   <br>
  * Ported uC/OS-II RTOS to a custom 68k system and executed a multithreaded application with task scheduling and
  synchronization   <br>
# Cosmic Impalas on 68k FPGA System    
*System Verilog, C
  * Interfaced a VGA framebuffer to the 68k memory space, enabling pixel-level control and display, mapping a
  256×224 monochrome bitmap to a 640×480 VGA screen   <br>
  * Created 8 KB dual-port pixel buffer and combinational graphics adapter to translate legacy Midway8080 memory
  layout to VGA-compatible output   <br>
  * Executed a real-time hardware timer with interrupt handling, Ported and modified the original C-based game logic,
  and Validated system via a real-time graphics test and gameplay demo   <br>

