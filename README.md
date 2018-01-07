# Pokemon-ML
Gotta predict them all! Pokemon!

## Type Prediction

### Combined Type Prediction

Predict the pokemon type regardless of its order. That is to say, we are not interested in making the distinction between `Type_1` and `Type_2` order. For example: a `grass / poison` type will be treated the same as a `poison / grass` type.

**Features to use in classification:**



- Battling Attributes: `Total`, `HP`, `Attack`, `Defense`, `Sp_Atk`, `Sp_Def`, `Speed`
- Physical Attributes: `Color`, `hasGender`, `Egg_Group_1`, `Egg_Group_2`, `Height_m`, `Weight_kg`, `Body_style`
- Other: `Generation`
