
To see the line numbers:
: set numbesr



To type anything we have to go to the insert mode & for that we have to press i button and press ESC to go to command mode.

To save the content we have to go to the execute mode and we have to type
:w

To delete a specific line we have to the command mode and then we have to type dd while we are in the line.

To delete a line in execute mode we have to type :d

to save and quit the vim
:q!

to delete a range of lines in execute mode
:3,10d
to delete a specific line number in execute mode
:5d        it will delete the number 5
to search something in command mode
/a                   it will find the word a in that file
to search a sentence or more than one words in command mode
/I am             if we press enter it will go to the next word, but if we press n then it will continue         searching if there are any other I am available in that file. N to search backwards.

j line number e thakbo okhane / diye search korle oi line number theke + forward e search hobe r ? use korle backward e search hobe.

ekhane 12 er jayga te amra whole document e 13 replace korbo
:%s/12/13/g
![image](https://github.com/user-attachments/assets/5c2b4d40-ebda-4605-87a1-0fdf6dd8dfff)



