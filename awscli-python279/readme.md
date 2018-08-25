To build:
```
docker build -t tomsmithokta/awscli-python279 .
```

To run/test:

```
docker run -v /Applications/MAMP/htdocs/docker/prod/awscli-python279/.aws:/root/.aws -it tomsmithokta/awscli-python279
```

```
source ~/.profile
aws s3 ls
```

This will list the s3 buckets in my "personal Okta" tenant (not TMM).