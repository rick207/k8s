# k8s
kubectl rollout restart deployment hello-kubernetes
kubectl exec hello-kubernetes-7f47f457f4-vvswc -- wget -O - -q http://hello-kubernetes |grep hello-kubernetes

# tshark
tshark -i eth0 -Y "http" :         wireshark style
tshark -i eth0 -f "not port 22"  : libcap style
tshark --color -v -c2

# tcpdump
host
src
dst
net 8.8.8.8/24
port
portrange 21-23
src port 
icmp || tcp
less || greater || <=128  : packet size

"dst 8.8.8.8 or dst 8.8.4.4" and port 443
