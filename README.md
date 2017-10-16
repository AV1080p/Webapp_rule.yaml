# Webapp_rule

![error](https://github.com/re4lity/Webapp_rule.yaml/blob/master/error.jpg)

3rd-party web applications on a network

This file contains the application signatures - unique application path, version string, application name. 

# Format

The format is specified below:

```
#AppName: 'JBoss jmx-console'
#  - 'unique_app_path_1'
#  - 'unique_app_path_2'
#  - 'version string'
#  - 'exploit_path'
#  - 'creds' --> for smart brute-forcing
```
# References

- [https://github.com/0xsauby/yasuo/blob/master/signatures.yaml](https://github.com/0xsauby/yasuo/blob/master/signatures.yaml)
- [https://github.com/ywolf/F-MiddlewareScan](https://github.com/ywolf/F-MiddlewareScan)
