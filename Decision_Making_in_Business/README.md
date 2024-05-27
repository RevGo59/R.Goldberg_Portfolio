**Project Goal:** Prioritize hypotheses to maximize key metrics, analyze A/B test results, state conclusions and recommendations.

**Stack:** A/B test, statistical hypotheses testing, matplotlib, pandas, scipy

**Conclusions:**
1) Data is processed and explored;
2) 9 Hypotheses assessed with RICE framework. Hypothesis # 7 is considered as the one that should be tested.
3) Metrix analysed:
   - Сumulative Revenue by groups:
   Revenue increases all over the testing timeframe. For group B the jump around 18th August is detected, reasons for this need to be further analysed.
   
   
   - Сumulative Average check by groups:
   Average Check for Group A increases at the beginning of the timeframe, then shows steady growth and stabilizes by the end of the timeframe. Average Check for Group B shows the intermittent growth with significant jump around 18th August, then modulates and relatively stabilizes.
   
   
   - Сumulative Average check Relative variation:
   Сumulative Average check for Group B generally is higher than for Group A. The jump on 18th august is also visible.
   
   
   - Сumulative Average orders number per user by groups:
    Plot is close to symmetrical. After 6th August Conversion for Group A seems to be always lower than for Group B. Conversion for Group B shows variations that seem to significantly decrease by the end of the timeframe.
    
   
   - Сumulative average orders number per user Relative variation:
   In the beginning of the timeframe Group B loses out to Group A, but takes the lead around 6th August. After 25th August Conversion for Group B stabilizes and shows only insignificant variations within 10-15%.
   
   
   - Number of Orders:
   The majority of usres placed just 1 order, there are some useres that placed 2-5 orders, and 3 users that placed 8,9 & 11 orders each.
   
   
   - Orders amount:
   2 Potentially abnormal values detected: 200000 & 1250000. Orders like that are highly unlikely even for a big web shop, and it seems like order 1250000 is responsible for the Revenue and Average check variation jump detected earlier. Rest of the orders are around the same variation limits.
   

   - Abnormal values detection and processing:
     - 95 & 99 percentiles for the number of orders are calculated. It shows that not more than 5% of users placed not more than 1 order, and not more than 1% of users placed not more than 2 orders. It is decided to acknowledge all users with more than 2 orders as abnormal values, and withdraw them.

     - 95 & 99 percentiles for the cost of orders are calculated. It shows that not more than 5% of users paid more than 26785, and not more than 1% of users paid not more than 53904 orders. It is decided to acknowledge all orders that cost  more than 53904 as abnormal values, and withdraw them.   
     
   
4) Statistical hypotheses testing results:  
   - The differences in Average orders number per user by groups (for row data) are statistically significant.
   - There are no statistically significant differences in Average check by groups (for row data).
   - The differences in Average orders number per user by groups (for cleared data) are statistically significant.
   - There are no statistically significant differences in Average check by groups (for cleared data).
   
**Thus it is decided to stop the test and state that Group B has won.**
