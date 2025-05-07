open 3 terminals

In first terminal-
1. javac *.java
2. rmic AddServerImpl
3. rmiregistry

In second terminal-
1. java AddServer

In third terminal-
1. java AddClient 127.0.0.1 8 9
