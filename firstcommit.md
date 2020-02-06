commit c46c7e4b82279e350698f26de521482d8bab9578 (HEAD -> master)
Author: Truls Jørgensen <trulsjor@gmail.com>
Date:   Thu Feb 6 11:19:29 2020 +0100

    En skjematisk fremstilling dav datamodellen i git

```mermaid
graph TB
classDef blob fill:cyan,stroke-width:0px;
classDef tree fill:orange,stroke-width:0px;
classDef commit fill:lightgreen,stroke-width:0px;
classDef tag fill:yellow,stroke-width:0px;
classDef peker fill:lightgrey,stroke:black, stroke-width:2px,stroke-dasharray:5,5


Datamodell.md:::blob
git-for-ikke-utviklere:::tree --> Datamodell.md
c46c7e4b82279e350698f26de521482d8bab9578:::commit -->git-for-ikke-utviklere
master:::peker-->c46c7e4b82279e350698f26de521482d8bab9578
HEAD:::peker --> master
