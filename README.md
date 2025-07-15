📊 Task_04_Descriptive_Stats
This project performs descriptive statistical analysis on three real-world datasets related to the 2024 U.S. presidential election and political social media activity, using three distinct approaches:

✅ Pure Python (no third-party libraries)

✅ Pandas

✅ Polars

Each method is implemented across all three datasets, and results are output as .txt files.

📁 Datasets Used (Do not include in repo)
2024_fb_ads_president_scored_anon.csv
→ Facebook ad campaigns

2024_fb_posts_president_scored_anon.csv
→ Facebook organic posts

2024_tw_posts_president_scored_anon.csv
→ Twitter posts

⚠️ Datasets are not included in this repository as per task instructions. Please download them manually if needed.

🧠 Project Structure
text
Copy
Edit
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
├── pandas_output_*.txt
├── polars_output_*.txt
├── pure_python_output_*.txt
│
└── README.md   ← (you are here)
⚙️ How to Run
Make sure you have the required dataset (.csv) in the same directory or adjust the paths in the script accordingly.

🔹 Pandas
bash
Copy
Edit
python pandas_stats_ads.py
python pandas_stats_fb_posts.py
python pandas_stats_twitter.py
🔹 Polars
bash
Copy
Edit
python polars_stats_ads.py
python polars_stats_fb_posts.py
python polars_stats_twitter.py
🔹 Pure Python
bash
Copy
Edit
python pure_python_stats_ads.py
python pure_python_stats_fb_posts.py
python pure_python_stats_twitter.py
Output will be saved as .txt files in the same folder.

🔍 What the Scripts Do
For each dataset and method, the scripts:

Display column names and data types

Automatically detect numeric fields and clean comma-formatted numbers

Compute:

Count, Mean, Min, Max, Std (for numeric columns)

Unique count and most frequent values (for categorical columns)

Group the data:

By account_type

By account_id and post_id (or page_id and ad_id)

📈 Observations & Reflections
Method	Pros	Cons
Pandas	Easy to use, rich functionality, great for fast iteration	Slower on very large files, some syntax overhead
Polars	Very fast, especially for grouping and aggregation	Slightly less intuitive syntax for beginners
Pure Python	Flexible and transparent, no dependencies	Verbose, slow, more error-prone, not scalable

💬 Recommendation
For most real-world data analysis scenarios, Pandas is the most accessible and productive. However, Polars is highly recommended for performance-intensive workflows. Pure Python is only practical for educational purposes or restricted environments.

🗃 Submission Notes
All .txt output files are included

No .csv files are committed

Each script is clearly named for its dataset and method

Output matches between all three methods

👨‍💻 Author
Kunal Ahirrao
Syracuse University | Applied Data Science
LinkedIn | GitHub

