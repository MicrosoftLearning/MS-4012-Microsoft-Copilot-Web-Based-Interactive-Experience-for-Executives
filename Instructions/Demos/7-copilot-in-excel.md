---
demo:
    title: 'Demo: Copilot in Excel'
---

[Back to Index](https://microsoftlearning.github.io/MS-4012-Microsoft-Copilot-Web-Based-Interactive-Experience-for-Executives/)

# Microsoft 365 Copilot in Excel

## Demo Setup

Download the Excel sample document [**EV_Charger-Sales_Analysis_v1.xlsx**](https://github.com/MicrosoftLearning/MS-4012-Microsoft-Copilot-Unlocked/raw/master/Resourcefiles/EV_Charger-Sales_Analysis_v1.xlsx). You will use this file to run the demo steps outlined in this guide.


## Talking Points

Copilot in Excel makes anyone a data analyst. You can use Copilot to quickly understand annual revenue trends, product sales, category performance, and what's driving your business results.

You've pulled all your data together into an Excel workbook that contains information on product sales, pricing, and customer feedback.

Copilot can help you shape and analyze these numbers across multiple tabs, making it easier to extract insights.

## Demo Steps

> **NOTE:** Make sure to open the Excel file **EV Charger – Sales Analysis v1.xlsx** before proceeding.

1. **Navigate to the "Sales by Product" tab** in the Excel file.

1. Use Copilot to Calculate Monthly Revenue:  

   Let's start by figuring out which category of your business is driving the most revenue. This sheet contains three years of sales data, with thousands of rows showing sales by product by month. Although it's a routine task, this volume of data can be unwieldy. You can ask Copilot to quickly calculate the monthly revenue by product.

   Use the following prompt:

   ```text
   Calculate monthly revenue by product and add a column with total revenue - refer to the Prices worksheet.
   ```
    - Copilot knows how to do that and which data to reference across tabs. 
    - Copilot creates a plan for how it will run those numbers, executes that plan showing its work as it goes, and prompts you to ask questions or iterate on the solution it reached.
    - Click **+Insert column**, then navigate back to the **Sales by Product** tab.
   

1. Use Copilot to analyze revenue by entering the following prompt in the Copilot pane:

    ```text
    What is the total revenue for each category so far in 2024?
    ```

    - Copilot will run the numbers and create a bar chart that you can add to your workbook.
    - Click **+Add to a new sheet**, then navigate back to the **Sales by Product** tab.

1. Now, use Copilot to highlight products with low sales by entering this prompt:

    ```text
    Highlight rows where the value in column H is less than $100K.
    ```

    - Copilot will apply conditional formatting, helping you identify products that aren’t performing to your standards.

1. **Navigate to the "Reviews" tab** to analyze customer feedback.

1. Ask Copilot to summarize the top concerns by entering the following prompt:

    ```text
    Summarize the top 3 customer concerns we should focus on.
    ```

    - Copilot will analyze the feedback and surface the top three customer concerns. It looks like charging speed is an emerging issue.

1. Next, highlight reviews mentioning charging speed by entering this prompt:

    ```text
    Highlight reviews that mention issues related to charging speeds.
    ```

    - Copilot will highlight all relevant reviews in the dataset.

### Wrap-up

With the help of Copilot, you've analyzed complex data sets and gained insights on product performance and customer feedback. These insights can be used to inform your next business review.

> **TIP:** If you want to explore further, try asking Copilot additional questions related to sales trends or customer satisfaction.
