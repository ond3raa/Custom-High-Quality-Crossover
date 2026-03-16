# Description
This is an audio crossover. Its function is to take an audio signal and split it into multiple speakers based on specific frequencies. It is used in speaker cabinets and sound systems to achieve the correct sound.

# How to use
The usage is quite simple: just assemble the PCB, solder the cables from the amplifier to the input, and connect the mid-bass speaker to the "woofer" output and the tweeter to the "tweeter" output.

# Why I made this
I created this project because I built speaker cabinets using car speakers and wired them the same way they were in the car. At frequencies around 2-10kHz, both speakers played simultaneously due to the missing 2nd-
order crossover, and the sound was sharp and aggressive. I designed this 2nd-order crossover to audibly eliminate this problem and improve the overall sound quality.

# Firmware & Software
This project is a passive analog audio crossover. It uses only discrete components, including capacitors, inductors, and resistors for frequency filtering. There are no microcontrollers or integrated circuits involved, so no firmware is required for this project to operate.

# BOM
