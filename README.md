# Illumaphone

## Table of Contents
- [Overview](#overview)
- [Problem Statement](#problem-statement)
- [Objectives](#objectives)
- [Scope](#scope)
- [Software Requirements](#software-requirements)
- [Hardware Requirements](#hardware-requirements)
- [Usage](#usage)
- [Video](#video)

## Overview
illumaphone is a project aimed at developing a musical instrument that utilizes photoresistors and Arduino to detect changes in light intensity. The system generates corresponding frequencies using Chuck programming, producing sound-like music. Users can manipulate music playback and volume by interacting with the photoresistors.

## Problem Statement

To develop a musical instrument that utilizes photoresistors and Arduino to detect changes in light intensity, and generate corresponding frequencies according to the sine waves using Chuck programming, that produces sound-like music. The system should allow users to manipulate music playback and volume by interacting with the photoresistors.

## Objectives

- Detect changes in light intensity using photoresistors.
- Convert light intensity variations into electrical signals.
- Interface Arduino with Chuck to generate frequencies and sine waves.
- Use an interface to monitor the input data.
- Enable the user to control music playback and volume by waving hands/flashlight according to the light-enabled surroundings.
- Calibration process to set initial parameters for accurate operation.
- Continuous operation to handle data streams and generate sound output in real-time.

## Scope

The project aims to create a music-generation system using Arduino and photoresistors. It involves sensing changes in light intensity with photoresistors, converting them to electrical signals using resistors and Arduino’s analog input, and generating frequencies and sine waves with Chuck, integrating it with an interface to monitor the input data.

## Software Requirements

- Arduino IDE
- MiniAudicle
- ThingSpeak

## Hardware Requirements

- Arduino UNO board
- 6 x LDR (Light Dependent Resistor) resistors
- 6 x 330 ohm resistors
- Breadboard
- Jumper wires
- Alligator pins

## Usage

1. Set up the Arduino UNO board with the LDR resistors and 330 ohm resistors on a breadboard.
2. Connect the Arduino to your computer and upload the provided Arduino code (`esp_to_things`).
3. Install and configure the Arduino IDE, MiniAudicle, and ThingSpeak as per the software requirements.
4. Run the Chuck program to generate frequencies and sine waves based on the input from the Arduino.
5. Interact with the photoresistors to control music playback and volume.

## Video
https://github.com/susmav1012/Illumaphone/assets/106637847/e9697c40-1492-47f4-90fb-ec9828cbfdf7

