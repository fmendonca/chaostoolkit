# README


Container project "Chaos Tool Kit" with tools kit by chaostoolkit.org

Usage Mode.

**1 - Use ready container**
```
podman run quay.io/fcalomen/chaostoolkit:latest -t chaostoolkit
```
````
podman exec -it chaostoolkit /bin/bash
````

**2 - Customize container**

The dockerfile file uses UBI(Universal Base Image) 9 as base image with python-3.9.

> registry.access.redhat.com/ubi9/python-311:latest

**Python Requirements**

requirements.txt
>awscli
>ansible
>ansible-core
>boto
>boto3
>botocore
>cffi
>cryptography
>ec2
>Jinja2
>jmespath
>MarkupSafe
>packaging
>pycparser
>pyparsing
>python-dateutil
>resolvelib
>s3transfer
>kubernetes
>jsonpatch
>chaostoolkit

Cloud CLI's
-
- aws cli
- gcloud-cli
- azure-cli
- openshift
- kubernetes
- rosa cli
