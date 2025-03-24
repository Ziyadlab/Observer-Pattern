# Observer Pattern Implementation

This repository contains two Java implementations of the Observer design pattern.

## Table of Contents
- [Overview](#overview)
- [Project 1: notifyactiveusers](#project-1-notifyactiveusers)
- [Project 2: sentsmstophonenumber](#project-2-sentsmstophonenumber)
- [How to Run](#how-to-run)
- [Requirements](#requirements)
- [License](#license)

## Overview
The Observer pattern is a behavioral design pattern where an object (the Subject) maintains a list of dependent objects (Observers) and notifies them of any state changes.

## Project 1: notifyactiveusers
### Description
This project demonstrates a basic implementation of the Observer pattern. The `Subject` class maintains a list of observers and notifies them of state changes. The following observer types are implemented:
- `BinaryObserver` (Displays state in binary)
- `OctalObserver` (Displays state in octal)
- `HexaObserver` (Displays state in hexadecimal)

### Key Classes
- `Subject`: Maintains the state and notifies observers.
- `Observer`: Abstract class for observers.
- `BinaryObserver`, `OctalObserver`, `HexaObserver`: Implement different state representations.
- `notifyactiveusers`: Main class that demonstrates the pattern.

## Project 2: sentsmstophonenumber
### Description
This project implements an event notification system using the Observer pattern. The `Publisher` class maintains event listeners and notifies them of file operations (`open` and `save`).

### Key Classes
- `Publisher`: Manages event listeners.
- `Editor`: Represents a file editor that notifies observers.
- `EventListener`: Interface for event listeners.
- `EmailNotificationListener`: Sends email notifications.
- `LogOpenListener`: Logs events to a file.
- `smssupportlistener`: Sends SMS notifications.
- `sentsmstophonenumber`: Main class demonstrating event-driven notifications.


