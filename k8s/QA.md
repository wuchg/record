

# node的role标签 
kubectl label node node1 node-role.kubernetes.io/node=  
kubectl label node node1 node-role.kubernetes.io/node-  


for i in 1 2 3; do kubectl label node node$i node-role.kubernetes.io/node=; done
