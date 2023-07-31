# Mid-size Maven Weather API

This project builds on the work done in  the 'smallMaven' project on GitHub, with the addition of a weather API named 'OpenWeatherMap'. The program demonstrates how to work with JSON data and provides weather data from cities worldwide. It is built using Maven and Java in Eclipse IDE.

## Getting Started

To use this program, you'll need an API key from OpenWeatherMap. You can sign up for a free account to obtain the key. Once you have the key, replace the 'hope' variable in the Main.java file with your API key.

### Prerequisites

- Java Development Kit (JDK) 8 or higher
  
- Eclipse IDE or any Java IDE of your choice (Maven is included in Eclipse by default, but it may vary in other IDEs)


### Installing

1. Clone this repository to your local machine:


2. Open the project in your (Eclipse or Other )  IDE.

3. Replace the 'hope' variable in the Main.java file with your OpenWeatherMap API key.

4. Run the Main.java file to fetch weather data for a specified location.

## Features

- Fetch weather data from OpenWeatherMap API
- Demonstrate how to work with JSON data
- Use POJO classes (Plain Old Java Objects) to represent the JSON structure (The POJO classes will help map the JSON properties to Java object properties, making it easier to work with JSON data in an object- 
  oriented manner).
- Introduces Use of APIs
- Provide weather data for cities worldwide

## Optional JSON Parsing

The project includes an optional method to parse JSON to Java using Gson. The method is commented out to demonstrate using POJO classes as a more traditional way of working with raw JSON data.




## Acknowledgments


- OpenWeatherMap API: [https://openweathermap.org/](https://openweathermap.org/)




