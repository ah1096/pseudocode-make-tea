# MAKING TEA

## ABOUT
- tea is a drink made by steeping tea leaves in boiling water
- there are various types of tea that require different temperatures of boiled water
- tea is prepared in a mug, teacup, or other vessel that can withstand having boiling water poured in it

## INIT: create variables
1. MUG: used to contain the tea
  * PROPERTIES: mugLocation, mugVolume
2. INFUSER: used to steep the tea
  * PROPERTIES: infuserFillAmount
3. TEA LEAVES: in three varieties: white, green, and black. we're using loose leaf because it's ✨eco-friendly✨  
  * PROPERTIES: teaChoice
4. WATER: the medium in which tea becomes a drink
  * PROPERTIES: waterTemp, waterFillAmount
5. KETTLE: boils the water
  * PROPERTIES: kettlFillAmount, kettleBoilTemp
6. ADDITIVES: things added to tea to make it taste different (lemon, milk, sugarcube, honey). DO NOT add lemon AND milk; the milk will curdle
  * PROPERTIES: dissolved
7. SPOON: used to stir additives into tea

## FUNCTIONALITY

**FUNCTION getMug**
1. select a mug
2. let mugLocation = a flat surface

**FUNCTION chooseTea**
1. let teaChoice = white, black, or green
2. insert chosen tea in the infuser
3. let infuserFillAmount = one tablespoon

**FUNCTION boilWater**
1. fill the kettle with water
2. IF teaChoice = black
       THEN let kettleBoilTemp = 208 F
            ELSE let kettleBoilTemp = 180 F

**FUNCTION fillMug**
1. put an object into the mug



