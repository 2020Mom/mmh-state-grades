
# Maternal Mental Health State Report Cards

## About this repository

The repository is distributed under Creative Commons License 'CC BY-SA 4.0'.  Users are free to copy and redistribute the material in any medium or format, to remix, transform, and build upon the material for any purpose, even commercially, subject to the following terms:

### Attribution

 You must give appropriate credit to The Policy Center for Maternal Mental Health, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the Policy Center endorses you or your use. 

### ShareAlike

If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.

# state_grades.csv

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