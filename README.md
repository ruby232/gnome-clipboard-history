# Gnome Clipboard History
In this repository, we position the menu at the mouse cursor's location in PopOs and Gnome 42.
[Fork from](https://github.com/SUPERCILEX/gnome-clipboard-history)  

## Install from source

### Build

```shell
cd ~/.local/share/gnome-shell/extensions/ && \
  git clone https://github.com/ruby232/gnome-clipboard-history.git clipboard-history@ruby232.dev && \
  cd clipboard-history@ruby232.dev && \
  make
```

### Restart GNOME

<kbd>Alt</kbd> + <kbd>F2</kbd> then type `r`.

### Install

```shell
gnome-extensions enable clipboard-history@ruby232.dev
```
