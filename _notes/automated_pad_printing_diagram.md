---
title: Automated Pad Printing diagram
Purpose: Generate overall flow of what the automation system will be doing for pad printing
---

<pre class="mermaid">
    flowchart TD;
    A[Gripper Opens] --> |Gripper grabs blank tube from start bin| B[Gripper loads tube into cache] --> C[Inkblot comes down on tube] --> D[Printing occurs] --> |Gripper opens and grabs printed tube| E[Gripper places printed tube into finished parts bin] --> A;
</pre>
