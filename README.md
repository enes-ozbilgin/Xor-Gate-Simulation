# XOR Gate Simulation (Neural Network)

![Language](https://img.shields.io/badge/Language-C-blue) ![Topic](https://img.shields.io/badge/Topic-Neural_Networks-green) ![Logic](https://img.shields.io/badge/Logic-XOR_Gate-orange)

A pure C implementation that simulates an **XOR (Exclusive OR)** logic gate using a minimal Neural Network architecture. This project demonstrates how a network of **3 neurons** can solve a non-linearly separable problem that a single perceptron cannot.

## 🧠 Project Overview

The XOR function returns `1` (true) only when the inputs differ. Unlike AND/OR gates, the XOR problem is **non-linearly separable**. 
This program simulates this behavior using a specific configuration of neurons (nodes) and weights, effectively creating a small "brain" that learns or executes the XOR logic.

### Truth Table Implemented
| Input A | Input B | Output (XOR) |
| :---: | :---: | :---: |
| 0 | 0 | **0** |
| 0 | 1 | **1** |
| 1 | 0 | **1** |
| 1 | 1 | **0** |

## 📂 Project Structure

* **`XOR-Gate.c`**: The main C source file containing the neuron structures, weight definitions, and the forward propagation logic to calculate the output.

## 🚀 Getting Started

### Prerequisites
* A C Compiler (GCC recommended).

### Compilation & Execution

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/enes-ozbilgin/Xor-Gate-Simulation.git](https://github.com/enes-ozbilgin/Xor-Gate-Simulation.git)
    cd Xor-Gate-Simulation
    ```

2.  **Compile the code:**
    *(Note: If the code uses `math.h` for activation functions like Sigmoid, include the `-lm` flag)*
    ```bash
    gcc XOR-Gate.c -o xor_sim -lm
    ```

3.  **Run the simulation:**
    ```bash
    ./xor_sim
    ```

## ⚙️ How It Works

The simulation likely uses a Multi-Layer Perceptron (MLP) approach or a specific combination of logic gates simulated by neurons:
1.  **Inputs:** Two binary inputs (0 or 1).
2.  **Hidden Layer/Neurons:** Processes the inputs to handle the non-linearity.
3.  **Output Neuron:** Combines the signals to produce the final XOR result.

## 👤 Author

**Enes Özbilgin**

* GitHub: [@enes-ozbilgin](https://github.com/enes-ozbilgin)

---
*Created to demonstrate the fundamentals of Neural Networks and Logic Gates in C.*
