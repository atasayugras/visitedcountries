# Travel Tracker App

---

## Description
The **Travel Tracker** application allows users to track the countries they have visited. Built with Node.js, Express, and EJS, this app interacts with a PostgreSQL database hosted on Render to manage country data efficiently.

---

## Features
- **Add countries** to your visited list by entering the country name.
- **Display total number of visited countries** on the home page.
- **Dynamic user interface** that visually highlights the countries visited.

---

## Dependencies
This project relies on the following packages:

- **Express**: Fast, unopinionated, minimalist web framework for Node.js.
- **EJS**: Embedded JavaScript templating for rendering HTML views.
- **pg**: Non-blocking PostgreSQL client for Node.js.
- **dotenv**: Module for loading environment variables from a `.env` file into `process.env`.
- **body-parser**: Middleware for parsing request bodies.

---

## Database
This project utilizes a PostgreSQL database to store country data, including country codes and names, as well as a record of visited countries.

### Tables Used:
- **countries**: Stores the country codes and names.
- **visited_countries**: Records the countries that have been visited by the user.

---

## Getting Started
### Prerequisites
- Node.js installed on your machine.
- PostgreSQL database (e.g., Render).

---

### Installation

Follow these steps to set up the project locally:

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

2. **Install dependencies**:
```bash
npm install
```

3. **Create a .env file with your database credentials**:
```bash
   PORT=3000
   DB_USER=<your_db_user>
   DB_HOST=<your_db_host>
   DB_NAME=<your_db_name>
   DB_PASSWORD=<your_db_password>
   DB_PORT=5432
```

4. **Start the server**:
```bash
node index.js
```

---

### Directory Structure
```bash
.
├── public/            # Static assets (CSS, JS, images)
├── views/             # EJS templates
├── config/            # Database configuration
├── .env               # Environment variables
├── package.json       # Project dependencies
└── index.js           # Main server file
```

---

### Contributing
Feel free to fork the repository and submit pull requests for any improvements or new features!

---

### License
This project is licensed under the MIT License.

---

### Instructions for Use
Replace these:
```bash
<repository-url>
<repository-folder>
``` 
with the actual URL and name for your project. Add or modify sections as needed based on your project specifics or to include any additional relevant information.
