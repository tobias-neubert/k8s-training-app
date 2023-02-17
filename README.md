# k8s-training-app
I am practicing my k8s skills using this repo. It is used as the source of all k8s resources that made up my demo app. 

The idea is that each microsoervice that the app is composed of, is developed in its own repository. Whenever a new release of such a microsoervice has been built and tested, it will render its own k8s resources and pushes them into this repo from where the k8s cluster will be updated.

See the k8s-training repo for more info. Currently it contaons the only microsoervice used for this demo app.
