# terminal-wars
This cheat sheet provides a quick overview of all the commands you need to be dangerous enough while working in the terminal.

The inspiration for this cheat sheet comes from the frustating feeling of switching between microsoft and mac systems and having to relearn all the commands.

This cheat sheet is a collection of all the commands I use on a daily basis and I hope it will help you too.

**There weren't any cheatsheets available that were both comprehensive, easy to read and to the point. So I decided to create one myself :')**

## Microsoft vs MacOS
| Microsoft | MacOS |
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
| rmdir | rmdir |
| type | cat |
| echo | echo |
| exit | exit |
| start | open |
| type nul > file.txt | touch file.txt |
| copy nul > file.txt | touch file.txt |

## Using wsl
There is a neat little trick you can use for using linux commands on the windows terminal. This is very useful if you are not able to remember the windows commands.

Example:
```bash
# imho this is a lot easier to do than writting the equivalent of touch in windows
$ wsl touch main.py
```

## Contributing
If you have any suggestions or improvements, feel free to open an issue or a pull request.

## Author
Felipe Vallejo