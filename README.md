# Movie Correlation Analysis (Python)

An analysis of movies that tests which factors line up with box-office earnings.

**Tools:** Python, pandas, seaborn, matplotlib, Jupyter  
**Data:** `movies.csv` in this folder ([source on Kaggle](https://www.kaggle.com/datasets/danielgrijalvas/movies)) — budget, revenue, cast, director, genre, and more

---

## How to run

From this project folder:

```text
python -m pip install -r requirements.txt
python -m jupyter notebook Movie_Correlation_with_Python.ipynb
```

Then run all cells. The notebook reads `movies.csv` from the same folder.

If the `jupyter` command is not recognized, use `python -m jupyter notebook` as shown above.

---

## What I did

- Cleaned the data and handled missing values
- Encoded categorical fields (company, genre) into numeric form
- Built a correlation matrix and visualized it with a heatmap and regression plots

## What I found

- Budget shows the strongest correlation with gross earnings
- The number of votes (audience engagement) is the next strongest
- Genre and production company have little correlation with earnings
