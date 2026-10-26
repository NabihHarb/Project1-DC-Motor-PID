
# Project 1: DC Motor PID Speed Control System

## Project Overview
Precise motor velocity control is fundamental in robotics, automated manufacturing, and automotive actuation. Uncontrolled DC motors experience speed fluctuations due to load variations, voltage drops, and friction. This project implements a closed-loop Proportional-Integral-Derivative (PID) speed controller using an Arduino Mega 2560 and a quadrature encoder, paired with a real-time plotting utility to analyze transient and steady-state responses.

## Why It Matters
In mechatronics systems, open-loop motor actuation is insufficient for precise motion. Implementing closed-loop control demonstrates core principles of feedback systems, real-time data logging, digital signal processing via hardware interrupts, and system tuning.

## Team Members & Roles
* **Nabih Harb** – Firmware Development, PID Controller Implementation, Hardware Integration
* **Hussein Haidar** – Data Logging Script, Serial Communication Protocol, Testing & Documentation

## Tools & Hardware Plan
* **Microcontroller & Hardware:** Arduino Mega 2560 Rev3, L298N H-Bridge Driver, 12V DC Motor with Quadrature Encoder, External Power Supply.
* **Firmware:** Arduino C++ (Interrupt-driven encoder reading, $100\text{ Hz}$ timer loop).
