1. SDLC Standard Time Allocation Matrix

The estimated duration for each phase is calculated based on the standard SDLC time allocation percentages, using an actual **Planning phase duration of 11 days**.

$$\text{Total Estimated Project Duration} = \frac{\text{Actual Planning Days}}{\text{Planning Percentage}} = \frac{11}{0.15} \approx 73 \text{ days}$$

| Phase | Standard Percentage (%) | Calculated Duration (Days) | Status |
| :--- | :---: | :---: | :---: |
| **Planning** | 15% | **Actual: 11 days** | Completed |
| **Analysis** | 20% | 15 days | In Progress |
| **Design** | 35% | 26 days | Scheduled |
| **Implementation** | 30% | 22 days | Scheduled |
| **Total Project** | **100%** | **74 days** | — |

---

## 2. RAD Iterative Timeline & Milestones Breakdown

Below is the detailed 6-week execution breakdown aligned with the **Rapid Application Development (RAD)** framework:

### Week 1: Requirements Planning & Initial Setup (Planning Phase)
- Finalize System Request, Feasibility Analysis, and RAD Methodology documentation.
- Gather functional and non-functional requirements from e-commerce stakeholders.
- Design high-level ERD and database schema for products, reviews, and verified orders.

### Weeks 2–3: Iteration 1 — Core Review Module V1.0 (Design & Analysis Phase)
- Implement relational database structures using MS SQL Server.
- Build responsive front-end components (Star Ratings 1-5, Text Feedback, Media Uploads) using React.js/HTML5.
- Develop Verified Buyer verification logic connected to order history.

### Week 4: Iteration 2 — Automated Moderation V2.0 (Implementation Phase)
- Develop Python NLP data preprocessing pipelines (NLTK / TextBlob).
- Implement automated profanity filters and anti-spam detection for review submissions.
- Integrate automated sentiment scoring to route flagged content for manual review.

### Week 5: Iteration 3 — Analytics & Power BI V3.0 (Implementation Phase)
- Connect SQL Server database directly to Power BI Desktop.
- Create dynamic executive dashboards tracking product ratings and return risk indicators.
- Enable management drill-down filters for defective inventory control.

### Week 6: System Integration, QA & Final Delivery (Cutover Phase)
- Conduct integration testing between UI, SQL Database, and Python moderation scripts.
- Perform load and performance benchmarking to ensure zero slowdown on site speeds.
- Finalize documentation and deliver the completed system prior to January 1st deadline.
