# Interface Engineering, Accessibility Design & User Manuals## Project: Sign Gen AI (HCI Frameworks)
This section maps out the Human-Computer Interaction (HCI) layouts, adaptive cross-device interface trees, and localized manual controls, as detailed in Chapter 6 of the project report.
---## 1. System Navigation Tree & Layout TopologiesThe client application is engineered for fluid multi-screen state transitions using responsive flexbox structures, ensuring seamless rendering across desktop school monitors and small-screen mobile devices.


[System Gateway]
│
├──► /login & /register ── (Enforces strong passwords & role-based cookies)
│
└──► [Authenticated Dashboard Router]
├──► /student ── (Dictionary views, MediaPipe webcam frame canvas, SignoBot)
├──► /teacher ── (LLM curriculum builder panels, class grade streams)
├──► /parent ── (Analytical tracking graphs, teacher mail hubs)
└──► /admin ── (Overarching system analytics, global schema locks)


---

## 2. Advanced Special Education Accessibility Profiles
To support primary school children with sensory challenges, the user interface goes beyond typical web frameworks by supporting advanced layout customization adjustments:

* **Urdu RTL Fluid Reflows:** Adjusting language toggles flips the entire visual dashboard alignment, rewriting text blocks and navigation bars to right-to-left layout configurations smoothly.
* **High-Contrast Theme Layers:** Swapping CSS variables dynamically inverts the background palettes to dark, stark, highly separated themes for color-blind or light-sensitive users.
* **Adaptive Typography Modifiers:** Text blocks, labels, and icon assets utilize responsive units (`rem`/`em`), allowing easy font-scaling across interfaces without ruining alignment grids.

---

## 3. Platform Interface Reference Wireframes
*(Once you upload your system screenshots into your assets folder, they will be embedded right here to serve as your visual proof)*

| Module Interface Screen | Primary Targeted Action | Visual Asset Mapping Path |
| :--- | :--- | :--- |
| Student Live Vision Studio | Real-time hand coordinate streaming | `../assets/screenshots/student_studio.png` |
| Teacher AI Content Workshop | Lesson prompt customization engine | `../assets/screenshots/teacher_workshop.png` |
| Parent Progress Portal | Data-visualization curves and charts | `../assets/screenshots/parent_analytics.png` |
