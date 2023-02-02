## Jib Java Gradle Template
Spin up an java development environment Codespace with gradle and Jib to build faster containerized java applications.

## Table of contents
 * [Creating codespace from this template](#codespace-from-this-template)
 * Creating codespace from blank template
 

## Codespace from this template
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

## Codespace from blank template

 * Navigate to your github home page and select `Codespaces` from the menu
 
   ![image](https://user-images.githubusercontent.com/61611561/216233844-f41de72f-ae28-4015-a4f3-f949ef51703b.png)

 * Under `Explore quick start templates` select `Use this template` for blank template. This will open a codespace with almost all development tools installed.
 
   ![image](https://user-images.githubusercontent.com/61611561/216233930-ddd8e986-7796-4a24-98f6-600f7d38c74f.png)

 * To costomize your env press `CTRL+SHIFT+P` and type `Configure Dev container` and select very first result
 
   ![image](https://user-images.githubusercontent.com/61611561/216234226-36c2bd83-7a95-473a-84f4-3b972890d571.png)
   
 * Now the options will appear to modify your existing confire or create from scratch. Select `Start from scratch`
   
   ![image](https://user-images.githubusercontent.com/61611561/216234539-f47f7e59-a7a2-473c-a777-c08beac8eba7.png)
   
 * Now on new prompt select `All definitions` then type `java`, select first item in appeared list and then version of jdk
 
   ![image](https://user-images.githubusercontent.com/61611561/216234878-3a3dd63f-fb8c-499c-997e-a284d1af953c.png)
   
   ![image](https://user-images.githubusercontent.com/61611561/216235015-ca5c59f2-9696-4f87-b652-b6624bd80206.png)
 
 * In the next prompt check the gradle options and CLick `Ok` two times.
 
   ![image](https://user-images.githubusercontent.com/61611561/216235308-4d6738fc-6a9a-4b2e-b799-91230750a471.png)
   
 * Now you have a enviroment ready with the gradle and java installed with jib-gradle-plugin to build containerized image




 
