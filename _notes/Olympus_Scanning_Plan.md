---
title: Olympus Scanning Plan
Purpose: To come up with an efficient plan to scan all the labels from the Olympus return
---

* Each box has 2 labels with 3 barcodes on each box label
* Each box has 300 bags
* Each bag has 1 label with 2 barcodes on each box label

### Plan of action
<pre class="mermaid">
    flowchart TD;
    A[Check Box Label] --> B{Barcode Damaged on Label?};
    B -->|Yes| C[Remove Bags from Box];
    C --> D[Scan Bag Labels];
    D --> E[Place Bags back in Box];
    B --> |No| F[Scan Box Labels];
    F --> C;
    E --> G[Check Next Box];
    G --> A;
</pre>