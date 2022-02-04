# mpr121

## Author

beserge

## Description

This tests the MPR 121 12x Capacitive Touch Sensor.  
  
On initialization failure, `MPR Init Error` will be output, and the test will halt.  
  
The test will print which buttons are currently pressed in a looping manner.  

The following data is also available.  

Filtered: "The ADC raw data outputs run through 3 levels of digital filtering to filter out the high frequency and low frequency noise encountered.  
Baseline: Read the baseline touch data. This is the 8bit value.  

## Wiring

| BMP pin | Daisy Pin |
|---------|---------|
| Power | 21 |
| GND | 40 |
| SCL | 12 |
| SDA | 13 |
