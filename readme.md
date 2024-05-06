# **KUBERNETES**

Instalar clúster y conectarlo.

`C:\User\<usuario>\.kube\config\`

`~/.kube/config`

![1715022133774.png](./images/1715022133774.png)


* Cambiar contexto:

  ```
  kubectl config use-context <nombre del context>
  ```
* Verificar contexto actual:

  ```
  kubectl config get-contexts
  ```

![1715022307701.png](./images/1715022307701.png)

* Verificar la configuración actual del context:

  ```
  kubectl config view
  ```
* Contexto actual:

  ```
  kubectl config current-context
  ```
  ---

  # **COMANDOS ÚTILES**
* Listar:

  ```
  kubectl get namespaces
  ```
  ```
  kubectl get pods
  ```
  ```
  kubectl get deploymets
  ```
  ```
  kubectl get services
  ```
  ```
  kubectl get service --all-namespaces
  ```
* Crear servicio:

  ```
  kubectl apply -f <file.yml>
  ```
* Borrar servicio:

  ```
  kubectl delete <name service>
  ```
