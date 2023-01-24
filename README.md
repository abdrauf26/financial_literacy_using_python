# Financial Literacy Using Python

<img width="951" alt="image" src="https://user-images.githubusercontent.com/96287600/214325975-2a1d2043-54b8-48b4-a7cb-c392bfd6da3c.png">


## Built With 💻

- [![Jupyter Badge](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=fff&style=flat)](https://jupyter.org/try)
- [![Python Badge](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff&style=flat)](https://www.python.org/)

## Financial Literacy Using Python 

### Calculating Total Amount Of Savings
```
saving_notes = 500
savings_coins = 70
total = saving_notes + savings_coins 
print ("The Total Amount Of Savings = $",total)

```
### Calculating Total Amount Of Savings (Keying in amount)
```
saving_notes = float(input("Enter the savings amount in notes: $"))
savings_coins = float(input("Enter the savings amount in coins: $"))
total = saving_notes + savings_coins 
print ("\nThe Total Amount Of Savings = $",total)

```
### Calculating Total Amount Of Savings in months (Keying in amount)
```
savings_per_mth = float(input("Enter the savings per month: $"))
total_mth = float(input("Enter the total number of months: "))
total = savings_per_mth * total_mth 
print ("The Total Amount Of Savings in",total_mth, "months is $",total)

```
### Using Function in Python 
```
def savings_expenses(): # How much savings that can last for the number of months of expenses
    total_savings = float(input("Enter your Total Amount Of Savings: $"))
    monthly_exp = float(input("Enter your Total Amount of Expenses: $"))
    num_of_mths = total_savings/monthly_exp
    print ("The Total Amount Of Savings can last for", num_of_mths, "months of expenses." ) 
savings_expenses()

```
### Managing the range for number of months of expenses in terms of savings
```
num_of_mths = float(input("Enter the number of months of expenses in terms of savings:"))

if 6<num_of_mths<13:
    print ("Well Done!!! Great Job !!! ")
    
elif 3<num_of_mths<5:
    print("You are doing great!!! Keep it up !!")

elif 0<num_of_mths<2:
    print("Awesome !!! Keep building your savings!!!")
    
else:
    print("The amount entered is not within range. Thank you.")

```
## [![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)
- [Jupyter Notebook Viewer - Financial Literacy Using Python](https://github.com/abdrauf26/financial_literacy_using_python/blob/main/Financial%20Literacy%20Using%20Python.ipynb)

## Social 📧 

[![Google Cloud Badge](https://img.shields.io/badge/Google%20Cloud-4285F4?logo=googlecloud&logoColor=fff&style=flat)](https://www.cloudskillsboost.google/public_profiles/c2ff4f8e-4f42-4380-b038-73104c7d98fc) [![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=fff&style=flat)](https://www.linkedin.com/in/abdrauf26/) [![Tableau Badge](https://img.shields.io/badge/Tableau-E97627?logo=tableau&logoColor=fff&style=flat)](https://public.tableau.com/app/profile/mohamed.abdul.rauf) [![GitHub Badge](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=fff&style=flat)](https://github.com/abdrauf26) [![Medium Badge](https://img.shields.io/badge/Medium-000?logo=medium&logoColor=fff&style=flat)](https://medium.com/@rauf.yusope) ![Profile views](https://gpvc.arturio.dev/abdrauf26) 

## Acknowledgements

- [Jupyter](https://jupyter.org/)
- [Conda](https://docs.conda.io/en/latest/)
- [Anaconda](https://anaconda.org/)
- [Github](https://github.com/)
- [Stack Overflow](https://stackoverflow.com/)
- [Jupyter nbviewer](https://nbviewer.org/)
- Badges - https://badges.pages.dev/
- Badges - https://naereen.github.io/badges/
- Badges - https://github.com/Ileriayo/markdown-badges#-office
