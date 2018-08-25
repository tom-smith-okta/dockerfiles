To build:

```
docker build -t tomsmithokta/awsprocesscreds-python279 .
```

To run/test:

```
docker run -v /Applications/MAMP/htdocs/docker/prod/awsprocesscreds-python279/.aws:/root/.aws -it tomsmithokta/awsprocesscreds-python279
```

```
aws s3 ls --profile okta
```

This will list the s3 buckets in my "personal Okta" tenant (not TMM).