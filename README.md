# dropped-glass
Windows set up

1. WSL Set Up
2. vscode
3. nvim in wsl (make sure you add ppa unstable)
4. for neovim sudo apt install cmake make gcc nodejs npm python3-pip python3-venv

5. telescope fzf doesn't build automatically in windows so go to .local/share/nvim
     find the telescope-fzf-native folder and build manually

If you have trouble starting mariadb using 
```
sudo /etc/init.d/mariadb start
# Then you can run
sudo mysql_secure_installation
```

```
cmake -S. -Bbuild -DCMAKE_BUILD_TYPE=Release && cmake --build build --config Release && cmake --install build --prefix build

```

6. PowerToys
```
winget install Microsoft.PowerToys --source winget
```

7. Hot keys

stop hyperkey from opening office365
```
REG ADD HKCU\Software\Classes\ms-officeapp\Shell\Open\Command /t REG_SZ /d rundll32
```
- install autohotkey

```
winget install autohotkey -s winget
```


