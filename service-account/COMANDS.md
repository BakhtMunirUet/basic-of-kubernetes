

kubectl create sa bmk-sa
kubectl create token bmk-sa

<!-- with time duration -->
kubectl create token bmk-sa --duration=1000h
