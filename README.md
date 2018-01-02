# HarakaMQ-Benchmark
A small benchmark for HarakaMQ

Step 1.
-----
To run the benchmark dotnet core 2.0 needs to be installed and running.

Step 2.
-----
# To run the Client-Server test on your local machine.

> goto "ClientServer/Broker" and run "Run.bat"

> goto "ClientServer/Receiver" and run "Run.bat"

> goto "ClientServer/Sender" and run "Run.bat"

> All time obervations are stored at "ClientServerSetup/Receiver/results.txt"

# To run the Cluster test on your local machine.

> goto "Cluster/Broker_C" and run "Run.bat"

> goto "Cluster/Broker_B" and run "Run.bat"

> goto "Cluster/Broker_Primary" and run "Run.bat"

> goto "Cluster/Receiver" and run "Run.bat"

> goto "Cluster/Sender" and run "Run.bat"

> All time obervations are stored at "Cluster/Receiver/results.txt"


# To run the Connection disruption test your need to be able to disconnect the running instances from each other.

> goto "Connection Disruption/Broker" and run "Run.bat"

> goto "Connection Disruption/Receiver" and run "Run.bat"

> goto "Connection Disruption/Sender" and run "Run.bat"

> Disconnect for example the sender after 2 messages has been received by the receiver

> Connect the diconnected device again after 10 seconds, and shortly after all messages should have been received in the correct order.
