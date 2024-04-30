# SVG-Logo-Maker
Module 10 Challenge

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


## Table of Contents:
- [Description](#Description)
- [Acceptance Criteria](#Acceptance-Criteria)
- [Technologies](#Technologies)
- [Installation](#Installation)
- [Usage](#Usage)
- [Preview / Screenshot](#Preview-Screenshot)
- [Contact](#Contact)
- [Output](#Output)
- [References](#References)
- [License](#License)


# Description
This is a command-line application that helps freelance web developers generate basic logos for their projects.

## Acceptance Criteria
- When prompted for text, you can enter up to three characters.
- When prompted for the text color, you can enter a color keyword or a hexadecimal number.
- When prompted for a shape, you will be presented with a list of shapes to choose from: circle, triangle, and square.
- When prompted for the shape's color, you can enter a color keyword or a hexadecimal number.
- After entering input for all the prompts, an SVG file named logo.svg will be generated in the current directory.
- The command line will output "Generated logo.svg" once the file is created.
- Open logo.svg in a web browser to view a 300x200 pixel image that matches the criteria you entered.

## Technologies
- Node.js
- jest
- Inquirer

## Installation
To install this application:
- Simply clone the repository
- run `npm install` & `npm init -y` to install the required dependencies.

## Usage
To generate a logo, run the command-line application and follow the prompts to input text, text color, shape, and shape color. After providing all the necessary inputs, a `logo.svg` file will be created in the current directory.
```bash
## Run Command
node index.js

## To Verify 
- use the command "npm test" in your terminal then follow prompt.

```

## Preview / Screenshot
![alt text](SVG-Logo-Maker.gif)

## Contact
For more projects and information about the developer, please visit:
 - https://ajfizzle.github.io/SVG-Logo-Maker
 - https://github.com/ajfizzle/SVG-Logo-Maker

## Output
The application generates a 300x200 pixel SVG file named "logo.svg" that reflects your chosen text, text color, shape, and shape color. You can open this file in any web browser to view your logo.

## References:
- UT Austin Bootcamp - UTA-VIRT-FSF-PT-02-2024-U-LOLC
- https://www.npmjs.com/package/inquirer/v/8.2.4
- https://developer.mozilla.org/en-US/docs/Web/SVG/Element/
- https://www.w3schools.com/graphics/

## License
- This project is licensed under the MIT License.