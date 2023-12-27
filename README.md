# user-wishlist-app
step 1
create deployment file
 step 2
 create secret
# kubectl create secret generic pgpassword --from-literal PGPASSWORD=hello_flask

step 3
Build the Image
# docker build -t awskingraju/user-wishlist-k8s:v1 .

step 3
push image to Dockerhub

# docker login

# docker push awskingraju/user-wishlist-k8s:v1

step 4
# create web-service file

step 5
create persistent volume claim, postgres deployment, postgres service, redis deployment ,redis service and ingress

step 6
install ingress addon
kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/deploy/static/provider/kind/deploy.yaml

step 7
apply all the file

step 8

