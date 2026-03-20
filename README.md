# WageGuard: Weekly Parametric Insurance for Quick-Commerce

**Guidewire DEVTrails 2026 University Hackathon - Phase 1 Submission**
**Team Lead:** Nischay Naman

## Project Overview
India's platform-based delivery partners are the backbone of our fast-paced digital economy. However, external disruptions such as extreme weather, pollution, and natural disasters can reduce their working hours and cause them to lose 20-30% of their monthly earnings. When disruptions occur, they bear the full financial loss with no safety net. 

WageGuard is an AI-enabled parametric insurance platform that safeguards gig workers against income loss caused by external disruptions such as extreme weather or environmental conditions. The solution provides automated coverage and payouts, incorporates intelligent fraud detection mechanisms, and operates on a simple weekly pricing model aligned with the typical earnings cycle of gig workers. 

*Note: This policy strictly covers loss of income only and excludes coverage for health, life, accidents, or vehicle repairs*.

## Target Persona
Quick-Commerce (Q-Commerce) Delivery Partners (e.g., Zepto, Blinkit). 
These riders operate under strict delivery SLAs. They are the most impacted when localized weather events force platforms to temporarily pause operations in specific zones.

## Core Scenarios (Parametric Triggers)
We are focusing on environmental disruptions that directly halt operations:
* **Severe Waterlogging/Heavy Rain:** When localized rainfall exceeds a safe operational threshold, causing deliveries to be halted. 
* **Extreme Heatwaves:** Temperatures exceeding local safety guidelines (extreme heat), resulting in an inability to work outdoors.

## Application Workflow
1. **Onboarding:** The rider registers, links their platform ID, and completes optimized onboarding and risk profiling.
2. **Weekly Subscription:** The financial model is structured on a Weekly pricing basis to match the typical payout cycle of a gig worker.
3. **Active Monitoring:** The system continuously utilizes real-time trigger monitoring via Weather APIs.
4. **Parametric Trigger & Automated Claim:** Automatic claim initiation for identified disruptions occurs instantly.
5. **Instant Payout:** Instant payout processing for lost income is executed via integrated payment systems.

## Platform Strategy: Web Application
We are developing WageGuard as a mobile-responsive web application. Delivery partners rely entirely on their smartphones, so a web app ensures they can easily check coverage, view active triggers, and receive instant payout notifications without needing to download a heavy native app.

## AI Integration
Our platform leverages AI across two critical pillars:
* **Dynamic Premium Calculation:** We use Machine Learning to adjust the Weekly premium based on hyper-local risk factors, such as lowering the premium if the worker operates in a zone historically safe from water logging.
* **Intelligent Fraud Detection:** AI will identify anomaly detection in claims, validate location and activity, and prevent duplicate claims. This includes catching delivery-specific fraud like GPS spoofing or fake weather claims using historical data.

## Tech Stack & Development Plan
Our tech stack and development plan leverages modern frameworks:
* **Frontend:** React and Next.js, styled with Tailwind CSS for a highly responsive user interface.
* **Backend:** Java to handle robust business logic, dynamic premium calculations, and API routing.
* **Cloud Infrastructure:** Oracle Cloud Infrastructure (OCI) for secure hosting.
* **Integrations:** Integration capabilities include Weather APIs and mocked Payment systems.

## Timeline Outlook
* **Phase 2 (Automation & Protection):** Build the core registration process, integrate the Java backend with the weather APIs to set up 3-5 automated triggers, and implement the dynamic premium calculation models.
* **Phase 3 (Scale & Optimise):** Implement advanced fraud detection algorithms, integrate the mock payment gateway for instant simulated payouts, and finalize the intelligent dashboard for workers and insurers.

## Phase 1 Pitch Video
[Insert Link to 2-minute video uploaded to a publicly accessible link here]
