# Deploy saleor-k8s-staging App

## Introduction

This repo consists of numerous helm charts that will be deployed together to create instances of saleor and strapi for the use of the konomo app. All helm charts will be deployed by running helm install on the charts/saleor-platform chart. 

The pipeline has been set up to deploy everything from scratch, including the argocd application, or if the instances already exist, it will update the helm charts and sync the argocd application
