# Strategic Production Scheduling

To launch a new product line successfully, a mid-sized manufacturing plant needed to carefully coordinate each step—from sourcing materials to final packaging. The target was to complete everything within 16 working days, keeping each department aligned and avoiding delays that could disrupt the schedule.

This plan maps out task dependencies, identifies the critical path, and highlights where there’s flexibility. With this structure in place, the production team could better organize workloads and spot potential bottlenecks before they became an issue.

---

### Project Objective

Coordinate all production tasks—procurement, assembly, QA, and shipping—to complete the rollout of a new smart speaker model within 16 working days.

---

### Task Breakdown

The entire process was divided into six main tasks:

- **A: Raw Material Procurement** (2 days)  
- **B: Machine Calibration** (3 days)  
- **C: Component Assembly** (4 days)  
- **D: Quality Inspection** (2 days)  
- **E: Packaging Preparation** (5 days)  
- **F: Final Packaging & Shipping** (4 days)

Each task is connected to others in a way that affects when it can start or finish.

---

### Task Flow Visualization

![image](https://github.com/user-attachments/assets/20fb6cf0-c50d-4fea-98e9-c7c9628e2f50)


This diagram shows how the tasks connect. For instance, Task F (Final Packaging & Shipping) can’t begin until both Task D (Inspection) and Task E (Prep) are done.

---

### Task Schedule Summary

| Task | Earliest Start | Earliest Finish | Latest Start | Latest Finish | Slack |
|------|----------------|-----------------|--------------|----------------|--------|
| A (Procurement) | 0 | 2 | 0 | 2 | 0 |
| B (Calibration) | 0 | 3 | 7 | 10 | 7 |
| C (Assembly) | 2 | 6 | 2 | 6 | 0 |
| D (Inspection) | 6 | 8 | 9 | 11 | 3 |
| E (Packaging Prep) | 6 | 11 | 6 | 11 | 0 |
| F (Shipping) | 11 | 15 | 11 | 15 | 0 |

- Tasks with **zero slack** are on the **critical path** and must be completed on time to keep the whole project on schedule.

---

### Key Insights

1. **Critical Path**: A → C → E → F  
   These tasks drive the entire timeline. Any delays here directly affect the final delivery date.

2. **Flexible Calibration**: Task B has 7 days of slack, meaning it can be shifted around without affecting the launch window.

3. **Inspection Cushion**: Task D has 3 days of wiggle room, helpful if QA runs longer than expected.

---

### Wrap-up

By clearly laying out task dependencies and identifying which steps are time-sensitive, the team was able to stay organized and keep production running smoothly. This kind of planning helped prevent last-minute chaos and allowed everyone involved to stay focused on what mattered most.

