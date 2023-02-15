# Netflix Conductor Environment for Development

Repository contains the data nessecary to create a Netflix Conductor environment for workflow, task, and event handler development. This is not intended to be a production quality install. No data is persisted from reboot to reboot.

To bring up the environment you need:
-Docker & Docker Compose (installed and running)
-TCP/UDP Ports 8080 (conductor server), 5000 (conductor ui), 6379 (redis), 9200 & 9300 (elasticsearch) unused
-At least 8 gigabytes of RAM free for use


