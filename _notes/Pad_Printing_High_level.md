---
title: Automated Pad Printing Project
Purpose: null
---


Endosampler pad printing (High Level) <br>
Raw tube stock --> Pad printer --> Printed tubes
<br>

Pad printing procedure
1. Load Raw tube stock to cache in pad printer
2. Wait for ink blot to hit tube producing printed tube
3. Remove printed tube from cache and load next tube

Open source robot arms are one option to look at prior to spending the money on an industrial soltion (UR3, Fanuc, etc.)

Tube dimensions are as follows: 3.1 mm diameter &plusmn; 0.2 mm with length of 9.125 in.

Gripper model created in Onshape on Friday 12/23/2023
Gripper diagram


<pre class="mermaid">
    flowchart TD;
    A[Gripper Opens] --> |Gripper grabs blank tube from start bin| B[Gripper loads tube into cache] --> C[Inkblot comes down on tube] --> D[Printing occurs] --> |Gripper opens and grabs printed tube| E[Gripper places printed tube into finished parts bin] --> A;
</pre>


Joe Reisch can help with automation of pad printing [Contact Information](http://www.reischpad.com/contact.html)