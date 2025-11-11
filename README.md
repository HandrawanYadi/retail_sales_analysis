

<h1 align="center">Retail Sales Performance Report</h1>


## Client Background
This analysis is based on a **retail sales dataset** containing **9,994 transaction records** spanning **four years (2019–2022)**. The data captures a comprehensive view of business operations across **multiple regions, customer segments, and product categories**, providing valuable insights into sales performance, profitability, and customer behaviour.

The dataset includes detailed attributes such as **order date, ship mode, customer and region details, product category, sales, discount, and profit**. It represents a simulated mid-sized retail operation handling **furniture, office supplies, and technology** products across various cities and regions.

Reporting to the Head of Operations, an in-depth analysis was conducted to evaluate the company’s sales performance and operational efficiency over the past several years. This review provides actionable insights to support data-driven decisions in inventory planning, sales strategy, and customer engagement.

---

## Northstar Metrics

- **Sales Revenue** — Tracks total revenue growth, highlighting consistent quarterly increases from 2014 to 2017 and peak performance in Q4 each year. Used to measure business expansion and seasonality trends.  
- **Average Order Value (AOV)** — Evaluates how much customers spend per order. Shows 2016 peak due to premium purchases, followed by a 2017 shift to lower-priced items, guiding pricing and bundling strategies.  
- **Profit** — Measures gross margin stability and efficiency gains. Demonstrates improved cost control, higher margins, and sustainable profitability by 2017.  
- **Number of Orders** — Indicates sales volume and customer engagement. Upward trajectory (+152% in four years) confirms that growth is driven by higher order counts rather than larger baskets.  
- **Pareto Sales Distribution** — Assesses contribution by sub-category. Reveals balanced diversification, with 8 sub-categories covering ~80% of sales, guiding focus for inventory planning and stock optimisation.

---

<!-- ========================================= -->
<!-- EXECUTIVE SUMMARY -->
<!-- ========================================= -->
<table align="center">
  <tr>
    <div width="920">
      <h1 align="center">Executive Summary</h1>
      <div align="center">
        <img width="992" height="555" alt="Sales Revenue Analysis 2014–2017" src="https://github.com/user-attachments/assets/75605255-15d4-4b3a-bf3d-16104afd2836" />
      </div>
      <td width="460" valign="top">
        <ol>
          <li>
            <strong>Revenue Growth and Peak Performance</strong>
            <ul>
              <li>Sales grew steadily from 2014 to 2017, with total quarterly revenue more than doubling within four years.</li>
              <li><strong>Q4 2017 ($212K)</strong> recorded the highest performance, surpassing the overall quarterly average of <strong>$144K</strong>.</li>
              <li>Consistent Q4 growth indicates strong year-end demand, likely driven by holiday shopping cycles and promotional campaigns.</li>
            </ul>
          </li>
          <li>
            <strong>Seasonality and Sales Pattern</strong>
            <ul>
              <li>Each year displayed a repeating seasonal pattern — weaker Q1–Q2 performance followed by recovery in Q3 and peaks in Q4.</li>
              <li>This predictable trend highlights cyclical buying behaviour and the importance of Q4 promotional strategies.</li>
            </ul>
          </li>
        </ol>
      </td>
      <td width="460" valign="top">
        <ol start="3">
          <li>
            <strong>Year-over-Year Analysis</strong>
            <ul>
              <li>2015 showed a mid-year dip but recovered in Q3–Q4, indicating a temporary slowdown rather than systemic decline.</li>
              <li>2016 maintained stable performance across quarters, suggesting better operational control and market stability.</li>
              <li>By 2017, quarterly sales exceeded all previous years, reflecting compounding growth and increased market penetration.</li>
            </ul>
          </li>
          <li>
            <strong>Key Takeaways & Recommendations</strong>
            <ul>
              <li>Plan inventory and logistics ahead of Q4 surges to capitalise on seasonal highs.</li>
              <li>Boost Q1–Q2 demand with loyalty incentives or off-season campaigns to reduce reliance on Q4 performance.</li>
              <li>Establish a rolling sales forecast using the <strong>$144K</strong> average as a quarterly benchmark.</li>
              <li>Use historical trends to guide campaign timing, resource allocation, and pricing strategy.</li>
            </ul>
          </li>
        </ol>
      </td>
    </div>
  </tr>
