# Interactive Audio Visualizer (TouchDesigner)

## Overview

An interactive audio visualizer built using **TouchDesigner** that transforms real-time audio input into dynamic visual patterns. The project reacts to sound frequencies, amplitude, and rhythm to create an immersive audiovisual experience.




https://github.com/user-attachments/assets/1dd45070-c9ec-4805-b11e-cc26ed79fc2c


https://github.com/user-attachments/assets/dea58fe3-59cb-45e8-86e2-08b8c02b9b0a





## Features

* Real-time audio input processing
* Frequency-based visual transformations
* Dynamic particle / shape generation
* Smooth, responsive animations
* Customizable parameters for visuals and audio sensitivity

## Tools & Technologies

* TouchDesigner
* Audio Device In CHOP
* Analyze CHOP / FFT
* SOPs, TOPs, and CHOPs
* GLSL / visual effects (if used)

## How It Works

1. Audio input is captured using **Audio Device In CHOP**
2. Signal is analyzed using **FFT / Analyze CHOP**
3. Extracted data (bass, mids, highs) drives visual elements
4. Visuals are generated and modified in real time using TOPs/SOPs
5. Output is rendered through a final COMP

## Controls

* Adjust audio sensitivity via CHOP parameters
* Modify visual intensity, scale, or color using UI sliders (if included)
* Toggle different visual modes (if implemented)

## Setup Instructions

1. Open the `.toe` file in TouchDesigner
2. Ensure audio input device is correctly selected
3. Click **Perform Mode** or run the project
4. Play music or provide live audio input

## Use Cases

* Live performances / VJ setups
* Interactive installations
* Music visualization experiments
* Creative coding projects

## Future Improvements

* More visual presets / themes
* MIDI or keyboard controls
* Beat detection enhancements
* Export / recording functionality

## Author

Ruthu Shetty

##Contacts

LinkedIn : https://www.linkedin.com/in/ruthushetty/
GitHub : https://github.com/RuthuShetty
