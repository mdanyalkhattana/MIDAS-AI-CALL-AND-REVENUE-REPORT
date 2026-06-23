## Professional Multi-Store AI Call Logs & Revenue Performance Dashboard



<img width="1020" height="576" alt="image" src="https://github.com/user-attachments/assets/de377894-8cc8-4c97-9746-b8fe8ed5dd40" />

<img width="1002" height="584" alt="image" src="https://github.com/user-attachments/assets/94e857e1-4d9a-4925-9aeb-2b36ee5bc7f4" />


📋
# Executive Overview
This repository contains the core analytical schemas, data models, and business intelligence layout files for an enterprise-grade Power BI Executive Dashboard tracking conversational AI performance and direct revenue correlation.

Optimized for Midas—a prominent USA-based multi-location franchise operation spanning 9 core strategic storefronts (including Tupelo, Oxford, and 7 additional regional centers)—this analytics system bridges the gap between customer service operational metrics and automotive retail revenue pipelines.

By ingesting granular conversational telemetry (AI Call Logs) and integrating structural CRM data via Service Geeni OpenAPI connectors, the reporting layer eliminates legacy manual spreadsheet workflows and delivers dynamic, real-time executive visibility.

 ## Key System Features & Deliverables
1.  ## Conversational AI Operations Engine
Telemetry Analysis: Deep logging of interactive call flows, customer inquiries, and agent hands-offs.

Sentiment & Intent Categorization: Aggregates unstructured voice data into unified service notes, auto-summarizing primary automotive concerns (e.g., standard maintenance, parts queries, diagnostic troubleshooting).

Appointment Conversion Rates: Programmatic counting of successful inbound appointment bookings generated directly via automated channels.

2. ##  Strategic Multi-Store Financial Layer
Unified Portfolio Performance: Direct multi-store aggregation comparing performance metrics side-by-side across all 9 operational centers (Tupelo, Oxford, etc.).

Revenue Performance Tracking: Measures real-time financial growth metrics, capturing period-over-period revenue trends (Weekly, Monthly, and Year-to-Date).

Repair Order (RO) Correlation: Ties unique caller IDs to Service Geeni Repair Orders to calculate exact ROI and direct revenue yields resulting from successful AI engagements.

3.  ## Production-Ready Data Pipeline Automation
API-Driven Architecture: Replaces brittle, manual Excel file extractions with scalable, schedule-driven API connections via n8n automation workflows.

Resilient SQL Backing: Features robust, programmatically generated Date Dimension relational schemas to maintain absolute temporal alignment across complex fiscal reporting cycles.

##  Technical Architecture & Modeling Specifications
Data Source Connectivity
Core CRM Platform: Service Geeni (OpenAPI Rest Endpoint Integration)

Voice Ingestion Layer: Structured JSON-formatted Conversational Telemetry (AI Call Logs)

# Core DAX Implementations (Data Analysis Expressions)
The underlying tabular data engine utilizes advanced DAX measures specifically optimized for performance, handling edge cases, and calculating precise statistical metrics:

Temporal Appointment Counts: Dynamically calculates weekly and monthly reservation frequencies, ensuring robust handling of null records or blank values without skewing historical baselines.

Period-over-Period Revenue Growth: Custom time-intelligence formulas tracking velocity variances across isolated store locations.

Metadata Engineering: Strict organization of measures utilizing clean display folders for professional maintenance and multi-developer governance.
