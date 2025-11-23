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
<h4>Sales Trends and Growth Rates</h4>

* PlaySphere generates an average of approximately $2 million in annual revenue with around 7,000 customer orders per year.
* Sales reached their highest point between 2020 and early 2021, driven by increased demand for gaming and electronic products during that pandemic period.
* Based on the 2019 and 2020 data, seasonality patterns show that sales and order volume peak in December (approximately 12% of total orders), while the lowest levels occur in January and February (4% - 5% of total orders).
* North America is the largest contributor to revenue, accounting for more than 52% of total global sales between 2019 and 2021. EMEA follows with 30.3%


<h4>Key Product Performance</h4>

* Demand for gaming electronics surged in 2020, driven largely by lockdown behavior and increased at-home entertainment. Several key products — including PlayStation 5 bundles, gaming monitors, and Nintendo Switch — saw rapid growth during this period.
* The strongest growth came from PlayStation 5 Bundles (+381%), Lenovo IdeaPad Gaming Laptops (+204%), and Acer Nitro V (+133%), reflecting a rapid shift toward high-performance gaming devices.
* Despite strong pandemic-driven demand, sales dropped significantly in 2021 (-70% to -90%) across almost all product categories, indicating that the spike was temporary and heavily tied to pandemic-specific behavior.
* Overall, just three products — the 4K Gaming Monitor, Nintendo Switch, and PS5 Bundle — contribute over $5.2M, making up more than 85% of total revenue ($6.15M).
* The 27-inch 4K Gaming Monitor is the strongest revenue driver, generating $1.97M, making it the top-performing product across all periods.
* The Nintendo Switch follows closely with $1.66M, showing consistently high sales throughout the timeline, indicating strong and stable consumer demand.
* Sony PlayStation 5 Bundle also delivers substantial results with $1.59M in revenue, reinforcing the dominance of gaming consoles during the observed years.


<h4>Key Sales by Marketing Channels & Plaftorm</h4>

* Direct marketing is the strongest revenue driver, generating the highest sales across every major product — especially the 27in 4K Monitor, Nintendo Switch, and PlayStation 5 Bundle.
* Social media consistently underperforms, with most products generating less than $30K from this channel.
* North America is the top-performing region, generating over $2.6M from direct marketing alone.
* EMEA ranks second, contributing $1.63M through direct marketing, showing strong customer responsiveness to targeted campaigns.
* Social media performs poorly across all regions — particularly in LATAM, where it generates only ~$1.7K.
* 2020 marks the peak of marketing performance, with direct marketing revenue jumping from $1.3M (2019) to $3.45M (2020), driven by pandemic-led online purchasing.
* Email and social media channels also saw substantial growth in 2020, reflecting the overall shift toward digital engagement.
* 2021 shows a steep decline, with direct marketing dropping back to ~$437K, returning close to pre-pandemic levels.
* These trends show that the pandemic spike was temporary, not a sign of long-term marketing growth.

<h4>Product Revenue & Performance by Region</h4>

* 2020 became a clear global anomaly, with every region surging by roughly +150% to +200% in revenue and orders due to a pandemic-driven demand spike rather than true regional growth.
* In 2021, all regions experienced an –85% to –90% collapse in revenue and orders, signaling a sharp post-pandemic correction that simply pulled demand back to near-2019 levels and confirmed the artificial nature of the 2020 spike.
* North America and EMEA remain playsphere’s core markets, consistently contributing ~75–85% of revenue and staying the only stable, meaningful drivers even after the 2021 downturn, while APAC and LATAM remain small and highly volatile.
* High-value products like monitors, PS5 bundles, and Nintendo Switches are heavily concentrated in Western markets—North America holding 50–65% and EMEA 30–35%—while APAC and LATAM together contribute under 15%, showing playsphere’s strongest product-market fit lies decisively in these two regions.
* Gaming and console products are ByteX’s primary revenue drivers, with the PS5 Bundle, Nintendo Switch, and 27” 4K Monitor contributing 60–70%+ of regional sales and remaining far more resilient than accessories, which consistently generate <5% and offer limited margin impact.
* APAC and LATAM are highly volatile markets, surging +190% in 2020 but collapsing –85% to –90% in 2021, reflecting supply-chain and price sensitivity as well as low brand penetration, making them opportunity regions rather than reliable revenue drivers.
