# 🏭 Siemens S7-300 to S7-1200 Compressor Control System Modernization

An industrial automation portfolio project documenting the complete modernization and migration of a legacy Siemens S7-300 compressor control system to a modern S7-1200 PLC architecture integrated with a SIMATIC Comfort HMI Panel using **TIA Portal**.

---

## 📌 Project Overview

Industrial compression systems require high reliability, precise pressure/temperature monitoring, and seamless operator control. This project upgrades a legacy S7-300 compressor application to a contemporary S7-1200 platform. It features structured SCL control logic, cyclic time-critical execution, comprehensive I/O signal mapping, and an intuitive HMI visualization interface for real-time plant supervision.

---

## 🏗️ System Architecture & Key Features

### 1. **Structured Control Logic & SCL Programming**
* Developed clean, modular automation code utilizing Structured Control Language (SCL) for complex interlocking, sequencing, and alarm management.
* Implemented fail-safe conditions, pressure/temperature thresholds, and automated loading/unloading cycles.

### 2. **Time-Critical Cyclic Execution (`OB30`)**
* Configured cyclic interrupt organization blocks (`OB30`) to handle time-critical sampling, sensor filtering, and PID/control loop calculations deterministically.

### 3. **HMI Integration (SIMATIC TP700 Comfort)**
* Designed a comprehensive operator interface featuring real-time graphical indicators, status displays, alarm banners, and manual/automatic control modes.
* Seamless tag mapping between the S7-1200 DBs and the HMI screen variables.

### 4. **I/O Signal Mapping & Data Management**
* Organized system variables using optimized Data Blocks (DBs) with structured data types for clear separation of inputs, outputs, timers, and setpoints.

---

## 🛠️ Hardware & Software Stack

| Component | Specification / Tool |
| :--- | :--- |
| **PLC Controller** | Siemens SIMATIC S7-1200 (CPU 1511 / S7-1200 equivalent architecture) |
| **HMI Panel** | SIMATIC TP700 Comfort Panel |
| **Engineering IDE** | Siemens TIA Portal |
| **Programming Languages**| SCL (Structured Control Language) & LAD |
| **Communication Protocol**| PROFINET Industrial Ethernet |
