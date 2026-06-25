# Particle Text Generator

A small experiment that converts text into particles using Canvas and animates them into the shape of the original text.

## Overview

This project visualizes text as a particle system.

Each character is rendered off-screen, sampled as pixel data, and then reconstructed using particles that move toward target positions.

The result is a simple but expressive animation where text appears to "emerge" from chaos.

## Features

- Text-to-particle conversion using Canvas API
- Smooth particle easing animation
- Real-time input updates
- No external libraries

## How it works

1. Text is drawn on an off-screen canvas
2. Pixel data is extracted using `getImageData`
3. Bright pixels are converted into target coordinates
4. Particles are initialized at random positions
5. Each particle moves toward its assigned target point

## Usage

Open `index.html` in a browser.

Type any text into the input field.

Watch it collapse into particles and reform.

## Tech Stack

- HTML5 Canvas
- Vanilla JavaScript

## Notes

This project is a visual experiment rather than a production-ready library.

Performance may vary depending on text size and screen resolution.

## License

MIT
