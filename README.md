# Micrograd

### **Project Description**  
This is a **custom-built neural network framework** implemented from scratch. It constructs fully connected layers of neurons, where each neuron computes a weighted sum of inputs (with randomly initialized weights between -1 and 1) and a bias term, applies an activation function, and propagates outputs forward through the network. The framework supports:  
1. **Forward Propagation**: Compute predictions by passing inputs through configurable layers (variable neurons per layer).  
2. **Loss Calculation**: Compare outputs to target values using a loss function (e.g., Mean Squared Error).  
3. **Backpropagation**: Calculate gradients for every weight and bias using chain-rule differentiation, enabling precise updates to minimize loss.  
4. **Network Visualization**: Map the architecture (neurons, layers, connections) and track gradients to debug and interpret learning behavior.  
5. **Optimization**: Adjust weights iteratively via gradient descent (or similar algorithms) to train the network and improve accuracy.  

The system acts as a foundational machine learning tool for experimenting with deep learning concepts, layer design, and optimization strategies.
