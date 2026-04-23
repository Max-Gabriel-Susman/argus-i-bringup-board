\# Argus I Bring-Up Board



A simplified STM32L452 bring-up/debug board designed in Altium Designer for the Argus project.



\## Purpose

This board is a minimal bench bring-up target intended to:

\- power from a 20-pin ARM JTAG connector

\- connect over JTAG

\- load and run simple firmware

\- verify reset/boot behavior

\- blink a green user LED

\- indicate power with a red LED



\## Main features

\- STM32L452CEU6

\- 20-pin ARM JTAG header

\- LP2985-33DBVR 3.3V regulator

\- red power LED

\- green user LED

\- reset pushbutton

\- test pads

\- optional SPI breakout header



\## Status

\- schematic complete

\- PCB routed

\- DRC clean

\- fabrication-ready



\## Tools

\- Altium Designer



\## Files

\- `argus\_I.PrjPcb` – Altium project

\- `argus\_I.SchDoc` – schematic

\- `argus\_I.PcbDoc` – PCB layout

\- `argus\_connectors.SchLib` / `argus\_connectors.PcbLib` – local custom library items

