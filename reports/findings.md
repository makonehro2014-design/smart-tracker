# Findings v1 — <topic>

## Dataset
-import pandas as pd

tips_url = "https://raw.githubusercontent.com/mwaskom/seaborn-data/master/tips.csv"
df_tips = pd.read_csv(tips_url)
display(df_tips.head())

import pandas as pd

mpg_url = "https://raw.githubusercontent.com/mwaskom/seaborn-data/master/mpg.csv"
df_mpg = pd.read_csv(mpg_url)
display(df_mpg.head())

import pandas as pd

penguins_url = "https://raw.githubusercontent.com/mwaskom/seaborn-data/master/penguins.csv"

df_penguins = pd.read_csv(penguins_url)
display(df_penguins.head())

import pandas as pd

taxis_url = "https://raw.githubusercontent.com/mwaskom/seaborn-data/master/taxis.csv"
titanic_url = "https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv"
life_exp_url = "https://ourworldindata.org/grapher/life-expectancy.csv"

df_taxis = pd.read_csv(taxis_url)
display(df_taxis.head())

## Cleaning decisions
- التكرار: (اتمسى/لا — وليه)
- النواقص: (dropna أو fillna — وليه)
- أنواع غلط / outliers: ...

## Finding 1
- الجملة: ...
- الدليل (نتيجة Pandas): ...

## Finding 2
- الجملة: ...
- الدليل: ...

## Finding 3
- الجملة: ...
- الدليل: ...

## Finding 4
- الجملة: ...
- الدليل: ...

## Finding 5
- الجملة: ...
- الدليل: ...
