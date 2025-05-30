# Analysing-Industry-Carbon-Emissions

# Overview

This project explores carbon emissions across various industries by analysing product carbon footprints (PCFs). Using publicly available data and DataLab’s AI-powered platform, we investigate the lifecycle emissions of products—from upstream production to downstream processes—helping to uncover where emissions are most concentrated within each industry.

# Objectives

- Quantify carbon emissions by industry based on individual product carbon footprints (PCFs).
- Understand the distribution of emissions across the upstream, operational, and downstream stages.
- Identify industries with the highest carbon intensity relative to product weight.
- Support sustainability efforts through data-driven insights.

# Data Source

The dataset is sourced from The Carbon Catalogue, hosted on Nature.com.
It includes publicly available PCF data stored in a PostgreSQL table named product_emissions, containing the following key fields:
- product_name, company, country, industry_group
- weight_kg, carbon_footprint_pcf (CO₂ equivalent)
- Emission stages: upstream_percent_total_pcf, operations_percent_total_pcf, downstream_percent_total_pcf

# Tools Used

- DataLab – for data querying, exploration, and notebook analysis
- PostgreSQL – for structured data storage and access

# Insights

- Greenhouse gas emissions tied to products contribute to over 75% of global emissions.
- Product emissions vary widely between industries such as Technology Hardware, Food & Beverage, Capital Goods, and Materials.
- Upstream processes account for a significant share of total emissions across most industries, particularly in manufacturing-heavy sectors.

# Key Findings

- Materials and Capital Goods industries have some of the highest carbon footprints per product.
- Software & Services show minimal physical emissions, demonstrating lower environmental impact per product.
- Food, Beverage & Tobacco sectors contribute heavily to downstream emissions, likely due to packaging, transport, and refrigeration.
- The Technology Hardware & Equipment sector exhibits a balanced distribution of emissions across all lifecycle stages.

# Recommendations

- Target upstream suppliers in carbon-intensive industries to reduce raw material-related emissions.
- Enhance operational efficiency in manufacturing processes, especially in the Capital Goods and Food sectors.
- Design for sustainability by focusing on end-of-life product impact and optimising packaging and logistics.
- Promote industry-specific carbon disclosure to drive transparency and competitive sustainability initiatives.
