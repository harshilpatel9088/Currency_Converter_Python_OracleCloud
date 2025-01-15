# Currency_Converter_Python_OracleCloud
# Live Currency Converter Dashboard

This project focuses on the development of a **Currency Converter Dashboard** utilizing a live API and the **Django framework** to create an intuitive and user-friendly dashboard. The application is hosted on a **virtual machine**, ensuring global accessibility 24/7.

## Project Overview

The primary goal of this project was to design a dynamic and interactive platform where users can:

- View **real-time currency conversions**.
- Analyze **historical trends** of currency conversion over the past 365 days.
- Access **forecasted conversion trends** for the next 30 days.

The website is designed with ease of use in mind, providing users with both current and historical data, alongside future predictions, all in one centralized dashboard.

## Tools and Technologies Used

### Programming Language:
- **Python**: The core programming language used for building the application.

### Libraries:
- **requests**: Used for making HTTP requests to interact with APIs and retrieve data from the web.
- **Pandas**: Utilized for converting data into data frames and performing data cleaning and processing tasks.
- **Plotly & Matplotlib**: Libraries for creating interactive and static visualizations.
- **Datetime & date**: Used for handling and manipulating dates and times.
- **Prophet**: A forecasting tool used for predicting currency conversion rates for the next 30 days.

### Framework:
- **Django**: The framework used for designing the web application. The goal of the project was to build a currency converter, which is hosted on a virtual machine.

### API:
- **Exchange Rates API**: The application integrates with [APILayer Exchange Rates API](https://apilayer.com/) to fetch real-time exchange rates.

### Cloud Technology:
- **Oracle Ubuntu Compute Instance**: The application is hosted on an Oracle Cloud virtual machine (VM) running Ubuntu. The Ubuntu machine was set up and configured to ensure secure access to the application.
- **Security Ports Configuration**: The VM's security ports were configured to allow access to specific ports required by the application, ensuring that the necessary services were exposed to the internet while maintaining the security of the system.
- **Gitbash**: Used to interact with the virtual machine.
- **Putty**: Used to set up and manage the virtual machine on Oracle Cloud.

### Website Design:
- **HTML & CSS**: Used for designing and styling the front-end of the website.

### Version Control:
- **Git**: Used for version control to commit and pull code to and from the virtual machine.

### Integrated Development Environment (IDE):
- **Visual Studio**: The primary IDE used for development.

### Operating Systems:
- **Windows**: For local development and testing.
- **Linux (Ubuntu)**: For hosting the application on the virtual machine.

### Additional Setup:
- **Registering Port with Domain Name & SSL Certificate**: Configured domain name and secured the application with an SSL certificate for secure communication.

## Project Execution

### 1. Finding an API for Exchange Rates
The first step in executing this project was identifying a reliable API to fetch real-time exchange rate data. After evaluating various options, the **Exchange Rates API** provided by [APILayer](https://apilayer.com/) was chosen due to its extensive currency support and reliable data accuracy.

### 2. Selecting a Framework for Dashboard Creation
The next step involved selecting an appropriate framework to build the dashboard. **Django** was chosen as the framework for this project. The primary reason for using Django was to design a web-based dashboard that could be deployed and run directly on a server, particularly on the cloud-based virtual machine (VM).

Other tools like **Tableau** or **Power BI** were considered for dashboard creation. However, these platforms typically require additional costs for hosting interactive dashboards on the cloud and do not provide cost-effective solutions for running dashboards directly on cloud-based virtual machines without incurring ongoing charges for hosting and access. In contrast, **Django** allowed for a fully functional, interactive web application that could be hosted on a cloud server (such as an Oracle VM) at a fraction of the cost, ensuring global accessibility without the extra overhead of recurring charges associated with third-party dashboard platforms.


