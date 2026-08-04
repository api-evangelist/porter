---
title: "Connect to Minikube"
url: "https://porter.sh/docs/integrations/minikube/"
date: "2001-01-01"
feed_url: "https://porter.sh/docs/integrations/index.xml"
---
The easiest way connect to a Minikube cluster from inside a Porter bundle is to embed the certificates used to authenticate to your cluster inside your kubeconfig. Minikube can do that for you automatically with a configuration setting: minikube config set embed-certs true With that setting enabled, the next time you run minikube start , your kubeconfig will have the certificates embedded. 🚨 There is an open issue with using Minikube’s Docker daemon when building a bundle #1383 .
