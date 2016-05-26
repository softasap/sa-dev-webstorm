sa-dev-webstorm
===============

[![Build Status](https://travis-ci.org/softasap/sa-dev-webstorm.svg?branch=master)](https://travis-ci.org/softasap/sa-dev-webstorm)

Installs Jetbrains phpstorm

    - {
        role: "sa-dev-webstorm",
        option_install_java: true,
        java_version: 7,
        phpstorm_version: "2016.1.2b"
      }


# Optionally install java
option_install_java: false

# if install java, which version
java_version: 7

# Supported phpstorm versions:
webstorm_version" in [ "2016.1.2b", "11.0.4", "10.0.5", "9.0.4", "8.0.3", "8.0.6", "7.0.5", "6.0.3", "5.0.4", "4.0.3", "3.0.3", "2.1.5", "1.0.2" ]




