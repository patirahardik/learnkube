#### To Create the replicaset
```
# kubectl create -f <replicaset file name>
```

#### Get pods details

```
# kubectl get pods
```

#### Get replicasets details

```
# kubectl get replicaset
```

#### Edit runtime replicas set file

```
# kubectl edit replicasets <replicaset name>
```


#### Increasing the number of replicas without edits the files.

```
# kubectl scale rs new-replica-set --replica=5
```