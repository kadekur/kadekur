## Lab 01

- Name: Sean Stevens
- Email: stevens.201@wright.edu

## Part 1 - GitHub Profile

1. [kadekur Profile](https://github.com/kadekur)

## Part 2 - Research

| Windows | Linux / Mac | Action |
| ---     | ---         | ---    |
| help    | man         | Opens a help screen on Windows that gives options for help. In Linux, this opens an interface to the system reference manuals |
| Get-Location | pwd    | Finds the file path in Windows and Linux |
| Get-ChildItem | ls    | Finds the items within the directory you are navigating |
| mkdir   | mkdir       | Creates a new directory |
| Set-Location | cd     | Moves the directory you are navigating to a new location |
| New-Item | touch      | Creates a new item |
| Move-Item | mv        | Moves an item to a different position |
| Copy-Item | cp        | Copies an item |
| Remove-Item | rm      | Deletes an item |
| notepad.exe | vim     | Opens the notepad app in Windows and opens a similar text editor in Linux |

## Part 3 - Command Line Navigation

My OS is:
- [x] Windows
- [] Linux
- [] Mac

My Command Line Shell is: Windows Powershell

### Navigating My OS on the Command Line

1. Create a directory named `DirA`: mkdir DirA
2. Create a directory named `Dir B`: mkdir 'Dir B'
3. Go into `DirA`: cd DirA
4. Go into `Dir B` from `DirA`: "cd .." followed by "cd 'Dir B'
5. Return to your user's home directory: cd ~
6. Create a file named `test.txt`: New-Item test.txt
7. Move the file named `test.txt` into `DirA`: Move-Item test.txt DirA
8. Contents of `test.txt`: $text = "You can do it!" followed by "Set-Content test.txt $text"
```
You can do it!
```
9. Make a copy of `test.txt` named `copy.txt` in `DirA`: Copy-Item test.txt copy.txt
10. View the contents of `DirA`: ls
11. Make a copy of `test.txt` in `Dir B` named `fodder.txt`: "Copy-Item copy.txt fodder.txt" followed by "Move-Item fodder.txt 'C:\Users\seana\Dir B'"
12. Delete / remove both `fodder.txt` AND `Dir B`: "Remove-Item 'C:\Users\seana\Dir B'" followed by "A"

## Citations

To add citations, provide the site and a summary of what it assisted you with.  If generative AI was used, include which generative AI system was used and what prompt(s) you fed it.

5. https://www.reddit.com/r/PowerShell/comments/a9clu7/how_do_you_create_a_home_directory_or_get_back_to/

r/Powershell helped me find the command to return to the user's home directory.

8. Used Google Gemini to find the command to set the text of a text file. Prompt: how do i set text of a txt file in powershell


11. Used Google Gemini to find the syntax of the move command. It helped me use the file path instead of the file name in a directory already being viewed. Prompt: how do I move an item into a different directory?
