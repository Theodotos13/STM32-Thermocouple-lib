This is a library for using thermocouples and thermistors with STM32 microcontrollers.
Features:
Temperature measurement using a thermocouple connected to an STM32 ADC input via an operational amplifier.
Measurement of the actual cold-junction temperature using an NTC or PTC thermistor.
Cold-junction temperature compensation for thermocouple measurements.
Thermocouple usage without cold-junction temperature measurement (a fixed room temperature is specified for compensation purposes).
Temperature measurement using NTC or PTC thermistors.
Temperature measurement using a thermocouple connected to the STM32 via a MAX6675 chip.
Connection of an external reference voltage source for higher-precision temperature measurement without using the MAX6675.
Function definitions and their arguments are documented in the thermocouple.c file in both Russian and English.
