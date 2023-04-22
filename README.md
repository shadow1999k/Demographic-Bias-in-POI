# Demographic-Bias-in-POI
This repository belong to demographic bias in POI. POI Point of interest (POI) data provides intelligence on real-world public places, such as retail stores, restaurants, parks, monuments, and other sites of convenience or tourist attractions

## Groups

## Age
- G1: Aged (> 30) users
- G2: Non-aged (<= 30) users

## Gender
- G1: Male users
- G2: Female users

## Model

```
python cpfairrank_model.py -d TRECx1516 -ug age
```


## Datasets
1. TRECx1516 
2. MovieLenz100k 
  Each user has at least 20 ratings. \
  A fair subset of original dataset is selected to be just like TRECx1516 in terms of age/gender bias. \
  User categorization --> the same strategy (like TRECx1516)
  
