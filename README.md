sudo tcpdump -i eth0
sudo tcpdump -i eth0 -vn
sudo tcpdump -i eth0 -vn host 8.8.8.8 and port 53 &
jobs -l
dig @8.8.8.8 A example.com
fg % [job-id]
sudo tcpdump -i eth0 port 80 -w http.pcap &
jobs -l
curl example.com
fg % [job-id]
tcpdump -r http.pcap -nv

