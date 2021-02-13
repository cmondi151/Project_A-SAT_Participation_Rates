### Colin Mondi - SAT Participation Rates

### Problem Statement

The college board expected a significant increase in SAT participation rates due to the updated test format released in 2016, but in recent years the results were insufficient compared to expectations.

### Executive Summary

The College Board is interested in methods to increase SAT participation. To address this interest, we utilized data reflecting both SAT and ACT participation and test scores from 2017, 2018, and 2019 at the state level. The independent datasets were profiled, cleansed, and merged which produced a clean and functional piece of data to work with. From there, the data was analyzed and key trends/findings were recognized in order to develop recommendation(s) on how to increase participation rates. Additional outside research was conducted as well to answer any questions the given data could not provide.

The dataset is consistent with the observation that SAT participation rates are rising while ACT participation rates are falling. Furthermore, a strong negative correlation between SAT and ACT participation is found meaning most states have high participation rates in one test but low rates for the other. There's also a negative correlation between test participation and scores indicating higher participation rates result in lower average scores. A key finding was the large amount of states that have 100% participation; for 2019, there are 15 states with 100% participation for the ACT and 8 states with 100% participation for the SAT. Outside research discovered most of these states have a signed contract with the College Board (SAT) or ACT, and mandate all students to take that specific test.

It was concluded that the best solution to increase SAT participation is to focus on closing contracts with a given state's Education Board guaranteeing 100% participation by students, specifically targeting states who have a signed contract currently in place with the ACT. The negative correlation between SAT and ACT participation suggests the 15 states who enforce all students to take the ACT will likely continue to have lower SAT participation rates.

### Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|SAT|The name of a state|
|sat_par_2017|float|SAT|The SAT participation rate in 2017 for a given state|
|sat_rw_2017|float|SAT|The average student SAT score of the 'Evidence-Based Reading and Writing' section in 2017 for a given state|
|sat_math_2017|float|SAT|The average student SAT score of the 'Math' section in 2017 for a given state|
|sat_total_2017|float|SAT|The average student SAT score in 2017 for a given state|
|state|object|ACT|The name of a state|
|act_par_2017|float|ACT|The ACT participation rate in 2017 for a given state|
|act_eng_2017|float|ACT|The average student ACT score of the 'English' section in 2017 for a given state|
|act_math_2017|float|ACT|The average student ACT score of the 'Math' section in 2017 for a given state|
|act_read_2017|float|ACT|The average student ACT score of the 'Reading' section in 2017 for a given state|
|act_scie_2017|float|ACT|The average student ACT score of the 'Science' section in 2017 for a given state|
|act_comp_2017|float|ACT|The average student ACT score in 2017 for a given state|

### Conclusions and Recommendations

A key finding that stood out was the number of states that had 100% participation rates for either the SAT or ACT. The reasoning that every single student participates in at least one of these tests is due to the fact that these states force all students to take it. For example, we see Illinois participation rates have increased from 9% to 100% after the state's decision to drop the ACT and enforce the SAT; in 2016 a 59.7 million-dollar deal was made with the College Board.

Comparing 2019 versus 2017, 39 total states have shown a decrease in ACT participation by at least -1%. On the contrary, not a single state has had a decrease in their SAT participation rate by more than -1% (District of Columbia and Nevada are the highest at -.6%). Across the nation on average there's been a ~10% increase in SAT participation and a ~7% decrease in ACT participation since 2017. It's safe to say the SAT is gaining popularity in recent years. But there's still more states that have signed contracts with the ACT. Looking at the most recent year (2019) there are 15 states with 100% participation for ACT but only 8 states with 100% participation for the SAT.

In order to increase SAT participation rates, I recommend the College Board focuses on closing contracts with a given state's Education Board guaranteeing 100% participation by students. The states targeted should include either 1) states that have a signed contract currently with the ACT or 2) states that don't have a signed contract with either test but have high ACT participation rates and low SAT participation rates.

Supporting evidence includes a use case, specifically Illinois. There's been an increase in the number of students who attend a two-year or four-year college by at least ~1-2% on average, year over year. Although there can be multiple other factors involved, it can still be said there's a ~5% increase in the number of students that have gone to college since 2016, which is the same year Illinois switched from the ACT to SAT.

The negative correlation between SAT and ACT participation indicates that it is most likely a given state will continue to have low SAT participation rates if they have a signed contract with the ACT (100% participation). An obvious potential reason for this is if a student is provided one of the tests to take for free, they're less obligated to take the other one in which they would have to pay for. It is encouraged that students take both tests if they can, but if a student had to take one versus the other it is more likely they'll take the test that 1) they don't need to pay for and 2) is mandatory.