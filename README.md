# Smart Financial Management System

## Overview

The Smart Financial Management System is an automated solution developed for SecureBank using Python. This system streamlines various financial operations, enhancing efficiency and user experience.

## Features

- **Loan Eligibility Assessment**: Evaluates customer eligibility for loans based on employment status, income, and credit score.
- **Investment Portfolio Classification**: Categorizes investment portfolios according to risk levels.
- **Automated Loan Repayment Tracking**: Monitors and tracks loan repayments to ensure timely payments.
- **Stock Market Trend Monitoring**: Observes stock market trends and triggers alerts for significant changes.
- **Currency Exchange Rate Tracking**: Monitors currency exchange rates and suggests optimal conversion times.

## Implementation Details

The system is implemented as a Jupyter Notebook utilizing `ipywidgets` for interactive user inputs, providing a user-friendly interface.

### 1. Loan Eligibility & Interest Rate Calculation

**Objective**: Determine loan approval and applicable interest rates based on user-provided data.

**Criteria**:

- **Employment Status**: Loan approval requires the applicant to be employed.
- **Income Threshold**: Minimum monthly income of PKR 50,000 is mandatory.
- **Credit Score Evaluation**:
  - 750 and above: 5% interest rate
  - 650 to 749: 8% interest rate
  - Below 650: Loan application rejected

**Implementation**:

- Structured `if-elif-else` statements encapsulate the decision-making logic.
- Utilized `ipywidgets` to create interactive input fields for employment status, income, and credit score.
- Displayed loan decisions and corresponding interest rates based on inputs.

### 2. Investment Portfolio Classification

**Objective**: Classify investment portfolios based on the user's risk tolerance.

**Risk Categories**:

- **Low Risk**: For conservative investors seeking stable returns.
- **Medium Risk**: Balanced approach for moderate volatility acceptance.
- **High Risk**: For investors comfortable with high volatility for potential higher returns.

**Implementation**:

- Employed `ipywidgets` sliders and selection tools for users to specify risk preferences.
- Based on input, the system suggests appropriate investment portfolios.

### 3. Automated Loan Repayment Tracking

**Objective**: Monitor and track loan repayments to ensure adherence to payment schedules.

**Implementation**:

- Developed a schedule tracker logging payment dates and amounts.
- Integrated alerts to notify users of upcoming due dates or missed payments.
- Utilized `ipywidgets` for users to input payment information and view repayment history interactively.

### 4. Stock Market Trend Monitoring

**Objective**: Observe stock market trends and provide timely alerts for significant fluctuations.

**Implementation**:

- Integrated with financial data APIs to fetch real-time stock market information.
- Analyzed data to identify trends and significant changes.
- Employed `ipywidgets` for users to select specific stocks and set alert thresholds.
- Displayed visualizations of stock performance and triggered alerts based on user-defined criteria.

### 5. Currency Exchange Rate Tracking

**Objective**: Monitor currency exchange rates and suggest optimal times for currency conversion.

**Implementation**:

- Fetched real-time exchange rate data from reliable financial APIs.
- Analyzed historical data to identify favorable conversion periods.
- Provided recommendations on optimal currency conversion times based on trends.
- Utilized `ipywidgets` for users to select currency pairs and view interactive exchange rate charts.

## Repository Structure

- `AF3005_Assignment1.ipynb`: Main Jupyter Notebook containing the implementation.
- `README.md`: This document, providing an overview and implementation details.
- `requirements.txt`: List of Python dependencies required to run the notebook.

