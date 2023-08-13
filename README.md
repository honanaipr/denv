# denv
venv-style seamless binding docker to bash.

## Usage #expected
```sh
docker run denv init denv # creates denv/ with denv configuration
docker run denv add gcc # makes gcc avaliable from **activated** environment
docker run denv add golang # makes golang avaliable from **activated** environment
. denv/activate # activates environment
go ... # execute gcc from container
gcc ... # execute gcc from container
denv/gcc make # specify container to avoid conflicts
```

### config.yaml template
```yaml
?
```

