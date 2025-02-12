# Kepler Data Parser

![Kepler Data Parser](https://www.cnet.com/a/img/resize/2b95a3aac72da3e380d70e9cc6fede1690780018/hub/2016/12/12/93950424-fb73-4d17-a234-90afbf2aca3a/sci2016-05.jpg?auto=webp&fit=crop&height=900&width=1200)

[![Node.js](https://img.shields.io/badge/Node.js-18.x-green?logo=node.js)](https://nodejs.org/)
[![CSV Parsing](https://img.shields.io/badge/CSV-Parsing-blue)]()
[![OS](https://img.shields.io/badge/OS-Linux%20%7C%20Windows%20%7C%20MacOS-lightgrey)]()
[![Automated Execution](https://img.shields.io/badge/Automation-Nodemon-orange)](https://www.npmjs.com/package/nodemon)
[![License](https://img.shields.io/badge/License-MIT-blue)](LICENSE)
[![Last Commit](https://img.shields.io/github/last-commit/Martell0x1/Kepler-DataAnalysis-Nodejs)]()

⭐ Star us on GitHub — it motivates us a lot!

[![GitHub Stars](https://img.shields.io/github/stars/Martell0x1/Kepler-DataAnalysis-Nodejs?style=social)](https://github.com/Martell0x1/Kepler-DataAnalysis-Nodejs)

This Node.js project retrieves Kepler data from NASA archives, reads and parses a CSV file, and automates execution using `nodemon`.

## Features
- 📡 Retrieves Kepler exoplanet data from NASA archives.
- 📊 Parses CSV files efficiently.
- 🔄 Uses `nodemon` for automatic execution on file changes.

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