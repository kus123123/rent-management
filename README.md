# rent-management
this repos contains rent management system


the entity relation of this database is as follows
![diagram-export-09-12-2024-23_52_32](https://github.com/user-attachments/assets/b92b8dda-8e51-4d55-869a-347a7fbeb30d)

the database i am using is postgresql which is easy to create and can provide a scalabale devlopment 

2. the cloud service i am using is azure cloud, had try to keep everything serverless .
3.  started creating property and room with serverless . with the help of azure web apps . the alternative is creating a server and keeping all backend api  on the server and as well as postgress on the same server .
4.  for generating electricty due and rent due we can use a trigger function or a simple cron job that checks what is the recent bill date and if new date is equal to due date then generate a new due rent and month array which is next to given month 
