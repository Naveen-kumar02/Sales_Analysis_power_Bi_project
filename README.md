# Sales_Analysis_power_Bi_project
## Objective 
The purpose of this project to analyse the sales trends between the Diwali 2023 and snkarathi 2024 

## How I Work on this project 
1 **Data Collection**:
- The data is provide by the company 
- dim_campaigns - Campaign_id, campaign_name , start_date, end_date
- dim_products - product_code, product_name, category
- dim_stores - store_id , city
- fact_events - event_id , store_id , campaign_id , product_code , base_price, promo_type , quantity_sold_before_promo , quantity_sold_after_promo

2 **Data Transformation**: 
- Data was transformed in power bi using power query
- removing duplicates , set first rows as header , fix the datatypes

3 **Data Modeling**:
- Relationship was establish between tables to create a logical data model.
- Measure are created by using the DAX function

4 **Visualization**:
- Designed a interactive dashboard with visual such as line chart, bar chart , Card visual , waterfal visual etc
- Fosused on user friendly design and meaningful insight

## Tools used 
- Power BI desktop , MySQL


