Youtube : https://www.youtube.com/watch?v=0RfZkwm3mTM&t=6s
Docs : https://chimbu.medium.com/canary-deployment-using-ingress-nginx-controller-2e6a527e7312

# canary-deployment-using-ingress-nginx-controller

Template files for the Medium article - https://medium.com/@chimbu/canary-deployment-using-ingress-nginx-controller-2e6a527e7312

Test command:

```
while sleep 0.5; do curl -H "Host: canary-app.com" http://<<LOAD-BALANCER-IP>>; echo ;done
```
