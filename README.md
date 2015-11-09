# FileFind

This script gets a list of files by calling "locate /home", and then allows you to search through them easily using a curses interface.
It uses xdg-open to open the selected file.

### Keyboard shortcuts:
| Key:              | Description:              |
|-------------------|---------------------------|
| most characters:  | search                    |
| up arrow:         | highlight next entry up   |
| down arrow:       | highlight next entry down |
| page up           | move one page up          |
| page down         | move one page down        |
| return:           | open selected file        |
