Add this to `.bazelrc` file or pass this options to a `build` command:
```
build --remote_executor=grpc://<External load balancer IP>:<PORT>
build --remote_instance_name=ubuntu16-04
```
