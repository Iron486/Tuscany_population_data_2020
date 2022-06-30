# Tuscany Population Data 2020

The data were collected in 2020 and they are related to Tuscany.

There are 15 columns and 27573 rows in the dataset. The columns are the following: Year, Postal Code, Town, Province, Age, Unmarried Men, Married Men, Divorced Women, Widowed Man, Total # Of Males, Unmarried Women, Married Women, Divorced Men, Widowed Women, Total # Of Females.

### **Inspiration**
You can perform an exploratory data analysis of the data, working with `Pandas` or `Numpy`.
Interesting visualizations can be performed too using, for instance, Python libraries to reproduce multivariate plots, frequency plots for each feature, plots that show marital status per age etc.
Furthermore, it could be very useful for people who want to practice SQL or queries using Pandas.

Remember to upvote if you found the dataset useful :).

### **Collection methodology**
The data were fetched from the following link: https://dati.toscana.it/dataset/popolazione-residente-in-toscana-per-eta-sesso-e-stato-civile-anno-2020/resource/2b480e62-cfca-437c-b060-a06ad4e3996a.
Some of the columns in the original dataset were removed since majority of rows contained missing values and they were not so indicative.
Some columns were transformed from `object` data type to `integer`, missing values indicated with `..` were filled with the integer '0' and the headers were translated to English.

Click the following file [Tuscany_population_data.ipynb](https://github.com/Iron486/Tuscany_population_data_2020/blob/main/Tuscany_population_data.ipynb) to take a look at the preprocessing steps.

### **License**
[CC0: Public Domain
Edit](https://creativecommons.org/publicdomain/zero/1.0/)
