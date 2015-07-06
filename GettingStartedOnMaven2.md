The new maven repository is now up and running, it is available at this url: http://gwtprojsonserializer.googlecode.com/svn/repo/

## Step 1: add the repository path to your pom.xml file ##
```
<repositories> 
  <repository> 
    <id>gwtprojsonserializer</id> 
    <url>http://gwtprojsonserializer.googlecode.com/svn/repo</url> 
  </repository>
</repositories> 
```
## Step 2: add the gwtprojsonserializer dependency ##
```
<dependency> 
   <groupId>com.kfuntak.gwt.json</groupId> 
   <artifactId>gwtprojsonserializer</artifactId> 
   <version>1.0.4</version> 
</dependency>
```

Note: gwtprojsonserializer version 1.0.3 should be used if you're using GWT 2.1 or older; if you're using GWT 2.2 or newer please use gwtprojsonserializer 1.0.4 or newer.