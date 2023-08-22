# Parking Gate ThreadPool Simulation

## Code Explanation

- The ‘ParkingGate’ class represents the parking gate with methods to enter and exit the parking area. 
- The 'lock' is used to ensure thread safety when modifying the 'available_spaces' attribute. 
- The 'car_simulation' function allows the user to simulate car entry and exit actions using different threads.
- The 'concurrent.futures.ThreadPoolExecutor' class represents a pool of worker threads that can be used to execute functions asynchronously. It provides a simple interface for submitting functions for execution and returning Future objects that represent the results of those functions and also handles concurrent car simulations.

## How to run code

1. Download the [parking_gate_threadpool.py](https://github.com/patelyash96/Parking-Gate-ThreadPool-Simulation/blob/main/parking_gate_threadpool.py) file.
2. Open a terminal or command prompt.
3. Navigate to the directory where you saved the parking_gate_threadpool.py file.
4. Run the script using the following command. 
    - python parking_simulation.py or python3 parking_simulation.py
5. After running the script, you will see prompts in the terminal asking you to simulate
    - Car entry
    - Car exit
    - Quit the simulation.
6. You can interact with the simulation by typing 'e' for car entry, 'x' for car exit, or 'q' to quit the simulation.

### Note
No additional Python libraries need to be installed for the provided parking gate simulation code to run. 
The code uses standard Python modules such as threading and does not rely on any third-party libraries. 
