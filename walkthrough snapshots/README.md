<h1 align="center">Walkthrough Snapshots for TrafficSync</h1>

This folder contains step-by-step snapshots illustrating the working of the TrafficSync project. Below is a brief walkthrough of each snapshot to guide you through the functionality of the project.

### 1. 4-Way Junction Simulation
![4-Way Junction Simulation](./4_Junction_Simulation.png)
This snapshot demonstrates the simulation of a 4-way traffic junction, highlighting the dynamic car loading based on traffic density.

### 2. Google Maps Real-Time Integration
![Google Maps Real-Time Integration](./Google_Map_Real_Time.png)
This snapshot showcases the integration of real-time Google Maps data to calculate traffic density dynamically.

### 3. Traffic Density Analysis and Adaptive Rendering
![Traffic Density Analysis and Adaptive Rendering](./Traffic_Density_Analysis_and_Adaptive_Rendering.png)
Here, the project's adaptive rendering feature is shown, where traffic density is analyzed, and cars are added or removed dynamically to reduce congestion.

---

### Additional Details
- **Online Mode**: Simulates traffic density using real-time data rendered from Google Maps. Due to API restrictions, this mode works only on localhost and is not functional on Vercel.
- **Offline Mode**: Simulates a high-density traffic scenario by default without relying on Google Maps data. This mode is used for deployment on Vercel.

For more details on setting up and running the project, refer to the main repository documentation. 
