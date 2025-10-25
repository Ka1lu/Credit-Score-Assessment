# Credit Score Assessment - Exploratory Data Analysis

**Author:** Kailas Binukumar  
**Email:** kailasbinukumar101@gmail.com  
**Project Type:** Internship Data Analysis Project

## 📊 Project Overview

This project presents a comprehensive exploratory data analysis (EDA) of credit score data, examining the relationships between various financial behaviors and credit assessment outcomes. Through detailed statistical analysis and visualization, this study identifies key factors that influence credit scores and provides actionable insights for credit risk assessment.

## 🎯 Objectives

- **Primary Goal**: Understand the factors that most significantly impact credit scores
- **Secondary Goals**: 
  - Identify patterns in customer payment behavior
  - Analyze relationships between demographic and financial variables
  - Provide data-driven recommendations for credit score improvement
  - Create comprehensive visualizations for stakeholder insights

## 📁 Project Structure

```
📦 Credit-Score-Analysis/
├── 📄 Program.ipynb          # Main analysis notebook
├── 📊 dataset-2.csv          # Credit score dataset
├── 📋 README.md              # Project documentation
```

## 📈 Dataset Description

The dataset contains **100,001 records** with **28 features** tracking customer credit behavior over 8 months.

### Key Features:
- **Target Variable**: Credit Score (Good, Standard, Poor)
- **Demographics**: Age, Occupation, Annual Income
- **Credit Behavior**: Payment history, Credit utilization, Debt levels
- **Financial Metrics**: Monthly salary, EMI, Investment amounts
- **Time Dimension**: 8-month tracking period

### Sample Features:
| Feature | Description | Type |
|---------|-------------|------|
| Credit_Score | Credit score category (Target) | Categorical |
| Credit_Utilization_Ratio | Percentage of credit used | Numerical |
| Payment_Behaviour | Payment pattern description | Categorical |
| Credit_History_Age | Length of credit history (days) | Numerical |
| Annual_Income | Yearly income in USD | Numerical |
| Delay_from_due_date | Days delayed from payment due date | Numerical |

## 🔍 Analysis Methodology

### 1. **Data Preparation**
- ✅ Data loading and structure inspection
- ✅ Missing value identification and handling
- ✅ Data type conversion and cleaning
- ✅ Feature engineering for categorical variables

### 2. **Exploratory Data Analysis**
- **Univariate Analysis**: Distribution of individual variables
- **Bivariate Analysis**: Relationships between features and credit scores
- **Multivariate Analysis**: Complex interactions between multiple variables
- **Time-Series Analysis**: Credit behavior tracking over 8 months
- **Customer Segmentation**: Analysis by demographics and behavior patterns

### 3. **Statistical Analysis**
- Correlation analysis using Pearson and Point-Biserial coefficients
- Statistical significance testing
- Distribution analysis and outlier detection
- Categorical variable association testing

## 📊 Key Findings

### 🔴 High Impact Factors
- **Credit Utilization Ratio**: Lower utilization (< 30%) strongly correlates with better scores
- **Payment Behavior**: Consistent payment patterns lead to higher credit scores
- **Credit History Age**: Longer credit history significantly improves scores
- **Payment Delays**: Fewer delays from due dates correlate with better scores

### 🟡 Medium Impact Factors
- **Credit Mix**: Diverse credit types show moderate positive correlation
- **Number of Credit Inquiries**: Fewer inquiries correlate with better scores
- **Outstanding Debt**: Lower debt levels associated with higher scores
- **Payment of Minimum Amount**: Consistent minimum payments help maintain scores

### 🟢 Low Impact Factors
- **Income Level**: Modest correlation with credit scores
- **Age**: Limited direct impact on credit assessment
- **Number of Bank Accounts**: Minimal correlation observed

## 📈 Visualizations Include

1. **Distribution Charts**: Credit score distribution across categories
2. **Correlation Heatmaps**: Feature relationship analysis
3. **Time Series Plots**: Credit behavior tracking over months
4. **Segmentation Analysis**: Customer group comparisons
5. **3D Scatter Plots**: Multi-dimensional relationship visualization
6. **Box Plots & Violin Plots**: Statistical distribution analysis

## 🛠️ Technologies Used

- **Python 3.x** - Primary programming language
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computations
- **Matplotlib** - Static visualization
- **Seaborn** - Statistical data visualization
- **SciPy** - Statistical analysis
- **Scikit-learn** - Data preprocessing and scaling

## 🚀 Getting Started

### Prerequisites
```bash
pip install pandas numpy matplotlib seaborn scipy scikit-learn jupyter
```

### Running the Analysis
1. **Clone the repository**
   ```bash
   git clone https://github.com/Ka1lu/Credit-Score-Assessment
   cd credit-score-analysis
   ```

2. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook Program.ipynb
   ```

3. **Run all cells** to reproduce the complete analysis

## 💡 Key Insights & Recommendations

### For Financial Institutions:
1. **Focus on payment behavior patterns** when assessing credit risk
2. **Consider credit utilization ratio** as a primary risk indicator
3. **Weight credit history length** heavily in scoring models
4. **Monitor payment delays** as early warning signals

### For Consumers:
1. **Maintain credit utilization below 30%** of available credit
2. **Establish consistent payment patterns** across all accounts
3. **Avoid payment delays** to maintain good credit standing
4. **Build and maintain long credit history** by keeping older accounts open
5. **Diversify credit mix** with different types of credit products

## 📊 Sample Outputs

The analysis produces:
- **24+ comprehensive visualizations**
- **Statistical correlation matrices**
- **Time-series trend analysis**
- **Customer segmentation insights**
- **Actionable recommendation framework**

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. Areas for improvement:
- Additional statistical tests
- Machine learning model implementation
- Interactive dashboard creation
- Real-time data integration

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📧 Contact

**Kailas Binukumar**  
- Email: kailasbinukumar101@gmail.com
- GitHub: [@YourGitHubUsername](https://github.com/Ka1lu)
- LinkedIn: [Your LinkedIn Profile](linkedin.com/in/kailas-binukumar)

## 🙏 Acknowledgments

- Dataset source and data providers
- Python community for excellent libraries
- Jupyter Project for the interactive notebook environment
- Internship program for project opportunity

---

⭐ **Star this repository if you found it helpful!**

## 📝 Project Status

- ✅ **Completed**: Core EDA analysis
- ✅ **Completed**: Statistical analysis and insights
- ✅ **Completed**: Comprehensive visualizations
- 🔄 **In Progress**: Advanced machine learning models
- 📋 **Planned**: Interactive dashboard development

---

*Last Updated: October 2025*