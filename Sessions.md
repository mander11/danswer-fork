## First session with Peter and Matt
 - https://github.com/danswer-ai/danswer/blob/main/CONTRIBUTING.md
 - https://docs.danswer.dev/system_overview
 - `docker compose -f docker-compose.dev.yml -p danswer-stack up -d index relational_db`
    - run from `danswer/deployment/docker_compose`

 - `python3 -m venv <name of venv>`

 - source <LOCATION_OF_VENV>/bin/activate
        - source .venv/python3.12.3/bin/activate

 - pip install -r backend/requirements/default.txt
 - pip install -r backend/requirements/dev.txt
 - pip install -r backend/requirements/model_server.txt

## Second session with Peter and Matt
- Matt teaches Peter the ins and outs of GUIs.
- A live view of the edits.
- Co-author investigation

## Third session
 - goal: get Danswer up and running
 - recreate initial error

## Fourth session 
 - Intro for Marc Matsen
 - Working on co-committing
 
## Fifth session
 - Fixed pip install
 - CPU architectures / GPU / graphical cards (nvidia)
 - co-committng
 $ git commit -m "Refactor usability tests.
>
>
Co-authored-by: NAME <NAME@@users.noreply.github.com>
Co-authored-by: ANOTHER-NAME <ANOTHER-NAME@EXAMPLE.COM>"

