## How to use the upgrade system

Each item requires it's own class which should inherit the constructor from the upgrade base class. The effect is completely customizable HOWEVER, it is recommended to create a key using the included dictionary list and make the effect that it increments the key, this is to save headache down the line. For items which effect is temporary, using the effect directly works well too. 

You now need to add the class into the "class item list" regioj using the following syntax:
``` 
upgradeList.Add(new NewUpgrade(upgradeGeneric.rarity.common, "Button tooltip"));
```

Then if you made a key for the item, add it into the "item key list" region using the following syntax 
```
items.Add("KeyName", 0)
```
If you do not use "0", you will start with n-amount of items (n being the number you substituted 0 for) when you start the game, this can be useful for debugging
