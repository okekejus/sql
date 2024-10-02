# Homework 6: Reflecton

- Due on Saturday, September 21 at 11:59pm
- Weight: 8% of total grade

<br>

**Write**: Reflect on your previous work and how you would adjust to include ethics and inequity components. Total length should be a few paragraphs, no more than one page.


The only thoughts I have regarding my previous work in this unit are related to the farmers market database and its structure. My understanding is that the database is currently in 2NF, but the inclusion of a lot of information within the same table (postal code information) might be a concern.

To enhance the database design while adhering to SQL data management ethics, maybe we could further normalize the postal_code_info table. This could involve creating separate tables for postal code details, such as demographic data, geographic information, and other relevant attributes. By doing this, we can reduce redundancy, minimize the risk of data anomalies, and ensure that each piece of information is stored in its appropriate context. This approach aligns with ethical data practices by promoting clear relationships between entities and improving data integrity.

If this were a real database for an organization/vendor, I would recommend regular audits and data governance policies to maintain the integrity of the data and ensure that it is used responsibly.
