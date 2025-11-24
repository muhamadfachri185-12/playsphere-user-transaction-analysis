<h1>playsphere-user-transaction-analysis</h1> 
This project analyzes user transaction behavior for PlaySphere Interactive, an Electronic & Gaming Products Retail company specializing in game purchases and hardware products.

<br>
<h2>Project Initiation</h2> 
The company wants to understand how total revenue across all products has performed from 2019 to 2021. The analysis is not supporting a specific business decision yet, but aims to give product, marketing, and finance teams a high-level view of trends and patterns in revenue.

**Key summary for surface insights:**<br>
1. The key KPI for this explorative analysis is USD price, supported by fields like product name and purchase timestamp.
2. The analysis focuses on identifying aggregate metrics, patterns, outliers, and unexpected anomalies — especially total revenue by month and product, plus min/max values.
3. Early insights will be surfaced by segmenting the data by region, category, marketing channel, or account creation method.


<br><br>

<p align="center">
  <img width="591" height="366" alt="Playsphere data structure drawio" src="https://github.com/user-attachments/assets/79238e75-4c8f-4fab-99ed-601c57e83889" />
</p>

<p>playsphere dataset ERD</p>

<br><br>
<h2>Insight & Deep Dive</h2>
<h3>Sales Trends and Growth Rates</h3>

* PlaySphere generates about $2M annually with ~7,000 orders, showing a stable mid-scale sales volume.
* Sales peaked in 2020 to early 2021, driven by a pandemic-era surge in demand for gaming and electronics.
* Seasonality is clear, with December contributing ~12% of annual orders, while January–February fall to just 4–5%, marking the lowest activity.
* Revenue is heavily concentrated in Western markets, with North America contributing 52% and EMEA 30.3%, reinforcing that these two regions are the core drivers of PlaySphere’s global performance.
<p align="center">
  <img width="710" height="124" alt="sales_performa" src="https://github.com/user-attachments/assets/319d9aef-5b2b-404e-b97b-3e9a4f7c539b" />
</p>
<p align="center">
  <img width="825" height="507" alt="image" src="https://github.com/user-attachments/assets/7968bf9e-ada1-43fb-98d4-9aeb960ead27" />
</p>

<h3>Key Product Performance</h3>


* Demand for gaming electronics spiked sharply in 2020 as lockdown behavior drove a major shift toward at-home entertainment, boosting sales for PlayStation 5 bundles, gaming monitors, and Nintendo Switch consoles.
* The fastest growth came from PS5 Bundles (+381%), Lenovo IdeaPad Gaming Laptops (+204%), and Acer Nitro V (+133%), highlighting a decisive consumer shift toward high-performance gaming devices.
* This surge proved temporary, as product sales dropped –70% to –90% in 2021, confirming that the 2020 boom was pandemic-driven rather than sustainable growth.
* Three products — the 4K Gaming Monitor, Nintendo Switch, and PS5 Bundle — dominate performance with more than $5.2M in revenue, accounting for over 85% of total sales ($6.15M).
* The 27-inch 4K Gaming Monitor is the top revenue contributor at $1.97M, making it the strongest performer across all years.
* The Nintendo Switch follows with $1.66M, showing consistently strong demand throughout the period.
* The PS5 Bundle adds $1.59M, reinforcing gaming consoles as one of the most influential and high-impact categories for PlaySphere.
<p align="center">
  <img width="711" height="191" alt="image" src="https://github.com/user-attachments/assets/8f74b28d-8195-4a74-8478-29aeb0d21994" />
</p>


<h3>Key Sales by Marketing Channels & Plaftorm</h3>


* Direct marketing is the dominant revenue engine, driving the highest sales across all major products, particularly the 27” 4K Monitor, Nintendo Switch, and PS5 Bundle.
* Social media remains the weakest channel, with most products generating under $30K and showing limited impact on overall revenue.
* North America leads performance with over $2.6M generated through direct marketing, reinforcing its position as PlaySphere’s strongest market.
* EMEA follows at $1.63M, indicating strong customer responsiveness to targeted outreach campaigns.
* Social media is especially ineffective in LATAM, contributing only ~$1.7K, confirming poor traction in emerging markets.
* Marketing activity peaked in 2020, when direct marketing revenue surged from $1.3M (2019) to $3.45M, fueled by pandemic-driven digital purchasing.
* Email and social channels also rose sharply in 2020, reflecting a broad shift toward online engagement during lockdowns.
* By 2021, performance dropped sharply, with direct marketing revenue falling back to ~$437K, returning near pre-pandemic levels.
* These shifts confirm that the 2020 spike was pandemic-driven and temporary, not a sustainable indicator of long-term channel growth.
<p align="center">
  <img width="394" height="126" alt="image" src="https://github.com/user-attachments/assets/8a41b9c6-0d83-4400-8236-4a972e3fe667" />
</p>


<h3>Product Revenue & Performance by Region</h3>

* 2020 became a clear global anomaly, with every region surging by roughly +150% to +200% in revenue and orders due to a pandemic-driven demand spike rather than true regional growth.
* In 2021, all regions experienced an –85% to –90% collapse in revenue and orders, signaling a sharp post-pandemic correction that simply pulled demand back to near-2019 levels and confirmed the artificial nature of the 2020 spike.
* North America and EMEA remain playsphere’s core markets, consistently contributing ~75–85% of revenue and staying the only stable, meaningful drivers even after the 2021 downturn, while APAC and LATAM remain small and highly volatile.
* High-value products like monitors, PS5 bundles, and Nintendo Switches are heavily concentrated in Western markets—North America holding 50–65% and EMEA 30–35%—while APAC and LATAM together contribute under 15%, showing playsphere’s strongest product-market fit lies decisively in these two regions.
* Gaming and console products are ByteX’s primary revenue drivers, with the PS5 Bundle, Nintendo Switch, and 27” 4K Monitor contributing 60–70%+ of regional sales and remaining far more resilient than accessories, which consistently generate <5% and offer limited margin impact.
* APAC and LATAM are highly volatile markets, surging +190% in 2020 but collapsing –85% to –90% in 2021, reflecting supply-chain and price sensitivity as well as low brand penetration, making them opportunity regions rather than reliable revenue drivers.
<p align="center">
  <img width="784" height="457" alt="image" src="https://github.com/user-attachments/assets/d59b2f03-2ca1-42be-bf12-129fd2d9bae8" />
