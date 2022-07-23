### @hideIteration true 
 
 
## Step 1
Spawn mobs that eat a particular crop. 
 
```python
def on_chat():
    pass
player.on_chat("jump", on_chat)
```

```ghost
def on_on_chat():
    pass
player.on_chat("jump", on_on_chat)
 
def on_travelled_walk():
    blocks.place(CARROTS, pos(0, 0, 0))
    if blocks.test_for_block(CARROTS, pos(0, 0, 0)):
        mobs.spawn(HORSE, pos(0, 0, 0))
player.on_travelled(WALK, on_travelled_walk)
```
