Java-Sockets_TCP-UDP
====================

Simple client-server program demonstrating tcp and udp socket communication.

How to Build:
    $make

How to Run on Server:
    $java server

How To Run on Client:
    $java client <server_address> <port_listed_by_server> <message>

Example:
    $java server
    Listening on port 12345

    $java client localhost 12345 "Hello World"
    ...
    Received reply from server: dlroW olleH

Tested Using:
    GNU Make 3.81
    javac 1.6.0_27
    java version "1.6.0_27"