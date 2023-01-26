
## League Scheduler

Notebook for generating a schedule for a league

### Usage
Run `jupyter lab` to launch the notebook

Functions provided to generate a season, inputs are number_of_teams (ideally this is an even number) and number_of_weeks (must be less than or equal to number of teams).
The code will ensure every team plays each other no more than once, and that each time is the home team (first in a pairing) for half of its games, assuming there are an even number of games in the season.

A helper function is provided to extract the schedule of any invidual team from the season schedule.
