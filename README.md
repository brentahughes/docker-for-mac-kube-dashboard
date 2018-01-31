# docker-for-mac-kube-dashboard

This is direct copy from https://raw.githubusercontent.com/kubernetes/dashboard/master/src/deploy/recommended/kubernetes-dashboard.yaml with one minor change. The service has been changed to a NodePort so port forwarding is not required.


## Install
`kubectl create -f https://raw.githubusercontent.com/bah2830/docker-for-mac-kube-dashboard/master/kube-dashboard.yaml`

Dashboard will be available at `https://localhost:30000`
