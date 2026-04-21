# MSALernen

## Setup Instructions for Running the Node.js Server with SQLite Database

### Prerequisites
- Node.js (version 14 or higher)
- npm (Node Package Manager)
- SQLite3

### Installation Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/kjwesner/MSALernen.git
   cd MSALernen
   ```

2. Install the required dependencies:
   ```bash
   npm install
   ```

3. Set up the SQLite database:
   - Make sure you have SQLite installed. If not, download it from [SQLite Download Page](https://www.sqlite.org/download.html)
   - Create a new database file (e.g., `database.db`) and set up your tables as needed.

4. Configure database connection:
   - Open the configuration file (usually `config.json` or `.env`) and set the database path to your SQLite database file:
     ```json
     {
       "database": "./path/to/database.db"
     }
     ```

5. Start the server:
   ```bash
   npm start
   ```

### Running the Application
- After starting the server, navigate to `http://localhost:3000` in your browser to access the application.

### Troubleshooting
- Ensure you have the correct version of Node.js and dependencies installed.
- Check console output for any errors related to database connections or missing modules.

### License
This project is licensed under the MIT License.