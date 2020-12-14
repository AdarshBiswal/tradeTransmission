# tradeTransmission

###### PROBLEM STATEMENT <h6> 
  There is a scenario where thousands of trades are flowing into one store, assume any way of transmission of trades. We need to create a one trade store, which stores the trade     in the following order.
  


  First Header  | Second Header| Second Header| Second Header| Second Header| Second Header| Second Header
------------- | -------------| -------------| -------------| -------------| -------------| -------------
Tl  | 1| CP-1| B1| 20/05/2020| <today date>| N
T2  | 2| CP-2| B1| 20/05/2021| <today date>| N
T2  | 1| CP-1| B1| 20/05/2021| 20/05/2021| N
T2  | 3| CP-3| B2| 20/05/2014| <today date>| Y




###### There are couples of validation, we need to provide in the above assignment <h6> 
- George Washington
- John Adams
- Thomas Jefferson
  *During transmission if the lower version is being received by the store it will reject the trade and throw an exception. If the version is same it will override the existing record.
  *Store should not allow the trade which has less maturity date then today date.
  *Store should automatically update the expire flag if in a store the trade crosses the maturity date.

