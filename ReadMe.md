# Battle Sim

## Project Overview

Battle Sim is a turn based battle simulator where you use the moves of the people that we put into the game, and simulate battles against you, your friends, and others.

## Team Information

- **Course:** CSCI 3308 - Software Development Methods and Tools
- **Team Number:** 012-3
- **Team Name:** Team Avatar

### Team Members

| Name       | GitHub Username | Email 
|------------|------------------------|---------------------|
| Max Martin | Max.Martin-2@colorado.edu | maxwellmartin1005-blip |
| Jamie Grove | Jamie.Grove@colorado.edu | jamiegrove76-pixel |
| Aidan Johnson | Aidan.Johnson-2@colorado.edu | Aidan-dev50 |
| Andre Kalberer | Andre.Kalberer@colorado.edu | AndreKalberer |
| Zander Trafton-Hancock | Zander.Trafton-Hancock@colorado.edu |ZandadaPanda96 |
| Yuan Zuo | Yuan.Zuo@colorado.edu | yuanzuo09 |

## Technology Stack

Will be updated as time goes on.
| Technology | Purpose |
|---|---|
| HTML | Structures the web pages. |
| CSS | Styles the application's user interface. |
| JavaScript | Implements client-side and server-side functionality. |
| Node.js | Runs the application server. |
| Express.js | Handles HTTP requests, routes, and communication between the interface and database. |
| Handlebars | Generates dynamic HTML pages using templates. |
| PostgreSQL | Stores user information and application data. |
| Docker | Runs the application and its supporting services in containers. |
| Docker Compose | Configures and runs the application and database together. |
| Git | Tracks source code changes. |
| GitHub | Hosts the repository and supports team collaboration and project management. |

## Prerequisites

Will be updated as time goes on.

Before running the application locally, install the following software:

- **Git:** To clone the repository.
- **Docker Desktop or Docker Engine:** To run the application containers.
- **Docker Compose:** To start and manage the application services.
- **A web browser:** To access the application.
- **Node.js and npm:** Needed if running the application or tests directly on the host machine rather than inside Docker.


## Running the Application Locally

Follow these steps to run the application on your local machine.

### Step 1: Clone the Repository

Open a terminal and run:

```bash
git clone git@github.com:ZandadaPanda96/cu-csci3308-fall2026-group-project-012-3-Battle-Sim.git
```

Navigate into the cloned repository:

```bash
cd /cu-csci3308-fall2026-group-project-012-3-Battle-Sim
```

### Step 2: Navigate to the Source Code Directory

```bash
cd ProjectSourceCode
```

### Step 3: Configure Environment Variables

Create the `.env` file described by the following:

```env
POSTGRES_USER=your_database_user
POSTGRES_PASSWORD=your_database_password
POSTGRES_DB=your_database_name
POSTGRES_HOST=db
POSTGRES_PORT=5432
SESSION_SECRET=your_local_session_secret
```

Make sure the database credentials, session configuration, and other required settings match the application's configuration.

### Step 4: Start the Application

Build and start the application and database containers:

```bash
docker compose up --build
```

Wait for the services to initialize. The database must be available before the application can successfully communicate with it.

### Step 5: Access the Application

Open your web browser and navigate to:

```text
http://localhost:3000
```

This address assumes the application maps port `3000` from the container to port `3000` on your machine.

### Step 6: Stop the Application

To stop the running containers, press `Ctrl+C` in the terminal and run:

```bash
docker compose down
```

This stops and removes the containers while normally preserving data stored in a named Docker volume.

To remove the database volume as well, use the following command only when you intend to delete the locally persisted database data:

```bash
docker compose down -v
```

### Troubleshooting

- Verify that Docker is running.
- Check that the `.env` file contains the required settings.
- Make sure the configured ports are not already in use.
- Check the container logs for errors:

  ```bash
  docker compose logs
  ```

- Confirm that the database initialization scripts run successfully.

## 6. Running Tests

The project includes automated tests to verify that the application's server and functionality behave as expected.

### Install Dependencies

If running tests directly on your machine, navigate to `ProjectSourceCode/` and run:

```bash
npm install
```

### Run the Test Suite

If the project's `package.json` defines a test script, run:

```bash
npm test
```

### Test Coverage


Will be updated as time goes on.

The test suite should verify functionality such as:

- User registration and input validation.
- User login and authentication.
- Session creation and logout.
- Communication between the server and database.
- Application-specific API endpoints.
- Appropriate responses to invalid requests.

**Note:** The commands above assume a test script is configured in `package.json`. Replace them with the actual test commands used by the project.
