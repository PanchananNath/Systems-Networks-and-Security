# Embedded Systems, Edge & TinyML

> **Section:** 01 · Systems · **Level:** Intermediate

Running software — and ML models — on constrained devices.

## Core subjects

- [ ] Microcontrollers (ARM Cortex-M, ESP32, RISC-V MCUs)
- [ ] RTOS concepts (FreeRTOS, Zephyr)
- [ ] Peripherals: GPIO, I2C, SPI, UART, DMA
- [ ] Power management
- [ ] TinyML: quantisation, pruning, early-exit networks, on-device inference
- [ ] Frameworks: TensorFlow Lite Micro, CMSIS-NN

## Key references

- Warden & Situnayake — *TinyML* (O'Reilly)
- Lin et al. — *MCUNet: Tiny Deep Learning on IoT Devices* (NeurIPS 2020)
- Zephyr and FreeRTOS documentation

## Lab ideas

- Deploy a quantised classifier on an ESP32/Cortex-M and measure latency and energy
- Add an early-exit branch to a CNN and measure accuracy vs. latency on a Raspberry Pi

## Related

- [Compilers & ML Compilers](../03-compilers/)
- [IoT & Embedded Security](../../03-security/09-iot-embedded-security/)

## Notes

Add notes as separate files in this folder (e.g. `notes-<subtopic>.md`) using [`templates/topic-note.md`](../../templates/topic-note.md).