</p>
<p align="center">
  <img width="820" height="513" alt="image" src="https://github.com/user-attachments/assets/670b018c-31f3-412d-8c09-05aeebc22a2d" />
</p>




<br><br>
<h2>Recommendations</h2>
<h3>Maximizing Product Performance</h3>
<h4>Prioritize High-Value Gaming Electronics</h4>
Focus inventory, marketing spend, and product expansion around the three core revenue engines — 27” 4K Gaming Monitor, Nintendo Switch, and PS5 Bundle — which generate 85% of total revenue. Increasing SKU variations (bundles, accessories add-ons, premium tiers) can strengthen margins and stabilize revenue.

<h4>Reduce Low-Margin Accessories</h4>
Accessories contribute <5% across regions and offer minimal financial impact. Limit SKU counts, bundle them with high-ticket items, or position them as upsells/add-ons rather than standalone products to increase average order value.

<h3>Customer Growth & Retention</h3>
<h4>Capitalize on Strong Western Market Loyalty</h4>
North America (52%) and EMEA (30.3%) consistently drive 75–85% of sales. Implement retention loops (VIP perks, early access console drops, exclusive bundles) aimed specifically at these markets to boost repeat purchases and sustain baseline revenue.

<h4>Address Seasonal Demand Patterns</h4>
Because December accounts for ~12% of annual orders and Jan–Feb drop to 4–5%, launch:

* Pre-Holiday preorder campaigns
* Post-holiday upgrade promotions
* Extended warranty offers in Q1

<h3>Optimizing Marketing Channels & Platforms</h3>
<h4>Double Down on Direct Marketing</h4>
Direct marketing contributed the largest share (peaking at $3.45M in 2020). Continue optimizing:

* Personalized email promotions
* Cart abandonment flows
* Regionalized direct offers
* High-intent retargeting campaigns

<h4>Reevaluate Social Media Strategy</h4>
Social media underperforms globally (<$30K per product):

* Scale back generic paid social
* Shift toward influencer-led content
* Deploy targeted campaigns in NA and EMEA only

<h3>Regional Growth Strategy</h3>
<h4>Strengthen Western Market Dominance</h4>
Allocate the majority of marketing, product launches, and inventory to North America and EMEA, where high-value items represent 60–70%+ of regional sales. Introduce region-exclusive bundles to maintain momentum.


<h4>Tailor Product Mix to Regional Sensitivity</h4>
Since high-value products are concentrated 80–95% in Western markets, APAC/LATAM should focus on:

* Mid-range monitors
* Affordable laptops
* Budget consoles/accessories

<br><br>
<h2>Clarifying Questions, Assumptions, and Caveats</h2>
<h3>Questions for Stakeholders Prior to Project Advancement</h3>

<h4>Mismatch Between PURCHASE_TS and SHIP_TS</h4>

* Many records show shipping dates occurring before the purchase date.
* Is this caused by input errors, timezone issues, or date-format inconsistencies (DD/MM vs MM/DD)? Which timestamp field should be treated as the primary source of truth?
<p align="center">
  <img width="464" height="80" alt="image" src="https://github.com/user-attachments/assets/ee84766b-723b-4d19-a7ef-484b78a3d2cc" />
</p>

<h4>Inconsistent Pricing for the Same Product</h4>

* Prices for the same product — such as the Nintendo Switch — vary significantly even within US country code records, ranging from approximately $134 to $175.
* This raises uncertainty about whether the differences come from seasonal discounts, temporary promotional pricing, or inconsistencies in how prices were recorded in the system.
<p align="center">
  <img width="1031" height="411" alt="image" src="https://github.com/user-attachments/assets/8b6dc6b3-9cdf-4175-ba66-b2dde5b397f7" />
</p>


<h4>Inconsistent PRODUCT_ID for Identical Product Names</h4>

* Same product names appear with different product IDs.
* Do these represent different SKUs, bundles, or data entry errors? Is there a master product table that serves as the authoritative reference?
<p align="center">
  <img width="270" height="339" alt="image" src="https://github.com/user-attachments/assets/ab2d51d9-7102-4f61-97f1-f114f0ce7e96" />
</p>

<h4>Regional Mapping Based on COUNTRY_CODE</h4>

* Are country codes already mapped correctly into NA, EMEA, APAC, and LATAM?
* Is there an official regional classification used internally?

<h3>Questions for Stakeholders Prior to Project Advancement</h3>

<h4>Shipping Timestamps Are Potentially Incorrect</h4>

* Shipping dates occurring before purchase dates invalidate SLA analysis, lead-time calculations, and fulfillment performance metrics.

<h4>Product Pricing Contains Extreme Outliers</h4>

* Widely inconsistent prices indicate possible data hygiene issues, influencing revenue, margin, and product-level insights.

<h4>Inconsistent PRODUCT_ID Assignments</h4>

* Analysis by product risk misinterpretation unless a verified mapping of products to IDs is established.

<h4>Potential Misclassification in Region Mapping</h4>

* Without validated region mapping, regional performance metrics may be inaccurate or misleading.
