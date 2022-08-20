# Mortality

This short repo is used to create two GIFs based on the survival rate of individuals by their sex, age and revenue in France.

## Data

The data I used is from French administration [INED (Institut National d'Études Démographiques)](https://www.ined.fr/fr/tout-savoir-population/chiffres/france/mortalite-cause-deces/table-mortalite/). I used the following [file](https://www.ined.fr/fichier/s_rubrique/193/morta_niv_2016.fr.xls). You can find how I treated this data in [this notebook](01_mortality_by_sex.ipynb).

## Women

![survival rate for women](mortalite_bar_femmes.gif)

## Men

![survival rate for men](mortalite_bar_hommes.gif)

## How to read it

![survival rate for men aged 75](table_mortalite_bar_hommes/075_mortalite_hommes.png)

From left to right, each bar represents 5% of the population according to their revenue (from poorest to richest). The considered age here is 75. We can see that about 50% of the poorest are already dead (red bar on the left) and that the richer you get, the more likely you are to live up to age 75.
