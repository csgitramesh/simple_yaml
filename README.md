apiVersion: v1
kind: Pod
metadata:
   name: Tomcat
spec:
   containers:
   - name: Tomcat
    image: tomcat: 8.0
    ports:
containerPort: 7500
   imagePullPolicy: Always