</table>

<h2 align="center">Dataset Overview</h2>

<div align="center">

| Attribute | Description |
|------------|-------------|
| Order ID | Unique order identifier |
| Order Date / Ship Date | Transaction and delivery timeline |
| Ship Mode | Shipping method used |
| Customer ID / Name | Customer-level details |
| Segment | Market classification (Consumer, Corporate, Home Office) |
| Country / State / City / Region | Geographical sales segmentation |
| Product ID / Name | Product-level identification |
| Category / Sub-Category | Product grouping |
| Sales / Quantity / Discount / Profit | Financial and performance indicators |
| Returned | Return status of the product |

</div>

<h1 align="center">Insights Deep-Dive</h1>
<h2 align="center">Sales Trend (2014–2017)</h2>

<img width="1245" height="698" alt="Screenshot 2025-11-09 at 2 57 14 PM" src="https://github.com/user-attachments/assets/e204f782-5cf6-4c9d-8581-488ffae03802" />

---

<h3><strong>Average Order Value (AOV)</strong></h3>
<ol>
  <li><strong>2016 Peak Shows Customers Can Spend More</strong>
    <ul>
      <li>AOV reached its highest point in <strong>2016 ($289)</strong>, likely because of successful product bundling or premium product sales.</li>
      <li>This proves customers are willing to spend more when offered the right mix of higher-value items or limited promotions.</li>
      <li>Management can use this insight to plan more targeted campaigns that push average transaction value up during slower sales periods.</li>
    </ul>
  </li>
  <li><strong>2017 Drop Suggests Shift to Lower-Priced Items</strong>
    <ul>
      <li>AOV fell to around <strong>$219–$230</strong> in 2017 even though total revenue kept growing.</li>
      <li>This means customers were buying <strong>more items at lower prices</strong>, not spending more per order.</li>
      <li>To fix this, pricing and marketing should focus on encouraging returning customers and highlighting mid- to high-tier products that lift basket size.</li>
    </ul>
  </li>
  <li><strong>Raising AOV Can Boost Revenue Without More Customers</strong>
    <ul>
      <li>A small increase in AOV (even <strong>5%</strong>) could add about <strong>$40K–$50K</strong> in quarterly revenue with the same number of orders.</li>
      <li>This makes AOV one of the easiest levers for leadership to improve profit without expanding the customer base.</li>
      <li>Keeping AOV steady above <strong>$250</strong> should be treated as a key target for long-term stability.</li>
    </ul>
  </li>
</ol>

<hr>

<h3><strong>Sales Revenue</strong></h3>
<ol>
  <li><strong>Upward Revenue Trend (2014–2017)</strong>
    <ul>
      <li>Total sales revenue nearly doubled from <strong>$96K in Q1 2014</strong> to <strong>$212K in Q4 2017</strong>.</li>
      <li>2014–2015 showed early volatility but established steady growth from mid-2016 onward.</li>
      <li>The <strong>average quarterly sales ($143K)</strong> indicates consistent business expansion.</li>
    </ul>
  </li>
  <li><strong>Seasonal Spikes in Late-Year Quarters</strong>
    <ul>
      <li>Q4 in both 2016 and 2017 outperformed earlier quarters by 20–30%.</li>
      <li>Growth patterns suggest strong performance driven by holiday promotions and increased Q4 consumer demand.</li>
    </ul>
  </li>
  <li><strong>2017 Record Performance</strong>
    <ul>
      <li>2017 achieved the <strong>highest single-quarter revenue ($212K)</strong>, reinforcing overall positive growth momentum.</li>
      <li>The strong finish marks successful scaling of operations and demand optimisation strategies.</li>
    </ul>
  </li>
