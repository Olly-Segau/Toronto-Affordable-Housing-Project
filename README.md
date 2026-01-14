# Toronto Affordable Housing Pipeline Dashboard

## 1. Background and Overview
* **Context:** Toronto is currently experiencing a significant housing affordability crisis, with rising rents and limited inventory. To provide transparency, the City of Toronto maintains a "Housing Pipeline" dataset that tracks every affordable housing project from the initial planning stages to final completion.

* **Goal:** The goal of this project was to take raw, complex municipal housing data and transform it into a high-level executive dashboard. This tool allows users to quickly identify where housing is being built, how many units are expected, and which phases of development are currently experiencing the most significant bottlenecks.

## 2. Data Structure Overview
The project utilizes the Affordable Rental Housing Pipeline dataset from the Toronto Open Data portal.

* Source: Toronto Open Data Portal
* Format: Flat-file CSV export.
* Key Attributes:
 - Project Metadata: Project names, addresses, and unique ID numbers.
 - Status: The current phase of the project (e.g., Planning, Under Construction, Completed).
 - Geographic Data: Ward names and coordinates for mapping.
 - Capacity: Total expected units per project and the "Housing Mix" (unit types).

## 3. Executive Summary
The analysis shows that while over 15,000+ units are currently in the pipeline, a substantial portion remains stuck in the "Planning" phase for extended periods. Geographic analysis reveals that housing development is heavily concentrated in a few central wards, leaving several suburban areas with virtually no upcoming affordable inventory. Furthermore, "Completed" projects represent the smallest slice of the total pipeline, highlighting a gap between project approval and final occupancy.

## 4. Insights Deep Dive
* **The "Planning" Bottleneck:** Using the Status slicer, the dashboard highlights that roughly 60% of all total units are still in the planning or pre-construction stage. This insight is crucial for understanding that a high "Total Unit" count does not translate to immediate housing availability.

* **Ward-Level Disparity:** The Map Visualization shows a clear clustering of projects in the Downtown and Waterfront areas. By comparing unit counts by Ward, we identified that the top 5 wards account for more than 50% of all planned affordable housing in the city.

* **Unit Density Analysis:** Through the use of Card Visuals, we can see that the average project size is increasing, moving from small-scale infill projects to large-scale, high-density developments that provide 200+ units per site.

## 5. Recommendation
* **Why this matters:** This project serves as a "Reality Check" for housing targets. It moves beyond simple announcements and tracks actual progress.

* **Recommendation:** Moving forward, the city should investigate why specific wards have zero active projects and consider incentives for developers to build in "low-density" affordable zones. Additionally, for future iterations of this dashboard, I recommend adding a "Time in Status" metric to track exactly how many days a project spends in the planning phase to help identify administrative delays.

  ## Author

#### Olorato Olly Segau
Data Analyst | SQL | Power BI | Reporting & Analytics
