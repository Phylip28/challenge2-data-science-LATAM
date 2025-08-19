# TelecomX LATAM - Customer Churn Analysis 📊

A comprehensive data science project focused on analyzing customer churn patterns for a Latin American telecommunications company using advanced data processing and visualization techniques.

## 🎯 Project Overview

This project implements a complete ETL (Extract, Transform, Load) pipeline to analyze customer behavior and churn patterns in the telecommunications industry. The analysis provides valuable insights into customer retention factors and helps identify patterns that lead to customer churn.

### Key Objectives
- **Customer Churn Analysis**: Identify patterns and factors contributing to customer churn
- **Data Processing**: Clean and transform complex nested JSON data structures
- **Exploratory Data Analysis**: Comprehensive statistical analysis and visualization
- **Business Insights**: Generate actionable insights for customer retention strategies

## 📁 Project Structure

```
challenge2-data-science-LATAM/
├── TelecomX_LATAM.ipynb          # Main analysis notebook
├── TelecomX_Data.json            # Original raw data (JSON format)
├── TelecomX_cleaned_data.csv     # Processed and cleaned dataset
├── TelecomX_diccionario.md       # Data dictionary and variable descriptions
├── .gitignore                    # Git ignore configuration
└── README.md                     # Project documentation
```

## 📊 Dataset Description

The dataset contains **7,267 customer records** with comprehensive information about:

### Customer Demographics
- **customerID**: Unique customer identifier
- **gender**: Customer gender (Male/Female)
- **SeniorCitizen**: Senior citizen status (0/1)
- **Partner**: Partner status (Yes/No)
- **Dependents**: Dependents status (Yes/No)
- **tenure**: Contract duration in months

### Service Information
- **PhoneService**: Phone service subscription
- **MultipleLines**: Multiple phone lines
- **InternetService**: Internet service type (DSL/Fiber optic/No)
- **OnlineSecurity**: Online security add-on
- **OnlineBackup**: Online backup service
- **DeviceProtection**: Device protection plan
- **TechSupport**: Technical support service
- **StreamingTV**: TV streaming service
- **StreamingMovies**: Movie streaming service

### Account Details
- **Contract**: Contract type (Month-to-month/One year/Two year)
- **PaperlessBilling**: Paperless billing preference
- **PaymentMethod**: Payment method
- **Charges**: Monthly and total charges
- **Churn**: Customer churn status (Target variable)

## 🔧 Technical Implementation

### Data Processing Pipeline

#### 1. 📌 Data Extraction
- Load data from JSON format
- Initial data exploration and validation
- Handle nested JSON structures

#### 2. 🔧 Data Transformation
- Clean and standardize data formats
- Remove duplicates and handle missing values
- Convert nested JSON columns to structured format
- Data type optimization

#### 3. 📊 Data Loading & Analysis
- Expand nested JSON columns into separate features
- Create analysis-ready dataset
- Generate summary statistics and data profiling

#### 4. 📄 Exploratory Data Analysis
- **Statistical Analysis**: Comprehensive descriptive statistics
- **Churn Distribution**: Customer churn patterns and rates
- **Demographic Analysis**: Customer segmentation by demographics
- **Service Usage**: Analysis of service adoption patterns
- **Correlation Analysis**: Relationship between features and churn

### Visualizations
- Distribution plots for numerical variables
- Churn rate analysis with pie charts and count plots
- Demographic segmentation visualizations
- Box plots for tenure analysis by churn status

## 🛠️ Technologies Used

- **Python 3.12+**: Core programming language
- **pandas**: Data manipulation and analysis
- **matplotlib**: Static plotting and visualization
- **seaborn**: Statistical data visualization
- **json**: JSON data handling
- **Jupyter Notebook**: Interactive development environment

## 🚀 Getting Started

### Prerequisites
- Python 3.12 or higher
- Jupyter Notebook
- Required Python packages (see installation)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Phylip28/challenge2-data-science-LATAM.git
   cd challenge2-data-science-LATAM
   ```

2. **Create virtual environment** (recommended)
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install required packages**
   ```bash
   pip install pandas matplotlib seaborn jupyter
   ```

### Usage

1. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

2. **Open the main analysis notebook**
   - Navigate to `TelecomX_LATAM.ipynb`
   - Run all cells to execute the complete analysis pipeline

3. **Explore the results**
   - Review generated visualizations
   - Analyze statistical summaries
   - Examine churn patterns and insights

## 📈 Key Findings

### Customer Demographics
- **Gender Distribution**: Balanced representation across gender
- **Senior Citizens**: ~16.3% of customers are senior citizens
- **Average Tenure**: 32.3 months with significant variation (SD: 24.6)

### Churn Patterns
- Detailed churn analysis revealing customer retention factors
- Correlation between service usage and churn probability
- Impact of contract types on customer retention

### Service Analysis
- Service adoption patterns across customer segments
- Revenue impact analysis through monthly charges
- Customer lifetime value insights

## 🔍 Analysis Methodology

The project follows a systematic approach:

1. **Data Quality Assessment**: Comprehensive data profiling and quality checks
2. **Feature Engineering**: Transform nested JSON data into analyzable features
3. **Statistical Analysis**: Descriptive and inferential statistics
4. **Visualization**: Multi-dimensional data exploration through charts
5. **Pattern Recognition**: Identify trends and correlations in customer behavior

## 📋 Data Dictionary

For detailed variable descriptions, refer to [`TelecomX_diccionario.md`](TelecomX_diccionario.md)

## 🤝 Contributing

Contributions are welcome! Please feel free to submit issues, feature requests, or pull requests.

## 📄 License

This project is part of a data science challenge for LATAM region analysis.

## 📞 Contact

For questions or collaboration opportunities, please reach out through the repository issues or discussions.

---

**Note**: This project demonstrates ETL pipeline implementation, data analysis techniques, and visualization best practices for telecommunications customer analytics.