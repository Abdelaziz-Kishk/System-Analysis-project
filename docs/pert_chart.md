# PERT Chart & Critical Path Analysis

## 1. Task Network Dependencies
- **Task A (SQL Database):** Starts at Week 1.
- **Task B (React UI):** Depends on Task A.
- **Task C (Python NLP):** Depends on Task A.
- **Task D (Tableau Dashboard):** Depends on Task C & Task A.
- **Task E (Integration & Testing):** Depends on Task B & Task D.

      +-------------------+
      |  [B] Frontend &   |
   +->|  Media (3 Weeks)  |---+
   |  +-------------------+   |
+------------+                |   +--->+--------------------+
|  [A] SQL   |                |        |   [E] Testing &    |---> Deployment
|  Database  |                v        | Integration(2 Wks) |     (Before Jan 1)
| (2 Weeks)  |--->+-------------------+|    +--------------------+
+------------+    |  [C] Python NLP   ||
| Filter (3 Weeks)  ||
+-------------------+|
|          |
v          |
+-------------------+|
|  [D] Tableau Dash ||
|    (2 Weeks)      |+
+-------------------+


## 2. Path Duration Analysis
1. **Path 1:** $A \rightarrow B \rightarrow E = 2 + 3 + 2 = 7 \text{ Weeks}$
2. **Path 2 (Critical Path):** $A \rightarrow C \rightarrow D \rightarrow E = 2 + 3 + 2 + 2 = \mathbf{9 \text{ Weeks}}$

### Conclusion:
The **Critical Path is 9 weeks**, ensuring completion well before the January 1 deadline while keeping core e-commerce performance intact
