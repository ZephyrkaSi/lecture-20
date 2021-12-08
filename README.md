# Home task #20
1. new git repo
2. all best practices (.gitignore, readme etc)
3. base on modules home task #18
4. add web module
5. add spring dispatcher servlet
6. add spring context
7. use xml config files
8. deploy to servlet container per student

###How to deploy:

1.
Build the project:
```sh
mvn clean install
```
2.
then:
- Copy war file into Tomcat root directory (apache-tomcat-X.x.xx/webapps)
- Run Tomcat bat file bin/startup.bat

or:

- Use Tomcat Manager from browser
- Click on browse and chose war file to deploy it.