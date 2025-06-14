# Launchpad

Official landing page for Salam Projects — introducing our mission, vision, and ongoing initiatives.

## Getting Started

### Standard Setup

1. Clone the repository:
   ```
   git clone https://github.com/SalamProjects/launchpad.git
   ```

2. Install Bun:
   - Using npm:
     ```
     npm install -g bun
     ```
   - Or visit [Bun installation docs](https://bun.sh/docs/installation) for other methods

3. Install dependencies:
   ```
   bun install
   ```

4. Run the development server:
   ```
   bun run dev
   ```

### Docker Setup

This project is configured to run in a Docker container for consistent and isolated builds.

#### Using Docker Compose

This is the easiest way to get the production application running.

1.  **Build and run the container:**

    From the root of the project, run:
    ```bash
    docker compose up -d --build
    ```
    This command builds the Docker image and starts the container in detached mode.

2.  **Access the application:**

    Once the container is running, you can access the application at `http://localhost:5173`.

3.  **To stop the container:**
    ```bash
    docker compose down
    ```


## Contributing

To contribute to this project:
1. Create a new branch
2. Make your changes
3. Open a Pull Request
