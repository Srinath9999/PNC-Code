Example Voting App
=========

A simple distributed application running across multiple Docker containers.

Getting started
---------------

To Start:
ansible-playbook   docker_voting.yml "  action="start"  -vvv

To Stop:
ansible-playbook   docker_voting.yml "  action="stop"  -vvv

To start with Docker:

## Linux Containers

The Linux stack uses Python, Node.js, .NET Core (or optionally Java), with Redis for messaging and Postgres for storage.

Run in this directory:
```
docker-compose up
```
The app will be running at [http://localhost:5000](http://localhost:5000), and the results will be at [http://localhost:5001](http://localhost:5001).

