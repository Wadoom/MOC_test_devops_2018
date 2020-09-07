Tests for candidates 2018     

For this test you can dockerize any application you want, but i must consist of front, back and DB.      
Also peristent data storage should be configured for DB.    
Use smallest container where you can.   

1. Dockerize app, make possible to run with docker-compose. App should consist of such components
1.1.1. nginx   
1.1.2. Frontend     
1.1.3. Backend      
1.1.4. DataBase (postgres prefered)     
1.2. App should run on one instance (can be VM) in one docker-compose receipt in such 
     sequence DB,backend, frontend, nginx    
2. Using ansible on Ubuntu 16.04   
2.1 Add SWAP   
2.2 Install on host nginx, postgresql, redis, docker-compose   
2.3 Using ansible make a deploy scenario     
2.3.1 Copy your project to remote server     
2.3.2 Run docker-compose.yml  

3. Kubernetes  
3.1. Create kubernetes cluster with 2 or 3 nodes  
3.2. Deploy application to cluster      
3.3. Start 2-3 replicas of each container    

----------------------------
   - FOR Advanced:  
     Install Kubernetes cluster with a help of ansible - 1 master 2 nodes  
