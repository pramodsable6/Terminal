# Linux commands

- Adding alias
```shell
alias java='java.exe'
```
- Check available memory  
`free -h` or `htop`

# WSL memory config - Windows Subsystems for Linux
1. Shutdown WSL
```
wsl --shutdown
```
2. Create a file at following location and insert below details - C:\Users\<your_user_name>\.wslconfig
```
[wsl2]
memory=12GB
```
3. Restart WSL and run free-h to
