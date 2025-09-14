# Jupyter

Jupyter is an open-source web application that allows you to create and share documents that contain live code, equations, visualizations and narrative text.

## Features

- **Interactive Computing**: Create and share documents with live code, equations, visualizations and narrative text
- **Multiple Languages**: Supports over 40 programming languages including Python, R, Julia, and Scala
- **Data Visualization**: Rich output including HTML, images, videos, LaTeX, and JavaScript
- **Big Data Integration**: Leverage big data tools like Apache Spark from Python, R and Scala
- **Flexible Interface**: Choose between classic Notebook interface or modern JupyterLab

## Use Cases

- Data cleaning and transformation
- Numerical simulation
- Statistical modeling
- Data visualization
- Machine learning
- Research and education
- Prototyping and experimentation

## Available Images

This app supports multiple Jupyter Docker images:

- **Base Notebook**: Minimal Jupyter installation
- **Minimal Notebook**: Base + Python 3.x
- **SciPy Notebook**: Minimal + scientific Python packages (pandas, numpy, matplotlib, etc.)
- **DataScience Notebook**: SciPy + R, Julia, and Scala kernels
- **TensorFlow Notebook**: SciPy + TensorFlow and Keras for machine learning
- **PySpark Notebook**: SciPy + Apache Spark for big data processing

## Getting Started

1. Choose your preferred Jupyter image variant
2. Set a secure token for authentication
3. Select between JupyterLab (modern) or Classic Notebook interface
4. Access your Jupyter environment through the web interface

Your notebooks and work files will be persisted in the app data directory, so they'll survive container restarts and updates.
