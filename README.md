# TP2 – UDP client-server with Java sockets

Compile: `javac *.java`

| Class | Steps | Run |
|---|---|---|
| UDPServer | 1, 2, 5 | `java UDPServer 8080 [bufferSize]` |
| UDPClient | 3, 4, 17, 18 | `java UDPClient localhost 8080 [--broadcast]` |
| SizeTester | 6, 7 | `java SizeTester localhost 8080` |
| ReliableUDPServer | 11, 12, 14 | `java ReliableUDPServer 8080 [dropRate]` |
| ReliableUDPClient | 11, 12, 14 | `java ReliableUDPClient localhost 8080 [timeoutMs] [maxAttempts]` |
| BurstSender / BurstReceiver | 13 | `java BurstReceiver 8080 [sleepMs]` / `java BurstSender localhost 8080 10000` |
| MulticastReceiver | 16, 17 | `java MulticastReceiver 239.0.0.1 8888 eth0` |
