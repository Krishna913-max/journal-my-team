
# REPORT — Environmental Impacts of Data Centres & Digital Platforms

## 1) Executive summary 
*Google operates some of the world's most energy-efficient data centres and has committed to operating on 24/7 carbon-free energy by 2030. However, its greenhouse-gas emissions and water consumption have increased in recent years as demand for cloud services and AI computing has grown. Google reported that total greenhouse-gas emissions increased by 13% in 2023 compared with 2022, largely because of increased data-centre energy demand and supply-chain emissions.

YouTube, as one of the world's largest video-streaming platforms, depends heavily on Google's global infrastructure. Video delivery, storage, recommendation systems and AI features consume significant electricity, creating ongoing environmental impacts.

The most impactful improvement for Google would be expanding carbon-aware workload scheduling across regions and times of day because location-based emissions vary considerably depending on the local electricity grid. The most impactful improvement for YouTube would be increasing carbon-aware processing of non-urgent workloads (analytics, transcoding and machine-learning jobs) to reduce emissions without affecting user experience.*

---

## 2) Case A — Data‑centre operator: <Google>

### 2.1 What they report (energy, carbon by scope, water)
-Google reported that total greenhouse-gas emissions increased by 13% year-over-year in 2023, primarily due to growing data-centre electricity use and supply-chain emissions. [1]
-Google maintained a global average of 64% carbon-free energy (CFE) across its grid regions in 2023. [1]
-Ten Google grid regions achieved at least 90% carbon-free energy in 2023. [1]
-Google has matched 100% of its annual electricity consumption with renewable energy purchases since 2017 and continues pursuing a goal of operating on 24/7 carbon-free energy by 2030. [1]
-Google's data centres achieved an average Power Usage Effectiveness (PUE) of 1.10 in 2023, compared with an industry average of approximately 1.58. [1]
-Google announced a goal to replenish 120% of freshwater consumed across offices and data centres by 2030. [2]
-Water stewardship projects replenished approximately 1 billion gallons of water, equivalent to around 18% of freshwater consumption in 2023. [1]

### 2.2 LB vs MB in practice 
*Location-based (LB) emissions reflect the actual carbon intensity of the electricity grid where electricity is consumed. Market-based (MB) emissions instead account for renewable-energy contracts, renewable energy certificates, and power purchase agreements.

LB emissions are generally more useful for engineering decisions because they show the real environmental impact of running workloads in a specific region and time period. A workload executed in a coal-heavy grid region usually causes higher emissions than the same workload executed in a cleaner grid region, regardless of renewable-energy accounting.

Google provides customers with the Google Cloud Carbon Footprint tool, which helps estimate emissions associated with cloud workloads and supports decisions about region selection and carbon reduction. [3]*

### 2.3 Risks & trade‑offs (grid & water) 
*Data-centre siting involves trade-offs between latency, electricity carbon intensity and water availability. Locating facilities close to users reduces latency and improves service quality, but nearby regions may rely on carbon-intensive electricity grids. Conversely, locating workloads in cleaner regions may reduce emissions but increase network latency. Studies of hyperscale data centres show that carbon intensity varies substantially between regions depending on local generation mixes.

Water use is another important consideration. Many facilities use evaporative cooling, which improves energy efficiency but can consume large volumes of freshwater during hot periods. Google has acknowledged water-management challenges and developed water-risk frameworks to guide cooling decisions. Two-thirds of Google's data centres reportedly use evaporative cooling, while some facilities increasingly use air cooling or alternative water sources. Water demand may spike during peak-temperature periods, especially in water-stressed regions.
*

---

## 3) Case B — Digital platform: <YouTube>

### 3.1 What’s public (policies, metrics)
*YouTube does not publish separate sustainability reports. Instead, environmental impacts are reported through its parent company, Google.

Relevant disclosures include:

