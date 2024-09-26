
# 🚀 KUPath: Shortest Paths in Kathmandu University
## What is the project about?
This project demonstrates key concepts of graph theory through an interactive web application. It allows users to explore paths, find minimum spanning trees, search for nodes, and calculate the shortest path between nodes (e.g., the Library, Football Field, Departmental Blocks, Canteen, etc.) within Kathmandu University. The application serves as a practical tool for visualizing and interacting with various graph algorithms in a real-world environment.



## Features

- **Visualize Graphs:** Display all collected paths between locations on the Kathmandu University campus.
- **Minimum Spanning Tree (MST):** Illustrates the most efficient connection between all nodes.
- **Node Search:** Allows users to find specific nodes such as the library, department buildings, or recreational areas.
- **Shortest Path:** Compute and display the shortest path between two nodes, such as between the Department of Computer Science and Engineering and the KU Library.


## Installation

- **Clone the Project**

```bash
git clone https://github.com/Nischal-Karki-1/KUPath.git
```
- **Install Backend Dependencies**
Navigate to the ```backend``` folder and install the required dependencies using:

```bash
pip install -r backend/requirements.txt
```
- **Install Frontend Dependencies**
Navigate to the ```frontend```frontend folder and install dependencies using:
```bash
cd frontend  
npm install --force
```
- **Run the Application**
Open two terminals to run the backend and frontend servers.

 -   #### Backend Terminal
 ```bash
cd backend
fastapi dev main.py
```
-   #### Frontend Terminal
 ```bash
cd frontend
npm start
```

   
## Screenshots
# Demo Images

- ### Home Page
<div align="center">
    <img src="https://github.com/user-attachments/assets/900aede2-b6a9-4d38-823b-023bca5db12d" alt="Home Page" width="600">
</div>

- ### Showing All Paths in the University
<div align="center">
    <img src="https://github.com/user-attachments/assets/7d0c6d6f-089c-4ca8-abed-45577ffad3a4" alt="All Collected Paths" width="600">
</div>

- ### Searching a Node
<div align="center">
    <img src="https://github.com/user-attachments/assets/9fbbad0f-86e6-470a-9fee-0ba75ec3f046" alt="Searching a Node" width="600">
</div>

- ### Showing Shortest Path
<div align="center">
    <img src="https://github.com/user-attachments/assets/50e7369c-3e60-494a-a890-e1f517d10f0e" alt="Shortest Path" width="600">
</div>

- ### Showing Minimum Spanning Tree
<div align="center">
    <img src="https://github.com/user-attachments/assets/9d4fb1c6-a9ee-4501-b327-1d0be3fe4af3" alt="Minimum Spanning Tree" width="600">
</div>

