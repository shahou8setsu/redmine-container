# redmine-docker
redmie standalone  container using db with adminer &amp; fluentd 

## Pre 
1. docker is already installed. 
2. Ports are not used: 8000 (for redmine), 8080 (for adminer), 24224 (for fluentd). 
※ if those ports are used , you must change ports in docker-compose.yaml .
3. (optional) git is installed.


## Installation

1.<br/>
git clone https://github.com/shahou8setsu/redmine-docker.git <br/>

if git is not installed in your environment, 
download repository and unzip where you want.

2.<br/>
cd redmine-docker <br/>
3.<br/>
docker compose up -d
