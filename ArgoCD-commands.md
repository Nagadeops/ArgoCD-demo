# ArgoCD commands:


# To login argocd via cli:

argocd login serverip:port # enter the username and password

# To list the clusters:

argocd cluster list

# To list projects:

argocd proj ist

# To list repos:

argocd repo list

# To list applications:

argocd app list

# To create project:

argocd proj create demo-project

# To get the argocd user info:

argocd account get-user-info

# To change the password for argocd account:

argocd account update-password

# To create new application:

argocd app create argocd-demo --repo https://github.com/Nagadeops/argocd-demo --path yaml --dest-namespace efault --dest-server https://kubernetes.default.svc

# To perform manual sync:

argocd app sync argocd-demo

# To get the details of app:
 
argocd app get argocd-demo

# To delete the app:

argocd app delete argocd-demo