Google reported a 13% increase in total greenhouse-gas emissions in 2023. [1]
Google maintained 64% carbon-free energy across its operations in 2023. [1]
Google's data centres achieved an average PUE of 1.10, among the industry's best reported efficiencies. [1]
Google continues pursuing 24/7 carbon-free energy by 2030 and net-zero ambitions across operations and value chains. [1]

Because YouTube relies on Google's infrastructure, these metrics are directly relevant to YouTube's environmental footprint.*

### 3.2 Operational realities & carbon‑aware opportunities 
*YouTube's dominant workloads include video storage, video delivery, content recommendation systems, advertising systems and AI-powered features. Continuous video streaming creates significant electricity demand because content must be stored, processed and delivered through large networks of servers.

A realistic opportunity to reduce location-based emissions is carbon-aware scheduling of non-urgent tasks such as video transcoding, analytics processing and recommendation-model training. These workloads can often be shifted to cleaner regions or cleaner times of day without affecting viewers. Research shows that carbon intensity varies significantly across regions and time periods, making workload shifting an effective emissions-reduction strategy.*

### 3.3 Water awareness 
*YouTube relies heavily on Google's data centres and therefore indirectly contributes to data-centre water consumption. Google reports freshwater consumption and replenishment efforts but does not provide detailed water-usage figures for YouTube specifically. Google has stated that water stewardship is a priority and aims to replenish more water than it consumes by 2030.

Future reporting could be improved by providing service-level water metrics and more facility-level disclosure in water-stressed regions. Such reporting would help stakeholders understand the relationship between growing AI and streaming demand and local water impacts.*

---

## 4) Two concrete recommendations 
- **For Google (Data-Centre Operator)**: 
*Google should publish more detailed region-level location-based emissions data and water-usage metrics, including peak-day water demand. This would improve transparency for customers making deployment decisions and help communities understand local environmental impacts. Google should also expand carbon-aware scheduling features so cloud customers can automatically shift flexible workloads toward cleaner electricity periods. Such measures could reduce actual grid emissions while preserving service quality..*  

- **For YouTube (Digital Platform)**: 
*YouTube should increase carbon-aware scheduling for video transcoding, recommendation-model training and analytics processing. These workloads generally do not require immediate execution and can be moved to lower-carbon regions or times with higher carbon-free electricity availability. YouTube could also publish more granular sustainability information, including estimated emissions associated with video streaming and AI features, helping users and researchers better understand platform impacts.*

---

## References (numbered list with links)
*List every source you cited, as a numbered list. Use direct links to official reports or reputable analyses. Example:*  
1. *Google 2024 Environmental report.*(hhttps://blog.google/company-news/outreach-and-initiatives/sustainability/2024-environmental-report/?utm_source=chatgpt.com)  
2. *Google Water Stewardship Project portfolio (2025).* (https://sustainability.google/progress/projects/eu-data-centers/?utm_source=chatgpt.com)
3. *Google Sustainability And Data Centre Efficency Information.* (https://blog.google/outreach-initiatives/sustainability/2024-environmental-report/?utm_source=chatgpt.com)
4. *Reuters: Investors Press Amazon, Microsoft And Google on Water And Power use in Data Centre.*(https://www.reuters.com/sustainability/boards-policy-regulation/investors-press-amazon-microsoft-google-water-power-use-us-data-centers-2026-04-06/?utm_source=chatgpt.com)
5. *Assessing the Carbon Emissions and Energy Consumption of U.S. Hyperscale Data Centres (2026).*(https://arxiv.org/abs/2606.05420?utm_source=chatgpt.com)
6.*Environmental Burden Of United States Data Centres in the Artificial Intelligence Era (2024).*(https://arxiv.org/abs/2411.09786?utm_source=chatgpt.com)
7. *Wattnet: Matching Electricity Consumption with Low-Carbon, Low-Water-Footprint Energy Supply(2026).*(https://arxiv.org/abs/2601.11623?utm_source=chatgpt.com)

