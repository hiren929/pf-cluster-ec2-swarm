# Docker Swarm PingFederate Clustering Using Layered Server Profiles

This directory contains layered server profiles for:

* **base** - Foundational server profile for PingFederate
* **clustering** - Configuration for PF clustering (run.properties, tcp.xml)
* **license** - PF license file (expires Oct 25, 2019)
* **oauth** - include the OAuth playground war file for engine nodes
* **extensesions** - integration kits and connectors

The **swarm** directory includes scripts to assist in deploying and cleaning up the services

**Note**: Prior to launching the swarm cluster, please enter your AWS credentials and Git Token information within the **env_vars** file. Then run the `'source env_vars'` command to add those variables into your envionment

