## This project is to demonstrate how to utilize contour for blue-green deployment. 
This main idea is taken from [a blog by Steve Sloka](https://blogs.vmware.com/cloudnative/2019/03/08/routing-traffic-kubernetes-contour-0-10/ "Blue-Green Deployment with Contour")
This example uses two versions of nginx, nginx-v1 and nginx-v2, to illustrate ideas in Steve's blog. 
ingress-rule.yaml determines which ingress-route is delegated to by root-ingressroute. This release uses "grey", which implies equally splitted traffic to two versions. 

Maintained by Shawn Ho hos@vmware.com
