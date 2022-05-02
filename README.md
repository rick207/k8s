# k8s
kubectl rollout restart deployment hello-kubernetes </br>
kubectl exec hello-kubernetes-7f47f457f4-vvswc -- wget -O - -q http://hello-kubernetes |grep hello-kubernetes</br>
kubectl scale deploy hello-kubernetes --replicas=20 </br>

# tshark
tshark -i eth0 -Y "http" :         wireshark style</br>
tshark -i eth0 -f "not port 22"  : libcap style</br>
tshark --color -V -c2</br>

# tcpdump
host</br>
src</br>
dst</br>
net 8.8.8.8/24</br>
port</br>
portrange 21-23</br>
src port</br> 
icmp || tcp</br>
less || greater || <=128  : packet size</br>

"dst 8.8.8.8 or dst 8.8.4.4" and port 443</br>

# containerd
ctr</br>
crictl</br>
