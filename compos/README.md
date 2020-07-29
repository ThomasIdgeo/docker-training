# Compositions to use with docker-compose

## Run a composition
To run a composition, run
```
docker-compose -f gs.yml up
```
Before running another, you should stop and clean the previous one, as they might conflict on volumes names.
To clean a composition, run
```
docker-compose -f gs.yml down -v
```
Replace gs.yml by the docker-compose file you want to run.
