# DroneDeliverySim3D

**DroneDeliverySim3D** is a simulation of drone delivery systems designed to model efficient routing algorithms, delivery and battery management queues, and data collection for performance analysis. This 3D simulation includes a backend service and a web interface for visualization and interaction.

---

## Features

- **Routing Algorithms**: Simulates efficient drone navigation for package deliveries.
- **Battery Management**: Implements battery queues for managing drone power resources.
- **Delivery Queues**: Organizes and prioritizes package deliveries.
- **Web Interface**: Interactive 3D visualization of the drone delivery process.
- **Documentation**: Includes auto-generated project documentation using Doxygen.

---

## Project Structure

DroneDeliverySim3D/ 
├── dependencies/ # External dependencies for the project 
│ ├── include/ # Header files for dependencies 
│ └── lib/ # Library files for dependencies
├── docs/ # Documentation files 
│ └── Doxyfile # Configuration for Doxygen 
├── service/ # Backend service code 
│ ├── include/ # Header files for the service 
│ ├── src/ # Source code for the backend 
│ └── Makefile # Build system for the service 
├── web/ # Web-based frontend 
│ ├── css/ # Stylesheets 
│ ├── public/ # Static assets 
│ ├── src/ # Source code for the web app 
│ ├── index.html # Entry point for the web app 
│ ├── package.json # Node.js dependencies 
│ ├── tsconfig.json # TypeScript configuration 
│ └── Dockerfile # Containerization for the web app 
├── .gitignore # Git ignore file 
├── Dockerfile # Containerization for the full project 
└── Makefile # Build system for the entire project

---

## Requirements

### Backend Service
- **C++ Compiler**: Compatible with the Makefile configuration.
- **Doxygen**: For generating documentation.

### Web Interface
- **Node.js**: For running the frontend web app.
- **npm** or **yarn**: For managing frontend dependencies.

---

## Getting Started

### Clone the Repository
```
bash
git clone https://github.com/danielvu04/DroneDeliverySim3D.git
cd DroneDeliverySim3D

```

---

## How It Works
  ###Backend Service:
  
  Manages the simulation logic, including routing, delivery queues, and battery management.
  Exposes an API for the web interface to interact with the simulation.
  Web Interface:
  
  Provides a 3D visualization of the simulation, allowing users to view drone movements and delivery statuses in real-time.
  Documentation:
  
  Generate the documentation using Doxygen:
    
    bash
    
    Copy code
    
    cd docs
    
    doxygen Doxyfile
   

--- 

## Contact
  If you have questions or suggestions, feel free to contact:
  
  Daniel Vu
  
  https://www.linkedin.com/in/daniel-vu04
  
  https://github.com/danielvu04
