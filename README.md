# 🏎️ Automotive Executive Sales Dashboard

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![UI/UX](https://img.shields.io/badge/Design-Premium-FF69B4?style=for-the-badge)

A high-fidelity, interactive Power BI dashboard designed for the automotive industry. This project demonstrates advanced data storytelling, dynamic UI navigation, and complex DAX modeling for executive-level reporting.

---

## 📂 Project Structure
Automotive-Sales-Dashboard/
├── 📊 Dashboard/
│   └── Raw_Car_Dashboard.pbix      # Main Power BI Project File
├── 📁 Data/
│   ├── Sales_Orders.csv            # Primary transaction data
│   └── New_Category.dax            # Summarized DAX table logic
├── 🖼️ Screenshots/                 # Dashboard UI Gallery
│   ├── main_view.png               
│   ├── suv_view.png                
│   └── filter_pane.png             
├── 🎨 Assets/
│   ├── Icons/                      # KPI and Navigation SVG icons
│   └── UI_Layout/                  # Background templates
└── 📝 README.md                    # Project documentation

🖼️ Dashboard Showcase
1. Executive Overview
The landing page features core KPIs: Sales ($746K), Growth (21.4%), and Profit ($292.30K) with a minimalist aesthetic.

2. Custom Pop-out Navigation
A "Clean UI" approach using Bookmarks to hide/show an advanced sidebar for Region, Ship Mode, and Customer filtering.

3. Dynamic Model Switching
Interactive navigation allows users to cycle through vehicle models (Audi, Lexus, Land Rover) which updates the visual context.

🛠️ Technical Implementation
DAX Modeling: Used SUMMARIZE functions to create dynamic category tables and Time Intelligence for YoY analysis.

UI/UX: Implemented a selection-pane-based carousel for car model switching.

Visual Stack: * Donut Charts: Booking channel segmentation (Direct, Third Party, Pre-Book).

Bar Charts: Service category analysis (Replacement vs. Servicing).

Trend Lines: Monthly sales seasonality tracking.

🚀 Installation & Usage
Clone the repository:

Bash
git clone [https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git)
Setup Data:

Open Raw_Car_Dashboard.pbix in Power BI Desktop.

Go to Transform Data -> Data Source Settings to re-link files if necessary.

🤝 Contributing
Fork the Project.

Create a Feature Branch (git checkout -b feature/AmazingFeature).

Commit Changes (git commit -m 'Add some AmazingFeature').

Push to the Branch (git push origin feature/AmazingFeature).

Open a Pull Request.

📜 License
Distributed under the MIT License.

Developed by: [Your Name]

Connect: [LinkedIn Profile Link]


Would you like me to help you write the **License file** text now?
