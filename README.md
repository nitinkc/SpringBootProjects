# Spring 5/Spring Boot Project Examples



## Update all the submodles
```
git pull --recurse-submodules
```


## Add new projects using the following command
```
git submodule add <GitHub Repo>
```


### In case the projects needs be deleted

* Delete the entry from .gitmodules file
* delete the entry from .git/config file
* delete the project folder from .git/modules/<git-project-name>
* Commit and push the changes on github

Projects

1. Spring 5 Introduction -  basic read and write from H1DB
2. spring5-di-concepts - Spring Dependency Injection Basics
3. spring5-data-jpa -
4. spring5-thymeleaf-pet-clinic
