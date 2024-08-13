# Bank-Customers Dashboard Tableau 

# Problem Statement 

The goal of this project is to explore the provided Bank Customers dataset to create interactive visualizations that offer insights into various aspects of customer data. The visualizations will help in understanding the distribution of balances across regions, customer demographics by gender, job class performance, average balances by gender, and the relationship between age and balance.

# Dataset Overview

𝐂𝐮𝐬𝐭𝐨𝐦𝐞𝐫 𝐈𝐃: Unique identifier for each customer.

𝐆𝐞𝐧𝐝𝐞𝐫: Gender of the customer (Male or Female).

𝐀𝐠𝐞: Age of the customer in years.

𝐑𝐞𝐠𝐢𝐨𝐧: Geographic region (East, West, North, South).

𝐉𝐨𝐛 𝐂𝐥𝐚𝐬𝐬𝐢𝐟𝐢𝐜𝐚𝐭𝐢𝐨𝐧: Type of job (Service, Business, Other).

𝐃𝐚𝐭𝐞 𝐉𝐨𝐢𝐧𝐞𝐝: Date the customer joined the bank.

𝐁𝐚𝐥𝐚𝐧𝐜𝐞: Customer's account balance


# Steps Followed


𝐋𝐨𝐚𝐝𝐞𝐝 𝐭𝐡𝐞 𝐃𝐚𝐭𝐚𝐬𝐞𝐭: Imported the Bank Customers dataset into Tableau.

𝐄𝐱𝐩𝐥𝐨𝐫𝐞𝐝 𝐃𝐚𝐭𝐚 𝐅𝐢𝐞𝐥𝐝𝐬: Familiarized with fields such as Customer ID, Gender, Age, Region, Job Classification, Date Joined, and Balance.

𝐃𝐚𝐭𝐚 𝐂𝐥𝐞𝐚𝐧𝐢𝐧𝐠: Ensured that the data was clean and well-formatted, with no missing values or inconsistencies.
Visualization Creation:

𝐏𝐢𝐞 𝐂𝐡𝐚𝐫𝐭 𝐟𝐨𝐫 𝐑𝐞𝐠𝐢𝐨𝐧𝐚𝐥 𝐁𝐚𝐥𝐚𝐧𝐜𝐞 𝐃𝐢𝐬𝐭𝐫𝐢𝐛𝐮𝐭𝐢𝐨𝐧:
Created a pie chart to show the total balance in each region (East, West, North, South).
Displayed the percentage of the total balance for each region using the Percent of Total calculation. 


