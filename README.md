# kustomize-python

#Check the script before applying kustomize

        cd kustomize-python/ordinary-deploy
    
        kubectl apply -f namespace.yml
        kubectl apply -f deploy.yml
        kubectl apply -f service.yml
        
        kubectl get pods -n dev
        kubectl get svc -n dev
  
  ![image](https://user-images.githubusercontent.com/54719289/116158588-d4559700-a6e6-11eb-92b5-7e4698ac65fa.png)


# Apply kustomize

      cd kustomize-python/ordinary-deploy
      
      kubectl apply -k .
      kubectl get pods -n dev
      kubectl get svc -n dev
      
 ![image](https://user-images.githubusercontent.com/54719289/116158588-d4559700-a6e6-11eb-92b5-7e4698ac65fa.png)
 
 
 # Updating port number and replicas in kustomize:
 
        cd kustomize-python
        
        kubectl apply -k .
        kubectl get pods -n dev
        kubectl get svc -n dev
      
        
![image](https://user-images.githubusercontent.com/54719289/116159231-c81e0980-a6e7-11eb-8658-1b3790d58067.png)
![image](https://user-images.githubusercontent.com/54719289/116159338-f3085d80-a6e7-11eb-8daf-53c0f3844d56.png)

![image](https://user-images.githubusercontent.com/54719289/116159371-05829700-a6e8-11eb-9c1d-f6ce2c5121bf.png)


![image](https://user-images.githubusercontent.com/54719289/116161400-9b6bf100-a6eb-11eb-80a8-612801c0644d.png)

                kubectl apply -f service.yml
                kubectl get svc -n dev

![image](https://user-images.githubusercontent.com/54719289/116161354-898a4e00-a6eb-11eb-9567-d6c74601a525.png)   but unable to check the UI....COnfirm this logic ..
Is it possible to update service port with kustomization


        
        

        
      
    
    
  
      
      
        
