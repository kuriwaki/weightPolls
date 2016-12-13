This repo is for building a app that dynamically estimates election day turnout based on different sets of turnout expectations. The outline of the process:

# Take in poll data
which we assume is unrepresentative of the voting population.

# Take in historical turnout data
which tells us how big the subgroups in the survey are, and how much of them turned out in a past election

# Combine them to estimate voteshare and turnout
most simply by linear combination, with the option of more complex models.

# Translate specific poll numbers to vote counts
showing that a `X` percentage change in `s` subgroup will translate to `v` changes in votes, and a different subgroup `t` will have to move their votes to `Y` percentage points to compensate for that change.  
