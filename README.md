# 📌 Customer Ticket Analysis & Automation

## 🚀 Project Overview
This project focuses on analyzing **customer support tickets**, identifying trends, and automating ticket management. It provides insights into **issue types, resolution times, agent performance**, and **automatically closes** long-resolved tickets to improve efficiency.

## 🛠️ Features
- 📊 **Data Analysis & Visualization**: Understand ticket trends, issue distribution, and resolution time.
- 🤖 **Automation**: Auto-closing resolved tickets after **48 hours**.
- 📈 **Priority-Based Insights**: Analyze resolution times across different priority levels.
- 🔍 **Sentiment Analysis**: Determines customer sentiment from ticket interactions.
- 📉 **Agent Performance Metrics**: Evaluates workload and resolution efficiency.

## 🏗️ Tech Stack
- **Python**: Data processing & automation
- **Pandas & NumPy**: Data handling & transformation
- **Matplotlib & Seaborn**: Data visualization
- **SQL**: Data storage & retrieval

## 📂 Dataset
The dataset includes **500 customer support tickets** with the following attributes:
- Ticket ID
- Customer ID
- Issue Type (Billing, Technical, Account, etc.)
- Priority (Low, Medium, High, Urgent)
- Status (Open, In Progress, Resolved, Closed)
- Created & Resolved Timestamp
- Resolution Time (in hours)
- Assigned Agent
- Sentiment Score

🔗 **[Download Dataset](sandbox:/mnt/data/customer_tickets.csv)**

## 📜 How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Customer-Ticket-Analysis.git
   cd Customer-Ticket-Analysis
   ```
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Run the **analysis script**:
   ```bash
   python customer_ticket_analysis.py
   ```
4. Review the **updated dataset** with automated ticket status:
   ```bash
   customer_tickets_updated.csv
   ```

## 📊 Visualization & Insights
- **Issue Type Distribution** 📌
- **Resolution Time by Priority** 🕒
- **Agent-wise Ticket Handling** 👨‍💼

## 🚀 Future Enhancements
- 🔥 **AI-based Chatbot Integration** for automatic ticket responses.
- 📡 **Live Dashboard** for real-time monitoring of ticket trends.
- 🔍 **Advanced NLP Sentiment Analysis** for better customer insights.

## 🤝 Contributing
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature-name`).
3. Commit changes (`git commit -m "Added new feature"`).
4. Push to the branch (`git push origin feature-name`).
5. Open a Pull Request.

## 📄 License
This project is **open-source** and available under the **MIT License**.
