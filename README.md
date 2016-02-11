Hazelcast-Yarn integration module


Instruction to start:


1) mvn clean install

2) Download Hazelcast distributive from: http://hazelcast.org/download/.

3) Start Hadoop file system

4)  Step to hazelcast-yarn.jar directory location.

Run: >> hadoop jar hazelcast-yarn.jar &lt;Path to hazelcast-yarn.jar> &lt;Path to Hazelcast ZIP-file> &lt;Hazelcast-Yarn property file>


Property file structure:


JVM_OPTS=&lt;Options of JVM >

CLUSTER_SIZE=&lt;Size of the cluster >

CPU_PER_NODE=&lt;Number of cpu core being used by Hazelcast node>

MEMORY_PER_NODE=&lt;Number of memory core being used by Hazelcast node>

HAZELCAST_WORK_DIR=&lt;Path to the Hazelcast work dir on HDFS>

HAZELCAST_CUSTOM_LIBS=&lt;Path to custom libs>
