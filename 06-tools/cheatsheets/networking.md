# Networking cheat sheet

Use these on your own machines and lab networks.

| Task | Command |
|---|---|
| Interfaces and addresses | `ip -br addr` |
| Routing table | `ip route` |
| Open sockets and listening ports | `ss -tulpn` |
| DNS lookup | `dig example.com +short` |
| Trace path | `tracepath example.com` / `mtr example.com` |
| Capture packets | `sudo tcpdump -i eth0 -w cap.pcap 'tcp port 443'` |
| Read a capture | `tcpdump -nr cap.pcap \| head` |
| Throughput test | `iperf3 -s` (server) · `iperf3 -c <server>` (client) |
| Add 100 ms delay, 1% loss | `sudo tc qdisc add dev eth0 root netem delay 100ms loss 1%` |
| Remove netem | `sudo tc qdisc del dev eth0 root` |
| Scan your own lab host | `nmap -sV <lab-ip>` |
