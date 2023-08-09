---
description: Here you can see how to setup variables.
---

# Variables

**Note:** It must be inside of your main file, in most cases this is `index.js`

### Setup Variables:

#### Information:

1. **Name** => the variable name. Call it whatever you want
2. **Value** => the default value of the variable. 

**Note:** It's always this default value unless you change it using functions like [$setVar](../../../functions/usdsetvar.md).

#### Usage:

```javascript
bot.variables({
  Name: "Value",
  Name2: "Value2"
})
```

#### Example Creation:
```javascript
bot.variables({
  prefix: "!",
  myName: "Leref"
})Note: If you're using a command handler, this remains the same!If you want to make a new variable, for example "apples", you just have to add a , after the last variable value and type the name and value of the new variable, as shown below:bot.variables({
  prefix: "!",
  myName: "Leref",
  apples: 0
})
```
