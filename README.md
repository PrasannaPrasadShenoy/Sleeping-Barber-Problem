**Sleeping Barber Problem Solution (Python)**

This Python program presents a solution to the Sleeping Barber Problem, a classical concurrency problem in computer science. The scenario simulates a barbershop where a barber sleeps when there are no customers and wakes up to serve them as they arrive. The barbershop has a limited number of seats for waiting customers. If the waiting area is full, incoming customers may leave.

**Key Features:**

1. **Graphical Interface**: Utilizes Tkinter library for creating a graphical user interface (GUI) to visualize the barbershop scenario.
2. **Thread-Based Simulation**: Implements a multi-threaded approach to simulate the barber and customer behavior concurrently.
3. **Image Representation**: Integrates image representations for the barber, customers, waiting chairs, and various states of the simulation.
4. **Interactions**: Customers trigger barber actions (e.g., waking up, starting haircuts) by pressing an "ENTER" button on the GUI.
5. **Dynamic Updates**: Displays real-time updates on the GUI to reflect changes in the barbershop's state, such as customer arrivals, waiting room occupancy, and barber activity.

**Simulation Components:**

- **Barber Thread**: Represents the barber's behavior, including sleeping, waking up, serving customers, and completing haircuts.
- **Customer Thread**: Models the actions of customers, such as arriving, waiting, and either occupying a waiting seat or leaving if the waiting area is full.
- **Semaphore Mechanism**: Utilizes semaphores to manage access to shared resources like the barber's readiness and the availability of waiting seats.

**Usage:**

1. Ensure Python is installed on your system.
2. Execute the Python script (`sleeping_barber.py`).
3. The graphical interface will be displayed, representing the barbershop scenario.
4. Customers can interact with the simulation by pressing the "ENTER" button to trigger their arrival.
5. Monitor the console output for updates on the simulation's progress and events.

**Contributions:**

Contributions to this project are welcome! Feel free to submit pull requests, suggest improvements, or report issues.

