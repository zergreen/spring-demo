# install
- use spring initialize for build sprigng
<img width="1440" alt="image" src="https://github.com/zergreen/spring-demo/assets/68957232/cee9f7cb-7cc2-449b-a05c-e4b6802942c0">

- zip file and locate to rootfolder then run: `mvn spring-boot:run `
- fyi : install mvn before

after complete then go to browser and search with this url:http://localhost:8080/users/mama
<img width="1025" alt="image" src="https://github.com/zergreen/spring-demo/assets/68957232/2e8bd6e8-16ab-4f3c-a7ce-39737f13e825">

# send request by postman
import file import-postman.json in postman. [.json](https://github.com/zergreen/spring-demo/blob/master/import-postman.json)
then it's will get this: Spring Boot CRUD Example as you can see
<img width="1134" alt="image" src="https://github.com/zergreen/spring-demo/assets/68957232/3aca8b92-a34a-4cfa-b18b-1fe0c731b102">

# Disclaimer
This project is not use database. Then when stop server , data will be clear.

# Hirachy
If you focus, it's look like model, view, controller.
<pre>.
└── com
    └── example
        └── demo
            ├── DemoApplication.java
            ├── controller
            │   └── UserController.java
            ├── model
            │   └── User.java
            └── repository
                └── UserRepository.java 
</pre>
<img width="356" alt="image" src="https://github.com/zergreen/spring-demo/assets/68957232/53d0a1b2-ba08-45fe-8d69-285106b3f484">
















