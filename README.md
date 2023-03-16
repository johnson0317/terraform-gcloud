## terraform-gcloud docker image

This helper image contains:

* google cloud sdk
* terraform
* terraform provider pre-installed, stores at `/opt/offline-tf-providers`
    * hashicrop/google
    * hashicrop/google-beta
    * hashicrop/tls


```bash
$ docker build -t zch0317/terraform-gcloud:2.0
```

```
$ docker login
```

```
$ docker push zch0317/terraform-gcloud:2.0
```
