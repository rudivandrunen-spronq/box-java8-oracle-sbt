Wercker Oracle Java 8 / sbt box
=========================

Wercker box with Oracle Java 8 and sbt installed

Basic working example 
---------------------

To build simple Play2 application You just have to create ```wercker.yml``` file with following content and place in the root of your Java project.

```yml
box: studiodev/java8-oracle-sbt@0.0.2
build:
  steps:
      - script:
          name: Run sbt tests
          code: sbt test
```


