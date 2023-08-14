# StreamlitDBAdmin

StreamlitDBAdmin provides an interactive and user-friendly interface to manage and interact with various databases. Easily view, edit, and manage your database schemas and tables right from the web interface.

## Table of Contents

1. [Features](#features)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Configuration](#configuration)
5. [Contributing](#contributing)
6. [License](#license)

## Features

- **Database Connection**: Connect to various database types with specified credentials.
- **Schema and Table Viewing**: Retrieve and display a list of schemas and tables.
- **Table Data Viewing and Editing**: View paginated table data and edit it directly within the interface.
- **Error Handling and Logging**: Robust error handling and logging for troubleshooting.
- **Performance Optimization**: Utilizes connection pooling for efficient database connections.

## Installation

To install StreamlitDBAdmin, follow the steps below:

```bash
# Clone the repository
git clone https://github.com/your-username/streamlit-db-admin.git

# Navigate to the directory
cd streamlit-db-admin

# Install the required dependencies
pip install -r requirements.txt

# Run the Streamlit app
streamlit run app.py
```

## Usage

Once the app is running, open your web browser and navigate to http://localhost:8501 to access the tool.

## Configuration

You can configure the database connection by setting the following environment variables:

DB_TYPE: The type of database (e.g., "postgresql")
DB_DATABASE: The name of the database
DB_HOST: The host of the database
DB_PORT: The port of the database
DB_USER: The username for the database connection
DB_PASSWORD: The password for the database connection

## Contributing

Contributions are welcome! Please read our Contributing Guide for more information on how to contribute.

## License

StreamlitDBAdmin is licensed under the MIT License. See the LICENSE file for more details.
