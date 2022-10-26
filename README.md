# terminal-wars
This cheat sheet provides a quick overview of all the commands you need in order to be dangerous enough while working in the terminal.

The inspiration for this cheat sheet comes from the frustating feeling of switching between Windows and Mac systems and having to relearn all the commands.

**There weren't any cheatsheets available that were comprehensive, easy to read and to the point. So I decided to create one myself :')**

## Windows vs MacOS
| Windows | MacOS |
| --------- | ----- |
| dir | ls |
| dir /A | ls -a |
| cd | cd |
| cd.. | cd .. |
| cls | clear |
| copy | cp |
| move | mv |
| del | rm |
| mkdir | mkdir |
| rmdir /S | rmdir |
| type | cat |
| echo | echo |
| exit | exit |
| start | open |
| type nul > file.txt | touch file.txt |
| copy nul > file.txt | touch file.txt |
| rename | mv |
| gsudo | sudo |

## sudo
The closest thing for the **superuser do** a.k.a. `sudo` command in Windows is the running as administrator.

But we want something similar to what we have in MacOS, so lucky for us there is a sudo for Windows called [gsudo](https://github.com/gerardog/gsudo).

To install it we run the following commands in our terminal:
```bash
# install the gsudo package either using scoop or chocolatey
$ scoop install gsudo
# check gsudo version
$ gsudo --version
# we can use gsudo as sudo or plainly as gsudo
$ gsudo <command>
$ sudo <command>
```

## [wsl](https://ubuntu.com/wsl)
**This is the best way I know to use a Linux terminal on a Windows computer**. You just need to type the following and Linux commands will work:
```bash
$ wsl
$ ls 
$ # it works!
$ # to switch back to windows commands just type
$ exit
```

Also there is a neat little trick you can use for using Linux commands on the Windows terminal. **This is very useful if you are not able to remember the Windows commands.**

Make sure you have wsl enabled in your computer, otherwise check this quick tutorial on [Installing WSL](https://learn.microsoft.com/en-us/windows/wsl/install).

Example:
```bash
# imho this is a lot easier to do than writting the equivalent of touch in windows
$ wsl touch main.py
```

## [Hyper](https://hyper.is/)
There are plenty of terminals on Windows, including the following:
* [Powershell](https://learn.microsoft.com/en-us/powershell/)
* Command Prompt
  
But I've worked best with Hyper, it offers plenty of plugins and themes to customize your terminal. It feels like a modern terminal.

## Contributing
If you would like to add more commands to this repo or add any improvements, feel free to do so by opening an issue or a pull request.

## Author
Felipe Vallejo
