# pioctl
## To install or upgrade pioctl

Prepare the environment variables for desired version:
```bash
export RELEASE={release number} # e.g. v0.1.2
export OS={your os name} # darwin for MacOS, linux for LINUX
export ARCH={your workstation architecture} # amd64, arm64

```
Download from github.com:
```bash
wget https://github.com/pilvio-com/pioctl/releases/download/${RELEASE}/pioctl_${RELEASE}_${OS}_${ARCH}.tar.gz -O - |tar zx
```
Move the extracted file to commands in your path. In example:
```bash
mv pioctl /usr/local/bin
```