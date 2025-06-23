# 🏥 Hospital Bed & Staffing Simulation Dashboard

This project is an interactive dashboard built with Streamlit to simulate and analyze patient flow in a hospital. It uses queuing theory to model system dynamics under different scenarios, helping to optimize bed capacity and staffing levels.

## 🚀 Features

- **Interactive Controls**: Adjust parameters like patient arrival rates, bed capacity, and staff numbers.
- **Multiple Scenarios**: Simulate different models, including baseline, experience-based staffing, and workload-dependent service rates.
- **Rich Visualizations**: View KPIs, system dynamics over time, and sensitivity analysis through interactive charts and plots.
- **Scenario Comparison**: Compare the performance of different simulation runs side-by-side.

## 🛠️ Setup & Installation

1.  **Clone the repository (or download the files):**
    ```bash
    git clone <your-repo-url>
    cd <your-repo-directory>
    ```

2.  **Install the required packages:**
    Make sure you have Python 3.7+ installed. Then, run the following command to install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## ▶️ How to Run the Application

To start the Streamlit application, run the following command in your terminal:

```bash
streamlit run dashboard.py
```

The application will open in your default web browser.

## 📁 Project Structure

- `dashboard.py`: The main Streamlit application script.
- `simulation.py`: Contains the core logic for the hospital simulation.
- `requirements.txt`: A list of the Python packages required to run the project.
- `report/`: Directory containing images used in the dashboard.
- `simulation_results.csv`: Example output data from a simulation run.
