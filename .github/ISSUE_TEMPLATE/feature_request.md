---
name: "Feature Request"
about: "Suggest an idea or new functionality for the product."
description: "Describe your idea for a new feature and why it would be valuable."
title: "CUSTOMER_CODE - [Feature]: <summary of the issue> "
projects: "9"
type: "Bug"
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
    A[User Submits a Feature Request] --> B[Product Team Reviews Idea];
    B --> C{Viable & Relevant?};
    C -->|Yes| D[Add to Product Backlog];
    C -->|No| E[Communicate Feedback to User & Reject];
    D --> F{Prioritize?};
    F -->|Yes| G[Schedule for Development];
    F -->|No| H[Keep in Backlog for Future Consideration];
    G --> I[Develop & Test Feature];
    I --> J[Release Feature to Users];
```
