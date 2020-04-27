# TPk8s ! 

Bonjour à tous, cette série d'exercice a pour but de vous familiariser avec l'utilisation de Kubernetes ! 

**ATTENTION: Faites bien attention à réaliser votre exercice dans le bon namespace.** 

# TP1
## Pods & Namespaces

 1. Existe-t-il un ou plusieurs pods déjà présent sur le cluster ? Supprimez le namespace crée lors de la présentation
 2. Essayez de lister et d'afficher les pods existants sur tous les namespaces (une commande kubectl existe)
 3. Créer un namespace à votre nom
 4. Créer un pod avec l'image nginx dont le  nom est "Pandora"
 5. Lister uniquement ce pod
 6. Faites un describe de ce pod
 7. Affichez les informations du pod au format YAML
 8. Exportez le .yaml dans un fichier
 9. Supprimez ce que vous avez déployé et lancez votre pod via le fichier yaml
 10. Lancez un pod avec deux containers à l'intérieur

# TP2
## Workloads

 1. Essayez de trouver un exemple de daemonset sur le cluster
 2. Créer un déploiement avec une image nginx:1.17 et dont le nom est "derby", assurez vous qu'il soit créé dans le bon namespace (le votre)
 3. Listez votre déploiement
 4. Augmentez le nombre de réplicas dans votre deploiement
 5. Modifier votre déploiement pour une image nginx:latest
 6. Faites un rollback

# TP3
## Role & RoleBinding

 1. Créez un role
 2. Associez ce role
 
# TP4
## Deployment & Services

 1. Créez un deployment de type nginx
 2. Exposez ce deployment avec une commande kubectl 
 3. Listez vos services
 4. Supprimez votre service
 5. Créez votre service en déployant via un fichier .yaml
 6. Inspectez votre service via une commande Kubectl

