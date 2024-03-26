# intro-analytics
learn sql and python for data analysis

----
## Getting started with SQL

Go to `https://hex.tech/` and click Get Started. Create an account using the free Community plan:

<img width="200" alt="Screenshot 2024-03-25 at 6 11 15 PM" src="https://github.com/rachelwhaley/intro-analytics/assets/9064317/d06ca8fe-3f74-4d09-87f4-399940dbf8a3">

Click `+ New` to create a new Hex project. 

#### Load your datasets
We are going to be using 2 datasets for this session:
* Data on all transcripts of Seinfeld episodes, from [data.world](https://data.world/juanjosecas/seinfeld-scripts)
* Ratings of every Seinfeld episode, from [Kaggle](https://www.kaggle.com/datasets/hod101s/seinfeld-imdb-ratings?resource=download) (originally sourced from IMDB)

To load the Transcripts data, click `Python Cell` to add a Python cell. We are going to use a python command to load one of our datasets into our notebook. Don't worry too much about the specifics of how this works yet -- we'll talk more about this in week 2. Paste this into your python cell:
```
  import pandas as pd
  df = pd.read_csv('https://query.data.world/s/2svp7yxiggyn4eui6wvklptslqctle?dws=00000')
```
And hit `Run` (or use Command-Enter on your keyboard). 
