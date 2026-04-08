# SmartParcel - Socket Programming Assignment

**Name:** Oswald Pereira  
**Student ID:** 20240005935 
**CUD Email:** 20240005935@students.cud.ac.ae

## How to Run

### Task 1: TCP Server
```bash
python3 server.py
```

### Task 2: TCP Client
```bash
python3 client.py
```

### Task 3: Multi-threaded Server & Load Test
```bash
# Start the server
python3 threaded_server.py

# In another terminal, run the load test
python3 load_test.py
```

### Task 4: UDP Health Check
```bash
# Make sure threaded_server.py is running first
python3 udp_ping.py
```

## Files Included
- `server.py` - Single-threaded TCP server
- `client.py` - TCP client demo
- `threaded_server.py` - Multi-threaded TCP + UDP server
- `load_test.py` - Tests 5 concurrent clients
- `udp_ping.py` - UDP health check client
- `report.pdf` - Architecture diagram and client-server explanation

## Requirements
- Python 3.x
- No external libraries needed (only standard library)
