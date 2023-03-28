# Go_server
Simple info web server 

Going to create a simple web server using go lang 



server   --->     /       ----> index.html (basic page)

         --->    /hellp   ----> going to hello func 

         --->    /form    ----> form func ---> form.html 


Steps:

1. Created a static folder: (what are things going to write)
    a. Created a two file one is index.html an other one is form.html 
a. index.html:
    Just return the title of our website
b. form.html: going to write some <label><lable> some basic info like
    (name, address, gender etc...) where user is going to give 

    a. <input type="submit" value="submit"/>   used to submit the details of <lable><label> (user info)


Test:

step 1: go build 
step 2: go run .\main.go\

will get localhost:808

login to localhost in google chrome

1. localhost:808/hello   ----> will get to simple hello world page 
2. localhost:8080/form.html  -----> need to add info and then hit submit to submit info.
