# 4LAFC

# Objective: Leverage transactional data to uncover strategic opportunities in food & beverage operations at BMO Stadium.


#Assumptions and corresponding transformations:
-All transactions occur during the midnight hour; this is to be confirmed by internal members prior to pipeline setup 

-Events with 2 nights are actually separate event_dates; Night 1 was assigned to the day prior from the dataset; this is to be confirmed by internal team members/event_schedule

-Quantity was incorrectly populated by default, original subtotal/price was used to calculate quantity; this is to be confirmed by internal team members

-110 North Bar and 110 South Bar are NOT to be combined based on separate vendor ID and Name

#Deliverable folder:
-Identifies top performers among performant F&B categories  
-Provides surface level insight on how to utilize these metrics for replicated success.

#Notebook folder: 
Provides 2 separate notebooks; Cleaning and processing, vizualization.  

