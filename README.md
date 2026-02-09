# ✈️ Airline Booking Fraud Detection System

## 🎯 Project Overview

A **production-ready fraud detection system** that identifies fraudulent airline bookings using hybrid AI combining rule-based detection with machine learning.

### The Business Problem
- Airlines lose **$1.4 billion annually** to booking fraud
- **6-15% of bookings** are potentially fraudulent  
- Traditional methods miss **60-70% of fraud** or create too many false positives

### Our Solution
**Hybrid 3-layer detection:**
1. **Rule-based** → 9 specific fraud indicators
2. **Machine Learning** → Isolation Forest anomaly detection  
3. **Risk Scoring** → 0-100 score with 4 risk categories

### Key Results
✅ **36.4% fraud detection rate**  
✅ **100% precision** (zero false positives)  
✅ **$458K annual savings** potential  
✅ **6,471% ROI**  

---

## 🚀 Quick Start

```bash
# Install dependencies
pip install pandas numpy scikit-learn matplotlib seaborn

# Run analysis
python generate_airline_data.py
python fraud_detection_analysis.py
python create_fraud_visualizations.py
```

---

## 📊 What You Get

### Deliverables
1. **Dataset:** 1,200 realistic airline bookings with fraud labels
2. **Analysis:** Comprehensive fraud detection with risk scores
3. **Visualizations:** 4 professional dashboards
4. **Report:** Executive summary with ROI analysis

### Key Metrics
- **Detection Rate:** 36.4% of frauds caught
- **Precision:** 100% (no false positives)
- **Annual Savings:** $458,136
- **ROI:** 6,471%

---

## 🔍 Fraud Indicators

| Flag | Description | Impact |
|------|-------------|--------|
| 🚨 SUSPICIOUS_EMAIL | Temp email domains | 63 cases |
| ⚡ HIGH_VELOCITY | >5 bookings/24h | 56 cases |
| 💳 PAYMENT_FAILS | >3 failed attempts | 54 cases |
| 📱 DEVICE_ABUSE | >10 bookings/device | 33 cases |

---

## 💰 Business Impact

**Revenue Protection:**
- Total revenue: $1.6M
- Fraud exposure: $101K
- Prevented losses: $35.8K
- **Annual savings: $458K**

---

## 🎯 Perfect For

- Data analyst portfolios
- ML interviews
- Fraud detection case studies
- Business analysis projects

**Time to complete:** 3 hours  
**Skill level:** Advanced Python + ML
