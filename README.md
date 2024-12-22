# Comprehensive Car Accident Analysis Programme

This project is a software designed to provide detailed analysis related to car accidents and insurance policies by integrating multiple specialized modules. Its main goal is to offer an interactive tool that enables users to calculate insurance premiums, compare cities based on accident statistics, and generate detailed reports in JSON format.

## Key Features

    Insurance Module (IM):
        Calculates car insurance policy premiums based on location and driver parameters.
        Allows management of driver profiles, including updating details and generating .txt reports.

    City Comparison Module (LS):
        Analyzes accident statistics in various cities, including severity and counts.
        Recommends the most suitable city based on user preferences.

    Report Generation Module (EH):
        Creates JSON files with data on traffic accidents and weather conditions in analyzed cities.

## Project Structure

The project is organized into independent modules to ensure scalability and maintainability:

    modulo_MAIN: Contains the main file (main.cpp) that integrates all module functions.
    modulo_Database: Provides the database to store and manage relevant data.
    modulo_IM: Handles insurance calculations and driver profile management.
    modulo_LS: Analyzes accident statistics and offers recommendations.
    modulo_EH: Generates JSON reports based on database information.

## Requirements

    C++ compiler compatible with C++11 or later (e.g., g++).
    Operating system with terminal support.

Compilation and Execution Instructions

    Clone this repository:

git clone [https://github.com/imartinnez/DB_Analysis_Poryect]
cd your-repository

Compile the project:

g++ modulo_MAIN/main.cpp modulo_Database/Database.cpp modulo_EH/GenerateJSON.cpp modulo_IM/CarModelList.cpp modulo_IM/Driver.cpp modulo_IM/FileGenerator.cpp modulo_IM/Policy.cpp modulo_IM/PriceCalculator.cpp modulo_LS/City.cpp modulo_LS/CityComparator.cpp modulo_LS/DriverProfile.cpp -o PROGRAMA

Run the program:

    ./PROGRAMA

## Credits

Developed by Iñigo Martínez as part of an integrated system for car accident analysis.
