# Orion APT Repository

This is a repo used to contain all the deb files contained in the Orion APT Repository, which is deployed using GitHub Actions

## Installing

```bash
curl -sfLo /etc/apt/trusted.gpg.d/orion-keyring.asc https://orion-network-dev.github.io/apt-registry/gpg.key
echo "deb https://orion-network-dev.github.io/apt-registry/ bookworm main" >/etc/apt/sources.list.d/orion.list
```
