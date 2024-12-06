# Kaim Week 0

## Project Overview
This project involves performing Exploratory Data Analysis (EDA) on solar radiation and weather data. The dataset includes various measurements such as Global Horizontal Irradiance (GHI), Direct Normal Irradiance (DNI), Diffuse Horizontal Irradiance (DHI), temperature, wind speed, and more.

## Development Process

### Step 1: Setup
1. Clone the repository:
    ```sh
    git clone <repository-url>
    ```
2. Navigate to the project directory:
    ```sh
    cd kaim-week-0
    ```
3. Create a virtual environment:
    ```sh
    python -m venv venv
    ```
4. Activate the virtual environment:
    - On Windows:
        ```sh
        venv\Scripts\activate
        ```
    - On macOS/Linux:
        ```sh
        source venv/bin/activate
        ```
5. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

### Step 2: Data Preparation
1. Place the dataset files in the [data](http://_vscodecontentref_/1) directory.

### Step 3: Exploratory Data Analysis (EDA)
1. Open the `eda.ipynb` file located in the [notebooks](http://_vscodecontentref_/2) directory using Jupyter Notebook or Jupyter Lab.
2. Run the cells in the notebook to perform the following EDA tasks:
    - Summary Statistics
    - Data Quality Check
    - Time Series Analysis
    - Evaluate Impact of Cleaning
    - Correlation Analysis
    - Wind Analysis
    - Temperature Analysis
    - Histograms
    - Z-Score Analysis
    - Bubble Charts
    - Data Cleaning

## Usage Instructions
1. Ensure that the virtual environment is activated.
2. Open the Jupyter Notebook:
    ```sh
    jupyter notebook notebooks/eda.ipynb
    ```
3. Run the cells in the notebook to perform the EDA tasks.

## Data Dictionary
- **GHI**: Global Horizontal Irradiance
- **DNI**: Direct Normal Irradiance
- **DHI**: Diffuse Horizontal Irradiance
- **Tamb**: Ambient Temperature
- **ModA**: Sensor Reading A
- **ModB**: Sensor Reading B
- **WS**: Wind Speed
- **WSgust**: Wind Gust Speed
- **RH**: Relative Humidity
- **WD**: Wind Direction
- **Cleaning**: Cleaning Indicator (1 if cleaned, 0 otherwise)
- **Timestamp**: Date and Time of the measurement
- **Comments**: Additional comments

