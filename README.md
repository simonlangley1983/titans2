# Titans2 GitHub data

Upload the `data` folder to your GitHub repo called `titans1`.

## How to add fixtures

1. Add a new match file in `data/matches/`, for example:
   `2026-05-23-altrincham.json`

2. Copy the existing match JSON and change:
   - `matchId`
   - `fixture.date`
   - `fixture.displayDate`
   - `fixture.kickoff`
   - `fixture.meetTime`
   - `fixture.venue`
   - `fixture.address`
   - `teams.home`
   - `teams.away`

3. Add a matching entry to `data/fixtures.json`.

The fixture `id` must match the match JSON `matchId`.
The fixture `matchFile` must point to the file you created.
