# mkdate
sh file to create directory in format M-D-Y
just put this file in /usr/local/bin/ and set chmod ugo+x 


use --help | -h to show help

!IMPORTANT

the last param must be the directory value well closed 
ex:
mkdate ./app/

result: ./app/M-D-Y/

the last / is important here because it say create dir inside this one

if you don't it will prefix youre mkdate directory
ex:

mkdate myapp-

result ./myapp-M-D-Y/ 






<!-- you can pass 1 argument to create it in specific directory
ex:

mkdate /home/$user/Documents
or

mkdate app/
 -->