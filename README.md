# CI/CD Build Phase

kaniko is a tool to build container images from a Dockerfile, inside a container or Kubernetes cluster.

kaniko doesn't depend on a Docker daemon and executes each command within a Dockerfile completely in userspace. This enables building container images in environments that can't easily or securely run a Docker daemon, such as a standard Kubernetes cluster.

Kainko will be the first phase in the CI pipline and will be used to build docker container image and push it withought the use of Docker daemon. this will ensure a secure and clean procedure without any leftovers in the kubernetes environment.

