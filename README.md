
# Background

This project is part of data analysis assignments under UCSD extension data science and visualization boot camp. 
This assignment objected to the understanding of Pandas library, having hands-on practice of using Jupiter notebook for python, and understanding some fundamental data analysis. In this assignment, the "Heroes of Pymoli" dataset is used for the analysis by demonstrating skills learned from previous lessons. This project is conducted in `Jupyter Notebook` and could refer to [Analysis of HeroesOfPymoli](https://nbviewer.jupyter.org/github/KeSavanh/pandas-challenge/blob/main/HeroesOfPymoli/HeroesOfPymoli.ipynb)

# Heroes of Pymoli

The dataset is about item purchasing in a video game called "[Heroes of Pymoli](https://github.com/KeSavanh/pandas-challenge/blob/main/HeroesOfPymoli/purchase_data.csv)" which mainly contains information on buying and demographic data of players. The dataset was provided in CSV format and consists of the following columns `Purchase ID`, `SN`, `Age`, `Gender`, `Item ID`, `Item Name`, `Price`, 

# Data processing

The CSV file was imported and read using the `.read_csv()` function in  Pandas, then converted to a data frame using `.DataFrame()` function. The dataset was broken down into specific fields for different analyses. The function `.groupby()` was used to sort out a specific column in this process.
The Pandas function `nunique` or `value_counts` was applied in writing syntax to calculate the count of a unique element as well as other calculations of average (`.mean()`), total value (`.sum()`). The results are held and clearly displayed by data frames.

# Findings

   1. The gender demographics of players showed a significantly large number of male players (484) or 84.03% out of the total players (576), and female players account for only 14.06% of the entire players. 
   2. The Purchasing analysis by age suggested showed the highest number of purchases (258) is by the players in the age range of 20 to 24, following by the players in the age range of 15 to 19 which considerably high school students. The combination of the players in two age ranges (365) distribute 63% of the total players. The finding could imply that the players in their 20s, the majority are financially independent college students and have more potential to pay than high school students.
   3. The total purchase value per item analysis indicated that "Final Critic" had the most purchasing frequency and gave the highest revenue among other items, even though its price ($ 4.61) is notably high when compared to the average price ($3.05). Therefore, "Final Critic" is the most popular and profitable item.

# Table of Content

   - [Player Count](https://nbviewer.jupyter.org/github/KeSavanh/pandas-challenge/blob/main/HeroesOfPymoli/HeroesOfPymoli.ipynb#)
   - [Purchasing Analysis (Total)](https://nbviewer.jupyter.org/github/KeSavanh/pandas-challenge/blob/main/HeroesOfPymoli/HeroesOfPymoli.ipynb#)
   - [Gender Demographics](https://nbviewer.jupyter.org/github/KeSavanh/pandas-challenge/blob/main/HeroesOfPymoli/HeroesOfPymoli.ipynb#)
   - [Purchasing Analysis (Gender)](https://nbviewer.jupyter.org/github/KeSavanh/pandas-challenge/blob/main/HeroesOfPymoli/HeroesOfPymoli.ipynb#)
   - [Age Demographics](https://nbviewer.jupyter.org/github/KeSavanh/pandas-challenge/blob/main/HeroesOfPymoli/HeroesOfPymoli.ipynb#)
   - [Purchasing Analysis (Age)](https://nbviewer.jupyter.org/github/KeSavanh/pandas-challenge/blob/main/HeroesOfPymoli/HeroesOfPymoli.ipynb#)
   - [Top Spenders](https://nbviewer.jupyter.org/github/KeSavanh/pandas-challenge/blob/main/HeroesOfPymoli/HeroesOfPymoli.ipynb#)
   - [Most Popular Items](https://nbviewer.jupyter.org/github/KeSavanh/pandas-challenge/blob/main/HeroesOfPymoli/HeroesOfPymoli.ipynb#)
   - [Most Profitable Items](https://nbviewer.jupyter.org/github/KeSavanh/pandas-challenge/blob/main/HeroesOfPymoli/HeroesOfPymoli.ipynb#)




