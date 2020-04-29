# docker-git-website

Runs a git cloned static website insite nginx.

## Usage

    docker run -p 80:80 -e GITADDR="https://github.com/diceone/dbuzz.git" diceone/git:latest
