# Cloud-Based Real-Time Weather Analytics and Alert System

## 📌 Project Overview
The **Cloud-Based Real-Time Weather Analytics and Alert System** is designed to monitor and analyze real-time weather conditions, focusing on temperature, humidity, and wind speed. Utilizing **AWS Cloud Services**, this system automates data ingestion, processing, visualization, and alert mechanisms to ensure proactive decision-making.

## 🚀 Features
- **Real-Time Data Ingestion**: Collects weather data from public sources or simulated datasets.
- **Cloud-Based Storage**: Uses **Amazon S3** for efficient data management.
- **Automated Processing**: Leverages **AWS Lambda** to process data and trigger alerts when thresholds are breached.
- **Interactive Dashboards**: Implements **Amazon QuickSight** to visualize weather trends.
- **Scalable Architecture**: Designed for handling large datasets and expanding to multiple locations.

## 🛠 Tech Stack & Tools
### **AWS Services**
- **Amazon S3** → Storage for weather data.
- **AWS Lambda** → Automated data processing and alerting.
- **Amazon QuickSight** → Visualization & dashboard creation.
- **AWS SNS (Optional)** → Sends notifications for threshold breaches.
- **Amazon Athena (Optional)** → Queries data in S3 for advanced analytics.

### **Other Technologies**
- Python (for data processing scripts)
- Pandas & NumPy (for data manipulation)
- CSV format (for structured data storage)

## 📊 Dataset Overview
The dataset consists of real-time weather metrics:
- **timestamp**: Recorded time of data entry.
- **temperature**: Measured in degrees Celsius.
- **humidity**: Percentage of air moisture.
- **wind_speed**: Measured in meters per second (m/s).

## 🔄 Data Processing Workflow
1. **Data Collection & Storage**
   - Weather data is collected and stored in **Amazon S3**.
   - New data files are uploaded periodically to simulate real-time ingestion.

2. **Data Processing & Alerts**
   - **AWS Lambda** function is triggered upon data upload.
   - Lambda checks if weather conditions exceed predefined thresholds.
   - If conditions are met, alerts are triggered via **AWS SNS** (if configured).

3. **Data Visualization**
   - **Amazon QuickSight** is used to create interactive dashboards.
   - Visual representations of temperature, humidity, and wind speed trends.

## 📌 Scalability & Future Enhancements
- **Multi-location Integration**: Expand the system to track weather across multiple regions.
- **Additional Metrics**: Incorporate parameters like air pressure and precipitation.
- **Machine Learning**: Use AI models to predict future weather trends based on historical data.
- **Mobile & Web Integration**: Develop a frontend for easy access to alerts and dashboards.

## ⚡ Challenges & Considerations
- Ensuring **real-time accuracy** of collected weather data.
- Managing **Lambda execution time** for large datasets.
- Designing **user-friendly QuickSight dashboards** for non-technical users.

## 📖 References
- Kevin Kiruri’s GitHub project **"Data Visualization with QuickSight and S3"**, which provided valuable insights into setting up AWS data pipelines.

## 📬 Contact & Contributions
For any suggestions or contributions, feel free to open an issue or submit a pull request.

---

📌 **Developed by:**  
- Tanvi Pradhan  
- Tanvi Salian  
- Aditya Ghuge  
