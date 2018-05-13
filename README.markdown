A [Giter8][g8] template for Sample application to show joining of two kafka streams and writing it to topic.

#joined-kafka-streams-example

A basic application to show how we can join two kafka streams. We read data from different topics, join them and write it to final topic. It will also print joined stream data to console.

**Prerequisite:** If you do not have kafka in your system. Download it from here

**1) Extract the folder**

```tar -xzf kafka_2.11-1.1.0.tgz```

```cd kafka_2.11-1.1.0```

**2) Start the Zookeeper**

```bin/zookeeper-server-start.sh config/zookeeper.properties```

**3) Start the Kafka Server**

```bin/kafka-server-start.sh config/server.properties```

# How to set up ?

**1) Clone the application**

```sbt new mahesh2492/joined-kafka-streams-example.g8```

**2) Compile the application**

```sbt clean compile```

**3)Run the application**
   
   ```sbt run```
   
   It will show two options to run i.e StreamData, StartApplication
  
  **1) StreamData**
  
  **2) StartApplication**

Template license
----------------
Written in <2018> by <Mahesh Chand> <mahesh.kndpl@gmail.com>

To the extent possible under law, the author(s) have dedicated all copyright and related
and neighboring rights to this template to the public domain worldwide.
This template is distributed without any warranty. See <http://creativecommons.org/publicdomain/zero/1.0/>.

[g8]: http://www.foundweekends.org/giter8/
