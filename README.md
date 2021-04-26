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
        
        
      
    
    
  
      
      
        
