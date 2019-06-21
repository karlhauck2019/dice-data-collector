# dice-data-collector

DICE Data Collector Container

This container uses Alpine Linux with Python 3.7.

Current Specs are Flask App running natively.

To get started:

1. Clone the Repo
2. CD into the directory and run docker-compose up --build

or download the OVA from: 

TODOs

# Quick

-~~Change web layer to Gunicorn~~

-~~Add timestamp to filename~~

-~~Add property collection for other object types~~

# Not quick

-Add error checking (Any error comes up as Error 500 currently)

-~~Add loading screen while appliance is collecting data~~

-Replicate TDM functionality for vCenter

-Investigate collecting telegraf metrics (Tom)

-~~Investigate pushing JSON data to API instead of download~~

-Investigate using appliance to push vrops to vCenter (Tom)

# Adds by the team


