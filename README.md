Remove :

    docker rm -vf $(docker ps -aq);
    
    docker rmi -f $(docker images -aq);
    
    docker volume rm $(docker volume ls -q);
    


Build:

    docker-compose up --build
    

Add database : 

    http://localhost:8002
    
    Username/Password : root/example
    
    add database : company
    
    add table : users(id,name) 
    

Run : 

    http://localhost:8001/
    


refer:

    image: thanhtrungxda/php_mysql
    
    https://github.com/trungnt89/php_mysql
    


   
