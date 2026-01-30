### The Mental Model: "The Path of the Packet"

#### When a user connects to http://<VM-IP>:8080, a TCP packet travels through these gates:
- The Internet (reaches your VM)
- The Firewall (Linux Kernel/AWS Security Group)
- The Socket (Is Nginx actually listening?)
- The Application (Nginx itself)

