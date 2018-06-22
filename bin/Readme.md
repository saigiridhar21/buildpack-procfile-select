# Heroku Buildpack: Copy Procfile.QA to Procfile

Factset.io checks for only Procfile and we can't provide any other custom entry point file. So, for the QA apps, we use this [buildpack](https://github.factset.com/analytics-api/qa-heroku-build-pack.git) before the [actual dotnet buildpack](https://github.factset.com/factset-io/dotnet-buildpack).

This buildpack copies the Profile.QA to Procfile

## Usage

```
https://github.factset.com/analytics-api/qa-heroku-build-pack.git
https://github.factset.com/factset-io/dotnet-buildpack
```

