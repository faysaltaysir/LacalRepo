# ESP32 Library Integration

This guide provides step-by-step instructions on how to integrate the ESP32 library into the Arduino IDE, including the process of adding ESP32 Sketch Data Upload capability.

## Table of Contents

- [ESP32 Library Integration](#esp32-library-integration)
  - [Table of Contents](#table-of-contents)
  - [About the Library](#about-the-library)
  - [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
    - [Adding ESP32 Sketch Data Upload](#adding-esp32-sketch-data-upload)
  - [Usage](#usage)
  - [Contributing](#contributing)
  - [License](#license)
  - [Acknowledgements](#acknowledgements)

## About the Library

Briefly describe what the ESP32 library is, its purpose, and any features it provides. Include links to the official documentation or GitHub repository.

## Getting Started

Follow these steps to integrate the ESP32 library into the Arduino IDE.

### Prerequisites

- [Arduino IDE](https://www.arduino.cc/en/software) installed on your computer.
- Internet connection for library download.

### Installation

1. Open the Arduino IDE.
2. Go to `File` > `Preferences`.
3. In the `Additional Boards Manager URLs` field, add the ESP32 board manager URL:

https://dl.espressif.com/dl/package_esp32_index.json


If there are multiple URLs, separate them with a comma.

4. Click `OK` to close the Preferences window.
5. Go to `Tools` > `Board` > `Boards Manager`.
6. In the Boards Manager, type `esp32` in the search bar.
7. Click on `ESP32 by Espressif Systems` and click `Install`.

The ESP32 board and library are now integrated into your Arduino IDE.

### Adding ESP32 Sketch Data Upload

To enable ESP32 Sketch Data Upload for handling files like images, web pages, or configuration data, follow these steps:

1. Download and install the [ESP32 Sketch Data Upload Tool](https://github.com/me-no-dev/arduino-esp32fs-plugin).
2. Follow the installation instructions for the tool based on your operating system.
3. After installing the tool, restart the Arduino IDE.
4. In the Arduino IDE, go to `Tools` > `ESP32 Sketch Data Upload` to open the data upload tool.

Now, you can use the `data` folder in your sketch directory to store files that will be uploaded to the ESP32 file system when you run the Sketch Data Upload tool.

