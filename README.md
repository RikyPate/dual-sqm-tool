# Dual SQM Tool

A simple and scientifically grounded tool to compare the performance of two photographic lenses (or the same lens in two different conditions) under varying sky brightness. It helps estimate the effective signal, signal-to-noise ratio, and exposure time equivalence across different sky quality values (SQM).

## Features
- Compare two setups with identical or different lenses.
- Input aperture (f-number), exposure time, pause, and quantum efficiency.
- Account for different sky conditions using SQM (Sky Quality Meter) values.
- Real-time calculations of:
  - Light per exposure
  - Number of effective exposures
  - Total signal and SNR
  - Exposure time equivalence between conditions
- Graph: hours required to match signal vs. SQM
- Integrated scientific guide in plain language

## How to Use
1. Open the tool in your browser (no installation required).
2. Input parameters for Lens A and Lens B (or same lens under two sky conditions).
3. Set the SQM value for each location.
4. Set total integration time and pause between shots.
5. View the computed metrics and efficiency comparison.

## Live Demo
This tool can be hosted using any static site solution. Suggested option:
- GitHub Pages (free)

## Technologies
- HTML / CSS / JavaScript
- Chart.js for visualizations

## License
This project is licensed under the MIT License — see the [LICENSE](./LICENSE) file for details.

## Acknowledgments
This tool is intended for astrophotographers, educators, and amateur astronomers who value measurable differences in sky quality. It encourages optimization and awareness of how much a dark sky can impact data acquisition.

No external libraries or frameworks are required — it runs entirely in the browser.
