# Session1


# Kirti Mandloi's Supply Chain Management (SCM), Supply Chain Analytics (SCA) and Optimization in SCM

Welcome to the repository! This README provides an in-depth look at the work and research we have been focusing on within the field of Supply Chain Management (SCM) and Supply Chain Analytics and Optimization. Below is a summary of key areas covered in the project, including optimization techniques, problem-solving strategies, and project workflow.

## Key Topics in Supply Chain Management and Analytics

### 1. **Optimization Techniques in Supply Chain Design**
   - Focus on procurement, logistics, and inventory management.
   - Explored techniques include:
     - **Deterministic Optimization**: Assumes that all parameters are known with certainty.
     - **Stochastic Optimization**: Deals with uncertain variables, e.g., demand or supply lead times.
     - **Robust Optimization**: Focuses on creating solutions that perform well under varying conditions.
   - These methods help businesses streamline operations, reduce costs, and mitigate risks.

### 2. **Linear and Integer Programming**
   - **Linear Programming (LP)**: Solved using Simplex and Dual Simplex methods, crucial for capacity planning and production scheduling.
   - **Integer Programming (IP)**: Explored Pure and Mixed Integer Linear Programming using Branch and Bound methods.
   - These techniques are pivotal in optimizing resource allocation in supply chains, minimizing operational costs.

### 3. **Network Design**
   - Tackled **Shortest Path Problems** and **Network Flow Problems**.
   - Optimizing logistics and distribution, ensuring faster and more cost-effective delivery.

### 4. **Heuristic and Metaheuristic Methods**
   - **Heuristic Methods**: Techniques like Greedy and Local Search for supply chain solutions.
   - **Metaheuristic Techniques**: Includes Genetic Algorithms, Simulated Annealing, Tabu Search, and Ant Colony Optimization.
   - These methods enable quick and practical solutions to complex supply chain problems, balancing cost, time, and resources.

### 5. **Advanced Optimization Techniques**
   - **Simulation-Based Optimization**: Involves Discrete Event Simulation and Monte Carlo Simulation for real-world scenario analysis.
   - **Stochastic Programming**: Two-Stage and Multi-Stage models to manage uncertainty in supply and demand.
   - **Robust Optimization**: Applied to capacity planning under uncertain conditions.
   - **Multi-Criteria Optimization**: Techniques such as Pareto Efficiency and Trade-Off Analysis ensure balanced solutions for conflicting objectives.

## Workflow for Projects

### General Workflow
Each project follows a systematic workflow to ensure consistency and thorough analysis. The typical steps include:
1. **Project Scoping and Objective Setting**
2. **Dataset Creation**: Generated synthetic datasets using Python libraries or Excel.
3. **Data Preprocessing**
4. **Data Analysis**: Identified patterns and trends using Exploratory Data Analysis (EDA).
5. **Visualization and Reporting**: Created dashboards using tools like Tableau, Power BI, or Python.
6. **Optimization Operations**: Implemented deterministic and uncertainty-based optimization models.
7. **Simulation and Scenario Analysis**
8. **Second Round of Visualization and Reporting**
9. **Presentation and Documentation**
10. **Review and Feedback**

---

## Dummy Projects Overview

To apply the above techniques, we worked on two key dummy projects:

### Project 1: Inventory Management

#### Steps:
1. **Data Generation**: Simulated datasets capturing demand, sales, inventory, and costs over a year.
2. **Optimization Operations**:
   - **Economic Order Quantity (EOQ)** and **Reorder Point (ROP)** formulas to optimize inventory levels.
   - **Safety Stock** and **Frequency of Orders** calculated to prevent stockouts.
3. **Dashboard Comparison**: Initial vs Optimized dashboards showed significant improvements in stockout rates and cost reductions.

#### Key Formulas:
- **EOQ**: 
  \[
  EOQ = \sqrt{\frac{2DS}{H}}
  \]
  - Where D = Demand rate, S = Ordering cost, H = Holding cost.

- **Reorder Point (ROP)**:
  \[
  ROP = d \times L
  \]
  - Where d = Average demand, L = Lead time.

- **Safety Stock**: 
  \[
  Safety\ Stock = Z \times \sigma_L
  \]
  - Where Z = Z-score for service level, \(\sigma_L\) = Standard deviation of demand during lead time.

---

### Project 2: Production and Distribution Management

#### Overview:
This project focused on optimizing production and distribution within a supply chain network. The goal was to minimize costs while ensuring that distribution centers receive the required products efficiently.

1. **Production Planning**: Determined the optimal quantity of products each plant should produce.
2. **Distribution Optimization**: Allocated products from plants to distribution centers, minimizing transportation costs and meeting demand requirements.

### Mathematical Models Used:
- **Linear Programming** for production cost minimization.
- **Network Flow Models** to optimize the flow of goods between plants and distribution centers.

---

## Tools and Techniques

- **Programming Languages**: Python
- **Libraries**: pandas, numpy, matplotlib, seaborn, Faker (for data generation), optimization libraries like `scipy.optimize`.
- **Visualization**: Tableau, Power BI, Python libraries (matplotlib, seaborn).

---

## Conclusion

Through these projects, I demonstrated a thorough understanding of supply chain management and optimization techniques. Whether tackling deterministic or uncertain variables, the techniques outlined here ensure effective decision-making, cost optimization, and supply chain resilience.

Feel free to explore the repository, and if you have any questions, please reach out!

**Kirti Mandloi**
