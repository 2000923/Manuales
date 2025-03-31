# Links between nodes

### Nodes can be connected with links/edges.

```mermaid
---
title: A link with arrow head
---
flowchart LR
    A-->B
```
```code
flowchart LR
    A-->B
```

---
```mermaid
---
title: An open link
---
flowchart LR
    A --- B
```
```code
flowchart LR
    A --- B
```

---
```mermaid
---
title: Text on links
---
flowchart LR
    A -- This is the text! --- B
```
```code
flowchart LR
    A -- This is the text! --- B
```

---
```mermaid
---
title: A link with arrow head and text
---
flowchart LR
    A -->|text|B
```
```code
flowchart LR
    A-->|text|B
%% Otra forma
flowchart LR
    A-- text --> B
```

---
```mermaid
---
title: Dotted link
---
flowchart LR
    A-.->B
```
```code
flowchart LR
    A-.->B
```

---
```mermaid
---
title: Dotted link with text
---
flowchart LR
    A-. text .-> B
```
```code
flowchart LR
    A-. text .->B
```

---
```mermaid
---
title: Thick link
---
flowchart LR
    A==>B
```
```code
flowchart LR
    A==>B
```

---
```mermaid
---
title: Thick link with text
---
flowchart LR
    A==text==>B
```
```code
flowchart LR
    A==text==>B
```

---
```mermaid
---
title: An invisible link
---
flowchart LR
    A~~~B
```
```code
flowchart LR
    A ~~~ B
```
```text
This can be a useful tool in some instances where you want to alter the default positioning of a node.
```

---
```mermaid
---
title: Chaining of links
---
flowchart LR
    A--text-->B--text2-->C
```
```code
flowchart LR
    A -- text --> B -- text2 --> c
```
```mermaid
flowchart LR
    a --> b & c --> d
```
```code
flowchart LR
    a --> b & c --> d
```
```mermaid
flowchart TB
    a & b --> c & d
```

