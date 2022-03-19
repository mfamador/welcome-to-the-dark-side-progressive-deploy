# Welcome to the Dark Side of Progressive Delivery


Dark launching allows development teams to test the efficacy of new, production-ready features without releasing them to an entire user base. 

This repo contains a demo to demonstrate how can we keep doing Progressive Delivery wirh Canary Deployments on both "main" version and on a completly new "dark" version that we want to be used only by a very restrict set of users.

This demo uses Istio Virtual Services which are created and handled by Flagger through Canary Deployments. To handle dark launches it has been used Isito Virtual Service Delegation feature.


