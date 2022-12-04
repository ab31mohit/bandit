# Commands  
- ## Level 0 to Level 1 :  
   ``` 
   cat readme  
   ```   
---  
- ## Level 1 to Level 2 :  
   ``` 
   find . -name '-'
   cat ./- 
   ```   
---  
- ## Level 2 to Level 3 :  
   ``` 
   cat 'spaces in this filename'  
   ```  
   ### or  
   ```  
   cat spaces\ in\ this\ filename
   ```   
   ### or  
   ```  
   cat spaces<doubel tab>
   ```   
---  
- ## Level 3 to Level 4 :  
   ``` 
   ls
   cd inhere
   ls -a
   cat .hidden  
   ```   
---  
- ## Level 4 to Level 5 :  
   ``` 
   ls
   cd inhere
   ls -a
   file ./*
   cat ./-file07
   ```   
---  
- ## Level 5 to Level 6 :  
   ``` 
   ls
   cd inhere
   ls -a
   file * | find -size 1033c ! -executable
   cat ./maybehere07/.file2  
   ```   
---  
- ## Level 6 to Level 7 :  
   ``` 
   find / -size 33c -user bandit7 -group bandit6 
   ```  
   ### or if you don't want error messages to be displayed  
   ```  
   find / -size 33c -user bandit7 -group bandit6 2>/dev/null
   ```   
   ### now get the password from the path we got  
   ```  
   cat /var/lib/dpkg/info/bandit7.password 
   ```
---  
- ## Level 7 to Level 8 :  
   ``` 
   grep "millionth" data.txt  
   ```   
---  
- ## Level 8 to Level 9 :  
   ``` 
   sort data.txt | uniq -u    
   ```   
---  
- ## Level 9 to Level 10 :  
   ``` 
   strings data.txt | grep '==' 
   ```   
---  
- ## Level 10 to Level 11 :  
   ``` 
   base64 -d data.txt  
   ```   
---  
