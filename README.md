# flask-helm-chart

## 1. Add helm repository
```bash
helm repo add flask https://eresseel.github.io/flask-helm-chart/
helm repo update
```

## 2. Deploy application to kubernetes cluster
```bash
helm install flask flask/flask --set redis.password=your_password
```