# To run the Images:
```bash
./update-image.sh
```

# To get all plguins and their coresponding versions

- Visit: http://yourjenkins:8080/script

```java
Jenkins.instance.pluginManager.plugins.each{
  plugin -> 
    println ("${plugin.getShortName()}:${plugin.getVersion()}")
}
```