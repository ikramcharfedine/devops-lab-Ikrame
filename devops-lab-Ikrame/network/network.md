## Network Specification
## Rules 
-the frontend and backend networks must not oberlap
the database is connected to the backend network only .
| legacy | 192.168.0.0/16 | 192.168.0.1 | 65534 | old network |
| frontend | 172.20.0.0/24 | 172.20.0.1 | 254 | web tier |
| backend | 172.22.0.0/24 | 172.22.0.1 | 254 | database tier |
