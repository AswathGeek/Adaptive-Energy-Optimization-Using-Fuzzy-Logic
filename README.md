# Adaptive-Energy-Optimization-Using-Fuzzy-Logic
This repository contains a Jupyter Notebook (Fuzzy_Model.ipynb) that implements a fuzzy inference system to model and predict appliance energy consumption based on various environmental and indoor conditions. The project leverages scikit-fuzzy to define fuzzy rules and membership functions, providing a human-interpretable approach to complex system modeling.

Description

The core of this project is a fuzzy logic model designed to estimate appliance energy consumption. By taking into account factors such as temperature, humidity, pressure, wind speed, and visibility, the system infers a "consumption" output. This approach is particularly useful for scenarios where precise mathematical models are difficult to derive, but expert knowledge or heuristic rules can be formulated.

Features
  * Fuzzy Logic Implementation: Utilizes the skfuzzy library to construct fuzzy sets, linguistic variables, and fuzzy rules.
  * Environmental Data Integration: Processes real-world environmental data to inform the fuzzy inference system.
  * Consumption Simulation: Simulates appliance consumption based on input conditions.
  * Data Exploration: Includes initial steps for loading and inspecting the dataset.

Dataset

The project uses the energydata_complete.csv dataset. This dataset contains timestamped records of various indoor and outdoor environmental parameters, along with appliance and light energy consumption. Key features include:

  * date: Timestamp
  * Appliances: Appliance energy consumption (Wh)
  * lights: Light energy consumption (Wh)
  * T1 to T9: Temperature in various rooms/locations
  * RH_1 to RH_9: Humidity in various rooms/locations
  * T_out: Outdoor temperature
  * Press_mm_hg: Atmospheric pressure
  * RH_out: Outdoor humidity
  * Windspeed: Wind speed
  * Visibility: Visibility
  * Tdewpoint: Dewpoint

Requirements

To run this notebook, you need the following Python libraries:

  * pandas
  * numpy
  * scikit-fuzzy
  * matplotlib
  * datetime
You can install them using pip:

Bash

pip install pandas numpy scikit-fuzzy matplotlib

Usage
  1.Clone the repository (if applicable).
  2.Ensure the dataset is available: Place the energydata_complete.csv file in the appropriate location as referenced in the notebook, or update the data_path variable to point to your dataset.
  3.Open the notebook: Launch Jupyter Notebook or JupyterLab and open Fuzzy_Model.ipynb.
  4.Run cells: Execute the cells sequentially to load data, define the fuzzy system, and simulate consumption.
