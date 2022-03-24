# Build the snap for Snapcraft

- Bump version in snapcraft.yaml if applicable
- Install ubuntu 16.04

```shell
sudo apt-get update
sudo apt-get upgrade
sudo apt-get install snapcraft git
git clone https://github.com/digicontributer/digibyte-core-packaging
cd digibyte-core-packaging/snap
snapcraft
```

digibyte-core_<VERSION>_amd64.snap will be created in the current directory on completion of the build process.