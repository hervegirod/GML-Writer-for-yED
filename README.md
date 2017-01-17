[![License](https://img.shields.io/badge/license-LGPL%202.1-blue.svg)](http://www.gnu.org/licenses/lgpl-2.1.html) [![Language](http://img.shields.io/badge/language-java-brightgreen.svg)](https://www.java.com/)
# GML-Writer-for-yED
Extends the gml export of JGraphT to better supports the import to yED.

Please note that the GML-Writer-for-yED is distributed WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

* Released: January 17, 2017
* Based on: JgraphT (and yED)
* Written by [Hayato Hess](mailto:hayato.hess@gmail.com) and Contributors

## Getting Started ##
The package `de.hess.examples` in the `Example` directory includes two small demo applications to help you get started. The page [https://hayato-hess.de/GMLwriter](https://hayato-hess.de/GMLwriter) offers some pictures of graphs created with the gml writer.

To use the gml writer ensure that your project has following dependencies:
```
<dependencies>
        <dependency>
            <groupId>org.jgrapht</groupId>
            <artifactId>jgrapht-core</artifactId>
            <version>0.9.1</version>
        </dependency>
        <dependency>
            <groupId>org.jgrapht</groupId>
            <artifactId>jgrapht-ext</artifactId>
            <version>0.9.1</version>
        </dependency>
</dependencies>
```
and includes the either [GMLWriterForYed-1.0.0.jar](https://hayato-hess.de/files/GmlWriter/GMLWriterForYed-1.0.0.jar).

### How to import in yED 
After exporting the graph to a .gml file, import it in [yED](https://www.yworks.com/products/yed) by using the open dialog. After importing, the graph will most likely look broken as every node is placed on top of each other. To resolve this, go to the `Layout` menu in yED and select one fitting layout. Further, the `Fit Node to Label` in the `Tools` menu is useful when the labels are longer than the node's widths.

## Download Ressources ##
* [Binaries](https://hayato-hess.de/files/GmlWriter/GMLWriterForYed-1.0.0.jar)
* [Source](https://hayato-hess.de/files/GmlWriter/GMLWriterForYed-1.0.0-sources.jar)
* [Documentation](https://hayato-hess.de/files/GmlWriter/GMLWriterForYed-1.0.0-javadoc.jar)

## Pictures ##
![yed1](http://hayato-hess.de/pictures/yED/YED1.jpg)
![yed2](http://hayato-hess.de/pictures/yED/YED2.jpg)
