
# flowchart

```code
flowchart LR
id
```

```mermaid
---
title: Node
---
flowchart LR
id
```

---

```mermaid
---
title: Node with text
---
flowchart LR
    id1[This is the text in the box]
```

```code
flowchart LR
    id1[This is the text in the box]
```

---

```mermaid
---
title: Use " to enclose the unicode text
---
flowchart LR
id["This ❤ unicode"]
```

```code
flowchart LR
    id["this ❤ unicode"]
```

----

```mermaid
---
title: Markdown formatting, use double quotes and backticks "`text`" to enclose the markdown text
---
%%{ init: {"flowchart": {"htmlLabels": false }} }%%
flowchart LR
    markdown["`This **is** _Markdown_`"]
    newLinux["`Line1
    Line2
    Line3`"]
    markdown --> newLinux
```

```code
%%{ init: {"flowchart": {"htmlLabels": false }} }%%
flowchart LR
    markdown["`this **is** _Markdown_`"]
    newLinux["`Line1
    Line2
    Line3`]
    markdown --> newLinux
```

---

```mermaid
---
title: Direction, this statement declares the direction of the flowchart, example TB
---
%% TB - Top to bottom
flowchart TB
    Start --> Stop
```

```code
flowchart TB
    Start --> Stop
```

---

```mermaid
---
title: Direction, this statement declares the direction of the flowchart, example TD
---
flowchart TD
%% TD - Top-Down / same as top to bottom
    Start --> Stop
```

```code
flowchart TD
    Start --> Stop
```

----

```mermaid
---
title:  Direction, this statement declares the direction of the flowchart, example BT
---
flowchart BT
%% BT - Bottom to top
    start --> stop
```

```code
flowchart BT
    Start --> Stop
```
----

```mermaid
---
title:  Direction, this statement declares the direction of the flowchart, example RL
---
flowchart RL
%% RL - Right to left
    Start --> Stop
```

```code
flowchart RL
    Start --> Stop
```

----

```mermaid
---
title:  Direction, this statement declares the direction of the flowchart, example LR
---
flowchart LR
%% LR - Left to 
    Start --> Stop
```

```code
flowchart LR
    Start --> Stop
```

[node-shapes](node_shapes.md)