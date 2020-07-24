Add this lines to `.bazelrc` or pass it as options to a `build` command:
```
build --remote_executor=grpc://<External load balancer IP>:<PORT>
build --remote_timeout=7200 # first build out of the box takes around 1400 seconds, so any number above 1500 will suffice
```
