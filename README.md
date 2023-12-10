# dropped-glass
Windows set up

1. WSL Set Up
2. vscode
3. nvim in wsl (make sure you add ppa unstable)
4. for neovim sudo apt install cmake make gcc nodejs npm python3-pip python3-venv

5. telescope fzf doesn't build automatically in windows so go to .local/share/nvim
     find the telescope-fzf-native folder and build manually

```
cmake -S. -Bbuild -DCMAKE_BUILD_TYPE=Release && cmake --build build --config Release && cmake --install build --prefix build

```

6. PowerToys
```
winget install Microsoft.PowerToys --source winget
```
