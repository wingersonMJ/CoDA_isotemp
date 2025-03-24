# CoDA_isotemp

![Under Construction](figs/whoops.jpg)





---

limited to first 14-days of data 
- 1972 days of data for 144 subjects

filtered out days where HR-calculated "wear time" is <20% (see figures in code for some justification, but really just selected based on what seemed good)
- 1632 days for 139 subjects (aka 5 subjects had no valid data at all)

If less than 7 days of data remaining, then removed from analysis
- 1558 days for 123 subjects

Remove missing for target (time to sx resolution)
- 102 subjects now

Mean impute for 3 missing pcsi, mode impute for 1 missing sex
