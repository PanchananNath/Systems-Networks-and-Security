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

- 🎓 [MIT 6.5940 TinyML and Efficient Deep Learning Computing](https://hanlab.mit.edu/courses/2024-fall-65940) — Song Han · MIT
- 📘 [Machine Learning Systems (free)](https://mlsysbook.ai/) — Vijay Janapa Reddi · Harvard
- 📄 [MCUNet: Tiny Deep Learning on IoT Devices](https://arxiv.org/abs/2007.10319) — Lin et al. (NeurIPS 2020)
- 📄 [BranchyNet: Fast Inference via Early Exiting](https://arxiv.org/abs/1709.01686) — Teerapittayanon et al. (ICPR 2016)
- 🛠 [TensorFlow Lite Micro](https://github.com/tensorflow/tflite-micro)
- 🛠 [Zephyr RTOS docs](https://docs.zephyrproject.org/latest/)

<sub>📘 book · 🎓 course · 📄 paper · 📑 spec/standard · 🛠 tool/docs</sub>

## Lab ideas

- Deploy a quantised classifier on an ESP32/Cortex-M and measure latency and energy
- Add an early-exit branch to a CNN and measure accuracy vs. latency on a Raspberry Pi

## Related

- [Compilers & ML Compilers](../03-compilers/)
- [IoT & Embedded Security](../../03-security/09-iot-embedded-security/)

## Notes

Add notes as separate files in this folder (e.g. `notes-<subtopic>.md`) using [`templates/topic-note.md`](../../templates/topic-note.md).
