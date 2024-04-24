# Self-Organizing Maps (SOMs) for Credit Card Applications

## Overview
This repository contains an implementation of Self-Organizing Maps (SOMs), a type of unsupervised learning used to produce a low-dimensional (typically two-dimensional), discretized representation of the input space of the training samples. This project applies SOMs to a dataset of credit card applications to identify patterns and potential outliers effectively.

## Repository Structure
- **Credit_Card_Applications.csv**: The dataset containing credit card application details.
- **SOM_Training.ipynb**: Jupyter notebook with all the code and visualizations.
- **requirements.txt**: List of libraries required to run the notebook.

## Dataset
The dataset `Credit_Card_Applications.csv` consists of several attributes related to credit card applications, which are preprocessed and fed into the SOM. The dataset includes both numerical and categorical data, ranging from personal information to financial details.

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/SOM-Credit-Card-Applications.git
   cd SOM-Credit-Card-Applications
   ```

2. **Install Dependencies:**
   Ensure that Python 3 and pip are already installed.
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Notebook:**
   Launch Jupyter Notebook or JupyterLab in the repository directory:
   ```bash
   jupyter notebook
   ```

## Usage
Open the `SOM_Training.ipynb` notebook to view the preprocessing steps, SOM training, and the visualization of results. The notebook is well-commented and includes markdown explanations for each step to facilitate understanding of the process.

## Features
- **Data Preprocessing**: Scaling features to normalize the data.
- **Training the SOM**: Using the MiniSom library to train a 10x10 SOM grid.
- **Visualization**: Using matplotlib and pylab to visualize the high-dimensional data in a two-dimensional map. This includes:
  - Distance map to show the mean distances between each neuron and its neighbors, highlighting potential clusters.
  - Scatter plot overlay to show where each application is mapped on the grid.

## Contributing
Contributions to this project are welcome! Please fork the repository, make your changes, and submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Conclusion
Using Self-Organizing Maps provides a powerful tool for exploratory data analysis, especially in complex datasets like credit card applications. By visualizing the application data in two dimensions, we can potentially identify fraud and segment customers effectively. This project demonstrates the setup, execution, and interpretation of SOMs using a real-world dataset.
