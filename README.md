# Embedded Systems Security Framework (ESSEF)

ESSEF is a framework proposed to support the selection of secure solutions in embedded systems. The process begins with the selection of one or more security functional requirements, including Integrity, Authenticity, Confidentiality, and Availability. These requirements, commonly found in various studies and standardized by ISO 27034, serve as a foundation for the framework.

## Getting Started

To use ESSEF, follow these steps:

1. Select one or more security functional requirements.
2. Generate a filter containing security solutions that meet the desired criteria.
3. Explore the Database of Solutions for relevant and market-appropriate choices for embedded systems.
4. Create a sub-model of the requirement tree based on the selected solutions.

## Sub-Model Creation

For each functional requirement, a sub-model is created. Detailed analysis is then performed on the Database of Solutions to compare computational resources required for their execution. Highlighted resources include FLASH memory consumption, RAM usage (static analysis), power consumption (measured during execution), and complexity.

## Resource Visualization

The identified resources are presented in a radar chart, considering factors such as FLASH memory, RAM, energy consumption, and complexity. These factors play a crucial role in the software market and directly impact project costs.

## User Selection

The final selection among solutions is left to the user, who can choose the solution with the best performance in each of the mentioned factors.

## Contributing

If you want to contribute to ESSEF, please follow our [contribution guidelines](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).
```

Feel free to customize the content further based on specific details or requirements for your framework.
