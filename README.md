# # Vehicle Management System

This project is a Vehicle Management System that allows users to create and manage different types of vehicles, including Cars, Trucks, and Motorbikes. Users can perform various actions on these vehicles, such as starting, accelerating, decelerating, and towing other vehicles.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contributing](#contributing)
- [Questions](#questions)


## Installation

1. Clone the repository:
    ```sh
    git clone <repository-url>
    cd <repository-directory>
    ```

2. Install dependencies:
    ```sh
    npm install
    ```

## Usage

1. Build the project:
    ```sh
    npm run build
    ```

2. Start the CLI:
    ```sh
    npm start
    ```

## Classes and Interfaces

### Classes

- [`Vehicle`](src/classes/Vehicle.ts): Base class for all vehicles.
- [`Car`](src/classes/Car.ts): Extends `Vehicle`.
- [`Truck`](src/classes/Truck.ts): Extends `Vehicle` and implements `AbleToTow`.
- [`Motorbike`](src/classes/Motorbike.ts): Extends `Vehicle`.
- [`Wheel`](src/classes/Wheel.ts): Represents a wheel.
- [`Cli`](src/classes/Cli.ts): Command-line interface for managing vehicles.

### Interfaces

- [`AbleToTow`](src/interfaces/AbleToTow.ts): Interface for vehicles that can tow other vehicles.
- [`Driveable`](src/interfaces/Driveable.ts): Interface for driveable vehicles.


## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.

## Questions

For any questions please contact me at noguera.ke@gmail.com or https://github.com/KevNoguera