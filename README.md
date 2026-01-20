This Repo is for testing out devpods environment
## DevContainer

This tool is for testing your program in a container or similiar as a VMs, so you can pock around without worrying will it break the main machine

### Installation
```
https://devpod.sh/docs/getting-started/install#install-devpod-cli
```
### Set Defualt Settings

```bash
#Set Devpod to use docker as provider
devpod provider add docker
devpod provider use docker

#Set IDE to none, VScode is supported, if wanted to
devpod ide use none
```

### Running up the first Devpod

```jsx
devpod up . --ide none --dotfiles git@github.com:armswk/dotfiles-devpod.git
```
### Recreate Devpod

```bash
devpod up . --recreate --dotfiles git@github.com:armswk/dotfiles-devpod.git
```

side quest: don’t forget, if you delete the pods. Need to enter these command again

```bash
devpod up . --dotfiles git@github.com:armswk/dotfiles-devpod.git
```
![Diagram](./images/mise+chezmoi_installation_map.drawio.png)
