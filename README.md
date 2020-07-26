# Cypher for Defenders: Leveraging Bloodhound Data Beyond the UI

## Before the Workshop

### D/L the deck
This file
The password will be provided at the begining of the Workshop

### Install Java 11 jdk
### Install neo4j 4.0.7 community edition
- Linux/Mac : https://go.neo4j.com/download-thanks.html?edition=community&release=4.0.7&flavour=unix&_ga=2.97133727.1263001926.1595785758-1639470248.1595785755  
- Windows : https://go.neo4j.com/download-thanks.html?edition=community&release=4.0.7&flavour=winzip&_ga=2.125011978.1263001926.1595785758-1639470248.1595785755  
- Extract the archive
- Go in neo4j directory `cd neo4j-community-4.0.7`
- Delete the `data` folder  
- Download this data.tgz from this repo 
- Extract data.tgz in `./neo4j-community-4.0.7`
- Start neo4j `cd bin` then `./neo4j console` in Linux/Mac or `neo4j console` in Windows
- Using your browser, connect to the console http://localhost:7474
User: *neo4j*  
Pass: *neo4jj*  
***Note: You can change the password, but do not loose it, you will need it for the workshop***

## Optional
### Install BloodHound 3.0.5
Download BloodHound : https://github.com/BloodHoundAD/BloodHound/releases/download/3.0.5/BloodHound-linux-x64.zip
