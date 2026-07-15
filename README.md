
#  Crystal Lattice Simulator (Condensed Matter Physics)

An interactive, single-page web simulation designed to demonstrate the fundamental principles of **Condensed Matter Physics** and **Solid-State Chemistry**. Users can construct an atomic 2D cross-section of a Sodium Chloride (NaCl) crystal lattice using native HTML5 drag-and-drop operations.

---

##  Physics Concepts Explored

### 1. Ionic Bonding & Crystal Structure
In condensed matter, solids form specific structures to minimize environmental energy. This simulator replicates a standard cubic rock-salt (\(NaCl\)) configuration where small Sodium cations (\(Na^+\)) and larger Chlorine anions (\(Cl^-\)) alternate to fill empty space.

### 2. Coulombic Lattice Energy
The simulator models potential system stability using simplified **Coulomb's Law** indicators:
* **Attraction (\(E < 0\)):** Occurs when opposite ions (\(Na^+\) and \(Cl^-\)) sit adjacent to one another.
* **Repulsion (\(E > 0\)):** Occurs when identical ions sit next to each other, introducing electrical instability.

The dashboard displays real-time energy readouts in electron-volts (eV) as ions are placed on the grid nodes.

---

##  Features

* **Interactive Drag and Drop:** Drag unlimited ions straight from the source bin into grid positions.
* **Real-time Engine:** Dynamic system calculation updates stability parameters with every single drop.
* **Lattice Clear:** Instantly reset the atomic configuration to test alternative arrangements.
* **Pure Stack:** Built entirely with vanilla JavaScript, semantic HTML5, and CSS3. Zero frameworks required.

---

##  Project Structure

```text
├── index.html   # Simulator layout, interface elements, and physics engine
├── style.css    # Responsive grid layout and atomic color assets
└── README.md    # Documentation and background information
```

---

## How to Run This Project Locally
##  How to Run This Project Locally

1. **Download** or clone this repository folder onto your computer.
2. Locate the file named `index.html`.
3. **Double-click** `index.html` to instantly run the app locally inside any standard web browser.
