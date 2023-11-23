# 課題
``` mermaid
flowchart TD
a{"必修か？"}
b{"先輩は？"}
cs[/"ーーーーーー"\]
ce[\"３回受講して"/]
c{"どうだったか"}
d["履修"]
e["非履修"]

a-->|yes|d
a-->|no|b-->|yes|cs
b-->|no|e
cs---ce
ce-->c
c-->|good|d
c-->|bad|e
```
# 課題２
``` mermaid
flowchart TD
a{"必修か？"}
b{"先輩は？"}
cs[/"ーーーーーー"\]
ce[\"３回受講して"/]
c{"どうだったか"}
f{"友達が3人いるか"}
d["履修"]
e["非履修"]

a-->|yes|d
a-->|no|b-->|yes|cs
b-->|no|e
cs---ce
ce-->c
c-->|good|d
c-->|bad|f
f-->|yes!!friend|d
f-->|no!!friend...|e
```
