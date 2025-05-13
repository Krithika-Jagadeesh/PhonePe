# PhonePe
**PhonePe Pulse**

This document provides a detailed overview of the functionality, design, and components of the PhonePe Pulse Dashboard, built using Streamlit. It outlines the various analytical features and visualizations embedded in the dashboard across multiple case studies. 
### 1. Navigation and Layout
The PhonePe Pulse dashboard is designed with an intuitive sidebar for navigation. Users can switch between the 'Home' section and the 'Case Studies' section:

**Home:** Displays a title and brief introductory message.
**Case Studies:** Contains five detailed analytical modules focusing on various aspects of PhonePe’s business operations.

Each case study is accessible via a dropdown menu, enabling dynamic content rendering based on user selection.

### 2. Case Studies Functionalities
**2.1 Case Study 1:** Decoding Transaction Dynamics
This module provides insights into the total transaction volume and amount on PhonePe across different states, transaction types, and time frames.

**Features:**
- Interactive choropleth map representing transaction amounts by state.
- Donut charts comparing transaction count and amount across transaction types.
- Bar chart showcasing top 10 states by transaction amount.
- Line chart visualizing transaction type distribution in a selected state.
- Quarterly trend analysis for a selected year using bar charts.

The visualizations support year and quarter filters, allowing granular analysis.

**2.2 Case Study 2: Device Dominance and User Engagement**
This case study explores user interaction patterns, especially from the perspective of devices, districts, and states.

**Features:**
- Heatmap representing transaction activity across states.
- Donut charts visualizing top states based on transaction count and amount.
- Bar charts showing top-performing districts.
- Line chart showing performance of pincodes.
- Low engagement region analysis highlighting areas with below-average transactions.

A mix of filters and visual feedback mechanisms help in identifying focus areas for growth.


**2.3 Case Study 3: User Registration Analysis**
This module analyzes the number of users registered with PhonePe across states, districts, and pincodes.

**Features:**
- Choropleth map of registered users by state.
- Bar chart displaying top states.
- Scatter plot for district-wise user count.
- Histogram showcasing top 50 pincodes with highest registrations.

These visualizations provide valuable insights into regional adoption of PhonePe.

**2.4 Case Study 4: Insurance Transactions Analysis**
Focuses on analyzing insurance-related transactions facilitated through PhonePe.

**Features:**
- Choropleth map displaying insurance transaction amounts.
- Bar chart for top states based on insurance transaction counts.
- Scatter and histogram charts for district and pincode-wise insurance metrics.

The module helps in understanding the geographical spread of PhonePe’s insurance offerings.

**2.5 Case Study 5: Market Expansion Strategy**
Designed to assist in strategic expansion by analyzing transaction performance across regions.

**Features:**
- Choropleth map for transaction amount by state.
- Donut charts for state-wise transaction count and amount.
- Bar chart for average transaction amount by state.
- Scatter and bar charts tracking transaction growth trends and quarterly growth percentages.

This section combines historical trends and real-time metrics to support business decisions.

### 3. Technologies and Libraries Used
**Streamlit:** Web application framework for building interactive dashboards.
**Plotly:** Charting and data visualization library for creating interactive plots.
**Pandas:** Data manipulation and preprocessing.
**MySQL + SQLAlchemy:** Data storage and querying.
**GeoJSON:** Spatial data rendering for map-based visualizations.
**Python:** Core programming language for building backend logic.

### 4. Conclusion
The PhonePe Pulse dashboard provides an integrated, interactive platform for visualizing business intelligence across multiple verticals. Its modular design enables focused insights, while dynamic elements like maps, charts, and filters enhance usability and decision-making. This tool can aid stakeholders in identifying trends, regional strengths, and opportunities for market penetration.

