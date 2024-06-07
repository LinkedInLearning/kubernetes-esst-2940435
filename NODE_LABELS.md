# Node-Label hinzufügen
```
kubectl label node <node-name> <label-key>=<label-value>
```

# Node-Label entfernen
```
kubectl label node <node-name> <label-key>-
```

# Node-Label disktype=ssd hinzufügen
```
kubectl label node <node-name> disktype=ssd
```

# Node-Label disktype=ssd entfernen
```
kubectl label node <node-name> disktype-
```

# Node-Namen ermitteln
```
kubectl get nodes
```
