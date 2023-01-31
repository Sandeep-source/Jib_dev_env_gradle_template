## Jib Java Gradle Template
Spin up an java development environment Codespace with gradle and Jib 

## Steps 📄
* Click on `Use Template`
* Make changes according to your requirements
* Run the default setup and push image to image registry with 
  ```shell
  gradle jib \
    -Djib.to.image=myregistry/myimage:latest \
    -Djib.to.auth.username=$USERNAME \
    -Djib.to.auth.password=$PASSWORD

  ```
* Push your changes to your repo
