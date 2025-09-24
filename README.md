
# PortFlow Monitor

**PortFlow Monitor** is a modern, real-time web dashboard that visualizes HTTP and HTTPS traffic flowing through specific network ports. Built with a sleek React frontend and a high-performance Rust backend, it provides immediate insights into your network activity with interactive graphs and intuitive metrics.

## Table of Contents

* [Features](#features)
* [Installation](#installation)
* [Usage](#usage)
* [Contributing](#contributing)
* [License](#license)

## Features

* **Real-Time Traffic Visualization**: Watch HTTP/HTTPS traffic on specific ports as it happens.
* **Interactive Graphs**: Modern, responsive charts built with React, Vite, and Shadcn.
* **High-Performance Backend**: Powered by Rust and Actix-Web for fast, reliable monitoring.
* **Customizable and Extensible**: Tailor the dashboard to track the metrics that matter most.

## Installation

### Prerequisites

Make sure you have the following installed:

* Node.js (v14 or higher)
* Rust (latest stable version)
* Cargo (Rust package manager)

### Clone the Repository

```bash
git clone https://github.com/obfusque/portflow-monitor.git
cd portflow-monitor
```

### Frontend Setup

Navigate to the `frontend` directory and install dependencies:

```bash
cd frontend
pnpm install
```

### Backend Setup

From the root directory, build the Rust backend:

```bash
cd ..
cargo build
```

## Usage

### Running the Frontend

Start the development server from the `frontend` directory:

```bash
pnpm dev
```

### Running the Backend

Start the backend server from the root directory:

```bash
cargo run
```

* Frontend: `http://localhost:3000`
* Backend: `http://localhost:8080`

## Contributing

We welcome contributions! Here's how to get started:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature/your-feature`).
6. Open a pull request.

Please follow coding standards and include tests for new functionality.

---
