# PacGame

![PacGame Screenshot](/PacGame.png)

## Description
A Pacman game in the terminal!

### Dependencies

#### Library
- **ncurses**

#### Library installation
Ubuntu/Debian based systems:
```bash
sudo apt-get install libncurses5-dev libncursesw5-dev
```

Red-Hat based systems:
```bash
sudo yum install ncurses-devel
```

Arch linux based systems:
```bash
sudo pacman -S ncurses
```

##### Compilation instructions
```bash
gcc main.c -o main -lncurses
```

##### Exit the game
```bash
ctrl + c
```
