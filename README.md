#### Download files from the pods

Download files from the pods with the selector information

#### Installation

```
cp kubectl-download ~/.krew/bin/
```

#### Usage

```
kubectl download ${selector} --namespace default --file /var/log/nginx.log
```