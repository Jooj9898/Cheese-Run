# 🎮 Embedded Systems 2D Game on STM32F031x6

In this project, I developed a 2D interactive game on an **STM32F031x6 microcontroller**, showcasing my proficiency in embedded systems, real-time processing, and low-level hardware interfacing.

---

## 🔧 **Key Technical Features**

### 🎨 **Display & Graphics Handling**
- Rendered pixel-based graphics on a **16x16 pixel display** using custom graphics arrays.
- Implemented the `putImage()` function to render images on specific coordinates.
- Enabled **sprite flipping** to support character movement animations.

### 🕹️ **GPIO & Input Handling**
- Managed **user inputs** (up, down, left, right) via GPIO pins with software debouncing and pull-up resistors.
- Configured inputs using the `pinMode()` function and implemented efficient polling for real-time responsiveness.

### ⏱️ **Real-Time Processing**
- Designed a **game loop** to handle:
  - User input.
  - Character movement.
  - Frame-by-frame display updates.
- Utilized a **SysTick interrupt** with a 1 ms timer resolution for time-sensitive tasks like delays and animations.

### ⚠️ **Collision Detection & Interaction**
- Developed a **collision detection algorithm** using geometric checks to detect sprite overlap with target areas.
- Enabled interactions such as:
  - Hitting obstacles.
  - Completing in-game tasks.

### 🚀 **Optimized Performance**
- Streamlined game logic, including input polling and graphics rendering, for optimal speed and memory usage.
- Leveraged efficient delay functions based on the SysTick timer for non-blocking, precise timing.

### 🛠️ **Low-Level System Configuration**
- Directly manipulated microcontroller registers for:
  - GPIO pin configuration.
  - Interrupt enablement.
  - System clock management.
- Gained hands-on experience with the **STM32 hardware architecture**.

---

## 💻 **Project Overview**
This project highlights my ability to design and implement a functional and interactive game on a resource-constrained microcontroller platform. It required a deep understanding of:
- Embedded systems principles.
- Real-time constraints.
- Hardware-software integration.

---

## 📽️ **Demonstration**
Watch the project in action on YouTube:  
[![YouTube Demo](https://img.shields.io/badge/Watch-Demo-red?logo=youtube)](https://www.youtube.com/watch?v=ijorRK4l044&ab_channel=CillianQuinn) 

