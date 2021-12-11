#KB-memory

This repo contains mongodb_log library updated from python2 to python3.

To record topics you need to have a running mongodb server on your machine and set port and host with rosparam


```
rosparam set mongodb_host <your_host> 
rosparam set mongodb_port <your_port>
```

To start recording you have to run    

`python3 src/mongodb_store/mongodb_log/scripts/mongodb_log.py /<topic_name>`

To replay all the recorded topics you have to run

`python3 src/mongodb_store/mongodb_store/scripts/mongodb_play.py`
