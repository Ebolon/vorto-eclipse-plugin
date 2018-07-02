# Vorto Eclipse Plugin
The Eclipse Plugin for Eclipse Vorto is friendly fork from the Vorto Repository and not officially related to Eclipse Vorto.

## Build
Clone the offical Vorto Repository:
```
git clone https://github.com/eclipse/vorto.git
```
Clone this repository into the vorto folder.
```
cd vorto
git clone https://github.com/Ebolon/vorto-eclipse-plugin.git
```
Add the `vorto-eclipse-plugin` as module to the vorto POM file.
```
<module>vorto-eclipse-plugin</module>
```
Now you can build the Vorto Eclipse Plugin
```
mvn install
```