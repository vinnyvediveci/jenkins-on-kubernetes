# jenkins-on-kubernetes
jenkins cluster run on kubernetes(minikube)


This repo documents the configuration of a distributed jenkins build system on a kubernetes cluster. The idea of a distributed build is to create completely isolated build and test environments per job, so as to create greater reproducibility. So far the Jenkins cluster works fine on minikube, and I've set it up + configured it manually. The next steps will be to configure the jobs to perform a ci/cd pipeline for the quarkus app, within a fully secure Jenkins with a persistent volume claim.