</ol>

<hr>

<h3><strong>Profit</strong></h3>
<ol>
  <li><strong>Overall Positive Growth</strong>
    <ul>
      <li>Average quarterly profit is <strong>$17.9K</strong>, reflecting steady gross margin improvements from 2014 to 2017.</li>
      <li>The <strong>highest quarterly profit ($33K in 2017)</strong> shows significant margin expansion in the later years.</li>
    </ul>
  </li>
  <li><strong>Operational Efficiency Gains</strong>
    <ul>
      <li>Profit variability decreased over time, suggesting better cost control and inventory efficiency.</li>
      <li>The 2016–2017 phase marks higher profitability per order and optimised pricing structure.</li>
    </ul>
  </li>
  <li><strong>Insight</strong>
    <ul>
      <li>Revenue and profit grew together, meaning that expansion did not come at the cost of margins — a sign of sustainable growth.</li>
    </ul>
  </li>
</ol>

<hr>

<h3><strong>Number of Orders</strong></h3>
<ol>
  <li><strong>Strong Upward Trajectory</strong>
    <ul>
      <li>Orders rose from <strong>385 in early 2014</strong> to <strong>969 by late 2017</strong>, a <strong>152% increase</strong> in total order volume.</li>
      <li>Growth rate accelerated after 2015, aligning with revenue improvements and increased AOV stability.</li>
    </ul>
  </li>
  <li><strong>Steady Growth Beyond Early Volatility</strong>
    <ul>
      <li>Average orders per quarter (~625) improved significantly after 2016.</li>
      <li>Increased order frequency contributed directly to overall sales growth.</li>
    </ul>
  </li>
  <li><strong>Key Observations</strong>
    <ul>
      <li>Revenue growth is primarily driven by order volume rather than per-order value.</li>
      <li>The alignment of higher order count, profit, and stable AOV underscores improved customer retention and acquisition.</li>
    </ul>
  </li>
</ol>


### **Summary**
| Metric | Trend | Key Insight |
|---------|-------|--------------|
| **Sales Revenue** | ↑ Rising | Doubled between 2014–2017; peak in Q4 each year |
| **AOV** | ↔ Fluctuating | Peaked 2016 ($289); stabilised by 2017 (~$230) |
| **Profit** | ↑ Improving | Highest in 2017 ($33K); steady margin control |
| **Orders** | ↑ Strong growth | +152% over 4 years; main driver of revenue gains |

---

<p align="center">

<h1 align="center">Pareto Analysis</h1>
<img width="1345" height="635" alt="Screenshot 2025-11-09 at 11 07 45 PM" src="https://github.com/user-attachments/assets/2adbe822-ba39-4e7b-b04c-561183c56b79" />

## Overview
<ul>
<li>This analysis visualises the relationship between total sales and their cumulative contribution across product sub-categories.</li>
<li>The chart combines:
  <ul>
    <li><strong>Bar graph</strong> representing total sales value (in thousands)</li>
    <li><strong>Line graph</strong> representing cumulative percentage of total sales</li>
  </ul>
</li>
</ul>

## Key Insights
<ol>
<li><strong>Sales Distribution Pattern</strong>
  <ul>
    <li>Phones and Chairs are the leading categories, each generating around 330K in sales.</li>
    <li>Storage, Tables, and Binders follow as solid contributors.</li>
    <li>Together, these 5 sub-categories make up roughly 56% of total sales.</li>
    <li>The sales spread indicates a balanced portfolio, with no extreme concentration in a few items.</li>
  </ul>
</li>

<li><strong>Cumulative Trend</strong>
  <ul>
    <li>The cumulative line reaches 80 percent of total sales after 8 categories.</li>
    <li>In a classic Pareto scenario, 80 percent would typically be reached after only 3 to 4 categories.</li>
    <li>The flatter cumulative curve reflects a more diversified sales distribution.</li>
  </ul>
