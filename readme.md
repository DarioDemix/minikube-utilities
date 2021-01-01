# Start Minikube on Windows
In order to start Minikube on Windows, you need to open cmd (or PowerShell) with administrator privileges.
- Windows:
```
minikube start
```
- Windows Pro:
```
minikube start --vm-driver="hyperv"
```
If you want to run Istio, you need to allocate more memory:
```
minikube start --vm-driver="hyperv" --memory=4000
```