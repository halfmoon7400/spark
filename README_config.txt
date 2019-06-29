setup hosts for master, slave

abc@gram:~$ cat /etc/hosts
127.0.0.1	localhost
127.0.1.1	gram
127.0.0.1	master

127.0.0.2	slave1
127.0.0.3	slave2


etup .bashrc 

export SPARK_HOME=/home/abc/spark-2.3.1-bin-hadoop2.7
export PATH=$PATH:$SPARK_HOME/sbin


command -> start-all.sh  
your spark cluster in local work!
check by jps
