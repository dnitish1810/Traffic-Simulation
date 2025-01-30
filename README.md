# Simplified Traffic Intersection Simulator

This Python project simulates a simplified traffic intersection to explore and visualize the effects of various traffic light control strategies on traffic flow. It was developed as part of a BScIT degree.

**Key Features:**

* **Visual Simulation:** Uses Pygame to provide a visual representation of the intersection, car movement, and traffic light changes.
* **Traffic Generation:** Randomly generates cars entering the intersection from four directions (North, South, East, West), allowing for adjustable traffic density.
* **Traffic Light Control:** Implements a basic fixed-time traffic light control system. (Can be extended to include more intelligent, traffic-responsive systems.)
* **Metrics Tracking:** Collects and displays important metrics such as average car waiting time, intersection throughput (number of cars passing through per unit time), and (optionally) collision counts.
* **Modular Design:** The code is organized into modules (car.py, traffic_light.py, etc.) for better readability and maintainability.

This simulation provides a foundation for understanding basic traffic management principles and exploring the impact of different traffic control algorithms.

## Technologies Used

* Python
* Pygame
* (Optional) NumPy  *(If you used NumPy, keep this line. Otherwise, remove it)*

## Installation


1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/TrafficSimulation.git](https://github.com/YOUR_USERNAME/TrafficSimulation.git)  *(Replace with your actual repository URL)*

## Create a Virtual Environment (Recommended):
python3 -m venv .venv  *(or python -m venv .venv depending on your system)*

## Activate the Virtual Environment
Linux/MacOs
source .venv/bin/activate

bash
.venv\Scripts\activate

## Install Dependencies
bash
pip install -r requirements.txt

## Usage
Run the simulation
python src/main.py

# Simplified Traffic Intersection Simulator

This Python project simulates a simplified traffic intersection to explore and visualize the effects of various traffic light control strategies on traffic flow. It was developed as part of a BScIT degree.

**Key Features:**

* **Visual Simulation:** Uses Pygame to provide a visual representation of the intersection, car movement, and traffic light changes.
* **Traffic Generation:** Randomly generates cars entering the intersection from four directions (North, South, East, West), allowing for adjustable traffic density.
* **Traffic Light Control:** Implements a basic fixed-time traffic light control system. (Can be extended to include more intelligent, traffic-responsive systems.)
* **Metrics Tracking:** Collects and displays important metrics such as average car waiting time, intersection throughput (number of cars passing through per unit time), and (optionally) collision counts.
* **Modular Design:** The code is organized into modules (car.py, traffic_light.py, etc.) for better readability and maintainability.

This simulation provides a foundation for understanding basic traffic management principles and exploring the impact of different traffic control algorithms.

## Technologies Used

* Python
* Pygame
* (Optional) NumPy  *(If you used NumPy, keep this line. Otherwise, remove it)*

## Installation

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/TrafficSimulation.git](https://github.com/YOUR_USERNAME/TrafficSimulation.git)  *(Replace with your actual repository URL)*

 * Create a Virtual Environment (Recommended):
   python3 -m venv .venv  *(or python -m venv .venv depending on your system)*

 * Activate the Virtual Environment:
   * Linux/macOS:
     source .venv/bin/activate

   * Windows:
     .venv\Scripts\activate

 * Install Dependencies:
   pip install -r requirements.txt

Usage
Run the simulation:
python src/main.py

Project Report
A detailed project report (PDF or link to a document) is available, explaining the design, implementation, and results of the simulation.  (Choose one of the options below)
 * Option 1 (If PDF in repo):  See report.pdf in the root directory.
 * Option 2 (If link to external doc):  [Link to your Google Doc, etc.] (Replace with your actual link)
 * Option 3 (If no separate report):  The key implementation details and results are discussed in the code comments and this README.
File Structure
TrafficSimulation/
├── README.md
├── LICENSE
├── src/
│   ├── main.py
│   ├── car.py
│   ├── intersection.py  *(If you have this file)*
│   ├── traffic_light.py
│   └── utils.py        *(If you have this file)*
├── assets/             *(If you have this folder)*
│   ├── car.png
│   └── ...
├── data/               *(If you have this folder)*
│   ├── results.csv
│   └── ...
└── requirements.txt

License
MIT License
Author
Nitish Verma

**Key Improvements and Explanations:**

* **Clearer Structure:**  The sections are organized logically.
* **Specific Instructions:** The installation and usage steps are more detailed.
* **Virtual Environment:** Emphasizes the importance of using a virtual environment.
* **File Structure:**  A simple file structure diagram helps users understand the project layout.
* **Project Report Options:** Provides different ways to handle the project report.
* **Placeholders:**  I've included placeholders like `YOUR_USERNAME`, `report.pdf`, and the file names in the file structure section.  **Make sure to replace these with your actual information.**
* **Emphasis on Best Practices:**  The README encourages good practices like using a virtual environment and having a license.
* **NumPy Note:**  The NumPy line is now conditional.  Remove it if you didn't use NumPy.
