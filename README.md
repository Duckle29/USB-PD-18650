# USB PD 18650

I needed a 12V 5A PSU for my Sequre S60 soldering iron, and I couldn't find any reasonably priced ones, so why not make
my own unreasonably priced one?

This uses an STM32G0 MCU with a TCPP03-M20 protection chip
A MPS programmable buck/boost to provide 5-20V output at up to 5A

The goal is currently to make a complete USB-PD supply with PPS support, but this may be dropped if I don't feel like it when I
figure out how hard it'll be. 