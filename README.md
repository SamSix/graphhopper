# Graphhopper

This is basically a fork of the open source _Graphhopper_.
To see the version included in the original graphhoper repo, see [README-original.md](https://github.com/SamSix/graphhopper/blob/master/README-original.md).

For now we only need the core library.

Building:

``` bash
cd ./core
./gradlew build
```
Publishing:

``` bash
cd ./core
./gradlew artifactoryPublish
```

## Older Documentation


This is a ~ branch ~ fork of the graphhopper repo. We are tracking the original repo by adding a remote repo called upstream.  This was done with the following command (this command  does not need to be run locally, this is just here for informational purposes)...

```
git remote add upstream git@github.com:graphhopper/graphhopper.git
```

### Updating from original

If you want to get the lateset changes from the original repo into this repo, run the following steps.

```
    git fetch upstream
    git merge upstream/master
    git push
```

For a ton more documentation, and what arguably could have been the readme, see this random document in internal.

See [yet another damned readme.](https://github.com/SamSix/internal/blob/master/docs/graphhopper_howto.md)
