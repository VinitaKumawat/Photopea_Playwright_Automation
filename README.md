# Photopea_Playwright_Automation
Automation of Photopea design creation using Playwright. The script creates a canvas, adds text, shapes, and imports an image automatically.
# Photopea Automation using Playwright

This project demonstrates browser automation of the Photopea editor using Playwright.  
The automation script performs several design actions such as creating a canvas, adding text, drawing shapes, and importing an image.

## Project Overview

The goal of this project is to automate basic design operations in Photopea using Playwright. The script simulates user actions like keyboard shortcuts and mouse interactions to interact with the Photopea interface.

## Features

- Open Photopea in a browser
- Create a new canvas with the required dimensions
- Add text elements
- Draw shapes (rectangle, triangle, circle)
- Import an image into the canvas
- Demonstrate browser automation using Playwright

## Technologies Used

- Node.js
- Playwright
- JavaScript

## Project Structure
photopea-playwright-automation
│
├── tests
│ └── photopea.spec.js
│
├── package.json
├── README.md

## Prerequisites

Make sure the following tools are installed on your system:

- Node.js (version 16 or higher)
- npm
- Git
  ## Setup Instructions

### 1. Clone the repository


git clone https://github.com/YOUR_USERNAME/photopea-playwright-automation.git


### 2. Navigate to the project folder


cd photopea-playwright-automation


### 3. Install dependencies


npm install


### 4. Install Playwright browsers


npx playwright install


## Run the Automation Test

To run the Playwright test:


npx playwright test


The script will open Photopea and perform automated design actions.

## Notes

- Photopea uses a canvas-based interface, so automation relies on keyboard shortcuts and mouse interactions rather than traditional selectors.
- Some interactions may depend on screen resolution and timing.

## Future Improvements

- Automate precise text styling (font size and colour)
- Improve shape placement
- Automate image background removal
- Add visual verification tests


