# Implementation Plan - Update Portfolio Projects

This plan details the steps to add two new projects (`IBC Telecom` and `Topex Pro`), update the existing `Touring Companions` project to `Aphrodite Collection` with its updated URL and a custom design mockup, and optimize the overall layout for 6 projects.

## Proposed Changes

### Project Layout Optimization
* Convert all project cards from `col-lg-3` (4 columns per row) to `col-lg-4` (3 columns per row). With 6 projects in total, this will create a perfectly balanced and responsive 2x3 grid on desktop screens, and a 2-column grid on tablets.

### New and Updated Assets
We will generate three high-quality, premium visual web/app mockups using modern dark/glassmorphic aesthetics:
1. `aphrodite_mockup.png`: A luxurious companion and escort agency directory dashboard design with elegant typography, dark theme, and gold accents.
2. `ibc_telecom.png`: A clean and modern telecom online recharge portal interface mockup.
3. `topex_pro.png`: A trading and investment platform dashboard with financial graphs, clean typography, and stock stats (similar to Groww).

### Project Content Changes

#### [MODIFY] [index.html](file:///c:/Dev-Hub-main/index.html)

1. **Update Touring Companions to Aphrodite Collection**:
   - Change heading title to **Aphrodite Collection**.
   - Change link from `https://touringcompanions.com/` to `https://staging.aphroditecollection.com/`.
   - Update image path from `assets/img/touring_logo.png` to `assets/img/aphrodite_mockup.png`.
   - Update `alt` text.

2. **Add IBC Telecom**:
   - Title: **IBC Telecom**
   - Duration: Feb 2023 – July 2023
   - Description Bullets:
     - Developed and maintained an online recharge platform for IBC Telecom using Laravel, enhancing overall performance and scalability.
     - Designed and implemented RESTful APIs to support core application functionalities, ensuring seamless integration.
     - Utilized Swagger for API documentation, improving collaboration and ensuring clear response structures.
     - Collaborated closely with cross-functional teams (designers, QA, project managers) to deliver features on time.
   - Tech Stack: Laravel, REST API, Swagger, PHP, MySQL
   - Image: `assets/img/ibc_telecom.png`

3. **Add Topex Pro**:
   - Title: **Topex Pro**
   - Duration: May 2025 – July 2025
   - Description Bullets:
     - Independently designed and developed a trading and investment platform enabling users to invest in stocks.
     - Solely responsible for end-to-end development, including system architecture, database design, and frontend integration.
     - Implemented Radius, Horizon, Queue, Cron Job and RESTful APIs for real-time processing and scheduling.
     - Optimized platform performance and resolved technical challenges for compliance-ready secure transactions.
   - Tech Stack: Laravel, Redis, Horizon, Cron Job, REST API
   - Image: `assets/img/topex_pro.png`

## Verification Plan

### Manual Verification
- Launch local environment (or open `index.html` in browser) and verify that:
  - The grid layout is properly aligned and responsive.
  - The 3D tilt hover animation works on the new cards.
  - The click targets (live demo link on Aphrodite Collection) lead to the correct destination.
  - Images load correctly and look premium.
