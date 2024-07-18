# my-new-repository
a repository for learning data engineering

## sample voter query

sample code:
``` sql
select voter_id, voter_first_name || " " || voter_last_name as voter_full_name
from voters
where voter_age < 35
limit 100
