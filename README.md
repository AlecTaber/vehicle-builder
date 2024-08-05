# Vehicle Builder
  ![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
## Description 

This project prompts the user to create a car, truck, or motorbike within their terminal. The user is  prompted to give information about a vehivle they want to create and when the vehicle is created they are able to perform a series of actions based on user input. The car, truck, and motorbike prompts are different from eachother and each type of vehicle can perform specific actions .

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)
- [Tests](#tests)
- [Contact](#contact)

## Installation

You can do a 'git clone' of my repository to clone it down onto your personal computer. Make sure you have NodeJS installed on your computer. After those steps are completed, you can do a "npm i" to install Typescript and inquirer. Once you have the correct packages installed, do a "npm run start" to use this application.

## Usage

Once you have the application running in your terminal, you will be prompted with a few questions about building a vehicle. You will be asked to build a new vehicle or asked to select an already existing vehicle. If you choose to create a new vehicle, you will be asked to choose a car, truck, or motorbike. You will then be asked about the vehicles make, model, year, weight and a few other things depending on the type of vehicle you are building. After you finish building your vehicle, you will be provided with some actions that your vehicle can perform. This includes starting your vehicle, speeding up, slowing down, turning left or right, stopping the vehicle, or performing vehicle type specific actions such as towing or doing a wheelie. When the vehicle is built, you are also able to print the details you provided in your terminal. All the vehicles you create are saved and can be reselected. They will not save when you exit your terminal so you cannot enter your terminal again and select them.

## Credits

This project was created by Alec Taber

## License
  
  This project uses the MIT License. For more information, visit [license link](https://opensource.org/licenses/MIT).

## Features

**Vehicle Creation**

- Create new vehicles of different types: Cars, Trucks, and Motorbikes.
- Assign unique VINs to each vehicle using a static method.
- Customize vehicle attributes during creation:
- Car: Color, Make, Model, Year, Weight, Top Speed.
- Truck: Color, Make, Model, Year, Weight, Top Speed, Towing Capacity.
- Motorbike: Color, Make, Model, Year, Weight, Top Speed, Front Wheel (Diameter, Brand), Rear Wheel (Diameter, Brand).

**Vehicle Selection**

- Select an existing vehicle from a list to perform actions on.

**Vehicle Actions**

- Perform a variety of actions on the selected vehicle:
- Print details.
- Start the vehicle.
- Accelerate by 5 MPH.
- Decelerate by 5 MPH.
- Stop the vehicle.
- Turn right.
- Turn left.
- Reverse the vehicle.
- Tow another vehicle (if the selected vehicle is a truck).
- Perform a wheelie (if the selected vehicle is a motorbike).

**Towing Capability**

- Trucks can tow other vehicles:
- Select a vehicle to tow from the list of existing vehicles.
- Prevent trucks from towing themselves.
- User Interaction
- User-friendly command-line interface using Inquirer.js for easy interaction.
- Prompts to guide the user through creating vehicles, selecting vehicles, and performing actions.

**Vehicle Management**

- Maintain a list of created vehicles within the application.
- Ability to create, select, and manage multiple vehicles.

**Extensibility**

- Easily extendable to add more vehicle types or actions in the future.

## Tests

N/A

## Contact

- GitHub: [AlecTaber](https://github.com/AlecTaber)
- Email: [alectaber12@gamil.com](mailto:alectaber12@gamil.com)

