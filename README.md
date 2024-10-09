# Problem Statement


# Data Dictionary
- `duration`: Represents the length of time a specific network connection was active for.
- `protocoltype`: Represents the specific commumication protocol used in each connection.
- `service`: Represents the destination network service used in a connection.
- `flag`: Represents the status of a connection as either "Normal" or "Error".
- `srcbytes`: Represents the number of data bytes transferred from the source to the destination in a single connection.
- `dstbytes`: Represents the number of data bytes transferred from the destination to the source in a single connection.
- `land`: Indicates whether the source and destination IP addresses and port numbers are equal (1 if equal, 0 otherwise).
- `wrongfragment`: Represents the total number of wrong fragments received in a connection.
- `urgent`: Represents the number of urgent packets in this connection. Urgent packets are packets with the urgent bit activated.
- `hot`: Represents the number of "hot" indicators in the content, such as entering a system directory, creating programs, and executing programs.
- `numfailedlogins`: Represents the count of failed login attempts.
- `loggedin`: Indicates whether a successful login occurred in a connection (1 if successfully logged in, 0 otherwise).
- `numcompromised`: Represents the number of "compromised" conditions in a connection.
- `rootshell`: Indicates whether root shell access was obtained in a connection (1 if yes, 0 otherwise).
- `suattempted`: Indicates whether the "su root" command was attempted or used in a connection (1 if yes, 0 otherwise).
- `numroot`: Represents the count of root operations performed in a connection.
- `numfilecreations`: Represents the count of file creation operations in a connection.
- `numshell`: Represents the count of shell prompts in a connection.
- `numaccessfile`: Represents the count of operations on access control files in a connection.
- `numoutboundcmds`: Represents the count of outbound commands in an FTP session.
- `ishostlogin`: Indicates whether a login belongs to the host list i.e., root or admin (1 if yes, 0 otherwise).
- `isguestlogin`: Indicates whether a login belongs to the guest list (1 if yes, 0 otherwise).
- `count`: Represents the number of connections to the same destination host as the current connection in the past 2 seconds.
- `srvcount`: Represents the number of connections to the same service as the current connection in the past 2 seconds.
- `serrorrate`: Represents the percentage of connections that have activated the flag s0, s1, s2, or s3, among the connections aggregated in `count`.
- `srvserrorrate`: Represents the percentage of connections that have activated the flag s0, s1, s2, or s3, among the connections aggregated in `srv_count`.
- `rerrorrate`: Represents the percentage of connections that have activated the flag REJ, among the connections aggregated in `count`.
- `srvserrorrate`: Represents the percentage connections that have activated the flag REJ, among the connections aggregated in `srv_count`.
- `samesrvrate`: Represents the percentage of connections that were to the same service, among the connections aggregated in `count`.
- `diffsrvrate`: Represents the percentage of connections that were to different services, among the connections aggregated in `count`.
- `srvdiffhostrate`: Represents the percentage of connections that were to different destination machines, among the connections aggregated in `srv_count`.
- `dsthostcount`: Represents the number of connections having the same destination host IP address.
- `dsthostsrvcount`: Represents the number of connections having the same destination port number.
- `dsthostsamesrvrate`: Represents the percentage of connections that were to the same service, among the connections aggregated in `dsthostcount`.
- `dsthostdiffsrvrate`: Represents the percentage of connections that were to different services, among the connections aggregated in `dsthostcount`.
- `dsthostsamesrcportrate`: Represents the percentage connections that were to the same source port, among the connections aggregated in `dsthostsrvcount`.
- `dsthostsrvdiffhostrate`: Represents the percentage connections that were to different destination machines, among the connections aggregated in `dsthostsrvcount`.
- `dsthostserrorrate`: Represents the percentage connections that have activated the flag s0, s1, s2, or s3, among the connections aggregated in `dsthostcount`.
- `dsthostsrvserrorrate`: Represents the percentage connections that have activated the flag s0, s1, s2, or s3, among the connections aggregated in `dsthostsrvcount`.
- `dsthostrerrorrate`: Represents the percentage connections that have activated the flag REJ, among the connections aggregated in `dsthostcount`.
- `dsthostsrvrerrorrate`: Represents the percentage connections that have activated the flag REJ, among the connections aggregated in `dsthostsrvcount`.


# Tableau Dashboard

Link: 

### Steps to reproduce the Tableau dashboard