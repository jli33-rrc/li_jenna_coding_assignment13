# UI Component Library: Environment Setup

Built using React (Next.js) and Storybook, this project features a responsive UI component library that includes buttons, text, tables, images, and more. It also runs pre-commit checks for Prettier, EsLint, and Tests using GitHub actions. The application is containerized with Docker and serves the production build on localhost:8018.

## Prerequisites
- Ensure [Docker](https://www.docker.com/get-started) is installed on your machine.

---

## Steps to Run the Application

### 1. Clone the Repository

Clone this project repository and navigate to its directory:

```bash
git clone https://github.com/jli33-rrc/li_jenna_coding_assignment13.git
cd li_jenna_coding_assignment13
```

### 2. Build the Docker Image

Build the Docker Image by using the following command:

```bash
docker build -f Dockerfile.prod -t li_jenna_coding_assignment13 .
```

### 3. Run the Docker Container

Run the Docker Container by using the following command:

```bash
docker run -p 8018:8018 --name li_jenna_coding_assignment13 li_jenna_coding_assignment13
```

### 4. Access the Application

Once the container starts successfully, you can access the application in your web browser at:

- Local: (http://localhost:8018)