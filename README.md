# East Van Euchre Club Euchre Analytics

East Van Euchre [analytics](analytics.html). [Code](analytics.Rmd) also available.

# Details

Reads in a CSV file with Euchre tournament data and outputs by-person summary statistics and summary graphs. Relies on the following fields (as named):
- "Name"
- "Opponent 1"
- "Round"
- "Score: Hand XX", where XX is a number (1-12)
- "Called: Hand XX", where XX is a number (1-12): Should be "x" or "v"

Saves the following statistics for each person:
- Points for
- Points against
- Calls
- We euchred
- We got euchred
- I got euchred
- Loner tries
- Loner wins
