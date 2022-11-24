# terminator-config

## install terminator 

```
sudo apt-get install terminator
```

## import settings

Place [config](https://github.com/masachika-kamada/terminator-config/blob/main/config) file in this repository under the `~/.config/terminator` directory

## shortcut key settings

![teminator](https://user-images.githubusercontent.com/63488322/203810710-8326fd7a-759b-4cc4-8342-d1f65875ee42.png)

## add alias

Add the following alias to `~/.bashrc`

```bash
alias rosterminator='terminator -l ros&exit'
```

## finally, use terminator

- `win + R` : launch terminator
- `rosterminator` : launch terminator optimized for ROS
