$env:HTTP_PORT=3001; $env:P2P_PORT=6001; npm start
$env:HTTP_PORT=3002; $env:P2P_PORT=6002; $env:PEERS="ws://192.168.1.5:6001"; npm start
http://localhost:3001/blocks
http://localhost:3002/blocks
