# STM32 Debug via VS Code, Task Engine & QEMU

This project demonstrates how to develop and debug STM32 microcontrollers using **Visual Studio Code**, `tasks.json`, and **QEMU**, without needing physical hardware.

## Purpose

- Show how STM32 development can be done using open-source tools
- Use QEMU to simulate STM32 hardware for development and debugging
- Create an integrated workflow using VS Code and task automation

---

## TODO 📌

### 🛠️ Project Structure

- [ ] Add a diagram or explanation of the general architecture
- [ ] Specify which STM32 model/series is targeted (e.g., STM32F1, STM32F4)

### ⚙️ Environment Setup

- [ ] Document required toolchains (e.g., `arm-none-eabi-gcc`, `qemu-system-arm`)
- [ ] List and explain VS Code extensions (e.g., Cortex-Debug, C/C++, CodeLLDB)
- [ ] Add explanation of the `tasks.json` setup and usage

### 🚀 Build & Run

- [ ] Step-by-step build instructions
- [ ] Explain how to run the compiled binary in QEMU
- [ ] Simulated flash settings, reset behavior, and memory mapping details

### 🐞 Debugging

- [ ] Explain how to start debugging via VS Code
- [ ] How to set breakpoints, step over/in, view memory/registers
- [ ] Configure GDB connection with QEMU (without J-Link/OpenOCD)

### 📦 Extra Features

- [ ] HAL vs bare-metal: explain abstraction layers used (if any)
- [ ] Add multiple tasks to `tasks.json` (e.g., build, clean, flash)
- [ ] Optional: plan for CI/CD or GitHub Actions for build checks

---

## License

MIT (or GPL v3, depending on the code base)

---

## Contributing

Feel free to open issues or pull requests! Contributions are always welcome 🙌

---

> This README is a work in progress. Feel free to suggest improvements or contribute directly! 🚀
