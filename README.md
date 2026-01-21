# EleKiosk
Linux based kiosk system, launched to maintain a website
# Linux Firefox Kiosk Display

A Linux-based kiosk system built using Firefox in kiosk mode, designed to display controlled content on a virtual machine.  
The project focuses on **safe kiosk design**, **remote content updates**, and **clear system documentation**.

## Purpose
This project explores how a Linux VM can be transformed into a reliable kiosk display using open-source tools, while keeping system recovery and safety in mind.

## Why Firefox Kiosk
- Native kiosk support
- Preinstalled on Ubuntu
- Reliable keyboard and TTY escape paths
- Ideal for dashboards and display-only applications

## Safety Philosophy
The kiosk is developed with a strict rule:
> Never enable auto-login or system startup until manual exits are verified.

Emergency exit methods and timed auto-exits are always tested first.

## Tech Stack
- Ubuntu Linux (VM)
- Firefox (kiosk mode)
- Bash scripting
- GitHub (documentation & version control)
///Thats beginning notes for the project, will help following along and creating something meaningful

