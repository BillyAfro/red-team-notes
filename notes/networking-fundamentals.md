# OSI Model Flow

Sending data: 7 → 1  
Receiving data: 1 → 7  
Direction depends on communication

## Layers:

7. Application → user/program (Chrome, apps) -> Data
6. Presentation → format + encryption (encode/decode) -> Data
5. Session → manages connection (start/keep/end session) -> Data
4. Transport → TCP / UDP (reliability, segmentation) -> Data Segments/Datagrams 
3. Network → IP + routing (find path) -> Data Packets 
2. Data Link → MAC address (local delivery) -> Data Frames
1. Physical → cable + signal (bits) -> Data streams in bits
