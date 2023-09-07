# RCCG Performance Management Automation

## Overview

This project is designed to automate performance management tasks for RCCG (Redeemed Christian Church of God)  for vision 2032 using Selenium, Python, and data analysis libraries. It allows authenticated users to log in to RCCG's systems, extract tables and reports, and perform data analysis. The results can be saved to a PostgreSQL database for further analysis and reporting.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)

## Prerequisites

Before using this automation tool, make sure you have the following prerequisites installed:

- Python (version 3.x)
- Selenium WebDriver (Python bindings)
- Required Python libraries for data analysis (e.g., pandas, numpy, matplotlib)
- PostgreSQL database
- Chrome or Firefox web browser
- Web driver executable (e.g., ChromeDriver or GeckoDriver) compatible with your browser version
- RCCG system credentials (username and password)

## Installation

1. Clone this GitHub repository:


2. Install the required Python packages using pip:


3. Download and configure the appropriate web driver executable (ChromeDriver or GeckoDriver) for your browser. Ensure the driver executable is in your system's PATH or specify its location in your script.

## Usage

1. Navigate to the project directory:


2. Modify the script to include your RCCG system credentials and customize data analysis tasks.

3. Run the script:


This will execute the automation process, including logging in, extracting data, performing analysis, and saving results to a PostgreSQL database.

## Configuration

- **Credentials**: In the script, provide your RCCG system credentials (username and password) to enable automated login.

- **Database Connection**: Configure the connection details (e.g., host, port, username, password) for your PostgreSQL database in the script.

- **Web Driver Configuration**: Ensure that the web driver executable (e.g., ChromeDriver or GeckoDriver) is correctly configured with the appropriate browser settings.

## Contributing

Contributions to this project are welcome! Feel free to submit bug reports, feature requests, or pull requests. Please follow the contribution guidelines and code of conduct.

## License

This project is licensed under the [MIT License](LICENSE).
