= Usage instructions:
There are 3 versions with increasing levels of data reliability and throughput.

== 1. Compile both the sender and receiver files: 
    $ javac Receiver3.java
    $ javac Sender3.java

== 2. Run the receiver side:

    $ java Receiver3 <Port> <Filename>
    
Where <Port> is the port number used for receiving from the sender and <Filename> is the name or filepath used to store the file on local disk.

An example would be:    
    $ java Receiver3 54321 receivedfile.jpg

== 3. Run the sender side:

    $ java Sender3 <IPaddress> <Port> <Filename>

Where <IPaddress> is the address at which to send to, <Port> is the port number used by the corresponding receiver and <Filename> is the file or filepath of the file to transfer from local disk.

An example would be:
    $ java Sender3 localhost 54321 filetosend.jpg