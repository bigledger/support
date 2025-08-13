---
name: "Task"
about: "You would like to report a bug to help us improve."
description: "Tell us what might have gone wrong, and let us fix it for you."
title: "CUSTOMER_CODE - [Task]: <summary of the issue> "
projects: "9"
type: "Task"
assignees:
  - blg-"name"
---
### **Feature Details**
**Instructions:** The more details you provide, the better we can understand and evaluate your request.

* What is the proposed feature?
* What problem would this feature solve?
* Who would benefit from this feature?
* Describe the user flow or how you envision using this feature.

### **Priority Level**
**Instructions:** Please select a priority from P0 to P9. The default is P5.
* **P9** = Highest Priority (Critical/Urgent)
* **P5** = Medium Priority (Default)
* **P0** = Lowest Priority

_Please use P9 sparingly, as a high number of P9 requests devalues their urgency._

Priority Level = P5

<br>
<br>
<br>


```mermaid
graph TD;
    A[User Submits a Task Request] --> B[Task Triage & Review];
    B --> C{Clarity & Details?};
    C -->|Yes| D[Assign Task to Team Member];
    C -->|No| E[Request More Information];
    E --> A;
    D --> F[Execute Task];
    F --> G[Verify Completion];
    G --> H[Close Task];
```
