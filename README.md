# MySQL-to-CSV-using-pandas

This simple project is intended to practice working with real-world PLM data, performing data transformations, and generating useful insights for product development tracking.
- Data residing in MySQL is read using SQLAlchemy and Pandas. 
- Extracted data is cleansed and transformed to fetch key metrics like:
    - Approval Time: Time taken for each product to get approved.
    - delay in approval: delay in approval time if the status is still in pending state.
    - Production Delays: Days products are delayed in manufacturing.
- Final dataframe is loaded to CSV file.