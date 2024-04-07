# my personal setup o nvim

inspired by: [https://www.youtube.com/watch?v=w7i4amO_zaE&t=1231s](https://www.youtube.com/watch?v=w7i4amO_zaE&t=1231s)

useful links:
[https://cheatography.com/thissitesucks/cheat-sheets/vscode-vim/](https://cheatography.com/thissitesucks/cheat-sheets/vscode-vim/)

## basic keymap

N.B: leader is currently space and C is ctrl.

leader+pv    ---->   start explore (:Ex)

    C+w-v        ---->   split vertical

    C+w-s        ---->   split horizontal

    C+w-c        ---->   close window

    C+w-h        ---->   move to left window

    C+w-j        ---->   move to down window

    C+w-k        ---->   move to up window

    C+w-l        ---->   move to right window

    C+w-w        ---->   move to next window

    C+w-r        ---->   rotate windows

    C+w-o        ---->   close other windows

### move in page
    
        C+u          ---->   move up
    
        C+d          ---->   move down
    
        C+b          ---->   move back
    
        C+f          ---->   move forward

### move in buffers
    
        C+h          ---->   move to left buffer
    
        C+l          ---->   move to right buffer
    
        C+j          ---->   move to next buffer
    
        C+k          ---->   move to previous buffer
    
        C+q          ---->   close buffer
    
        C+o          ---->   open buffer
    
        C+t          ---->   open new buffer
    
        C+T          ---->   open new buffer in new tab
    
        C+H          ---->   move to left tab
    
        C+L          ---->   move to right tab
    
        C+J          ---->   move to next tab
    
        C+K          ---->   move to previous tab
    
        C+Q          ---->   close tab
    
        C+O          ---->   open tab
### move to definitions function etc

    g+d          ---->   go to definitions

    g+r          ---->   go to references

    g+i          ---->   go to implementations

    g+o          ---->   go to type definitions

    g+D          ---->   go to declaration

    g+e          ---->   go to last edit

    g+q          ---->   go to quickfix

    g+*         ---->   go to next word under cursor

### move to next and previous

### chamge words
    [https://phoenixnap.com/kb/vim-find-replace#:~:text=Use%20the%20slash%20and%20dot,the%20text%20and%20hit%20Enter.](https://phoenixnap.com/kb/vim-find-replace#:~:text=Use%20the%20slash%20and%20dot,the%20text%20and%20hit%20Enter.)

example:

### telescope
    leader+pf    ---->   project files

    leader+ps    ---->   project search

### harpoon
    leader+a     ---->   add files to harpoon

C+e         ---->   quick menu (swapfile)

    C+h          ---->   go to harpoon file 1

    C+t          ---->   go to harpoon file 2

    C+n          ---->   go to harpoon file 3

    C+s          ---->   go to harpoon file 4

### undotree

    leader+u      ---->   treework

### fugitive    

    leader+gs   ---->   git tree