![Screenshot 2024-08-13 170128](https://github.com/user-attachments/assets/5a040903-e53e-40a9-b735-d2323195fc33)

𝐁𝐚𝐫 𝐂𝐡𝐚𝐫𝐭 𝐟𝐨𝐫 𝐂𝐮𝐬𝐭𝐨𝐦𝐞𝐫 𝐃𝐢𝐬𝐭𝐫𝐢𝐛𝐮𝐭𝐢𝐨𝐧 𝐛𝐲 𝐆𝐞𝐧𝐝𝐞𝐫:
Built a bar chart to show the number of customers by gender.
Added colors (Red for Female, Green for Male) and labels to display the distinct count of male and female customers.

![Screenshot 2024-08-13 170142](https://github.com/user-attachments/assets/f6fd4edb-a7d5-40d2-8a36-54782a871b28)


𝐆𝐫𝐚𝐩𝐡 𝐟𝐨𝐫 𝐉𝐨𝐛 𝐂𝐥𝐚𝐬𝐬 𝐚𝐧𝐝 𝐁𝐚𝐥𝐚𝐧𝐜𝐞 𝐛𝐲 𝐑𝐞𝐠𝐢𝐨𝐧:
Created a graph to show which job class has the highest and lowest sum of balance in each region.
Displayed both maximum and minimum balance values for each region.

![Screenshot 2024-08-13 170156](https://github.com/user-attachments/assets/0f1defaa-2ad4-455e-9a3b-538b4fc1c3e3)

𝐓𝐚𝐛𝐥𝐞 𝐟𝐨𝐫 𝐀𝐯𝐞𝐫𝐚𝐠𝐞 𝐁𝐚𝐥𝐚𝐧𝐜𝐞 𝐛𝐲 𝐆𝐞𝐧𝐝𝐞𝐫:
Used a calculated field to determine the average balance for male and female customers.
Presented the results in a table format with columns for Gender and Average Balance.

![Screenshot 2024-08-13 170724](https://github.com/user-attachments/assets/2a64125d-f4a2-46d2-9684-583ed2ce903c)

𝐒𝐜𝐚𝐭𝐭𝐞𝐫 𝐏𝐥𝐨𝐭 𝐟𝐨𝐫 𝐀𝐠𝐞 𝐯𝐬. 𝐁𝐚𝐥𝐚𝐧𝐜𝐞:
Created a scatter plot with Age on the x-axis and Balance on the y-axis.
Used shapes to represent different job classifications and colored the data points based on gender.

![Screenshot 2024-08-13 170220](https://github.com/user-attachments/assets/e7fca03d-7a93-457b-b9da-140bdd45d761)



# Insights

𝐑𝐞𝐠𝐢𝐨𝐧𝐚𝐥 𝐁𝐚𝐥𝐚𝐧𝐜𝐞 𝐃𝐢𝐬𝐭𝐫𝐢𝐛𝐮𝐭𝐢𝐨𝐧:

The pie chart reveals which regions hold the highest and lowest total balances. This helps identify regions with the most financial activity.

𝐆𝐞𝐧𝐝𝐞𝐫 𝐃𝐢𝐬𝐭𝐫𝐢𝐛𝐮𝐭𝐢𝐨𝐧:

The bar chart shows the number of male and female customers. Color-coded bars provide a clear visual distinction between genders.

𝐉𝐨𝐛 𝐂𝐥𝐚𝐬𝐬 𝐁𝐚𝐥𝐚𝐧𝐜𝐞 𝐛𝐲 𝐑𝐞𝐠𝐢𝐨𝐧:

The graph identifies which job classifications contribute the most and least to the balance in each region. This can highlight financial contributions based on job roles.

𝐀𝐯𝐞𝐫𝐚𝐠𝐞 𝐁𝐚𝐥𝐚𝐧𝐜𝐞 𝐛𝐲 𝐆𝐞𝐧𝐝𝐞𝐫:

The table shows average balances for male and female customers. It helps in understanding gender-based financial behaviors.

𝐀𝐠𝐞 𝐯𝐬. 𝐁𝐚𝐥𝐚𝐧𝐜𝐞:

The scatter plot reveals any correlation between age and balance. Different shapes and colors provide additional insights into job classifications and gender distribution.


# Recommendations

𝐅𝐮𝐫𝐭𝐡𝐞𝐫 𝐀𝐧𝐚𝐥𝐲𝐬𝐢𝐬:

Consider exploring trends over time by analyzing the Date Joined
field. This could uncover seasonal patterns or changes in customer behavior.

𝐒𝐞𝐠𝐦𝐞𝐧𝐭 𝐀𝐧𝐚𝐥𝐲𝐬𝐢𝐬

Perform segmentation analysis to identify high-value customer profiles based on balance, age, and job classification.

𝐀𝐝𝐝𝐢𝐭𝐢𝐨𝐧𝐚𝐥 𝐕𝐢𝐬𝐮𝐚𝐥𝐢𝐳𝐚𝐭𝐢𝐨𝐧𝐬:

Add trend lines or regression analysis to the scatter plot to better understand the relationship between age and balance.

𝐄𝐧𝐡𝐚𝐧𝐜𝐞𝐝 𝐈𝐧𝐭𝐞𝐫𝐚𝐜𝐭𝐢𝐯𝐢𝐭𝐲:

Implement filters and drill-down options to allow users to explore specific regions, job classifications, or age groups in more detail.

𝑻𝒉𝒊𝒔 𝒑𝒓𝒐𝒋𝒆𝒄𝒕 𝒂𝒊𝒎𝒆𝒅 𝒕𝒐 𝒆𝒙𝒑𝒍𝒐𝒓𝒆 𝒂𝒏𝒅 𝒗𝒊𝒔𝒖𝒂𝒍𝒊𝒛𝒆 𝒌𝒆𝒚 𝒂𝒔𝒑𝒆𝒄𝒕𝒔 𝒐𝒇 𝒕𝒉𝒆 𝒃𝒂𝒏𝒌'𝒔 𝒄𝒖𝒔𝒕𝒐𝒎𝒆𝒓 𝒅𝒂𝒕𝒂𝒔𝒆𝒕 𝒕𝒐 𝒈𝒂𝒊𝒏 𝒊𝒏𝒔𝒊𝒈𝒉𝒕𝒔 𝒊𝒏𝒕𝒐 𝒄𝒖𝒔𝒕𝒐𝒎𝒆𝒓 𝒅𝒆𝒎𝒐𝒈𝒓𝒂𝒑𝒉𝒊𝒄𝒔, 𝒇𝒊𝒏𝒂𝒏𝒄𝒊𝒂𝒍 𝒃𝒆𝒉𝒂𝒗𝒊𝒐𝒓, 𝒂𝒏𝒅 𝒓𝒆𝒈𝒊𝒐𝒏𝒂𝒍 𝒅𝒊𝒔𝒕𝒓𝒊𝒃𝒖𝒕𝒊𝒐𝒏. 𝑻𝒉𝒆 𝒗𝒊𝒔𝒖𝒂𝒍𝒊𝒛𝒂𝒕𝒊𝒐𝒏𝒔 𝒉𝒆𝒍𝒑 𝒊𝒏 𝒖𝒏𝒅𝒆𝒓𝒔𝒕𝒂𝒏𝒅𝒊𝒏𝒈 𝒕𝒉𝒆 𝒅𝒊𝒔𝒕𝒓𝒊𝒃𝒖𝒕𝒊𝒐𝒏 𝒐𝒇 𝒂𝒄𝒄𝒐𝒖𝒏𝒕 𝒃𝒂𝒍𝒂𝒏𝒄𝒆𝒔, 𝒄𝒖𝒔𝒕𝒐𝒎𝒆𝒓 𝒅𝒆𝒎𝒐𝒈𝒓𝒂𝒑𝒉𝒊𝒄𝒔 𝒃𝒚 𝒈𝒆𝒏𝒅𝒆𝒓, 𝒋𝒐𝒃 𝒄𝒍𝒂𝒔𝒔 𝒑𝒆𝒓𝒇𝒐𝒓𝒎𝒂𝒏𝒄𝒆 𝒂𝒄𝒓𝒐𝒔𝒔 𝒓𝒆𝒈𝒊𝒐𝒏𝒔, 𝒂𝒗𝒆𝒓𝒂𝒈𝒆 𝒃𝒂𝒍𝒂𝒏𝒄𝒆𝒔 𝒃𝒚 𝒈𝒆𝒏𝒅𝒆𝒓, 𝒂𝒏𝒅 𝒕𝒉𝒆 𝒓𝒆𝒍𝒂𝒕𝒊𝒐𝒏𝒔𝒉𝒊𝒑 𝒃𝒆𝒕𝒘𝒆𝒆𝒏 𝒂𝒈𝒆 𝒂𝒏𝒅 𝒃𝒂𝒍𝒂𝒏𝒄𝒆.


# Live Dashboard Access  

https://public.tableau.com/app/profile/vamsika.sneha.varada/viz/Practiceset3Bank-CustomersDataset/BankCustomerDashboard?publish=yes


# Snapshot of Bank-Customers Dashboard (Tableau Public)

![Screenshot 2024-08-13 164256](https://github.com/user-attachments/assets/0e85a74d-514b-4745-ba81-e91a3293743d) 







