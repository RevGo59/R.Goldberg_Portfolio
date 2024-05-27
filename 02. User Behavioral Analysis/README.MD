**Context:**
Some UI updates were proposed for groceries sales Mobile App, but managers are concerned that those updates will have a negative impact on users behaviour. As a part of A/A/B test, users from control groups 246 & 247 kept interacting with the App without UI updates, users from group 248 experienced those updates.

**Project goal:**
Run User Behavioral Analysis for groceries sales Mobile App. Analyse A/A/B test results, state conclusions and recommendations.

**Conclusions:**
1) Data is processed and explored.

2) Events tunnel analysis:
   - Estimated events order is defined: MainScreenAppear - OffersScreenAppear - CartScreenAppear -PaymentScreenSuccessful. 
   - 38% users vanish in going from MainScreenAppear to OffersScreenAppear. Reasons to that need to be analysed (technical error/UI problem) and adequate measures need to be taken.
   - In going from first to the last tunnel event remain only 47% users. The main reason for that is the loss in going from MainScreenAppear to OffersScreenAppear. But also the reason why only 80% users remain after going from CartScreenAppear to PaymentScreenSuccessful needs to be analysed (pricing/assortment/technical error).
  
3) A/A/B test:
   - А/А test:
        - Ratio for groups 246 & 247 is 1.15 %.
        - No user behavioral differences detected.
        - Grouping was performed correctly.
        - Conditions for A/A test are fulfilled, thus A/A/B test results may be considered as accurate.\
   - A/A/B test: no grounds to consider ratio for groups statistically significant discovered for:
        - Groups 246 & 248.
        - Groups 247 & 248.
        - Combined control group (246&247) & 248.

**Users behaviour does not depend on suggested UI updates, thus concerns on those updates should be considered as groundless.** 
