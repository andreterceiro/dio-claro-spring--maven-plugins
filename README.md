# General

[class](https://web.dio.me/course/gerenciamento-de-dependencias-e-build-em-java-com-maven/learning/dce5d3ad-6da2-40f2-bc80-ebdfdb1d4f3d?back=/track/coding-the-future-claro-java-spring-boot&tab=undefined&moduleId=undefined).

General things about plugins:

![general things about plugins in Maven](images/general-plugins.png)

Most used plugins:

![most used plugins](images/most-used-plugins.png)

How o use a plugin:

![how to use a plugin](images/how-to-use-a-plugin.png)

Example:

```
mvn dependency help
```

## Plugin configuration

![plugin configuration](images/plugin-configuration.png)

At start some comfiguration is the same as the configurations of a dependency:

- groupId;
- artifactId;
- version.

After, we can have configurations related specifically the plugin that is be configured. Example of configuration: `release` (please see the image).

## Example of generation of a Javadoc

First of all, please install one plugin. Insert this plugin in `pom.xml`: `maven-javadoc-plugin`.

![javadoc plugin install](images/javadoc-plugin-install.png)

Then execute:

```
mvn javadoc:javadoc
```

At this time you already need to have the `Javadoc` comments in the right places.

The content will be generated in the folder "`target`".

Example of generated `javadoc`:

![javadoc example](images/javadoc-example.png)