# OO-Pattern-Music-Store-Sim
Music Store Simulation Demonstrating Object Oriented Patterns
<br/>

## Project Summary

This project is a simulation of a music shop that allows the user to choose between two stores, Northside and Southside, and run the simulation for 10 days. The project is implemented using Java version 17.0.2 and follows a well-structured object-oriented design. This project showcases proficiency in Java programming, OOP concepts, design patterns application in creating a comprehensive music shop simulation.

## Language and OOP Patterns

*   The project is written in Java, leveraging the latest version 17.0.2 of the language.
*   The codebase follows object-oriented programming principles, with a well-defined class hierarchy and the use of various design patterns.
*   The key design patterns employed in this project include:
    * Abstract Factory: Used to create different types of guitar kits (e.g., Acoustic, Electric, Bass) for the Northside and Southside stores.
    * Command: Implemented to handle user input and execute corresponding actions, such as buying, selling, and managing inventory.
    * Singleton: Used to ensure that there is only one instance of the Simulation class, which orchestrates the overall execution of the music shop simulation.

## Class Hierarchy and Functionality

The project's class hierarchy is as follows:
*   Main: The entry point of the application, responsible for initializing and running the simulation.
*   Simulation: The central class that manages the overall execution of the music shop simulation, including creating the Northside and Southside stores, handling user input, and generating the final summary.
*   Store: Represents a music shop store, with properties and methods for managing inventory, processing customer transactions, and generating reports.
*   Staff: Handles the day-to-day operations of the store, such as buying, selling, and creating guitar kits.
*   Item: The base class for all types of items sold in the music shop, with subclasses for specific item types (e.g., GuitarKit, Guitar, Amplifier).
*   ItemType: An enumeration that defines the different types of items available in the music shop.
*   AbstractGuitarKit: An interface that defines the contract for creating different types of guitar kits.
*   NorthsideGuitarKit and SouthsideGuitarKit: Concrete implementations of the AbstractGuitarKit interface.

## Key Functionalities

The key functionalities of the project include:
*   Allowing the user to choose between Northside and Southside stores and run the simulation for 10 days.
*   Generating daily announcements of all actions during the simulation.
*   Implementing interactive user commands like "Name", "Time", "Sell", "Buy", and "Toggle".
*   Managing inventory, processing customer transactions, and calculating metrics for each store.
*   Providing a summary of simulation results at the end of 10 days.

## Assumptions and Implementation Details

The project makes assumptions such as considering every 7th day as Sunday and pricing items randomly between 1 and 50. Implementation details include representing item conditions from 1 to 5 and using ArrayLists to manage items.

## Key Learnings
Applying Object Oriented Programming principles, implementing design patterns like Abstract Factory and Command, handling user input effectively, and generating detailed reports.

## Areas for improvement
Enhancing UI/UX, expanding analytics capabilities, exploring more design patterns for scalability, and improving error handling.
