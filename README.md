# Vehicle Builder

## Project Overview

This project is made to display a TypeScript command-line application that builds and uses cars to have additional options for motorbikes and trucks. The application prompts the user to create a new vehicle or select an existing vehicle. After going through the creation process or the selection process, the user is able to perform certain actions with the selected vehicle. The user is returned to the actions menu after each action until they decide to exit the application.

## Table of Contents

- [Usage](#usage)
- [Instructions](#instructions)
- [Key Features](#key-features)
- [Technology Stack](#technology-stack)

## Usage

The application will use [Inquirer](https://www.npmjs.com/package/inquirer) for collecting input from the user. The application will be invoked by using the following command:

```bash
npm run start
```

## Instructions

1. The application prompts the user to create a new vehicle or select an existing vehicle

2. After the vehicle is created or selected, the user can perform actions with it, such as driving or using other vehicle features

3. The user can continue performing actions with the vehicle until they choose to exit

## Key Features

* **Vehicle Selection:** Allows the user to select from existing vehicles that have already been created.
* **Vehicle Creation:** Prompts the user to create a new vehicle by providing necessary details like vehicle type (car, truck, motorbike), make, model, etc.
* **Vehicle Actions:** After selecting a vehicle, the user can perform various actions (e.g., drive, park, etc.) and see the result in the command line interface.
* **Dynamic Actions Menu:** After completing an action, the user is returned to the main actions menu, where they can continue interacting with the vehicle until they choose to exit.

## Technology Stack

This application needs the following tools and technologies to operate:
* **Inquirer:** Collects user input for creating or selecting vehicles and performing actions.
* **Node.js:** Executes the command-line interface for vehicle creation and management.
