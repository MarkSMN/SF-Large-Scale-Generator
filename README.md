# SF-Large-Scale-Generator
# Soft Focus Large Scale Generator

A generative art tool that bridges digital composition and physical construction. This project consists of two parts:
1. A web-based composition generator that creates gradient-based rectangular layouts
2. Accompanying OpenSCAD code that generates 3D-printable components matching the digital compositions

## Overview

This project enables artists and makers to:
- Generate unique large-scale compositions (48" × 60")
- Visualize gradient effects and color relationships
- Create the physical components needed to build these compositions in the real world
- Experiment with different color combinations and layouts before printing

## Web Generator

The web interface allows you to:
- Generate random compositions with varying rectangular subdivisions
- Customize left-to-right gradient colors
- Preview compositions at scale
- Generate thin strips and full-width elements for visual interest

### Technical Details

- Built with p5.js for composition generation
- Operates on a 48" × 60" canvas (scaled for preview)
- Generates rectangles in standard widths: 4", 8", 12", 16", 20", 24"
- Heights are generated in 0.5" increments
- Real-time gradient preview

## Physical Build System

The companion OpenSCAD code generates STL files for 3D printing the physical components of each composition. These components are designed to:
- Snap together for easy assembly
- Create seamless gradient effects when printed in different colors
- Stack in 0.5" height increments
- Span widths from 4" to 48"

### Build Components

The physical system consists of:
- Interlocking base pieces in various widths
- Snap-fit joints for secure assembly
- Modular design for easy printing and assembly
- Surface texturing for gradient effects

## Usage

1. Use the web generator to create and refine your composition
2. Note the dimensions of each rectangle in your chosen design
3. Use the OpenSCAD code to generate corresponding STL files
4. 3D print the components in your chosen colors
5. Assemble according to your digital composition

## Installation

```bash
git clone https://github.com/YOUR_USERNAME/soft-focus-large-scale-generator.git
cd soft-focus-large-scale-generator
```

The web generator can be run by opening `index.html` in a browser.

## OpenSCAD Requirements

- OpenSCAD installed on your system
- Basic understanding of 3D printing parameters
- Printer capable of your desired component sizes

## Contributing

Contributions are welcome! Feel free to:
- Submit bug fixes
- Propose new features
- Share your built compositions
- Suggest improvements to the build system

## License

MIT License - Feel free to use, modify, and share!

## Acknowledgments

This project builds on the intersection of digital art generation and physical fabrication, enabling large-scale artistic works through accessible 3D printing technology.
