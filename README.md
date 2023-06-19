
# Maternal Mental Health State Report Cards

The county-level data from [mmh-risk-factors](https://github.com/2020Mom/mmh-risk-factors) is aggregated at the state level in [csv/state_grades.csv](csv/state_grades.csv).  The following fields define the dataset:

<pre>   
    "STABRV"        State Abreviation
    "STATE"         Name of state
    "WPRFS"         Risk Factor Score for the State (weighted by # of births)
    "PROVIDERS"     (#) Certified PMH Providers
    "PRESCRIBERS"   (#) Licensed Prescribers
    "TOTPOP"        Population, total
    "FEMPOP"        Female Population, total
    "RPRAFEM"       (#) Female aged 15-44 years
    "BIRTHS_EST"    Estimate of Annual Births
    "RATIO"         (#) Certified PMH Providers per 1k Annual Births
    "REQPROV"       (#) Required Certified PMH Providers
    "COVERAGE"      (%) "PROVIDERS" / "REQPROV"
    "GAP"           (#) "REQPROV" - "PROVIDERS"
    "TOTAL"         Total Point Allocation for State Grades
    "P1"            Pillar 1 Point Allocation
    "P2"            Pillar 2 Point Allocation
    "P3"            Pillar 3 Point Allocation
    "P1g"           Pillar 1 Grade
    "P2g"           Pillar 2 Grade
    "P3g"           Pillar 3 Grade
</pre>