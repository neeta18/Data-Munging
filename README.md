# Data-Munging
1. Create the following columns, from the ​Ad_unit_name column in the dataset: a. amp_or_non_amp b. story c. position    Example: 1.1 CarToq_ad_first_story_pos_top (122380182)        story = first, position = top, Nonamp  1.2 amp-cartoq-bottom (21684306640)       story = None, position = bottom, Amp      2. Use the ​DAY​ column to map the day's name in the week. Example: Map 1 -> Monday up to 7 -> Sunday   3. Here, eCPM for some data is incorrect, Merge ​Actual_eCPM         data from the other sheet ( Actual_eCPM.csv ) such that new           column for ​Actual_eCPM is created. Create another column        Actual_Revenue​ which is defined as:  Actual_Revenue = Total Impression * Actual_eCPM    (if not provided, take the given revenue in the dataset as           Actual_Revenue to fill the remaining ​Actual_Revenue column       data with it.)     After completing the above 3 tasks save the results as          DFP_solution.csv    4. Identify the best-performing Ad position in terms of eCPM and          revenue, separately in amp and non-amp case. 
