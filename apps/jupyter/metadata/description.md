# Jupyter

Jupyter is an open-source web application that allows you to create and share documents that contain live code, equations, visualizations and narrative text.

## Features

- **Interactive Computing**: Create and share documents with live code, equations, visualizations and narrative text
- **Multiple Languages**: Supports over 40 programming languages including Python, R, Julia, and Scala
- **Interface Localization**: Available in 10 languages including Portuguese (Brazil), Spanish, French, German, Chinese, Japanese, Korean, Russian, and Italian
- **Flexible Authentication**: Choose between secure token authentication or open access (no login required)
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
- **All-Spark Notebook**: Everything included - the most comprehensive option with all tools and libraries

## Getting Started

1. Choose your preferred Jupyter image variant
2. Select authentication mode (secure token or open access)
3. Set a secure token if using token authentication (optional for open access)
4. Select between JupyterLab (modern) or Classic Notebook interface
5. Choose your preferred interface language (including Português Brasil)
6. Access your Jupyter environment through the web interface

## Authentication Options

- **Token Authentication (Recommended)**: Requires a secure token to access Jupyter. Best for production or shared environments.
- **No Authentication (Open Access)**: No login required. Suitable for local development or trusted private networks only.

Your notebooks and work files will be persisted in the app data directory, so they'll survive container restarts and updates.
