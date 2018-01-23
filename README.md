# Pokemon-ML
Gotta predict 'em all! Pokemon!

This is an exploration and analysis of the Pokemon from generations 1 to 6. The data is from [kaggle user alopez247](https://www.kaggle.com/alopez247/pokemon/data).

## Type Prediction

I am curious to see if we can develop a model which can have predict pokemon type. A Pokemon's type is indicative of the elemental characteristics associated with that pokemon and its attacks.

Current work on predicting Pokemon type can be found in these notebooks: `/notebook/02_typePrediction.ipynb` and `/notebook/02_WaterTypePredictions.ipynb`.

**Features to use in classification:**

- Battling Attributes: `Total`, `HP`, `Attack`, `Defense`, `Sp_Atk`, `Sp_Def`, `Speed`
- Physical Attributes: `Color`, `hasGender`, `Egg_Group_1`, `Egg_Group_2`, `Height_m`, `Weight_kg`, `Body_style`
- Other: `Generation`
