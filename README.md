# East Van Euchre Club Euchre Analytics

East Van Euchre [analytics](analytics.html). [Code](analytics.Rmd) also available.

# Details

## Input
Reads in a CSV file (currently [Euchre Analytics December 3rd @ Anza - MASTER DATA.csv](Euchre Analytics December 3rd @ Anza - MASTER DATA.csv)) with tournament statistics and outputs. Relies on the following fields (as named):
- "Name"
- "Opponent 1"
- "Round"
- "Score: Hand XX", where XX is a number (1-12)
- "Called: Hand XX", where XX is a number (1-12): Should be "x" or "v"

## Output
The code prints a table of by-person summary statistics and a series of graphs.
