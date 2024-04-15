
# Netflix Conductor Environment for Development

Repository contains the data nessecary to create a local Netflix Conductor environment for workflow, task, and event handler development. This is not intended to be a production quality install and there should not be assumption that data will be persisted between container restarts.

To bring up the environment you need:
 - Docker & Docker Compose (installed and running)
 - TCP/UDP Ports 8091 (conductor server), 8090 (conductor ui), 6379 (redis), 9200 & 9300 (elasticsearch) unused
 - At least 8 gigabytes of RAM free for use

Clone to your machine and change into the cloned directory. Open a command prompt in the directory and run 

    docker-compose up -d

Once all containers are running the UI and server are accessible using localhost links  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;UI :  &nbsp;&nbsp;http://localhost:8091  
Server :&nbsp;&nbsp; http://localhost:8090 


  
Have Fun!
