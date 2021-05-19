# Welcome!

This Python template lets you get started quickly with a simple one-page playground.

```python runnable
print('Hello World!')
```

# Advanced usage

If you want a more complex example (external libraries, viewers...), use the [Advanced Python template](https://tech.io/select-repo/429)
while True:
    ally_bot_alive = int(input())  
    total_entities = int(input())  
    shieldDic = {} # create en empty dic
    for i in range(total_entities):
        inputs = input().split()
        ent_id = int(inputs[0])  # the unique gameEntity id, stay the same for the whole game
        ent_type = inputs[1] 
        health = int(inputs[2])  
        shield = int(inputs[3])  
        shieldDic[ent_id] = shield  # store the shield value for the id
        ... 