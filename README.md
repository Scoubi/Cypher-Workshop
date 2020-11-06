# Cypher for Defenders: Leveraging Bloodhound Data Beyond the UI

## Before the Workshop

### D/L the deck
[Cypher For Defender](BTV%20-%20Cypher%20For%20Defenders.zip)  

The password will be provided at the begining of the Workshop

### Install Java 11 jdk
Option 1 from Oracle : https://www.oracle.com/java/technologies/javase-jdk11-downloads.html (need registration)  
Option 2 from OpenJDK : https://jdk.java.net/java-se-ri/11  
  
On *Debian Based Linux* you can use `sudo apt install openjdk-11-jre-headless`  
  
On *OSX*, if you have `brew` installed, you can use 
```
brew install openjdk@11 
echo export JAVA_HOME=/usr/local/opt/openjdk@11 >>~/.bash_profile && source  ~/.bash_profile
```

### Install neo4j 4.0.7 community edition
- Linux/Mac : https://go.neo4j.com/download-thanks.html?edition=community&release=4.0.7&flavour=unix&_ga=2.97133727.1263001926.1595785758-1639470248.1595785755  
- Windows : https://go.neo4j.com/download-thanks.html?edition=community&release=4.0.7&flavour=winzip&_ga=2.125011978.1263001926.1595785758-1639470248.1595785755  
- Extract the archive
- Go in neo4j directory `cd neo4j-community-4.0.7`
- Delete the `data` folder  
- Download this [data.tgz](data.tgz) 
- Extract data.tgz in `./neo4j-community-4.0.7`  
```tar -zxf data.tgz ./```
- Start neo4j `cd bin` then `./neo4j console` in Linux/Mac or `neo4j console` in Windows
- Using your browser, connect to the console http://localhost:7474  
User: **neo4j**  
Pass: **neo4jj**  
**Note: You can change the password, but _do not loose it_, you will need it for the workshop**

## Optional
### Install BloodHound 3.0.5
Download BloodHound : https://github.com/BloodHoundAD/BloodHound/releases/tag/3.0.5  
It will help with one or two lab questions
