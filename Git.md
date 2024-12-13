Git Course :


Markdown provides backslash escapes for the following characters:

\ backslash
` backtick
*asterisk
_ underscore
{} curly braces
[] square brackets
() parentheses
# hash/pound mark
+ plus sign
- dash (hyphen)
. dot
! exclamation mark








check user name nd user email  if added in configuration for current dirctory :
       git config --list

      git config --get user.name
      git config --get user.email

add username and user email in global dirctory mean home directory :
      git config --add --global user.name "HusnainAliDigifloat"
      git config --add --global user.email 'husnain.ali.digifloat@gmail.com'


Intitialize git :
              git init

Check status which file is added in git and which one is not added yet:
              git status
add files : 
               git add .    for sll files added
               git file filename.py                      for specific file should be added
               
commit code :
              git commit -m "best commit why we are commiting"

