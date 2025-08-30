# 🚇 Metro Route Finder – Delhi Metro

A **C++ desktop application** for finding the shortest route between metro stations in the Delhi NCR region using **Dijkstra’s Algorithm** and a console-based interface.

---

This application reads metro station data from multiple files—like station codes, color mappings, and connection distances—to construct a weighted graph. Using Dijkstra’s algorithm, it computes and displays the optimal route between a source and destination. The console interface visualizes route steps, fare, distance, and travel time.


### 📂 Files & Structure
Metro-Route-Finder/
├── main_code.cpp # Core application implementing graph and Dijkstra logic
├── database.csv # Station and connection data
├── matrix.txt # Adjacency matrix representation
├── node_values_new.txt # Station-to-station distance definitions
├── stationcodes.txt # Station names with codes
├── stationcolorcodes.txt # Color coding for metro lines
├── Delhi Metro algo project report.pdf # Detailed project documentation
├── Mapenglish_0708182.jpg # Metro map reference
├── README.md # Project overview
├── _config.yml # Repository config (if any)
├── main_code.exe # Executable (for Windows)

---

### ✨ Key Features
- Efficient route calculation using **Dijkstra’s shortest-path algorithm**  
- Console-based route display with **color-coded line changes**  
- Shows route details: **station sequence, total distance, estimated fare, and travel time**  
- Works offline and delivers **fast performance**  
- Backed by comprehensive metro data in structured files  

---

### ⚙️ How to Run
```bash
# Step 1: Clone the repository
git clone https://github.com/HarshTiwari14/Metro-Route-Finder.git
cd Metro-Route-Finder

# Step 2: Compile the program
g++ main_code.cpp -o metro-finder

# Step 3: Execute the application
./metro-finder

# Step 4: Provide input in console
# - Enter source station
# - Enter destination station
# - (Optional) enter intermediate station
# The program will display the shortest route with distance, fare, and travel time.




Happy Coding!!


