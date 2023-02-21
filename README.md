# working-with-ansible


## Created a role called print that contains a folder named ""task"" within is a ""main.yml"" file containing some configuration. Assigned to run on localhost

### screenshot shows success
![Screenshot (2)](https://user-images.githubusercontent.com/69207791/219063302-66ed31e3-933f-4c01-b87a-48b5fc9ba472.png)


## NEXT - Installing some dependencies and a simple web application using ansible!

### changed main.yml to main-remote.yml. Added an inventory file. made changes to the main-remote.yml


### I had used the command module to create a directory and on the second run i found out that the playbook threw an error for that module. I took to myself to fix the issues as i had no intrest in using the file module to create a directory. The stat module was what i needed, it checked if the directory existed and skipped the command moudule if it did. This way there was no error thrown. This shows the success of the playbook.

![Screenshot (5)](https://user-images.githubusercontent.com/69207791/220317148-b4bba9ae-9659-42e0-9744-c87d7f305caa.png)


### this shows the successful deployment of our sample html. 
![Screenshot (4)](https://user-images.githubusercontent.com/69207791/220317127-868e96b8-997d-49c5-9388-74b9e7f8ea25.png)



