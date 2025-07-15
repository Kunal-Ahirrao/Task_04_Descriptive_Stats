# 📊 Task_04_Descriptive_Stats

This project performs descriptive statistical analysis on three real-world datasets related to the **2024 U.S. presidential election and political social media activity**, using three different methods:

- ✅ Pure Python (no third-party libraries)
- ✅ Pandas
- ✅ Polars

Each approach is applied across all datasets, and results are exported as `.txt` files for consistency and reporting.

---

## 📁 Datasets Used

> ⚠️ **NOTE**: Datasets are not included in this repository per project instructions.  
> Please download the following datasets manually before running the code:

1. `2024_fb_ads_president_scored_anon.csv` – Facebook ad campaigns  
2. `2024_fb_posts_president_scored_anon.csv` – Facebook organic posts  
3. `2024_tw_posts_president_scored_anon.csv` – Twitter posts  

---

## 🧠 Repository Structure

Task_04_Descriptive_Stats/
│
├── pandas_stats_ads.py
├── pandas_stats_posts.py
├── pandas_stats_twitter.py
│
├── polars_stats_ads.py
├── polars_stats_posts.py
├── polars_stats_twitter.py
│
├── pure_python_stats_ads.py
├── pure_python_stats_posts.py
├── pure_python_stats_twitter.py
│
├── pandas_output_.txt
├── polars_output_.txt
├── pure_python_output_*.txt
│
└── README.md

---

## ⚙️ How to Run

Make sure the corresponding `.csv` dataset is in your working directory. Then run each script based on the method you want to test.

### ▶️ Pandas Scripts

python pandas_stats_ads.py
python pandas_stats_posts.py
python pandas_stats_twitter.py
⚡ Polars Scripts

python polars_stats_ads.py
python polars_stats_posts.py
python polars_stats_twitter.py
🧪 Pure Python Scripts

python pure_python_stats_ads.py
python pure_python_stats_posts.py
python pure_python_stats_twitter.py
All results will be saved in .txt files in the project folder.

🔍 What Each Script Does
Each script performs:

📌 Column type inspection

🧹 Cleaning (e.g., comma-separated numbers)

📈 Descriptive statistics (count, mean, min, max, std)

📊 Grouped analysis by:

account_type

account_id + post_id or page_id + ad_id

📈 Method Comparison
Method	Pros	Cons
Pandas	Easy, widely used, great documentation	Slower on very large datasets
Polars	Lightning fast, ideal for large-scale grouped stats	Slightly steeper learning curve
Pure Python	Full control, no dependencies	Verbose, slower, not scalable

✅ Recommendation
For practical work, Pandas is ideal due to its simplicity and expressiveness.
If performance is critical (e.g., millions of rows), consider switching to Polars.
Pure Python is excellent for learning or environments without external libraries.

📬 Submission Notes
.csv files are excluded

.txt output files are included

File naming follows {library}_stats_{dataset}.py and {library}_output_{dataset}.txt

👨‍💻 Author
Kunal Ahirrao
Master’s in Applied Data Science
Syracuse University
LinkedIn | GitHub

---

Let me know if you’d like this saved into an actual `README.md` file or zipped up with your final project folder!







