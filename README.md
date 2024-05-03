# redmine-docker(postgres)
redmine standalone  container using postgres with adminer &amp; fluentd 

## Pre 
1. docker is already installed. 
2. These Ports are not used:<br/>
   8000 & 3000 (for local & redmine) <br/>
   5432 (for postgres) <br/>
   8080 (for adminer) <br/>
   24224 (for fluentd). <br/>
※ if those ports are used , you must change ports in docker-compose.yaml .
4. (optional) git is installed.
5. (optional) .env file are modified for your environment.


## Installation

1.<br/>
git clone https://github.com/shahou8setsu/redmine-docker.git <br/>

if git is not installed in your environment, <br/>
download repository and unzip where you want.

2.<br/>
cd redmine-docker <br/>
3.<br/>
docker compose up -d

### ※不具合、不明点などあればIssueにいただけると幸い<br/>
