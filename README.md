# MultiInsight-Text-to-SQL_Results_Comparison

## Introduction

Welcome to **MultiInsight-Text-to-SQL_Results_Comparison**! This GenAI application addresses a major challenge faced by performance teams during SFT execution. It simplifies the process of analyzing test results from multiple runs, each with more than 200 testing steps, which are typically maintained in different Excel files.

## Problem Statement

Performance teams perform multiple runs during SFT execution with simultaneous hit applications and various loads to evaluate application stability after every code check-in in the SFT environment. They manually analyze results from over 200 testing steps in each run, making the process tedious, time-consuming, and prone to errors.

## Solution

To solve these problems, this GenAI application:

- **Automates Analysis**: Upload multiple Excel sheets or one by one using the "Browse file" option. The application converts Excel data into tables for analysis.
- **Comprehensive Comparison**: Provides a detailed comparison analysis of all testing steps across different cycle runs (e.g., WPC cycle one and cycle two).
- **Insightful Reporting**: Highlights performance improvements and degradations with detailed analysis and recommendations. Also, generates downloadable Excel sheets and Word documents for further analysis.

## Features

- **Multi-Model Support**: Compare the SQL results from various Text-to-SQL models side by side.
- **User-Friendly Interface**: An easy-to-navigate UI for selecting and comparing query results.
- **Detailed Comparison**: In-depth comparison of query results, highlighting differences and similarities.
- **Performance Metrics**: Analyze the performance of different models based on various criteria such as response time, execution time, and result quality.
- **Complete Analysis**: Option to download complete analysis of each testing step with over 200 records into an Excel sheet for local storage and further analysis.
- **Automated Analysis**: Converts uploaded Excel data into tables for automated analysis.
- **Comprehensive Reporting**: Provides detailed insights and recommendations, highlighting performance improvements and degradations.

## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- Python 3.12 or higher
- Required Python libraries (specified in `requirements.txt`)

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/MultiInsight-Text-to-SQL_Results_Comparison.git
    cd MultiInsight-Text-to-SQL_Results_Comparison
    ```

2. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Contact

For any inquiries or feedback, you can reach out to me via email: [bhaggarg@in.ibm.com](mailto:bhaggarg@in.ibm.com) or mobile: +91 907-579-6549.

---

Happy comparing your performance testing results!
