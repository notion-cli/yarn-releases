# Notion Supported Yarn Releases

A repository of Yarn releases for use with Notion.

We may eliminate this if Yarn offers a way to programmatically access releases without GitHub authentication.

## Adding new Yarn versions

In order to add support for new yarn versions, do the following:

1. Download the tarball from [Yarn's website](https://yarnpkg.com). The following curl script _should_ do the trick:

```
curl -L -o dist/yarn-v1.12.1.tar.gz https://github.com/yarnpkg/yarn/releases/download/v1.12.1/yarn-v1.12.1.tar.gz
```

2. Update `index.json` to add the new version.
