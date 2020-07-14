## Use Environment Variable in lambda

```shell
$ serverless deploy -v

$ serverless invoke -f hello-env-taro -l
"Taro"
--------------------------------------------------------------------
START RequestId: 0a747d38-eb09-40f2-9b06-7a9c910f3c0b Version: $LATEST
END RequestId: 0a747d38-eb09-40f2-9b06-7a9c910f3c0b
REPORT RequestId: 0a747d38-eb09-40f2-9b06-7a9c910f3c0b	Duration: 0.30 ms	Billed Duration: 100 ms	Memory Size: 1024 MB	Max Memory Used: 35 MB


$ serverless invoke -f hello-env-jiro -l
"Jiro"
--------------------------------------------------------------------
START RequestId: 8831e4d8-0f72-4aa7-a80a-3aad16ac045d Version: $LATEST
END RequestId: 8831e4d8-0f72-4aa7-a80a-3aad16ac045d
REPORT RequestId: 8831e4d8-0f72-4aa7-a80a-3aad16ac045d	Duration: 0.26 ms	Billed Duration: 100 ms	Memory Size: 1024 MB	Max Memory Used: 35 MB
``` 