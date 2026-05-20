Contains post rule motif detection output dfs. Permutation output files were excluded from the repository because they exceed GitHub size limits

"Data_for_summary_heatmap.csv" represents the summary df of each response motif's execution speed compared to one another via linear modeling and earth movers distance
- Rule_1 and Rule_2 = which rule's response motifs were compared
- Rule_1_speed and Rule_2_speed = the mean motif execution speed for each rule
- EMD = the earth movers distance comparison between each rule's motif execution speed distribution
- p = the p value of the linear comparison between each rule's motif execution speed distribution
- Group_ID = Which social group the response motif execution speeds are being compared from (group 1 2 or 3)

"indiv_combined.csv" contains the count of how many times each individual executed each response motif
- actor_2 = the Color ID of each individual bird
- count = the count of motif executions for a particular rule
- Group = the particular rule of which response motif execution was quantified and which social group the individual who executed the motif belonged to (group 1 2 or 3)
- groupid = which social group the individual belonged to (group 1 2 or 3)
- rule = the particular rule of which response motif execution was quantified (Retailation, Pile-on, Pass-along, Opportunism, and Punishment)

"rules.length.data.frame.csv" contains the execution speed for each observed repsonse motif execution event 
- rule_type = the particular rule (Retailation, Pile-on, Pass-along, Opportunism, and Punishment)
- rule_time = the time in seconds in which a particular response motif instance took to be executed
- Group = which social group the individual belonged to (group 1 2 or 3)

"rules.length.data.frame_MM_2021.csv", "rules.length.data.frame_MM_2022G1.csv", and "rules.length.data.frame_MM_2022G1.csv" contains the execution speed for each observed repsonse motif execution event as well as information about the individuals involved
- actor, subject, actor_2, and subject_2 represent the individuals involved in the reponse motif sequence. actor is the initial aggressor and subject is the intial target of the aggression in the behavioral sequence. actor_2 represents the second aggressor in the behavioral chain and subject_2 the target of that second aggressor
- rule_type = the particular rule (Retailation, Pile-on, Pass-along, Opportunism, and Punishment)
- rule_time = the time in seconds in which a particular response motif instance took to be executed
- date_period = the date and observation session (1 or 2) of the motif execution instance
- Group = which social group the individual belonged to (group 1 2 or 3)

"tdr_count_rand_comb.csv" and "tdr_count_real_comb.csv" contain the overall counts of response motif execution events for each rule in each group. the real version contains the observed counts of motif execution while the rand version contains the number of response motif execution events when the behvaioral sequence is randomly permuted
- count_of_rule_follows = the number of times a aprticular rule's response motif was detected
- Group = the particular rule of which response motif execution was quantified and which social group this execution count corresponded to (group 1 2 or 3)
- groupid = which social group the individual belonged to (group 1 2 or 3)
- rule = the particular rule of which response motif execution was quantified (Retailation, Pile-on, Pass-along, Opportunism, and Punishment)
