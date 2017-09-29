# ironbasechrome
Base image with chrome for iron.io workers

## Docker security

```
wget https://raw.githubusercontent.com/jfrazelle/dotfiles/master/etc/docker/seccomp/chrome.json
docker run ... --security-opt seccomp:/path/to/chrome.json ...
```
