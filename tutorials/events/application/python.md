# Tutorial

## Step 1
Run events to write your story. 

```python
def travelled_walk():
    mobs.spawn(PRIMED_TNT, pos(0, 0, 0))
player.on_travelled(WALK, travelled_walk)

def on_item_interacted():
    pass
player.on_item_interacted(IRON_SHOVEL, on_item_interacted)
```
