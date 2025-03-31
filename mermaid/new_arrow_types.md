# New arrow types

```mermaid
---
title: Circle edge
---
flowchart LR
    A --o B
```
```code
flowchart LR
    A --o B
````
--- 

```mermaid
---
title: Cross edge
---
flowchart LR
    A --x B
```
```code
flowchart LR
    A --x B
```

--- 

```mermaid
---
title: Multiple directional arrows
---
flowchart LR
    A o--o B
    B <--> C
    C x--x D

```
```code
flowchart LR
    A o--O B
    B <--> C
    C x--x D
```

--- 

```mermaid
---
title: Minimum length of a link
---
flowchart TD
    A[Start]-->B{Is it?}
    B--> |yes| C[ok]
    C-->D[Rethink]
    D-->B
    B-->|no| E[End]

```
```code
flowchart LR
    A[Start]-->B{Is it?}
    B--> |yes| C[ok]
    C-->D[Rethink]
    D-->B
    B-->|no| E[End]
```

--- 

```mermaid
---
title: Minimum length of a link
---
flowchart TD
    A[Start]-->B{Is it?}
    B--> |yes| C[ok]
    C-->D[Rethink]
    D-->B
    B-->|no| E[End]
```
```code
flowchart LR
    A[Start]-->B{Is it?}
    B--> |yes| C[ok]
    C-->D[Rethink]
    D-->B
    B-->|no| E[End]
```
```code
flowchart TD
    A[Start] --> B{Is it?}
    B--yes-->C[ok]
    C-->D[Rethink]
    D-->B
    B--no-->E[End]
```

|Length|1|2|3|
|------|-|-|-|
|Normal|---|----|-----|
|Normal with arrow| --> | ---> | ---->|
|thick|===|====|=====|
|thick with arrow|==>|===>|====>|
|Dotted|-.-|-..-|-...-|
|Dotted with arrow|-.->|-..->|-...->|

Examples:

```mermaid
---
title: Normal
---
flowchart TD
    A[GNU-Linux] --- B[Redhat]
    A ---- C[Debian]
    A ----- D[Mandriva]
```

---

```mermaid
flowchart TD
    A[GNU/Linux] --> B[Redhat]
    A ---> C[Debian]
    A ----> D[Mandriva]
```

--- continuara

---

```mermaid
---
title: Special characters break syntax
---
flowchart LR
    id1["This is the (text) in the box"]
```
```code
flowchart LR
    id1["This is the (text) in the box"]
```

---

```mermaid
---
title: Entity codes to escape characteres
---
flowchart LR
    A["A double quote:#quot;"] --> B["A dec char:#9829;"]
```
```code
flowchart LR
    A["A double quote:#quot;"] --> B["A dec char:#9829;"]
```