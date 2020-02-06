
```mermaid
graph TB
classDef blob fill:cyan,stroke-width:0px;
classDef tree fill:orange,stroke-width:0px;
classDef commit fill:lightgreen,stroke-width:0px;
classDef tag fill:yellow,stroke-width:0px;
classDef peker fill:lightgrey,stroke:black, stroke-width:2px,stroke-dasharray:5,5

Blob:::blob
Tree:::tree
Tree-->Blob
Tree --> Blob
Tree --> Blob
Tree --> Tree
```

Tree i Git  representerer en katalog, og inneholder Trees og Blobs i tillegg til navn og modus for disse. Innholdet i et Tree består av en liste av modus, type, navn og SHA-1 for hvert element - som kan være enten Blob eller Tree.
