Hazelcast-Yarn integration module


Instruction to start:


1) mvn clean install


2) Download Hazelcast distributive from: http://hazelcast.org/download/ to <HAZELCAST_DISTRIBUTIVE> directory


3) Copy target/hazelcast-yarn.jar into <HAZELCAST_DISTIBUTIVE>/bin


4) Start Hadoop file system


5) Run: >> hadoop jar hazelcast-yarn.jar <Path to hazelcast-yarn.jar> <Path to Hazelcast ZIP fix> hazelcast-yarn.properties


Property file structure:


JVM_OPTS=<Options of JVM>

CLUSTER_SIZE=<Size of the cluster>

CPU_PER_NODE=<Number of cpu core being used by Hazelcast node>

MEMORY_PER_NODE=<Number of memory core being used by Hazelcast node>

HAZELCAST_WORK_DIR=<Path to the Hazelcast work dir on HDFS>

HAZELCAST_CUSTOM_LIBS=<Path to custom libs>
