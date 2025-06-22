# Probability Distributions and Gradient Descent Assignment

## 📋 Assignment Overview

This assignment explores fundamental concepts in probability theory and machine learning optimization through hands-on implementation and analysis. Students will work in groups to implement probability distributions, apply Bayesian inference, and understand gradient descent both theoretically and practically.

## 🎯 Learning Objectives

By completing this assignment, you will:
- Gain deep understanding of key probability distributions and their applications
- Apply Bayesian probability to solve real-world problems
- Master gradient descent through manual calculations and code implementation
- Develop skills in mathematical modeling and data visualization

## 📊 Part 1: Probability Distributions

### Requirements
1. **Implementation**: Create the probability distribution from scratch without using statistical libraries
2. **Real-world Application**: Choose a relevant problem that demonstrates the distribution's practical use
3. **Visualization**: Generate clear, well-labeled graphs using Matplotlib
4. **Analysis**: Explain the distribution's characteristics and when to use it

### Deliverables
- Python implementation of the distribution formula
- Real-world example with complete solution
- Visualization with proper labels and legends
- Written analysis of the distribution's properties

## 🔍 Part 2: Bayesian Probability

### Objective
Apply Bayes' theorem to a practical problem and demonstrate the power of updating beliefs with new evidence.

### Suggested Applications
- Medical diagnosis and testing accuracy
- Email spam filtering systems
- Equipment reliability analysis
- Market research and customer behavior
- Quality control in manufacturing

### Requirements
1. **Problem Selection**: Choose a compelling real-world scenario
2. **Implementation**: Code Bayes' theorem from scratch in Python
3. **Step-by-step Analysis**: Show how prior beliefs update with new evidence
4. **Interpretation**: Explain the practical significance of your results

### Key Components to Include
- Prior probability definition and justification
- Likelihood calculation with clear assumptions
- Posterior probability computation
- Sensitivity analysis (how results change with different priors)

## 📐 Part 3: Manual Gradient Descent Calculation

### Problem Setup
**Linear Regression Model**: y = mx + b

**Initial Conditions**:
- m₀ = -1 (initial slope)
- b₀ = 1 (initial intercept)
- α = 0.1 (learning rate)
- Data points: (1, 3) and (3, 6)

### Step-by-Step Process

#### For Each Iteration:

1. **Compute Predictions**:
   ```
   ŷᵢ = m × xᵢ + b
   ```

2. **Calculate Gradients** (using MSE cost function):
   ```
   ∂J/∂m = -(2/n) × Σ(yᵢ - ŷᵢ) × xᵢ
   ∂J/∂b = -(2/n) × Σ(yᵢ - ŷᵢ)
   ```

3. **Update Parameters**:
   ```
   m_new = m_old - α × (∂J/∂m)
   b_new = b_old - α × (∂J/∂b)
   ```

### Requirements
- **Number of iterations**: Equal to the number of group members
- **Documentation**: Show all intermediate calculations clearly
- **Individual Participation**: Each member must complete at least one iteration
- **Analysis**: Describe the convergence trend and error reduction

## 💻 Part 4: Gradient Descent Implementation

### Technical Requirements
- **Primary Library**: Use SciPy for optimization components
- **Visualization**: Create plots with Matplotlib
- **Code Style**: Make each gradient descent step explicitly visible
- **Documentation**: Include clear comments explaining each step

### Implementation Tasks

1. **Convert Manual Calculations**: Translate your manual work into Python code
2. **Parameter Updates**: Implement the gradient descent update rules
3. **Prediction Generation**: Use final parameters to make predictions
4. **Visualization**: Create two separate plots:
   - Plot 1: Parameter evolution (m and b over iterations)
   - Plot 2: Cost function/error reduction over iterations
   
## 📈 Visualization Requirements

### Part 1 (Distributions)
- Clean, professional-looking plots
- Proper axis labels and titles
- Legend when appropriate
- Multiple parameter values shown for comparison

### Part 4 (Gradient Descent)
- **Plot 1**: Parameter evolution
  - X-axis: Iteration number
  - Y-axis: Parameter values
  - Two lines: one for m, one for b
  
- **Plot 2**: Error/Cost reduction
  - X-axis: Iteration number  
  - Y-axis: Cost function value
  - Show convergence trend
    
### Documentation Standards
- **Code Comments**: Explain complex logic and mathematical operations
- **Function Docstrings**: Describe parameters, return values, and purpose
- **Mathematical Notation**: Use clear variable names that match mathematical symbols
- **Results Interpretation**: Explain what your results mean in practical terms

## ⚠️ Common Pitfalls to Avoid

1. **Using Built-in Statistical Functions**: Implement distributions from scratch
2. **Abstracting Gradient Descent**: Keep each step visible and understandable
3. **Poor Visualization**: Ensure plots are clear and informative
4. **Insufficient Analysis**: Don't just show results—explain their significance
5. **Missing Manual Calculations**: Show all work for the gradient descent steps

## 🔧 Technical Setup

### Environment Setup
- Python 3.7+
- Jupyter Notebook or Python IDE
- Libraries: NumPy, Matplotlib, SciPy

## 🤝 Group Work Guidelines

- **Equal Participation**: Ensure all members contribute meaningfully
- **Documentation**: Keep track of individual contributions
- **Collaboration**: Use version control (Git) for code sharing
- **Communication**: Regular meetings to discuss progress and challenges

## 📚 Additional Resources

### Mathematical References
- Probability theory textbooks for distribution formulas
- Bayesian statistics resources for practical applications
- Optimization theory for gradient descent understanding

### Programming Resources
- NumPy documentation for array operations
- Matplotlib gallery for visualization examples
- SciPy optimization module documentation
