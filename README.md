# Decorator Practice

This repository contains a Java project that demonstrates the implementation of the Decorator design pattern. The project simulates a data source system with encryption and compression functionalities added dynamically using decorators.

## Table of Contents
- [Introduction](#introduction)
- [Usage](#usage)
- [Key Features](#key-features)
- [Project Structure](#project-structure)
- [Development](#development)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The Decorator design pattern is a structural pattern in object-oriented programming that allows behavior to be added to individual objects, either statically or dynamically, without affecting the behavior of other objects from the same class. This repository contains a Java project that showcases the use of the Decorator pattern to extend the functionality of a base data source class with encryption and compression features.

## Usage

To use the project:
1. Clone the repository to your local machine.
2. Open the project in your preferred Java development environment.
3. Review the code in the provided Java files.
4. Compile and run the Main class to see the demonstration of the Decorator pattern in action.

## Key Features

- Implementation of the Decorator design pattern in Java.
- Encryption and compression functionalities added dynamically to a base data source class.
- Clear separation of concerns between the base class and decorators.
- Modular and extensible design allowing for easy addition or removal of functionalities.

## Project Structure

The project consists of the following Java files:
- FileDataSource.java: Implements the base data source class for file operations.
- DataSource.java: Defines the interface for data sources.
- DataSourceDecorator.java: Abstract class serving as the base decorator.
- EncryptionDecorator.java: Adds encryption functionality to the data source.
- CompressionDecorator.java: Adds compression functionality to the data source.
- Main.java: Main class demonstrating the usage of decorators.

## Development

If you want to contribute to the project or make improvements:
- Fork the repository.
- Make your changes.
- Submit a pull request.


