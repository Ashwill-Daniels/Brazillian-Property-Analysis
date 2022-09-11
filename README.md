# Brazillian-Property-Analysis
Mock scenario:

A client asks me to draw up a list of the cheapest 3-bedroom house in each state of Brazil. I am then to compare each house's price and cost per square meter and make a recommendation. 

Data:

I used a public dataset on BigQuery called Properatti - Brazil Real Estate Listings. This dataset contained many large tables, so I only used one (properties_sell_201802)(There were only 20 unique states in the table). This table lists properties posted from 01-08-2017 to 01-02-2018.

Tools:

I used BigQuery(SQL), Google Sheets and Tableau for this project.

Constraints:
The listing must be a house.
It must have 3 bedrooms.
The cost per square meter must be listed.

Result:

After applying the above constraints to the table, I was left with houses from 11 states.

—----------------------------------------------------------------------------------------------------------------------------

Appendix:

BigQuery dataset ID: properati-data-public.properties_br

Tableau presentation:           https://public.tableau.com/app/profile/ashwill.daniels/viz/CheaphousesBrazil/Map

