# 📊 Advanced CSV Data Analyst Tool

<div align="center">

![Python](https://img.shields.io/badge/python-3.8+-blue.svg)
![Streamlit](https://img.shields.io/badge/streamlit-1.28+-red.svg)
![Pandas](https://img.shields.io/badge/pandas-2.0+-green.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Status](https://img.shields.io/badge/status-active-success.svg)

**A powerful, interactive web application for analyzing CSV data through natural language queries and rich visualizations.**

[🚀 Live Demo](https://advanced-csv-analysis-tool.streamlit.app/)  • [🐛 Report Bug](https://github.com/Hat-GitBot/Advanced-CSV-Analysis-Tool/issues) 

</div>

---

## 🎯 Overview

Transform the way you analyze data! This application allows anyone to explore CSV files using natural language queries - no SQL or programming knowledge required. Simply upload your data and ask questions like "What's the average salary by department?" or "Show me the top 10 customers."

### ✨ Key Features

🔍 **Natural Language Processing**
- Ask questions in plain English
- Automatic pattern recognition and query parsing
- Intelligent context understanding

📊 **Comprehensive Analytics**
- Statistical analysis (mean, median, sum, count, min, max)
- Group-by operations with automatic aggregations
- Correlation and distribution analysis
- Time series trend detection
- Top N rankings and percentile calculations

📈 **Rich Visualizations**
- Interactive Plotly charts (bar, line, scatter, pie)
- Correlation heatmaps
- Distribution histograms
- Box plots for outlier detection
- Customizable chart builder

💡 **User-Friendly Interface**
- Multi-file upload support (up to 500MB)
- Real-time data preview with search
- Query history tracking
- Downloadable results (CSV, JSON)
- Mobile-responsive design

---

## 🚀 Live Demo

👉 **Try it now:** [https://advanced-csv-analysis-tool.streamlit.app/](https://advanced-csv-analysis-tool.streamlit.app/)

### Quick Start Guide:
1. Visit the live demo
2. Upload your CSV file(s)
3. Browse the data in the Data View tab
4. Go to Q&A Analysis tab
5. Type your question (e.g., "Average sales by region")
6. Get instant results with visualizations!

---

## 💬 Query Examples

### Basic Queries
```plaintext
"How many rows?"
"Total count of records"
"Average price"
"Sum of sales"
"Highest score"
"Lowest value"
"Unique categories"
```

### Advanced Queries
```plaintext
"Average salary by department"
"Total revenue by product category"
"Top 10 customers by spending"
"Correlation between age and income"
"Percentage distribution of user types"
"Number of employees in France"
"Sales trend over time"
"Missing values in the dataset"
```

### Grouping & Aggregation
```plaintext
"Average rating by country"
"Total orders by month"
"Count of users by status"
"Sum of purchases by region"
```

---

## 🛠️ Local Installation

### Prerequisites

- Python 3.8 or higher
- pip package manager
- Virtual environment (recommended)

### Installation Steps

1. **Clone the repository**
```bash
git clone https://github.com/Hat-GitBot/Advanced-CSV-Analysis-Tool.git
cd Advanced-CSV-Analysis-Tool
```

2. **Create a virtual environment** (optional but recommended)
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install dependencies**
```bash
pip install -r requirements.txt
```

4. **Run the application**
```bash
streamlit run app.py
```

5. **Open your browser**
```
The app will automatically open at http://localhost:8501
```

---

## 📦 Dependencies

```
streamlit>=1.28.0
pandas>=2.0.0
numpy>=1.24.0
plotly>=5.17.0
```

All dependencies are listed in `requirements.txt` for easy installation.

---

## 📊 Supported Query Types

| Query Type | Keywords | Example | Output Format |
|-----------|----------|---------|---------------|
| **Count** | how many, number of, count | "How many users?" | Numeric value |
| **Average** | average, mean, avg | "Average age by country" | Number or grouped table |
| **Sum** | total, sum | "Total revenue by product" | Number or grouped table |
| **Maximum** | highest, maximum, max, top | "Highest salary" | Single value or top N list |
| **Minimum** | lowest, minimum, min | "Lowest price" | Single value |
| **Unique** | unique, distinct | "Unique categories" | List of values |
| **Distribution** | distribution, breakdown, group | "Distribution by region" | Frequency table + chart |
| **Correlation** | correlation, correlated | "Correlation between X and Y" | Correlation coefficient |
| **Percentage** | percentage, percent, proportion | "Percentage of each type" | Percentage breakdown |
| **Missing** | missing, null, empty | "Missing values" | Missing data summary |
| **Trend** | trend, over time, timeline | "Sales trend over time" | Time series chart |

---

## 🎨 Interface Overview

### 📋 Tab 1: Data View
- Interactive data table with pagination
- Search and filter functionality
- Download filtered results
- Column information display

### 📈 Tab 2: Statistics
- Comprehensive statistical summaries
- Categorical data analysis
- Correlation matrices with heatmaps
- Distribution insights

### 💬 Tab 3: Q&A Analysis
- Natural language query input
- Real-time answer generation
- Multiple result formats (tables, charts, values)
- Query history tracking

### 📊 Tab 4: Visualizations
- Custom chart builder
- Multiple chart types
- Interactive Plotly visualizations
- Export charts as images

---

## 🧪 Example Use Cases

### Business Analytics
- Analyze sales performance by region
- Track customer demographics
- Monitor product performance
- Evaluate marketing campaigns

### HR Analytics
- Employee satisfaction scores
- Salary benchmarking by department
- Turnover rate analysis
- Workforce distribution

### Financial Analysis
- Revenue trends over time
- Expense categorization
- Budget vs. actual comparisons
- Profit margin analysis

### Data Science
- Exploratory data analysis (EDA)
- Feature correlation discovery
- Missing data assessment
- Quick statistical summaries

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the Project**
2. **Create your Feature Branch** (`git checkout -b feature/AmazingFeature`)
3. **Commit your Changes** (`git commit -m 'Add some AmazingFeature'`)
4. **Push to the Branch** (`git push origin feature/AmazingFeature`)
5. **Open a Pull Request**

### Development Setup

```bash
# Clone your fork
git clone https://github.com/Hat-GitBot/Advanced-CSV-Analysis-Tool.git

# Create a branch
git checkout -b feature/your-feature

# Make changes and test
streamlit run app.py

# Commit and push
git add .
git commit -m "Description of changes"
git push origin feature/your-feature
```

---

## 🐛 Known Issues & Limitations

- Very large files (>500MB) may cause memory issues
- Complex nested queries are not yet supported
- Date parsing may fail for non-standard formats
- Limited to CSV format (Excel support coming soon)

See [open issues](https://github.com/Hat-GitBot/Advanced-CSV-Analysis-Tool/issues) for a full list.

---

## 🔜 Roadmap

- [ ] Excel file support (.xlsx, .xls)
- [ ] PDF export of analysis reports
- [ ] SQL query interface
- [ ] Machine learning predictions
- [ ] Multi-language support
- [ ] Cloud storage integration (Google Drive, Dropbox)
- [ ] Scheduled analysis and email alerts
- [ ] API endpoints for programmatic access
- [ ] Collaborative features (share analyses)
- [ ] Custom query templates

---

## 👨‍💻 Author

**Hayate Ito**
- **LinkedIn**: [Deepak Shamsheer](https://www.linkedin.com/in/deepak-shamsheer-6099b8212)
- **Email**: gitbotdown@gmail.com
- **Live Demo**:  [advanced-csv-analysis-tool.streamlit.app](https://advanced-csv-analysis-tool.streamlit.app/)
---

## 🙏 Acknowledgments

- [Streamlit](https://streamlit.io/) - For the amazing web framework
- [Pandas](https://pandas.pydata.org/) - For powerful data manipulation
- [Plotly](https://plotly.com/) - For interactive visualizations
- [NumPy](https://numpy.org/) - For numerical computing
- All contributors and testers who helped improve this project

---

## 📞 Support

If you encounter any issues or have questions:

- 📧 **Email:** gitbotdown@gmail.com
- 🐛 **Issues:** [GitHub Issues](https://github.com/Hat-GitBot/Advanced-CSV-Analysis-Tool/issues)
- 💬 **Discussions:** [GitHub Discussions](https://github.com/Hat-GitBot/Advanced-CSV-Analysis-Tool/discussions)
---

_Last Updated: November 2025_
