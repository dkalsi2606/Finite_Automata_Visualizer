# Finite Automata Visualiser

An interactive web-based tool to design, visualize, and simulate **Deterministic (DFA)** and **Non-Deterministic Finite Automata (NFA)**, including full support for **ε-transitions**.

---

## Features

* Visual creation and editing of states on a canvas
* Support for transitions, including self-loops and bidirectional edges
* Works with both DFA and NFA models
* Input string simulation with step-by-step trace
* Clean and responsive user interface
* Drag-and-drop state positioning

---

## How to Use

### Adding States

* Click **"+ State"**, then click on the canvas
* Or enter a state name manually using the input field

### Adding Transitions

* Select **"→ Transition"**
* Click the source state, then the destination state
* Enter symbol(s); multiple symbols can be comma-separated
* **NOTE**- The transition from start to a node at the end of a chain may not be visible. So, drag the states so the diagram is more spread out.

### Modifying States

* Double-click a state to toggle accept state
* Use the ▶ button to set the start state
* Drag states to reposition them
* Right-click a state to delete it

### Running Simulation

* Enter an input string (e.g., `aab`)
* Click **Run**
* View:

  * Acceptance or rejection result
  * Step-by-step trace
  * Visual animation on the canvas

---

## Example

Construct an NFA with:

* States: `q0`, `q1`, `q2`
* Start state: `q0`
* Accept state: `q2`
* Transitions:

  * `q0 → q1 : a`
  * `q1 → q1 : b`
  * `q1 → q2 : a`

---

## Project Structure

```
finite-automata-visualiser.html   # Main application file
```

This project is implemented using plain HTML, CSS, and JavaScript. No external dependencies or build tools are required.

---

## Running Locally

Open the file directly in a web browser:

```
finite-automata-visualiser.html
```

---

## Author

Daksh Kalsi

---

## Contributing

Contributions are welcome. Feel free to fork the repository and submit improvements.

---

## License

This project is intended for educational use and is free to use and modify.
