# Electronic Piano PCB

A simple electronic piano built using the NE555 timer IC in astable mode. Different push buttons generate different musical tones by changing the RC timing network.

## Features

- Four musical notes
- NE555 Timer based design
- Single-layer PCB
- EasyEDA schematic and layout
- Simple and low-cost design

## Components

| Component | Value |
|------------|---------|
| NE555 Timer | 1 |
| Resistors | 1kΩ |
| Capacitor C1 | 10µF |
| Capacitor C2 | 100nF |
| Push Buttons | 4 |
| Speaker/Buzzer | 1 |
| 5V Supply | 1 |

## Working Principle

The NE555 timer operates in astable mode.

Each push button connects a different resistor value into the timing circuit.

Changing the RC time constant changes the output frequency.

The output square wave drives a speaker to generate sound.

## Project Structure

```
electronic-piano-pcb/
│
├── schematic/
│   └── piano_schematic.png
│
├── pcb-layout/
│   └── piano_layout.png
│
├── gerber/
│   └── gerber_files.zip
│
├── gcode/
│   └── milling_files.nc
│
└── README.md
```

## Tools Used

- EasyEDA
- PCB CNC Milling
- NE555 Timer IC

## Future Improvements

- Add more keys
- Use microcontroller-based tone generation
- Add amplifier stage
- Add volume control

