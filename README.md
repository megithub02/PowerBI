
# Superstore Sales Dashboard

### Dashboard Link :C:\Users\hp\Pictures\Saved Pictures\Screenshot 2024-02-20 234326.png

## Objective

To contribute to the sucess of a buisness by utilizing data analysis of sales & profit using KPI filters charts donust charts for different matrix.


### Steps followed 

- Step 1 : Loaded data into Power BI Desktop, dataset is a csv file.


- Step 2 : Open power query editor & in view tab under Data viewer and transform the data, delete the error columns.


- Step 3 : It was observed that in none of the columns errors & empty values were present except "Payment mode".


- Step 4 : A DAX query used for creation of the table for Average Delivery (i.e column named "Avg Delivery")   

for creating new column following DAX expression was written;
       
        AvgDelivery = 

        DATEDIFF('SuperStore_Sales'[Order Date], 'SuperStore_Sales'[Ship Date], DAY)
        


![Snap_1](https://user-images.githubusercontent.com/102996550/174089602-ab834a6b-62ce-4b62-8922-a1d241ec240e.jpg)

        
- Step 5 : New measure was created to find Avg Ship Day.


- Step 6 : In the report view, under the view tab, theme was selected.

- Step 7 :Visual filters (Slicers) were added for entire data of Region (i.e Slicers name "Central", "South", "West", "East"). 

- Step 8 : Four KPI added for entire data (i.e "Sales", "Profit", "Quantity", "Ship Day" ).

           
- Step 9 : Three Clustred bar charts were also added to the report design area representing the number of. While creating this visual, field named "Sales by Sub Category", "Sales by Ship Mode" and "Sales by Sub-Category" used for better understanding. 


- Step 10 :  Two Area chart used for comparison between year and year monthly sales and monthly profit.
  

- Step 11 : Three donut chart inserted "Sales by Region", "Sales by Payment mode" and "Sales by Segments".



# Snapshot of Dashboard (Power BI Service)

![dashboard_snapo](https://user-images.githubusercontent.com/102996550/174096257-11f1aae5-203d-44fc-bfca-25d37faf3237.jpg)

 
 # Report Snapshot (Power BI DESKTOP)

 
![Dashboard_upload](https://user-images.githubusercontent.com/102996550/174074051-4f08287a-0568-4fdf-8ac9-6762e0d8fa94.jpg)

# Insights

Incorporated data analysis techniques, specializing in time series analysis to deliver valuable insights accurate sales forcasting and interactive dashboard creation driving buisness sucess.

 
 ### Sales Region
 
 2.1)  22% Central.
 2.2)  29% East.
 2.3)  33% West.
 2.4)  16% South.
 
         thus, maximum customers belong to 'West' region.
         
### Orders Segment

3.1) 18% Home and Office supplies
3.2) 48% consumer
3.30 33% Coporate
       
       thus, more customers have customer type 'consumer'.

### Sales by Payment mode

4.1) 35 % online payment mode.
4.2) 43 % COD payment mode.
4.3) 22 % card payment mode.

        thus, more customers have used 'Online payment mode'.
# 
Displaying # Superstore sales dashboard# PowerBI
