---
title: "Atajos"
---

#### Crear un pod alpine e instalar telnet

```bash
kubectl run -i --tty --rm debug --image=alpine --restart=Never -- sh;
apk update; apk add busybox-extras
```