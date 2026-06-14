class SanthoshKumar:
    def __init__(self):
        self.name            = "Santhosh Kumar"
        self.location        = "Vellore, Tamil Nadu, India"
        self.degree          = "B.C.A — Vellore Institute of Technology (2023–2026)"
        self.email           = "santhosh.work010@gmail.com"
        self.linkedin        = "linkedin.com/in/sanx07"

        self.stack = [
            "Python (Pandas, NumPy, Matplotlib, Seaborn)",
            "SQL", "Excel", "Power BI",
            "Machine Learning (Scikit-learn, XGBoost, Random Forest)",
        ]

        self.currently_learning = [
            "Advanced ML pipelines",
            "Azure Data Services",
            "dbt + BigQuery for analytics engineering",
        ]

        self.fun_fact = "I once found a 0.99 correlation between two fuel metrics \
and built a whole regression model around it 🚗📊"

    def motto(self) -> str:
        return "Data is the new oil — I'm here to refine it."

me = SanthoshKumar()
print(me.motto())
