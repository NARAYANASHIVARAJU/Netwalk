Netwalk
classic Pipe Puzzle Game implemented in C++ using the SFML (Simple and Fast Multimedia Library) framework.
 Pipe Puzzle Game (C++ & SFML)

 Description  
This is a **Pipe Puzzle Game** implemented in **C++** using the **SFML (Simple and Fast Multimedia Library)** framework.  

The goal is to **connect the server to all computers** by rotating the pipes until the signal flows through the entire network. Each tile contains a pipe segment that can be rotated with mouse clicks. Once connected correctly, the computers light up, showing a successful connection.

---

 Features
- Randomly generated puzzle grid on each run  
- Click to rotate pipes clockwise  
- Smooth pipe rotation animation  
- Server supplies connection to computers through pipes  
- Computers light up once connected to the server  

---

 Requirements
- **C++11 or higher**  
- **SFML 2.5+** (Graphics, Window, System modules)  
 Install SFML on Linux (Ubuntu):
```bash
sudo apt-get install libsfml-dev
