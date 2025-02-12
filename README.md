# Kepler Data Parser

This Node.js project retrieves Kepler data from NASA archives, reads and parses a CSV file, and automates execution using `nodemon`.

## Features
- Reads Kepler exoplanet data from a CSV file.
- Parses and processes the data for analysis.
- Uses `nodemon` for automatic execution on file changes.

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
   ```

2. Install dependencies:
    ```
    npm install
    ```
## Usage
To run the script, use:
```
    node index.js
```

or with nodemon for automatic execution on changes:
```
    npx nodemon index.js
```
## File Structure
```
    /repo
    │── kepler_data.csv            # Kepler Data file
    │── index.js                   # Main script for reading and parsing CSV
    │── package.json               # Project dependencies and metadata
    │── README.md                  # Documentation
```

## Dependencies
- nodejs
- nodemon
- csv-parse
- fs

## Contributing

- Feel free to submit issues or pull requests if you'd like to improve this project.

## License

- This project is licensed under the MIT License.