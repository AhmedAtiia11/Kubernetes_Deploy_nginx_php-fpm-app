# Kubernetes_Deploy_nginx_php-fpm-app
Deploy a simple PHP page using Nginx and PHP-FPM on Kubernetes node
commands to run 
1- kubectl apply -f nginx-config_configmap.yaml 
2- kubectl apply -f nodeport-service.yaml 
3- kubectl apply -f nginx_php-fpm.yaml 
4- kubectl cp index.php nginx-phpfpm:/var/www/html -c nginx-container
5- curl localhost:30012
