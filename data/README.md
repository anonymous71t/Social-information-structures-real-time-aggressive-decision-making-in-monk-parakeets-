This folder contains the input data for the rule motif detection code.
 
"2021_interactions_raw.csv",  2022_interactions_group1.csv, and 2022_interactions_group2.csv contains the raw interaction data of the birds in the social groups.
- orderkey = key
- sessionKEY = contains the date and observer
- session_start_timeStamp = the start time of data collection that day
- date = observation date
- full_time = observation time
- time = observation time (only hours and minutes)
- actor = individual doing the behavior
- subject = individual receiving the behavior
- behavior = behavior
- unknown = description (affiliative or agonistic) of unknown behavior
- flight = description (for example "some" of how many individuals were in flight during flight behavior
- comment = additional notes

2021_birdIDs.csv and 2022_birdIDs.csv contain the individual information for each monk parakeet used in the experiment
- bandID = unique band number
- sex = male or female
- population = whether the birds were among the new captives for the experiment ((all birds used in this study were new captives
- year captured = year individual was captured
- year death = year individual passed away
- site captured = which site the bird was captured (birds were trapped in 4 different feral populations)
- cage_id_2021 and 2022 = cage id of individuals during the 2021 and 2022 field seasons
- mark_id... = unique color combination used for individual identification (mark_id3 represents the color combinations used in the 2021 experiments and mark_id22 for the 2022 experiments)
- experimental_group_2022 = which social group an individual belonged to (group 1_west = 2022G1 or 2_east = 2022G2)
- comments = additional notes

MOPA_bin_rank_2021_test.csv, MOPA_bin_rank_2022G1.csv, and MOPA_bin_rank_2022G2.csv contain the dominance information of the birds in each social group
- bin = the number of 3-4 day observation periods
- id = unique color code combination of each bird
- dom_ec = eigenvector centrality
- between = betweenness centrality
- rank = ordinal rank measure
- power = dominance rank score where a power value closer to 1 indicates a higher-ranked)

2021_3daybins.csv and 2022_3daybins.csv contain the date and rank assessment period for each experimental period during each year's field season
- date = the date in the form of year-month-day
- capture = the number of the capture events
- total_obs_day = the total number of observation days
- perturbation = the numbered experimental trial (not applicable in this study)
- type = the perturbation type (removal or reintroduction) (not applicable in this study)
- experiment = the perturbation type (removal or reintroduction) (not applicable in this study)
- bin_all = number label for the 3-days to obtain rank for the whole field season
- n_birds = total number of birds in the group
- capture = the number of the capture events
- capture_date = date of capture events
- focal_bird = describes which rank typed bird in the group to perturb (not applicable in this study)
- dompattern_focal = rank assessment periods for each focal rank
- bin = number label for the 3-day observation period used to obtain rank for the experiment
