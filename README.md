# BetaCrew-Assignment

# Requirements
Please ensure that you have Node.js version 16.17.0 or higher installed on your system.

Clone the repo into your machine.

# Instructions to run Server
1. Navigate to BetaCrew-Assignment/betacrew_exchange_server folder in command prompt or any terminal
2. Run the command "node main.js" to start the BetaCrew exchange server.

# Instructions to run Client
1. In another terminal / command prompt window, Navigate to BetaCrew-Assignment/betacrew_exchange_client folder.
2. Run the command "node client.js" to start the BetaCrew exchange client. 
3. Note: When client is running, the last packet with sequence number 14 might get missed though we assume that the last packet is never missed. So we need to run client.js some multiple times to collect all 14 packets.
4. The output file, packets.json will be generated in the same folder (betacrew_exchange_client)
5. Open the json file to view all the received packets.
