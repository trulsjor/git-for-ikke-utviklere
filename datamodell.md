```mermaid

graph TB

Blob
Tree-->Blob
Tree --> Blob
Tree --> Blob
Tree --> Tree
Commit --> Tree
Commit --> Commit
Tag --> Commit
p1((Branch))-->Commit
p2((Remote)) --> Commit
p3((HEAD)) --> p1
