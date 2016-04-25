#A few fixes

Routes:

POST /institution/:id - updates ID with hardcoded working_hours param
POST /event/:id - same but with start_time
use GET /institution & /event for ID's

GET /event/name lists names and start_time as a pretty sting (N.B: 'pretty' is subjective)

And ofc it uses mongolabs db for heroku.
