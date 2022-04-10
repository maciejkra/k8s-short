
# Minikube

```
minikube ssh
mkdir /DIR
echo $(date) Hello > /DIR/index.html
```

# Docker (mac)

```
mkdir /DIR
echo $(date) Hello > /DIR/index.html
```

# Docker (windows)

In windows, you are using Shares in Docker, so make sure that you have drive shared and when using this drive in K8s, always add /DRIVE_LETTER/ before path. And use / instead of \ and /d/ instead of d:\.

If you are using WSL, use normal path, not /run/desktop/mnt/host/c/path/to/file

```
mkdir DIR
echo $(date) Hello > DIR/index.html
```

