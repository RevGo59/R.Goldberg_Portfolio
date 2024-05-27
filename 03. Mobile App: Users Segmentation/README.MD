**Context**:
"Unnecessaries" is an App for viewing and posting local advertisements. "Unnecessaries: Someone needs your unnessesary stuff!"

**Project Goal**:
Identify User groups based on their behavior and state recommendations to ensure Conversion in the target event growth.

**Conclusions:**
1) Data is processed and explored:
   - No gaps detected;
   - No duplicates detected;
   - Datatype coorrected;
   - Tables named properly;
   - Sources table & dataset log are merged;
   - Timeframe 7th October - 3rd November.
        
2) Evaluated metrics:
   - Retention rate;
   - Time spent in the App;
   - Events frequency;
   - Conversion to target event.

Time spent in the App is considered to be the base for users segmentation.

3) Data is divided into 4 groups by users, based on time they spent in the App in such a way, that the number of unique users in each group is approximately equal.

4) Retention Rate for each group is evaluated. Users that spent the most time in the App proved to show the best Retention over the timeframe.


5) Conversion to target event for each group is evaluated. Users that spent the most time in the App proved to show the best Conversion over the timeframe.


6) Groups defined based on the time spent in the App metric seem to show significant differences by both Retention Rate and Conversion.

7) Statistical hypotheses testing results:

    - Users from source "yandex" perform statistically significant lower Conversion Rate in the target event than users from the "google" source.     
    - Users performed "tips_click" event perform statistically significant lower Conversion Rate in the target event than users performed "search" event.

**Recommendations:**
Taking into consideration that:
   a) "Tips_cklick" event seems to be one of the least frequent, however Conversion in the target event is significantly higher.\
   b)  "Search" event is in the top-3 most frequent events, however the Conversion in the target event is significantly lower.

Following recommendations are proposed:
1) It seems like users are not quite interested in the recommended ads. However, if they meet the eye, the Conversion in the target event is significantly higher.
Reasons for that need to be analysed more thoroughly. Since "tips_show" is the most frequent event, it is recommended ads generation algorithm that should be revised and improved.


2) Users do use search quite frequently, however the Conversion in the target event is significantly lower. Thus the search results do not meet users' needs. Users that spend more time in the App tend to lash out more time for search in particular and, as a result, show higher Conversion in the target event.
Reasons to that need to be analysed more thoroughly: search parameters should be inspected and improved. In addition it seems that search history should be used for recommended ads generation.
