# 📊 POWER BI LEARNING PORTFOLIO
## *"Small Collection, Big Learnings"*

---

## 🎯 What's Inside?

This repository contains my Power BI learning journey from a Microsoft course.

**What you'll find:**
- 📈 Power BI report files (.pbix)
- 📸 Dashboard screenshots

---

## 📂 Project Structure

```
power-bi-learning/
│
├── 📁 reports/          # .pbix report files
│   ├── sales_dashboard.pbix
│   ├── customer_analysis.pbix
│   └── hr_dashboard.pbix
│
├── 📁 screenshots/      # Dashboard screenshots
│   ├── sales_dashboard.png
│   ├── customer_analysis.png
│   └── hr_dashboard.png
│
└── README.md
```

---

## 📊 My Reports

| Report | Description | Key Learnings |
|--------|-------------|---------------|
| **Sales Dashboard** | Sales by region and product | Slicers, filters, KPIs |
| **Customer Analysis** | Customer segmentation | DAX calculated columns |
| **HR Dashboard** | Employee headcount and salary | Matrix visuals |

---

## 🎓 What I Learned

### From Microsoft Course:
- Data import and transformation
- Table relationships and modeling
- Basic DAX (SUM, AVERAGE, CALCULATE)
- Choosing the right visuals
- Adding slicers and interactivity

### Key DAX Formulas:
```dax
Total Sales = SUM(Sales[Revenue])
Avg Order = AVERAGE(Sales[Revenue])
YTD Sales = TOTALYTD(SUM(Sales[Revenue]), 'Date'[Date])
```

---

## 🚀 How to Use

1. **Clone the repo:**
   ```bash
   git clone <your-repo-url>
   cd power-bi-learning
   ```

2. **Open any report:**
   - Browse to `/reports` folder
   - Double-click any `.pbix` file
   - Opens in Power BI Desktop

3. **View screenshots:**
   - Check `/screenshots` folder
   - See dashboard previews

---

## 💡 What's Next

- Build more complex dashboards
- Learn advanced DAX
- Practice with real-world datasets

---

## 📄 License

Free to use for learning and inspiration.

---

**Learning Power BI, one dashboard at a time!** 📊
