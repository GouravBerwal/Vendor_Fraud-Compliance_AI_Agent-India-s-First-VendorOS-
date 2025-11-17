# Vendor Fraud & Compliance AI Agent 🛡️ - (India's First VendorOS)
## Project Overview :
 VendorOS is India’s first AI-powered Vendor Fraud &amp; Compliance Agent. It automates vendor verification, detects invoice fraud, scores risk, validates GST/MSME documents, and monitors compliance in real time. Built for Indian enterprises to reduce fraud, streamline onboarding, and ensure procurement integrity.
## 🧱 How It Works (Simple Explanation) :
The system works in 4 simple steps:
1. **Collect Data** - Gathers vendor and invoice information
2. **Clean & Prepare** - Organizes and processes the data
3. **Detect Fraud** - Uses AI to find suspicious patterns
4. **Generate Reports** - Creates risk scores and easy-to-understand reports
## 📁 Project Structure :
'''VendorOS/<br>
│
├── 📘 Vendor Fraud & Compliance AI Agent.ipynb   &nbsp;&nbsp;&nbsp;&nbsp;   # Main notebook<br>
│
├── data/                                     &nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;      # Cleaned & processed datasets<br>
│   ├── vendors.csv<br>
│   ├── invoices.csv<br>
│   └── fraud_features.csv<br>
│
├── reports/                                 &nbsp;&nbsp;&nbsp;&nbsp;  &nbsp;&nbsp;&nbsp;&nbsp;      # Auto-generated reports<br>
│   ├── vendor_summary_reports/<br>
│   └── fraud_network_graphs/<br>
│
├── models/                                   &nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;      # Saved ML models<br>
│   ├── fraud_detector.pkl<br>
│   └── risk_scorer.pkl<br>
│
├── utils/                                     &nbsp;&nbsp;&nbsp;&nbsp;  &nbsp;&nbsp;&nbsp;&nbsp;    # Helper scripts (optional)<br>
│   ├── data_generator.py<br>
│   ├── preprocess.py<br>
│   └── scoring_engine.py<br>
│
└── vendor_risk_scores.csv                        &nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;  # Final exported risk scores<br>'''
## 🛠️ Installation & Setup :
Required Libraries & Why We Need Them :<br>
**Core data handling** :<br>
pip install pandas     &nbsp;&nbsp;&nbsp;&nbsp; # For working with tables and data<br>
pip install numpy     &nbsp;&nbsp;&nbsp;&nbsp;  # For mathematical calculations

**Machine Learning** :<br>
pip install scikit-learn &nbsp;&nbsp;&nbsp;&nbsp;# Pre-built AI models we use<br>
pip install xgboost     &nbsp;&nbsp;&nbsp;&nbsp;# Advanced AI algorithm<br>
pip install lightgbm    &nbsp;&nbsp;&nbsp;&nbsp;# Another smart AI algorithm

**Data Visualization** :<br>
pip install matplotlib  &nbsp;&nbsp;&nbsp;&nbsp;# For creating charts and graphs<br>
pip install seaborn     &nbsp;&nbsp;&nbsp;&nbsp;# For pretty visualizations<br>
pip install plotly      &nbsp;&nbsp;&nbsp;&nbsp;# For interactive charts

**Special Features** :<br>
pip install networkx    &nbsp;&nbsp;&nbsp;&nbsp;# For detecting vendor connections/networks<br>
pip install pyvis       &nbsp;&nbsp;&nbsp;&nbsp;# For interactive network diagrams<br>
pip install shap        &nbsp;&nbsp;&nbsp;&nbsp;# To explain how AI makes decisions<br>
pip install easyocr     &nbsp;&nbsp;&nbsp;&nbsp;# For reading text from invoices (optional)<br>
pip install rapidfuzz   &nbsp;&nbsp;&nbsp;&nbsp;# For finding similar text patterns
## 📊 Step-by-Step Process :
1. **Creating Sample Data** : 
We create fake vendor and invoice data to test our system. In real life, you would use actual company data.

What it does:

- Creates 120 fake vendors with details like GST numbers, PAN cards, addresses

- Generates 600 sample invoices

- Some invoices are intentionally made suspicious to test fraud detection
2. **Identity Verification Agent** :
This checks if vendor information looks legitimate.

Checks performed:

- PAN card format validation

- GST number matches PAN card

- Bank account length verification

- Mock GST registration check
3. **Invoice Analysis Agent** :
Analyzes invoices for suspicious patterns.

What it looks for:

- Duplicate invoice numbers

- Same invoice template used across different vendors

- Unusual payment amounts

- Suspicious text patterns in invoice content
4. **Risk Scoring Engine** :
This is the brain of the system that calculates vendor risk scores.

How it works:

- Uses Random Forest AI algorithm (like a smart decision tree)

- Considers multiple factors:

 &nbsp; &nbsp;  &nbsp;&nbsp; &nbsp;- Invoice fraud patterns

 &nbsp; &nbsp;  &nbsp;&nbsp; &nbsp;- Identity verification results

 &nbsp; &nbsp;  &nbsp;&nbsp; &nbsp;- Financial stability

 &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;- Business history

- Outputs risk probability (0-100%) and risk label (Safe/Risky)
5. **Fraud Network Detection** :
Creates connection maps between vendors to detect fraud rings.

What it finds:

- Vendors sharing same directors

- Vendors using same bank accounts

- Suspicious vendor clusters
6. **Results & Reports** :
Generates easy-to-understand outputs:

Outputs:

- 📊 Risk scores for all vendors

- 🏆 Vendor trust badges

- 📈 Interactive charts and graphs

- 📄 Individual vendor reports

- 🔍 Fraud pattern analysis

## 🎯 Key Features
## For Beginners:
- **Easy to Understand**: Plain English risk labels (Safe/Risky)

- **Visual Reports**: Color-coded risk indicators

- **Trust Badges**: Simple rating system (like star ratings)

## For Technical Users:
- **Machine Learning**: Advanced AI models

- **Network Analysis**: Detects complex fraud patterns

- **Explainable AI**: Shows why a vendor was flagged

- **Customizable Rules**: Can add business-specific rules
## 🚀 Getting Started
Quick Start:
- Run the notebook cell by cell

- The system will create sample data automatically

- View the generated risk scores and reports

- Replace sample data with your actual vendor data

## For Production Use:
- Replace the synthetic data with:

- Real vendor master data

- Actual invoice records

- GST/Udyam/MCA API integrations

- Company financial statements
## 📈 Sample Output
The system generates:

- vendor_risk_scores.csv - Complete risk assessment

- HTML reports for each vendor

- Interactive dashboards

- Fraud pattern heatmaps
## 🛡️ Real-World Applications
- Procurement Teams: Screen new vendors before onboarding

- Finance Departments: Monitor existing vendor relationships

- Compliance Teams: Ensure regulatory compliance

- Audit Teams: Focus investigations on high-risk vendors
## 💡 Why This Matters
Traditional vendor verification is manual and time-consuming. This AI system:

- ⚡ Processes 100+ vendors in minutes

- 🔍 Detects patterns humans might miss

- 📊 Provides consistent, unbiased assessments

- 💰 Saves money by preventing fraud early
## 🤝 Team
**Team** : BharatPitchers
**Lead Developer** : Gourav Berwal
**Course** : 5-Day AI Agents Intensive with Google
## 📄 License
**This project is created for educational purposes as part of the AI Agents course.**