</li>

<li><strong>Operational Interpretation</strong>
  <ul>
    <li>Sales are distributed across multiple categories, implying steady multi-product demand.</li>
    <li>Operational improvements should focus on:
      <ul>
        <li>Enhancing demand forecasting accuracy</li>
        <li>Maintaining balanced stock levels</li>
        <li>Improving replenishment lead times and throughput</li>
      </ul>
    </li>
    <li>SKU reduction is not essential; focus should be on process efficiency and service reliability.</li>
  </ul>
</li>

<li><strong>Strategic Summary</strong>
  <ul>
    <li><strong>Top performers</strong> - require strong service-level and consistent stock availability.</li>
    <li><strong>Mid-range contributors</strong> — maintain lean but reliable inventory control.</li>
    <li><strong>Tail categories</strong> — low revenue share; suitable for periodic review or rationalisation.</li>
  </ul>
</li>

---

<h1 align="center">Recommendations</h1>

The following recommendations summarise key actions identified from the **Retail Sales Performance Report (2014–2017)** to support continued growth, strengthen margins, and improve operational efficiency.

### **Sales**

- **Plan ahead for peak seasons**  
  Q4 consistently delivers the highest sales performance, exceeding other quarters by up to 30%. Ensure inventory, staffing, and marketing activities are aligned to capture this surge in demand.

- **Stabilise sales in low-performing quarters**  
  Q1 and Q2 demonstrate weaker performance. Introduce targeted campaigns, loyalty incentives, or bundled offers during these periods to reduce seasonality gaps and maintain consistent revenue flow.

- **Adopt the $144K average as a performance benchmark**  
  Use the average quarterly sales of $144K as a reference point for forecasting, sales planning, and performance evaluation.

---

### **Products and Inventory**

- **Focus on high-performing categories**  
  Phones and Chairs remain the strongest revenue drivers. Maintain optimal stock levels, reinforce marketing efforts, and ensure supply continuity for these key products.

- **Optimise mid-performing categories**  
  Sub-categories such as Storage, Tables, and Binders show stable demand. Apply lean inventory practices to maintain balance between availability and capital efficiency.

- **Evaluate and manage low-performing products**  
  Review slow-moving categories regularly. Retain only those that contribute strategic or niche value; otherwise, rationalise inventory to free up working capital.

- **Implement structured inventory control**  
  Adopt an **ABC–XYZ classification** to link product value with demand variability. This approach will enhance replenishment accuracy and prevent overstocking.

---

### **Profitability**

- **Maintain margin discipline**  
  Profit growth reached a quarterly peak of $33K in 2017. Continue reinforcing pricing control, supplier management, and operational efficiency to sustain profitability.

- **Refine discount strategy**  
  Evaluate the long-term impact of discounting. Focus on targeted promotions that drive meaningful sales uplift without eroding margin.

---

### **Customer and Order Management**

- **Encourage repeat purchasing**  
  Order volumes increased by more than 150% over the review period. Build on this momentum through customer retention initiatives such as loyalty programmes or repeat-purchase incentives.

- **Use order data to guide forecasting**  
  Incorporate historical order trends into demand planning and procurement. This ensures alignment between sales activity and stock availability.

---

### **Operations**

- **Strengthen demand forecasting**  
  Leverage historical seasonality patterns—particularly Q3 and Q4 surges—to plan production, logistics, and workforce scheduling with greater accuracy.

- **Maintain balanced product diversification**  
  Pareto analysis shows that 8 sub-categories account for approximately 80% of total sales, indicating a well-diversified portfolio. Retain this structure while improving process efficiency and replenishment speed.

---

<p align="center">
  <em><sub>This project uses a publicly available retail dataset and a sample company context, created for analytical demonstration and portfolio presentation purposes.</em></sub>
</p>

