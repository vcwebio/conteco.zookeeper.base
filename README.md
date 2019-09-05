# The Conteco zookeeper.base Image

The Confluent Zookeeper base image.

## Modifications

### JSON Output

`output-to-JSON`  
Custom implementation to extract LEVEL and MESSAGE from non-JSON log output.

### Configuration

Modification of `log4j.properties.template` and `tools-log4j.properties.template` files to set JSON output.

## Tags

* 5.1.2  
