apiVersion: v1
kind: Service
metadata:
  name: my-service
spec:
  type: NodePort
  selector:
    app: custom
  ports:
   - protocol: TCP
     targetPort: 8080
     port: 8080
     nodePort: 30007
