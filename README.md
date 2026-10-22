For metalLB the loadbalancer IP address mut be configured on the k8s node to be able to open it from the Internet
  e.g. sudo ip addr add 128.110.223.38/21 dev eno1
  which node? check the metalLB speaker, the last line in the desc.:
  kubectl describe svc http=demo-loadbalancer
