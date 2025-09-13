# ✈️ Flight Delay Prediction with Graph Neural Networks

This repository contains a project that uses a **Graph Neural Network (GNN)** to predict flight delays. Unlike traditional models that treat flights independently, this approach models the airline network as a graph to capture interconnectedness, which improves prediction accuracy.

---

### 🚀 Key Highlights

* **Problem:** Traditional models miss how a single flight delay can affect the entire airline network.
* **Solution:** We use a GNN to model these relationships, treating each flight as a node and their connections as edges.
* **Results:** The GNN model achieved an **F1-Score of 0.82**, outperforming the baseline Random Forest model, which scored 0.77.
* **Future Work:** Possible improvements include using a larger network dataset, integrating real-time weather data, and deploying the model for real-time predictions.

---

### 📖 How to Explore This Project

* **View the Notebook:** The `FlightDelayPrediction.ipynb` notebook includes all the code and outputs, so you can see the results and visualizations without needing to run it yourself.
* **Run the Notebook:** If you wish to run the code, ensure you have the necessary libraries installed. In Google Colab, everything other than torch_geometric is preinstalled.
* **See the Presentation:** For a high-level overview of the project, including the background, methodology, and results, please view the `Graph Neural Network for Predicting Flight Delays.pptx.pdf` file.
