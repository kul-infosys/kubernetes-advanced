## Day 2 & 3
```
   54  kubectl get nodes 
   55  ls -ltr /etc/kubernetes/manifests/
   56  clear 
   57  kubectl apply -f https://docs.projectcalico.org/v3.11/manifests/calico.yaml
   58  kubectl get nodes 
   59  clear 
   60  kubectl get nodes 
   61  history 
   62  kubectl get nodes 
   63  clear 
   64  cat /home/ubuntu/.kube/config 
   65  clear
   66  kubectl get pods -o wide -A
   67  sudo kubeadm delete
   68  sudo kubeadm destroy
   69  sudo kubeadm --help
   70  sudo kubeadm reset
   71  rm -rf /home/ubuntu/.kube/config 
   72  clear 
   73  sudo kubeadm init --apiserver-advertise-address=192.168.4.87 --pod-network-cidr=10.244.0.0/16
   74  kubectl get nodes 
   75  mkdir -p $HOME/.kube
   76  kubectl get nodes 
   77  clear 
   78  kubectl get pods -o wide -A
   79  kubectl create  deployment test --image httpd
   80  kubectl get pods
   81  kubectl describe pod test-f8f5df87b-82s5m 
   82  history 
   83  kubectl delete -f https://docs.projectcalico.org/v3.11/manifests/calico.yaml
   84  history 
   85  kubectl apply -f https://docs.projectcalico.org/v3.11/manifests/calico.yaml
   86  kubectl get pods -A | grep -i calico
   87  kubectl get pods 
   88  kubectl get pods -o wide
   89  kubectl get pods 
   90  kubectl get ns
   91  htop
   92  exit
   93  kubectl get nodes 
   94  kubectl get pods 
   95  kubectl delete deploy test
   96  clear 
   97  kubectl get nodes 
   98  clear 
   99  kubectl get deployment 
  100  kubectl edit deployment vote
  101  kubectl delete deployment --all
  102  kubectl get deployment 
  103  pwd
  104  git clone Not Attended
  105  Not Attended
  106  clear 
  107  kubectl api-resources
  108  mkdir kubernetes
  109  cd kubernetes/
  110  vi deployment.yml
  111  cd ..
  112  git clone https://github.com/kul-infosys/kubernetes-advanced.git
  113  cd kubernetes-advanced/
  114  ll
  115  git pull origin main
  116  clear 
  117  cat deployment.yml 
  118  kubectl apply -f deployment.yml 
  119  clear 
  120  git pull origin main
  121  kubectl apply -f deployment.yml 
  122  kubectl get pods
  123  kubectl get deployment.yml 
  124  kubectl get deployment
  125  kubectl describe pod kul
  126  kubectl get all
  127  kubectl delete -f deployment.yml 
  128  kubectl get all
  129  kubectl delete svc --all
  130  kubectl get all
  131  clear 
  132  kubectl apply -f deployment.yml 
  133  kubectl get all
  134  clear 
  135  kubectl get all --show-labels
  136  git pull origin main
  137  kubectl apply -f deployment.yml 
  138  kubectl get all --show-labels
  139  kubectl get pods
  140  kubectl get pods -o wide
  141  kubectl get nodes --show-labels
  142  kubectl delete -f deployment.yml 
  143  clear 
  144  kubectl apply -f deployment.yml 
  145  kubectl get pods
  146  kubectl delete -f deployment.yml 
  147  git pull origin main
  148  kubectl apply -f deployment.yml 
  149  kubectl get pods
  150  kubectl describe pod
  151  kubectl label node k8s-node-1 env=perf
  152  kubectl get nodes --show-labels
  153  kubectl describe pod
  154  kubectl get pods
  155  kubectl get pods -o wide
  156  history 
  157  clear 
  158  kubectl get nodes
  159  kubectl describe nodes | grep -i taint
  160  kubectl get nodes --show-labels
  161  kubectl taint k8s-node-1 taint=true:NoSchedule
  162  kubectl taint node k8s-node-1 taint=true:NoSchedule
  163  kubectl describe nodes | grep -i taint
  164  kubectl delete -f deployment.yml 
  165  kubectl apply -f deployment.yml 
  166  kubectl get pods
  167  kubectl describe pod
  168  git pull origin main
  169  kubectl get pods
  170  kubectl apply -f deployment.yml 
  171  git pull origin main
  172  kubectl get pods
  173  kubectl apply -f deployment.yml 
  174  kubectl get pods
  175  kubectl get pods -o wide
  176  git pull origin main
  177  clear 
  178  kubectl get all
  179  kubectl apply -f deployment.yml 
  180  git pull origin main
  181  kubectl apply -f deployment.yml 
  182  git pull origin main
  183  kubectl apply -f deployment.yml 
  184  git pull origin main
  185  kubectl apply -f deployment.yml 
  186  kubectl get all
  187  clear 
  188  kubectl describe svc kul
  189  kubectl get pods -o wide
  190  git pull origin main
  191  kubectl describe deployment kul
  192  kubectl apply -f deployment.yml 
  193  kubectl describe deployment kul
  194  kubectl get rs
  195  kubectl describe rs kul-5bb594f8d7
  196  kubectl describe rs kul-5bb594f8d7 | grep -i  Created pod:
  197  kubectl describe rs kul-5bb594f8d7 | grep -i  "Created pod"
  198  kubectl describe rs kul-885dd764b | grep -i  "Created pod"
  199  kubectl describe rs kul-885dd764b | grep -i  "pod: kul-"
  200  kubectl describe svc kul
  201  kubectl get pods -o wide
  202  vi deployment.yml 
  203  kubectl apply -f deployment.yml 
  204  kubectl get pods -o wide
  205  clear 
  206  kubectl get deployment --show-labels
  207  kubectl get rs
  208  kubectl rollout history deployment kul
  209  kubectl describe deployment kul 
  210  kubectl rollout undo deployment kul
  211  kubectl describe deployment kul 
  212  kubectl rollout history deployment kul
  213  kubectl rollout undo deployment kul --to-revision=2
  214  kubectl rollout history deployment kul
  215  kubectl describe deployment kul 
```
