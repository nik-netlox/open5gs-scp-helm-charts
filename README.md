# open5gs-scp-helm-charts
Open5gs helm charts for deploying core components with LoxiLB SCP.

## Steps to install
```
$ git clone https://github.com/nik-netlox/open5gs-scp-helm-charts.git
```
Edit values.yaml and yaml files in templates directory as per your setup
```
$ kubectl create ns open5gs
$ helm -n open5gs upgrade --install core5g ./open5gs-scp-helm-charts/
```

Follow this blog to know more: https://dev.to/nikhilmalik/5g-service-communication-proxy-with-loxilb-4242
