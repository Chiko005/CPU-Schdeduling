# CPU-Schdeduling

# CPU Scheduling Simulator

## Overview
The **CPU Scheduling Simulator** is a graphical application that allows users to visualize and analyze different CPU scheduling algorithms. It provides an interactive interface where users can input process details and observe how scheduling decisions affect execution order, turnaround time, and waiting time.

## Features
- Supports multiple scheduling algorithms:
  - **First Come First Serve (FCFS)**
  - **Shortest Job Next (SJN)**
  - **Priority Scheduling**
  - **Round Robin (RR)**
  - **Shortest Remaining Time First (SRTF)**
- Dynamic Gantt chart generation.
- Performance metrics calculation (turnaround time, waiting time, response time).
- Customizable background and UI themes.
- Real-time simulation of scheduling execution.
- Exportable results for analysis.

## Installation
### Prerequisites
- **Java Development Kit (JDK 8 or later)**
- **Maven** (for dependency management)
- **An IDE** (IntelliJ IDEA, NetBeans, or Eclipse recommended)

### Steps
1. Clone the repository:
   ```sh
   git clone [repository_link]
   ```
2. Navigate to the project directory:
   ```sh
   cd CPU-Scheduling-Simulator
   ```
3. Compile the source files:
   ```sh
   javac -d bin src/main/java/*.java
   ```
4. Run the application:
   ```sh
   java -cp bin SchedulingGUI
   ```

## Usage
1. Open the simulator.
2. Enter process details (arrival time, burst time, priority, etc.).
3. Select a scheduling algorithm.
4. Click "Run" to execute the simulation.
5. View the Gantt chart and performance metrics.

## Technology Stack
- **Programming Language:** Java (Swing, AWT for GUI development)
- **Build Tool:** Maven
- **Version Control:** GitHub
- **Development Environment:** IntelliJ IDEA / NetBeans / Eclipse

## Future Enhancements
- Multi-core CPU scheduling support.
- Performance comparison across different algorithms.
- Web-based implementation using modern JavaScript frameworks.
- AI-driven optimization for scheduling decisions.

## Contributors
- Ashish K. Dash

## Contact
For any issues or improvements, feel free to raise an issue or contribute to the repository.


